# Glossário do Projeto: Magic: The Gathering

## Descrição

O glossário é um artefato de elicitação de requisitos que documenta e define os principais termos técnicos, conceitos específicos do domínio e funcionalidades relacionados ao projeto. Este documento organiza alfabeticamente os termos utilizados tanto no contexto do jogo Magic: The Gathering quanto nas ferramentas e recursos oferecidos pela plataforma LigaMagic, estabelecendo um vocabulário comum para toda a equipe e stakeholders. A metodologia e os conceitos aplicados neste documento foram baseados nas práticas descritas por Wiegers e Beatty (2013) na obra *Software Requirements*, adaptados para o contexto específico do projeto LigaMagic.

## Objetivo

O objetivo deste glossário é facilitar o entendimento e a comunicação entre os membros da equipe de desenvolvimento, usuários e demais partes interessadas, eliminando ambiguidades na interpretação de termos específicos. Ao consolidar definições claras, sinônimos, antônimos e remissivas entre conceitos relacionados, busca-se garantir que todos compartilhem uma compreensão uniforme dos requisitos e funcionalidades do sistema.

## Metodologia

A elaboração deste glossário foi realizada através da identificação e catalogação de termos relevantes durante as atividades de elicitação de requisitos. Cada termo foi definido com base no contexto do jogo Magic: The Gathering e da plataforma LigaMagic, incluindo sinônimos, antônimos quando aplicável, e remissivas cruzadas para facilitar a navegação entre conceitos relacionados. Os termos foram organizados em duas categorias principais: "Termos Gerais e de Jogo" e "Funcionalidades do Site", mantendo ordenação alfabética para facilitar a consulta.

## Conteúdo

### Termos Gerais e de Jogo

|  ID | Termo                            | Definição Revisada                                                                    | Sinônimos / Antônimos                                         | Remissivas                                              |  Autor |
| :-: | :------------------------------- | :------------------------------------------------------------------------------------ | :------------------------------------------------------------ | :------------------------------------------------------ | :----: |
|  1  | **Booster**                      | Pacote lacrado de cartas pertencentes a uma coleção específica.                       | Sinônimos: Pacote — Antônimos: Não há                         | Ver: *Coleção*                                          | Samuel |
|  2  | **Card**                         | Termo em inglês para “carta”, unidade fundamental do jogo.                            | Sinônimos: Carta — Antônimos: Não há                          | Ver: Deck                                                       | Samuel |
|  3  | **Coleção / Edição (Set)**       | Conjunto de cartas lançado em uma data específica, com tema e símbolo próprios.       | Sinônimos: Edição — Antônimos: Não há                         | Ver: *Formato*                                          | Samuel |
|  11 | **Criatura (Creature)**          | Tipo de carta que representa um ser que luta pelo jogador; pode atacar e bloquear.    | Sinônimos: Bicho (informal) — Antônimos: Não há               | Ver: *Habilidade*                                       | Thiago |
|  4  | **Deck**                         | Baralho de no mínimo 60 cartas utilizado em partidas.                                 | Sinônimos: Baralho, Biblioteca (informal) — Antônimos: Não há | Ver: *Decklist*, *Arquétipo*                            | Samuel |
|  5  | **Decklist**                     | Lista completa das cartas que compõem um deck.                                        | Sinônimos: Lista de deck — Antônimos: Não há                  | Ver: *Deck*                                             | Samuel |
|  13 | **Feitiço (Sorcery)**            | Carta que só pode ser jogada na fase principal do jogador.                            | Sinônimos: Não há — Antônimos: Não há                         | Ver também: *Mágica Instantânea*                        | Thiago |
|  6  | **Formato**                      | Conjunto de regras que define quais coleções podem ser usadas na construção de decks. | Sinônimos: Não há — Antônimos: Não há                         | Ver: *Coleção*                                          | Samuel |
|  14 | **Habilidade (Ability)**         | Texto de uma carta que descreve efeitos ativados, desencadeados ou estáticos.         | Sinônimos: Não há — Antônimos: Não há                         | Ver também: *Criatura*, *Feitiço*, *Mágica Instantânea* | Thiago |
|  12 | **Mágica Instantânea (Instant)** | Feitiço que pode ser jogado a qualquer momento, inclusive no turno do oponente.       | Sinônimos: Instantânea — Antônimos: Não há                    | Ver: *Feitiço*                                          | Thiago |
|  7  | **Mana**                         | Energia usada para conjurar feitiços, representada por cores.                         | Sinônimos: Não há — Antônimos: Não há                         | Ver: *Terreno*                                          | Samuel |
|  8  | **Raridade**                     | Classificação que indica a frequência com que uma carta aparece em boosters.          | Sinônimos: Não há — Antônimos: Não há                         | Ver: Carta                                                       | Samuel |
|  9  | **Sideboard**                    | Até 15 cartas extras usadas para ajustar o deck entre partidas.                       | Sinônimos: Reserva — Antônimos: Não há                        | Ver: *Deck*                                             | Samuel |
|  10 | **Terreno (Land)**               | Tipo de carta que gera mana.                                                          | Sinônimos: Não há — Antônimos: Não há                         | Ver: *Mana*                                             | Samuel |


