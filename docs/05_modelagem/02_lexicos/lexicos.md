# Léxicos

## Descrição

Os léxicos são termos específicos do domínio da aplicação **LigaMagic** que possuem significado particular no contexto do sistema. Este documento apresenta a Noção e o impacto de cada termo identificado, categorizando-os como **sujeitos** (atores), **verbos** (ações) ou **objetos** (entidades) do sistema.

## Objetivo

Definir e padronizar o vocabulário utilizado no projeto **LigaMagic**, garantindo que todos os envolvidos no desenvolvimento tenham uma compreensão uniforme dos termos específicos do domínio. Este artefato serve como referência para reduzir ambiguidades na comunicação e documentação do projeto.

## Metodologia

Os léxicos foram identificados por meio da análise do domínio da aplicação **LigaMagic**, e foram redigidos com o apoio da [lista de verificação](../../06_verificacao/entrega3/02_lexicos/verificacao_lexicos.md) utilizada na elaboração dos léxicos. Foram categorizados conforme a classificação LAL (Léxico Ampliado da Linguagem):

- **Sujeito**: Entidades que realizam ações no sistema
- **Verbo**: Ações que podem ser executadas no sistema
- **Objeto**: Entidades passivas manipuladas pelo sistema
- **Estado**: Situações específicas em que um objeto ou sujeito do sistema pode se encontrar

Cada léxico possui:

- **Noção**: Explicação clara e concisa do termo
- **Impacto**: Como o termo afeta ou é afetado por outros elementos do sistema
- **Sinônimos**: Termos alternativos que podem ser utilizados para referenciar o mesmo conceito. Nem todos os léxicos possuem sinônimos, sendo identificados apenas quando existem variações comumente utilizadas no domínio.

## Léxicos Identificados

### SUJEITO

#### L01 - Membro

- **Noção:**
  Pessoa que realizou o `Cadastro` e possui uma `Conta` ativa no site **LigaMagic**, diferenciando-se de um `Visitante`, que não possui cadastro.
- **Impacto:**
  - Executa `Login` para acessar funcionalidades restritas.
  - Pode `Comprar` e vender `Cartas`, atuando como `Comprador` ou `Vendedor`.
  - Gerencia sua `Coleção de Cartas`.
  - Cria e gerencia `Decks`, atuando como `Jogador`.
  - Participa ativamente do `Fórum`.

<br>
Fonte: Samuel, 2025.

#### L02 - Visitante

- **Noção:**
  Pessoa que navega pelo site **LigaMagic** sem ter realizado `Login` em uma `Conta`. Possui acesso limitado às funcionalidades públicas da plataforma.
- **Impacto:**
  - Pode `Pesquisar` por `Cartas` e visualizar seus detalhes.
  - Consegue visualizar `Decks` públicos criados pela comunidade.
  - Pode ler os tópicos e mensagens do `Fórum`.
  - É impedido de realizar ações restritas, como `Comprar Carta`, `Leiloar Carta`, criar `Decks`, gerenciar uma `Coleção de Cartas` ou publicar no `Fórum`.
  - Pode iniciar o processo de `Cadastro` para se tornar um `Membro`.

<br>
Fonte: Thiago, 2025.

---

### VERBO

#### L03 - Cadastrar

- **Noção:**
  Ação realizada por um `Visitante` para criar uma `Conta` no sistema. Ocorre quando o `Visitante` preenche um formulário com dados pessoais (nome, e-mail, senha).
- **Impacto:**
  - O sistema verifica se os dados são válidos e se o e-mail já está registrado.
  - Cria uma nova `Conta` no banco de dados.
  - Muda o estado do `Visitante` para `Membro`.
  - Permite que o novo `Membro` realize `Login`.

<br>
Fonte: Raissa, 2025.


#### L04 - Login

- **Noção:**
  Ação realizada por um `Membro` para acessar sua `Conta`. Ocorre quando o `Membro` informa suas credenciais (e-mail e senha) em um formulário específico.
- **Impacto:**
  - O sistema autentica as credenciais do `Membro`.
  - Inicia uma sessão segura, dando acesso a áreas restritas como "Minha `Coleção de Cartas`" e "Meus `Decks`".
  - Se as credenciais estiverem incorretas, o acesso é negado.
  - É um pré-requisito para as ações de `Comprar Carta` e `Leiloar Carta`.
  
<br>
Fonte: Vera, 2025.


#### L05 - Pesquisar Carta

- **Noção:**
  Ação realizada por qualquer pessoa (`Visitante` ou `Membro`) para encontrar uma `Carta` específica no banco de dados do site. O usuário insere critérios de busca, como nome, cor, tipo ou `Edição`.
- **Impacto:**
  - O sistema filtra o banco de dados de `Cartas` com base nos critérios fornecidos.
  - Exibe uma lista de `Cartas` correspondentes à pesquisa.
  - Permite a visualização dos detalhes de uma `Carta` específica.
  - A partir do resultado, um `Membro` pode adicionar a `Carta` a um `Deck` ou à sua `Coleção de Cartas`.

