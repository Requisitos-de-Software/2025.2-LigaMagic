# Léxicos

## Descrição

Os léxicos são termos específicos do domínio da aplicação **LigaMagic** que possuem significado particular no contexto do sistema. Este documento apresenta a definição e o impacto de cada termo identificado, categorizando-os como **sujeitos** (atores), **verbos** (ações) ou **objetos** (entidades) do sistema.

## Objetivo

Definir e padronizar o vocabulário utilizado no projeto **LigaMagic**, garantindo que todos os envolvidos no desenvolvimento tenham uma compreensão uniforme dos termos específicos do domínio. Este artefato serve como referência para reduzir ambiguidades na comunicação e documentação do projeto.

## Metodologia

Os léxicos foram identificados por meio da análise do domínio da aplicação **LigaMagic**, e foram redigidos com o apoio da [lista de verificação](../../06_verificacao/entrega3/02_lexicos/verificacao_lexicos.md) utilizada na elaboração dos léxicos. Foram categorizados conforme a classificação LAL (Léxico Ampliado da Linguagem):


- **Sujeito**: Entidades que realizam ações no sistema
- **Verbo**: Ações que podem ser executadas no sistema
- **Objeto**: Entidades passivas manipuladas pelo sistema

Cada léxico possui:

- **Definição**: Explicação clara e concisa do termo
- **Impacto**: Como o termo afeta ou é afetado por outros elementos do sistema
- **Sinônimos**: Termos alternativos que podem ser utilizados para referenciar o mesmo conceito. Nem todos os léxicos possuem sinônimos, sendo identificados apenas quando existem variações comumente utilizadas no domínio.

## Léxicos Identificados

### SUJEITO

#### L01 - Membro

- **Definição:**
  Pessoa que realizou o `Cadastro` e possui uma `Conta` ativa no site **LigaMagic**, diferenciando-se de um `Visitante`, que não possui cadastro.
- **Impacto:**
  - Executa `Login` para acessar funcionalidades restritas.
  - Pode `Comprar` e vender `Cartas`, atuando como `Comprador` ou `Vendedor`.
  - Gerencia sua `Coleção de Cartas`.
  - Cria e gerencia `Decks`, atuando como `Jogador`.
  - Participa ativamente do `Fórum`.

#### L02 - Visitante

- **Definição:**
  Pessoa que navega pelo site **LigaMagic** sem ter realizado `Login` em uma `Conta`. Possui acesso limitado às funcionalidades públicas da plataforma.
- **Impacto:**
  - Pode `Pesquisar` por `Cartas` e visualizar seus detalhes.
  - Consegue visualizar `Decks` públicos criados pela comunidade.
  - Pode ler os tópicos e mensagens do `Fórum`.
  - É impedido de realizar ações restritas, como `Comprar Carta`, `Leiloar Carta`, criar `Decks`, gerenciar uma `Coleção de Cartas` ou publicar no `Fórum`.
  - Pode iniciar o processo de `Cadastro` para se tornar um `Membro`.

---

### VERBO

#### L03 - Cadastrar

- **Definição:**
  Ação realizada por um `Visitante` para criar uma `Conta` no sistema. Ocorre quando o `Visitante` preenche um formulário com dados pessoais (nome, e-mail, senha).
- **Impacto:**
  - O sistema verifica se os dados são válidos e se o e-mail já está registrado.
  - Cria uma nova `Conta` no banco de dados.
  - Muda o estado do `Visitante` para `Membro`.
  - Permite que o novo `Membro` realize `Login`.

#### L04 - Pesquisar Carta

- **Definição:**
  Ação realizada por qualquer pessoa (`Visitante` ou `Membro`) para encontrar uma `Carta` específica no banco de dados do site. O usuário insere critérios de busca, como nome, cor, tipo ou `Edição`.
- **Impacto:**
  - O sistema filtra o banco de dados de `Cartas` com base nos critérios fornecidos.
  - Exibe uma lista de `Cartas` correspondentes à pesquisa.
  - Permite a visualização dos detalhes de uma `Carta` específica.
  - A partir do resultado, um `Membro` pode adicionar a `Carta` a um `Deck` ou à sua `Coleção de Cartas`.

#### L05 - Comprar Carta

- **Definição:**
  Ação realizada por um `Membro`, na função de `Comprador`, para adquirir uma `Carta` de um `Vendedor` na plataforma. Ocorre após o `Membro` selecionar uma `Carta` e adicioná-la ao `Carrinho de Compras`.
- **Impacto:**
  - A `Carta` é movida para o `Carrinho de Compras` do `Membro`.
  - O sistema processa o pagamento.
  - Após a confirmação, o sistema registra a transação e notifica o `Vendedor`.
  - A `Carta` pode ser adicionada automaticamente à `Coleção de Cartas` do `Membro`.

#### L06 - Login

- **Definição:**
  Ação realizada por um `Membro` para acessar sua `Conta`. Ocorre quando o `Membro` informa suas credenciais (e-mail e senha) em um formulário específico.
