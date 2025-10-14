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

#### L01 - Membro {#l01-membro}

- **Noção:**
  Pessoa que realizou o [Cadastro](#l03-cadastrar) e possui uma [Conta](#) ativa no site **LigaMagic**, diferenciando-se de um [Visitante](#l02-visitante), que não possui cadastro.
- **Impacto:**
  - Executa [Login](#l04-login) para acessar funcionalidades restritas.
  - Pode [Comprar](#l06-comprar-carta) e vender [Cartas](#l08-carta), atuando como [Comprador](#) ou [Vendedor](#).
  - Gerencia sua [Coleção de Cartas](#l10-colecao-de-cartas).
  - Cria e gerencia [Decks](#l09-deck), atuando como [Jogador](#).
  - Participa ativamente do [Fórum](#l13-forum).

#### L02 - Visitante {#l02-visitante}

- **Noção:**
  Pessoa que navega pelo site **LigaMagic** sem ter realizado [Login](#l04-login) em uma [Conta](#). Possui acesso limitado às funcionalidades públicas da plataforma.
- **Impacto:**
  - Pode [Pesquisar](#l05-pesquisar-carta) por [Cartas](#l08-carta) e visualizar seus detalhes.
  - Consegue visualizar [Decks](#l09-deck) públicos criados pela comunidade.
  - Pode ler os tópicos e mensagens do [Fórum](#l13-forum).
  - É impedido de realizar ações restritas, como [Comprar Carta](#l06-comprar-carta), [Leiloar Carta](#l07-leiloar-carta), criar [Decks](#l09-deck), gerenciar uma [Coleção de Cartas](#l10-colecao-de-cartas) ou publicar no [Fórum](#l13-forum).
  - Pode iniciar o processo de [Cadastro](#l03-cadastrar) para se tornar um [Membro](#l01-membro).

---

### VERBO

#### L03 - Cadastrar {#l03-cadastrar}

- **Noção:**
  Ação realizada por um [Visitante](#l02-visitante) para criar uma [Conta](#) no sistema. Ocorre quando o [Visitante](#l02-visitante) preenche um formulário com dados pessoais (nome, e-mail, senha).
- **Impacto:**
  - O sistema verifica se os dados são válidos e se o e-mail já está registrado.
  - Cria uma nova [Conta](#) no banco de dados.
  - Muda o estado do [Visitante](#l02-visitante) para [Membro](#l01-membro).
  - Permite que o novo [Membro](#l01-membro) realize [Login](#l04-login).

#### L04 - Login {#l04-login}

- **Noção:**
  Ação realizada por um [Membro](#l01-membro) para acessar sua [Conta](#). Ocorre quando o [Membro](#l01-membro) informa suas credenciais (e-mail e senha) em um formulário específico.
- **Impacto:**
  - O sistema autentica as credenciais do [Membro](#l01-membro).
  - Inicia uma sessão segura, dando acesso a áreas restritas como "Minha [Coleção de Cartas](#l10-colecao-de-cartas)" e "Meus [Decks](#l09-deck)".
  - Se as credenciais estiverem incorretas, o acesso é negado.
  - É um pré-requisito para as ações de [Comprar Carta](#l06-comprar-carta) e [Leiloar Carta](#l07-leiloar-carta).

#### L05 - Pesquisar Carta {#l05-pesquisar-carta}

- **Noção:**
  Ação realizada por qualquer pessoa ([Visitante](#l02-visitante) ou [Membro](#l01-membro)) para encontrar uma [Carta](#l08-carta) específica no banco de dados do site. O usuário insere critérios de busca, como nome, cor, tipo ou [Edição](#l11-edicao).
- **Impacto:**
  - O sistema filtra o banco de dados de [Cartas](#l08-carta) com base nos critérios fornecidos.
  - Exibe uma lista de [Cartas](#l08-carta) correspondentes à pesquisa.
  - Permite a visualização dos detalhes de uma [Carta](#l08-carta) específica.
  - A partir do resultado, um [Membro](#l01-membro) pode adicionar a [Carta](#l08-carta) a um [Deck](#l09-deck) ou à sua [Coleção de Cartas](#l10-colecao-de-cartas).

#### L06 - Comprar Carta {#l06-comprar-carta}

- **Noção:**
  Ação realizada por um [Membro](#l01-membro), na função de [Comprador](#), para adquirir uma [Carta](#l08-carta) de um [Vendedor](#) na plataforma. Ocorre após o [Membro](#l01-membro) selecionar uma [Carta](#l08-carta) e adicioná-la ao [Carrinho de Compras](#l21-carrinho-ativo).
- **Impacto:**
  - A [Carta](#l08-carta) é movida para o [Carrinho de Compras](#l21-carrinho-ativo) do [Membro](#l01-membro).
  - O sistema processa o pagamento.
  - Após a confirmação, o sistema registra a transação e notifica o [Vendedor](#).
  - A [Carta](#l08-carta) pode ser adicionada automaticamente à [Coleção de Cartas](#l10-colecao-de-cartas) do [Membro](#l01-membro).

#### L07 - Leiloar Carta {#l07-leiloar-carta}

- **Noção:**
  Processo iniciado por um [Membro](#l01-membro), na função de [Vendedor](#), para vender uma [Carta](#l08-carta) ao [Membro](#l01-membro) que oferecer o maior lance dentro de um período determinado. O [Vendedor](#) define um lance inicial e a duração do [Leilão](#l15-leilao-ativo).
- **Impacto:**
  - Cria um registro de [Leilão](#l15-leilao-ativo) no sistema, associado à [Carta](#l08-carta) e ao [Vendedor](#).
  - A [Carta](#l08-carta) fica temporariamente indisponível para venda direta.
  - Outros [Membros](#l01-membro) podem registrar lances.
  - Ao término do período, a [Carta](#l08-carta) é vendida ao [Membro](#l01-membro) com o maior lance.

---

### OBJETO

#### L08 - Carta {#l08-carta}

- **Noção:**
  Unidade fundamental do jogo Magic: The Gathering. Possui atributos como nome, custo de [Mana](#l14-mana), cor, [Edição](#l11-edicao), [Raridade](#), tipo e texto de [Habilidade](#).
- **Impacto:**
  - Pode ser pesquisada através da [Busca Avançada](#l05-pesquisar-carta).
  - Pode ser adicionada por um [Membro](#l01-membro) a uma [Coleção de Cartas](#l10-colecao-de-cartas).
  - É o componente principal de um [Deck](#l09-deck).
  - Pode ser comprada, vendida ou leiloada por [Membros](#l01-membro).
  - Seu preço é exibido e acompanhado pelo sistema.

#### L09 - Deck {#l09-deck}

- **Noção:**
  Conjunto de no mínimo 60 [Cartas](#l08-carta) que um [Membro](#l01-membro) utiliza para jogar. É baseado em um [Formato](#l12-formato) específico e em uma estratégia de jogo.
- **Impacto:**
  - Um [Membro](#l01-membro) pode criar, editar e salvar múltiplos [Decks](#l09-deck).
  - Pode ter sua lista de [Cartas](#l08-carta) (Decklist) exportada ou compartilhada.
  - Pode ser analisado pelo sistema para verificar sua legalidade em um [Formato](#l12-formato) específico.
  - [Decks](#l09-deck) criados por [Membros](#l01-membro) podem ser públicos ou privados.

#### L10 - Coleção de Cartas {#l10-colecao-de-cartas}

- **Noção:**
  Ferramenta que permite a um [Membro](#l01-membro) catalogar todas as [Cartas](#l08-carta) que possui.
- **Impacto:**
  - Facilita o gerenciamento da coleção pessoal do [Membro](#l01-membro).
  - Auxilia na montagem de [Decks](#l09-deck) ao mostrar as [Cartas](#l08-carta) disponíveis para o [Membro](#l01-membro).
  - Permite ao [Membro](#l01-membro) identificar [Cartas](#l08-carta) para venda ou troca.

#### L11 - Edição {#l11-edicao}

- **Noção:**
  Conjunto de [Cartas](#l08-carta) de Magic: The Gathering lançadas juntas em uma data específica. Cada [Edição](#l11-edicao) possui um símbolo único que a identifica.
- **Impacto:**
  - É um critério fundamental na [Pesquisa de Carta](#l05-pesquisar-carta).
  - Determina a legalidade de uma [Carta](#l08-carta) em um [Formato](#l12-formato) de jogo.
  - Ajuda o [Membro](#l01-membro) a organizar sua [Coleção de Cartas](#l10-colecao-de-cartas).
  - O preço de uma [Carta](#l08-carta) pode variar significativamente dependendo da sua [Edição](#l11-edicao).

#### L12 - Formato {#l12-formato}

- **Noção:**
  Conjunto de regras que define quais [Edições](#l11-edicao) de [Cartas](#l08-carta) são permitidas na construção de um [Deck](#l09-deck). Exemplos: Standard, Modern, Commander.
- **Impacto:**
  - Restringe as [Cartas](#l08-carta) que um [Membro](#l01-membro) pode incluir ao criar um [Deck](#l09-deck).
  - O sistema pode validar um [Deck](#l09-deck) para verificar se ele é legal em um determinado [Formato](#l12-formato).
  - É um critério de busca para encontrar [Decks](#l09-deck) públicos e artigos estratégicos.

#### L13 - Fórum {#l13-forum}

- **Noção:**
  Seção do site onde os [Membros](#l01-membro) podem criar discussões (tópicos) e publicar mensagens para interagir com a comunidade de jogadores de Magic: The Gathering.
- **Impacto:**
  - Permite a troca de informações e estratégias entre os [Membros](#l01-membro).
  - Um [Membro](#l01-membro) pode criar, responder e seguir tópicos.
  - O conteúdo do [Fórum](#l13-forum) é moderado para garantir o cumprimento das regras da comunidade.

#### L14 - Mana {#l14-mana}

- **Noção:**
  Recurso fundamental do jogo, utilizado para conjurar as mágicas (jogar as [Cartas](#l08-carta)). A [Mana](#l14-mana) é representada por cores (Branco, Azul, Preto, Vermelho, Verde) e símbolos incolores.
- **Impacto:**
  - O "Custo de Mana" é um atributo principal de uma [Carta](#l08-carta).
  - É um critério essencial para a construção de um [Deck](#l09-deck) por um [Membro](#l01-membro).
  - É utilizado como filtro na [Pesquisa de Carta](#l05-pesquisar-carta).

---

### ESTADO

#### L15 - Leilão Ativo {#l15-leilao-ativo}

- **Noção:**
  - Período em que um [Leilão](#l15-leilao-ativo) está aberto para receber lances dos [Membros](#l01-membro). Inicia-se quando o [Vendedor](#) cadastra a [Carta](#l08-carta) para leiloar e termina quando o tempo definido expira.
- **Impacto:**
  - [Membros](#l01-membro) podem submeter lances de valor superior ao lance atual.
  - O sistema exibe o tempo restante e o maior lance publicamente.
  - Ao final do tempo, transita para o estado [Leilão Encerrado](#l16-leilao-encerrado).

#### L16 - Leilão Encerrado {#l16-leilao-encerrado}

- **Noção:**
  - Situação de um [Leilão](#l15-leilao-ativo) após o término do seu prazo.
- **Impacto:**
  - O sistema não aceita mais novos lances para este [Leilão](#l15-leilao-ativo).
  - O [Membro](#l01-membro) com o maior lance é declarado o vencedor.
  - Inicia o processo de transação, movendo a compra para o estado [Pagamento Aprovado](#l17-pagamento-aprovado).

#### L17 - Pagamento Aprovado {#l17-pagamento-aprovado}

- **Noção:**
  - Situação de uma transação após a confirmação do pagamento pela instituição financeira.
- **Impacto:**
  - O [Vendedor](#) recebe uma notificação oficial para preparar e enviar o pedido.
  - A transação é confirmada no histórico de compras do [Comprador](#) e de vendas do [Vendedor](#).
  - Libera a próxima etapa do fluxo, que levará ao estado [Pedido Enviado](#l18-pedido-enviado).

#### L18 - Pedido Enviado {#l18-pedido-enviado}

- **Noção:**
  - Situação de uma compra após o [Vendedor](#) despachar o produto e registrar o envio na plataforma.
- **Impacto:**
  - O [Comprador](#) é notificado de que seu pedido está a caminho.
  - O código de rastreamento, se aplicável, é disponibilizado para o [Comprador](#).
  - Habilita a ação de [Avaliar Transação](#) para o [Comprador](#) após o recebimento.

#### L19 - Pedido Entregue {#l19-pedido-entregue}

- **Noção:**
  - Situação final de uma transação, que ocorre quando o [Comprador](#) confirma o recebimento do produto em bom estado.
- **Impacto:**
  - O ciclo da transação é formalmente encerrado.
  - Libera o pagamento para o [Vendedor](#), caso esteja retido pelo sistema.
  - Permite que tanto o [Comprador](#) quanto o [Vendedor](#) realizem a [Avaliar Transação](#).

#### L20 - Pedido Cancelado {#l20-pedido-cancelado}

- **Noção:**
  - Situação de uma transação que foi interrompida e anulada antes de ser concluída. O cancelamento pode ocorrer por falta de pagamento, a pedido do [Comprador](#) ou por impossibilidade de envio pelo [Vendedor](#).
- **Impacto:**
  - A transação é registrada como inválida no histórico de ambos os [Membros](#l01-membro).
  - As [Cartas](#l08-carta) do pedido retornam ao estoque do [Vendedor](#) e ficam disponíveis para venda novamente.
  - Dispara o envio de notificações para [Comprador](#) e [Vendedor](#) informando sobre o cancelamento.

#### L21 - Carrinho Ativo {#l21-carrinho-ativo}

- **Noção:**
  - Situação em que o [Carrinho de Compras](#l21-carrinho-ativo) de um [Membro](#l01-membro) contém um ou mais itens selecionados, mas a compra ainda não foi finalizada.
- **Impacto:**
  - Os itens no carrinho não ficam reservados no estoque do [Vendedor](#) e podem ser adquiridos por outro [Comprador](#).
  - Permite ao [Membro](#l01-membro) adicionar mais itens, remover existentes ou alterar quantidades.
  - Ao finalizar a compra, transita para o estado [Pagamento Aprovado](#l17-pagamento-aprovado). Se esvaziado, retorna ao estado "Carrinho Vazio".

---

## Video de validação feita com um jogador

Para realizar a validação dos requisitos fizemos uma consulta com um Jogador do app, disponível aqui:

- [Assista ao vídeo no YouTube](https://youtu.be/-oI5j4mZHHI). Este video foi produzido pela aluna Angélica Campos.
  Observação: a câmera parou de gravar um dos participantes por um breve período, mas o conteúdo da apresentação foi preservado.
- [Assista ao vídeo no YouTube](https://youtu.be/3K4RufgxZ-E). Este video foi produzido pela aluna Vera Lucia Bezerra.
- [Assista ao vídeo no YouTube](https://youtu.be/YXONTjL32WU). Este video foi produzido pelo aluno Thiago Viriato Accioly (Na descrição tem os minutos de cada parte).
- [Assista ao vídeo no YouTube](https://youtu.be/YXONTjL32WU). Este video foi produzido pelo aluno Samuel Nogueira Caetano (Na descrição tem os minutos de cada parte).
- [Assista ao vídeo no YouTube](https://youtu.be/1lxHnaYfWR4). Este video foi produzido pelo aluno Marcelo De Araujo Lopes (Na descrição tem os minutos de cada parte).

## Bibliografia

> **SERRANO, Milene; SERRANO, Maurício.** _Requisitos – Aula 10_.

## Nível de Contribuição dos Integrantes

| Nome     | % de Contribuição |
| :------- | :---------------: |
| Samuel   |      16.67%       |
| Thiago   |      16.67%       |
| Angelica |      16.67%       |
| Vera     |      16.67%       |
| Raissa   |      16.67%       |
| Marcelo  |      16.67%       |

## Histórico de Versão

| Versão |    Data    | Descrição                                      |                  Autor(es)                  | Revisor |
| :----: | :--------: | :--------------------------------------------- | :-----------------------------------------: | :-----: |
|  1.0   | 07/10/2025 | Criação inicial do documento de léxicos        |               Samuel, Thiago                |    -    |
|  1.1   | 11/10/2025 | Adicionando Video de Validação                 |                   Raissa                    | Thiago  |
|  1.2   | 11/10/2025 | Adicionando Video de Validação dos integrantes |                   Thiago                    | Raissa  |
|  1.3   | 12/10/2025 | Melhorada a rastreabilidade dos requisitos     | [Samuel](https://github.com/samuelncaetano) | Thiago  |