<br>
Fonte: Samuel, 2025.

#### L06 - Comprar Carta

- **Noção:**
  Ação realizada por um `Membro`, na função de `Comprador`, para adquirir uma `Carta` de um `Vendedor` na plataforma. Ocorre após o `Membro` selecionar uma `Carta` e adicioná-la ao `Carrinho de Compras`.
- **Impacto:**
  - A `Carta` é movida para o `Carrinho de Compras` do `Membro`.
  - O sistema processa o pagamento.
  - Após a confirmação, o sistema registra a transação e notifica o `Vendedor`.
  - A `Carta` pode ser adicionada automaticamente à `Coleção de Cartas` do `Membro`.

<br>
Fonte: Thiago, 2025.

#### L07 - Leiloar Carta

- **Noção:**
  Processo iniciado por um `Membro`, na função de `Vendedor`, para vender uma `Carta` ao `Membro` que oferecer o maior lance dentro de um período determinado. O `Vendedor` define um lance inicial e a duração do `Leilão`.
- **Impacto:**
  - Cria um registro de `Leilão` no sistema, associado à `Carta` e ao `Vendedor`.
  - A `Carta` fica temporariamente indisponível para venda direta.
  - Outros `Membros` podem registrar lances.
  - Ao término do período, a `Carta` é vendida ao `Membro` com o maior lance.
  
<br>
Fonte: Marcelo, 2025.


---

### OBJETO

#### L08 - Carta

- **Noção:**
  Unidade fundamental do jogo Magic: The Gathering. Possui atributos como nome, custo de `Mana`, cor, `Edição`, `Raridade`, tipo e texto de `Habilidade`.
- **Impacto:**
  - Pode ser pesquisada através da `Busca Avançada`.
  - Pode ser adicionada por um `Membro` a uma `Coleção de Cartas`.
  - É o componente principal de um `Deck`.
  - Pode ser comprada, vendida ou leiloada por `Membros`.
  - Seu preço é exibido e acompanhado pelo sistema.

<br>
Fonte: Samuel, 2025.

#### L09 - Deck

- **Noção:**
  Conjunto de no mínimo 60 `Cartas` que um `Membro` utiliza para jogar. É baseado em um `Formato` específico e em uma estratégia de jogo.
- **Impacto:**
  - Um `Membro` pode criar, editar e salvar múltiplos `Decks`.
  - Pode ter sua lista de `Cartas` (Decklist) exportada ou compartilhada.
  - Pode ser analisado pelo sistema para verificar sua legalidade em um `Formato` específico.
  - `Decks` criados por `Membros` podem ser públicos ou privados.

<br>
Fonte: Thiago, 2025.

#### L10 - Coleção de Cartas

- **Noção:**
  Ferramenta que permite a um `Membro` catalogar todas as `Cartas` que possui.
- **Impacto:**
  - Facilita o gerenciamento da coleção pessoal do `Membro`.
  - Auxilia na montagem de `Decks` ao mostrar as `Cartas` disponíveis para o `Membro`.
  - Permite ao `Membro` identificar `Cartas` para venda ou troca.
  
<br>
Fonte: Vera, 2025.


#### L11 - Edição

- **Noção:**
  Conjunto de `Cartas` de Magic: The Gathering lançadas juntas em uma data específica. Cada `Edição` possui um símbolo único que a identifica.
- **Impacto:**
  - É um critério fundamental na `Pesquisa de Carta`.
  - Determina a legalidade de uma `Carta` em um `Formato` de jogo.
  - Ajuda o `Membro` a organizar sua `Coleção de Cartas`.
  - O preço de uma `Carta` pode variar significativamente dependendo da sua `Edição`.
- **Sinônimo:**
  - Coleção.

<br>
Fonte: Angélica, 2025.

#### L12 - Formato

- **Noção:**
  Conjunto de regras que define quais `Edições` de `Cartas` são permitidas na construção de um `Deck`. Exemplos: Standard, Modern, Commander.
- **Impacto:**
  - Restringe as `Cartas` que um `Membro` pode incluir ao criar um `Deck`.
  - O sistema pode validar um `Deck` para verificar se ele é legal em um determinado `Formato`.
  - É um critério de busca para encontrar `Decks` públicos e artigos estratégicos.
  
<br>
Fonte: Raissa, 2025.


#### L13 - Fórum

- **Noção:**
  Seção do site onde os `Membros` podem criar discussões (tópicos) e publicar mensagens para interagir com a comunidade de jogadores de Magic: The Gathering.
- **Impacto:**
  - Permite a troca de informações e estratégias entre os `Membros`.
  - Um `Membro` pode criar, responder e seguir tópicos.
  - O conteúdo do `Fórum` é moderado para garantir o cumprimento das regras da comunidade.