<div align="center">
  <strong>Autoria de <a href="https://github.com/samuelncaetano">Samuel Nogueira Caetano</a> e de <a href="https://github.com/Acciolyy">Thiago Accioly</a></strong>
</div>

### Funcionalidades do Site

|  ID | Termo                             | Definição Revisada                                                                           | Sinônimos / Antônimos                                    | Remissivas              | URL                                                                                                                                          |  Autor |
| :-: | :-------------------------------- | :------------------------------------------------------------------------------------------- | :------------------------------------------------------- | :---------------------- | :------------------------------------------------------------------------------------------------------------------------------------------- | :----: |
|  1  | **Arquétipo**                     | Classificação da estratégia principal de um deck (Aggro, Control, Combo, Midrange).          | Sinônimos: Estratégia — Antônimos: Não há                | Ver: *Deck*, *Decklist* | [https://www.ligamagic.com.br/?view=dks/decks](https://www.ligamagic.com.br/?view=dks/decks)                                                 | Samuel |
|  2  | **Artigos**                       | Seção de publicações com conteúdo sobre estratégias, análises, novidades e campeonatos.      | Sinônimos: Publicações, Posts — Antônimos: Não há        | Não há                       | [https://www.ligamagic.com.br/?view=artigos/home&artigos=1&noticias=1](https://www.ligamagic.com.br/?view=artigos/home&artigos=1&noticias=1) | Samuel |
|  3  | **Busca Avançada**                | Ferramenta que permite filtrar cartas por critérios variados.                                | Sinônimos: Pesquisa detalhada — Antônimos: Busca simples | Ver: *Card*, *Coleção*  | [https://www.ligamagic.com.br/?view=dks/decks](https://www.ligamagic.com.br/?view=dks/decks)                                                 | Samuel |
|  6  | **Carrinho / Meu Carrinho**       | Lista de produtos selecionados para posterior compra.                                        | Sinônimos: Carrinho de compras — Antônimos: Não há       | Ver: Leilão                       | [https://www.ligamagic.com.br/?view=mp/carrinho&open=1](https://www.ligamagic.com.br/?view=mp/carrinho&open=1)                               | Thiago |
|  4  | **Fórum (Forum)**                 | Espaço de discussão para tópicos, dúvidas e interações da comunidade.                        | Sinônimos: Comunidade, Discussão — Antônimos: Não há     | Não há                       | [https://www.ligamagic.com.br/?view=forum/forum](https://www.ligamagic.com.br/?view=forum/forum)                                             | Thiago |
|  5  | **Leilão**                        | Modalidade em que compradores dão lances e vence quem oferece o maior valor no tempo limite. | Sinônimos: Auction (inglês) — Antônimos: Venda direta    | Ver: Carrinho                       | [https://www.ligamagic.com.br/?view=leilao/listar](https://www.ligamagic.com.br/?view=leilao/listar)                                         | Samuel |
|  7  | **Minha Coleção (My Collection)** | Ferramenta para catalogar cartas do usuário e gerenciar o acervo.                            | Sinônimos: Acervo pessoal — Antônimos: Não há            | Ver: *Deck*, *Card*     | [https://www.ligamagic.com.br/?view=colecao/colecao](https://www.ligamagic.com.br/?view=colecao/colecao)                                     | Thiago |



<div align="center">
  <strong>Autoria de <a href="https://github.com/samuelncaetano">Samuel Nogueira Caetano</a> e de <a href="https://github.com/Acciolyy">Thiago Accioly</a></strong>
</div>

---

[Técnica de elicitação – Glossário (PDF)](../../00_assets/pdfs/elicitacao/tecnica_de_elicitacao_glossario.pdf)

## Vídeo de Validação

[Link do Vídeo de Validação](https://youtu.be/3EbsaRfX9Tk)

## Referências
- **WIEGERS, Karl; BEATTY, Joy.** *Software Requirements. *3. ed. Redmond: Microsoft Press, 2013.

## Nível de Contribuição dos Integrantes
| Nome | % de Contribuição |
| ---- | ----------------- |
|  Samuel    |  50%                 |
|    Thiago  |        50%           |

## Histórico de versão

| Versão |    Data    | Descrição                                         | Autor(es) | Revisor(es) |
| :----: | :--------: | :------------------------------------------------ | :-------: | :---------: |
|  1.0   | 23/09/2025 | Elaboração da lista de verificação                |  Samuel   |   Thiago    |
|  1.1   | 30/09/2025 | Adicionado PDF do documento original do glossário |  Samuel   |   Thiago    |
|  1.2   | 02/09/2025 | Formatação e organização do documento             |  Samuel   |      -      |
|  1.3   | 24/10/2025 | Adição do Vídeo de Validação             |  Thiago   |      -      |
|  2.0   | 18/11/2025 | Correção das não conformidades: ordem alfabética, siglas, sinônimos/antônimos e remissivas             |  Thiago   |      Samuel      |