- **Impacto:**
  - O sistema autentica as credenciais do `Membro`.
  - Inicia uma sessão segura, dando acesso a áreas restritas como "Minha `Coleção de Cartas`" e "Meus `Decks`".
  - Se as credenciais estiverem incorretas, o acesso é negado.
  - É um pré-requisito para as ações de `Comprar Carta` e `Leiloar Carta`.

#### L07 - Leiloar Carta

- **Definição:**
  Processo iniciado por um `Membro`, na função de `Vendedor`, para vender uma `Carta` ao `Membro` que oferecer o maior lance dentro de um período determinado. O `Vendedor` define um lance inicial e a duração do `Leilão`.
- **Impacto:**
  - Cria um registro de `Leilão` no sistema, associado à `Carta` e ao `Vendedor`.
  - A `Carta` fica temporariamente indisponível para venda direta.
  - Outros `Membros` podem registrar lances.
  - Ao término do período, a `Carta` é vendida ao `Membro` com o maior lance.

---

### OBJETO

#### L08 - Carta

- **Definição:**
  Unidade fundamental do jogo Magic: The Gathering. Possui atributos como nome, custo de `Mana`, cor, `Edição`, `Raridade`, tipo e texto de `Habilidade`.
- **Impacto:**
  - Pode ser pesquisada através da `Busca Avançada`.
  - Pode ser adicionada por um `Membro` a uma `Coleção de Cartas`.
  - É o componente principal de um `Deck`.
  - Pode ser comprada, vendida ou leiloada por `Membros`.
  - Seu preço é exibido e acompanhado pelo sistema.

#### L09 - Deck

- **Definição:**
  Conjunto de no mínimo 60 `Cartas` que um `Membro` utiliza para jogar. É baseado em um `Formato` específico e em uma estratégia de jogo.
- **Impacto:**
  - Um `Membro` pode criar, editar e salvar múltiplos `Decks`.
  - Pode ter sua lista de `Cartas` (Decklist) exportada ou compartilhada.
  - Pode ser analisado pelo sistema para verificar sua legalidade em um `Formato` específico.
  - `Decks` criados por `Membros` podem ser públicos ou privados.

#### L10 - Coleção de Cartas

- **Definição:**
  Ferramenta que permite a um `Membro` catalogar todas as `Cartas` que possui.
- **Impacto:**
  - Facilita o gerenciamento da coleção pessoal do `Membro`.
  - Auxilia na montagem de `Decks` ao mostrar as `Cartas` disponíveis para o `Membro`.
  - Permite ao `Membro` identificar `Cartas` para venda ou troca.

#### L11 - Edição

- **Definição:**
  Conjunto de `Cartas` de Magic: The Gathering lançadas juntas em uma data específica. Cada `Edição` possui um símbolo único que a identifica.
- **Impacto:**
  - É um critério fundamental na `Pesquisa de Carta`.
  - Determina a legalidade de uma `Carta` em um `Formato` de jogo.
  - Ajuda o `Membro` a organizar sua `Coleção de Cartas`.
  - O preço de uma `Carta` pode variar significativamente dependendo da sua `Edição`.
- **Sinônimo:**
  - Coleção.

#### L12 - Formato

- **Definição:**
  Conjunto de regras que define quais `Edições` de `Cartas` são permitidas na construção de um `Deck`. Exemplos: Standard, Modern, Commander.
- **Impacto:**
  - Restringe as `Cartas` que um `Membro` pode incluir ao criar um `Deck`.
  - O sistema pode validar um `Deck` para verificar se ele é legal em um determinado `Formato`.
  - É um critério de busca para encontrar `Decks` públicos e artigos estratégicos.

#### L13 - Fórum

- **Definição:**
  Seção do site onde os `Membros` podem criar discussões (tópicos) e publicar mensagens para interagir com a comunidade de jogadores de Magic: The Gathering.
- **Impacto:**
  - Permite a troca de informações e estratégias entre os `Membros`.
  - Um `Membro` pode criar, responder e seguir tópicos.
  - O conteúdo do `Fórum` é moderado para garantir o cumprimento das regras da comunidade.

#### L14 - Mana

- **Definição:**
  Recurso fundamental do jogo, utilizado para conjurar as mágicas (jogar as `Cartas`). A `Mana` é representada por cores (Branco, Azul, Preto, Vermelho, Verde) e símbolos incolores.
- **Impacto:**
  - O "Custo de Mana" é um atributo principal de uma `Carta`.
  - É um critério essencial para a construção de um `Deck` por um `Membro`.
  - É utilizado como filtro na `Pesquisa de Carta`.

---

## Bibliografia

> **SERRANO, Milene; SERRANO, Maurício.** *Requisitos – Aula 10*.

## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição |
| :----- | :---------------: |
| Samuel |        75%        |
| Thiago |        25%        |

## Histórico de Versão

| Versão |    Data    | Descrição                               | Autor(es) | Revisor |
| :----: | :--------: | :-------------------------------------- | :-------: | :-----: |
|  1.0   | 07/10/2025 | Criação inicial do documento de léxicos |  Samuel   | Thiago  |