<br>
Fonte: Angélica, 2025.

#### L14 - Mana

- **Noção:**
  Recurso fundamental do jogo, utilizado para conjurar as mágicas (jogar as `Cartas`). A `Mana` é representada por cores (Branco, Azul, Preto, Vermelho, Verde) e símbolos incolores.
- **Impacto:**
  - O "Custo de Mana" é um atributo principal de uma `Carta`.
  - É um critério essencial para a construção de um `Deck` por um `Membro`.
  - É utilizado como filtro na `Pesquisa de Carta`.
  
<br>
Fonte: Marcelo, 2025.

---

### ESTADO

#### L15 - Leilão Ativo

- **Noção:**
  - Período em que um `Leilão` está aberto para receber lances dos `Membros`. Inicia-se quando o `Vendedor` cadastra a `Carta` para leiloar e termina quando o tempo definido expira.
- **Impacto:**
  - `Membros` podem submeter lances de valor superior ao lance atual.
  - O sistema exibe o tempo restante e o maior lance publicamente.
  - Ao final do tempo, transita para o estado "Leilão Encerrado".
  
<br>
Fonte: Marcelo, 2025.


#### L16 - Leilão Encerrado

- **Noção:**
  - Situação de um `Leilão` após o término do seu prazo.
- **Impacto:**
  - O sistema não aceita mais novos lances para este `Leilão`.
  - O `Membro` com o maior lance é declarado o vencedor.
  - Inicia o processo de transação, movendo a compra para o estado "Pagamento Pendente".
  
<br>
Fonte: Raissa, 2025.


#### L17 - Pagamento Aprovado

- **Noção:**
  - Situação de uma transação após a confirmação do pagamento pela instituição financeira.
- **Impacto:**
  - O `Vendedor` recebe uma notificação oficial para preparar e enviar o pedido.
  - A transação é confirmada no histórico de compras do `Comprador` e de vendas do `Vendedor`.
  - Libera a próxima etapa do fluxo, que levará ao estado "Pedido Enviado".

<br>
Fonte: Samuel, 2025.

#### L18 - Pedido Enviado

- **Noção:**
  - Situação de uma compra após o `Vendedor` despachar o produto e registrar o envio na plataforma.
- **Impacto:**
  - O `Comprador` é notificado de que seu pedido está a caminho.
  - O código de rastreamento, se aplicável, é disponibilizado para o `Comprador`.
  - Habilita a ação de `Avaliar Transação` para o `Comprador` após o recebimento.

<br>
Fonte: Thiago, 2025.

#### L19 - Pedido Entregue

- **Noção:**
  - Situação final de uma transação, que ocorre quando o `Comprador` confirma o recebimento do produto em bom estado.
- **Impacto:**
  - O ciclo da transação é formalmente encerrado.
  - Libera o pagamento para o `Vendedor`, caso esteja retido pelo sistema.
  - Permite que tanto o `Comprador` quanto o `Vendedor` realizem a `Avaliar Transação`.
  
<br>
Fonte: Vera, 2025.


#### L20 - Pedido Cancelado

- **Noção:**
  - Situação de uma transação que foi interrompida e anulada antes de ser concluída. O cancelamento pode ocorrer por falta de pagamento, a pedido do `Comprador` ou por impossibilidade de envio pelo `Vendedor`.
- **Impacto:**
  - A transação é registrada como inválida no histórico de ambos os `Membros`.
  - As `Cartas` do pedido retornam ao estoque do `Vendedor` e ficam disponíveis para venda novamente.
  - Dispara o envio de notificações para `Comprador` e `Vendedor` informando sobre o cancelamento.

<br>
Fonte: Angélica, 2025.

#### L21 - Carrinho Ativo

- **Noção:**
  - Situação em que o `Carrinho de Compras` de um `Membro` contém um ou mais itens selecionados, mas a compra ainda não foi finalizada.
- **Impacto:**
  - Os itens no carrinho não ficam reservados no estoque do `Vendedor` e podem ser adquiridos por outro `Comprador`.
  - Permite ao `Membro` adicionar mais itens, remover existentes ou alterar quantidades.
  - Ao finalizar a compra, transita para o estado "Pagamento Pendente". Se esvaziado, retorna ao estado "Carrinho Vazio".

<br>
Fonte: Angélica, 2025.

---

## Bibliografia

> **SERRANO, Milene; SERRANO, Maurício.** _Requisitos – Aula 10_.

## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição |
| :----- | :---------------: |
| Samuel |        75%        |
| Thiago |        25%        |

## Histórico de Versão

| Versão |    Data    | Descrição                               |   Autor(es)    | Revisor |
| :----: | :--------: | :-------------------------------------- | :------------: | :-----: |
|  1.0   | 07/10/2025 | Criação inicial do documento de léxicos | Samuel, Thiago |    -    |
