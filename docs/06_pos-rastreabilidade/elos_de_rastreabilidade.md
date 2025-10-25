# Elos de Pós-Rastreabilidade

## Introdução

A _rastreabilidade de requisitos_ é um pilar fundamental para a gerência e a qualidade no desenvolvimento de software. Ela é definida como a "habilidade de acompanhar e descrever a vida de um requisito, em ambas as direções". Um requisito não pode ser efetivamente gerenciado sem rastreabilidade.

Este documento adota o Meta-modelo de Toranzo, uma abordagem que estrutura a rastreabilidade classificando as informações em quatro níveis distintos: ambiental, organizacional, gerencial e desenvolvimento. (**Sayão e Leite.** _Rastreabilidade de Requisitos_) [[1]](#refs1); (**Milene Serrano e Maurício Serrano.** _Requisitos – Aula 26_) [[2]](#refs2)

A metodologia foca em dois tipos principais de rastreabilidade:

- **_Pré-Rastreabilidade (Origem dos Requisitos):_**
  - **_Backward-from:_** Estabelece o vínculo de cada requisito às suas fontes originais (stakeholders, documentos e técnicas de elicitação como [Análise de Documentos](../03_elicitacao/tecnicas/analise_documentos.md) e [Observação](../03_elicitacao/tecnicas/observacao.md)), respondendo às perguntas “quem solicitou”, “com qual objetivo” e “com base em qual evidência”.
- **_Pós-Rastreabilidade (Implementação dos Requisitos):_**
  - **_Forward-from:_** Estabelece o vínculo de cada requisito aos artefatos produzidos durante o desenvolvimento — como [Cenários](../05_modelagem/01_cenarios/cenarios.md), [Léxicos](../05_modelagem/02_lexicos/lexicos.md), [Casos de Uso](../05_modelagem/03_casos_de_uso/casos_de_uso.md), [Especificação Suplementar](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md), [Histórias de Usuário](../05_modelagem/05_Agil/01_historias_de_usuario.md), [Backlog](../05_modelagem/05_Agil/02_backlogs.md) e [NFR Framework](../05_modelagem/05_Agil/03_nfr_framework.md) — permitindo verificar cobertura de implementação, validar consistência entre artefatos e identificar lacunas ou impactos de mudança.

## Objetivo

O objetivo deste documento é estruturar e gerenciar os requisitos do sistema **LigaMagic** utilizando o Meta-modelo de Toranzo. Esta abordagem visa garantir que todos os requisitos sejam claramente ligados às suas fontes (elos _backward-from_) e aos artefatos criados durante o projeto (elos _forward-from_).

## Metodologia

Para aplicar o modelo, cada requisito ou artefato rastreável do **LigaMagic** é documentado em um cartão estruturado. Este cartão detalha o nível de informação, os elementos envolvidos e os elos de rastreabilidade, conforme o modelo da Tabela 1.

<p style="text-align: center"><b>Tabela 1:</b> Modelo de cartão</p>

| **Item**                   | **Descrição**                                                                       |
| -------------------------- | ----------------------------------------------------------------------------------- |
| **Descrição do requisito** | Qual requisito está sendo tratado (RFx, RNFx, etc.)                                 |
| **Categoria**              | Nível de informação (Ambiental, Organizacional, Gerencial ou Desenvolvimento)       |
| **Elementos**              | Elementos rastreáveis associados (ex: UCx, CENx, Backlog)                           |
| **Elos Backward-from**     | Tipo de elo (ex: Recurso) e a origem do requisito (ex: Backlog do Produto)          |
| **Elos Forward-from**      | Tipo de elo (ex: Satisfação, Representação) e o artefato que o satisfaz (ex: UC-01) |

<p style="text-align: left">Fonte: Estrutura adaptada do Meta-modelo de Toranzo (<b>Sayão e Leite</b> <em>Rastreabilidade de Requisitos<em>; <b>Milene Serrano e Maurício Serrano</b> <em>Requisitos – Aula 26<em>).</p>

## Legenda

As tabelas a seguir detalham os identificadores e relacionamentos utilizados neste documento para garantir a correta aplicação do Meta-modelo de Toranzo.

---

<p style="text-align: center"><b>Tabela 2:</b> Níveis de Informação.</p>

| **Nível de Informação** | **Descrição**                                                                                                               |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Ambiental**           | Informações oriundas do contexto no qual a organização está inserida.                                                       |
| **Organizacional**      | Informações pertencentes à organização                                                                                      |
| **Gerencial**           | Informações que auxiliam a gerência do projeto.                                                                             |
| **Desenvolvimento**     | Informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento (requisitos, diagramas, etc). |

<p style="text-align: left">Fonte: (<b>Sayão e Leite.</b> <em>Rastreabilidade de Requisitos</em>); (<b>Milene Serrano e Maurício Serrano.</b> <em>Requisitos – Aula 26</em>).</p>

---

<p style="text-align: center"><b>Tabela 3:</b> Elementos identificadores.</p>

| **Elemento**                  | **Identificador / Descrição** |
| ----------------------------- | ----------------------------- |
| **Requisito**                 | RFx, RNFx                     |
| **Caso de uso**               | UCx                           |
| **Cenário**                   | CEx                           |
| **História de usuário**       | USx                           |
| **Técnica de elicitação**     | OBx, ADx, Ex                  |
| **NFR Framework**             | NFRx                          |
| **Especificação suplementar** | ESx                           |

---

<p style="text-align: center"><b>Tabela 4:</b> Tipos de Elo.</p>

| **Tipo de Elo**   | **Descrição**                                                                                    |
| ----------------- | ------------------------------------------------------------------------------------------------ |
| **Backward-from** | Indica a origem do requisito, ligando requisitos às suas fontes.                                 |
| **Forward-from**  | Indica como o requisito contribui para outros elementos, ligando requisitos a artefatos criados. |

<p style="text-align: left">Fonte: (<b>Sayão e Leite.</b> <em>Rastreabilidade de Requisitos</em>); (<b>Milene Serrano e Maurício Serrano.</b> <em>Requisitos – Aula 26</em>).</p>

---

<p style="text-align: center"><b>Tabela 5:</b> Relacionamento entre Informações.</p>

| **Relacionamento**   | **Descrição**                                                                  |
| -------------------- | ------------------------------------------------------------------------------ |
| **Satisfação**       | Classe origem tem dependência de satisfação com a classe destino.              |
| **Recurso**          | Classe origem tem dependência de recurso com a classe destino.                 |
| **Responsabilidade** | Registra a participação, responsabilidade e ação de pessoas sobre artefatos.   |
| **Representação**    | Captura a representação ou modelagem dos requisitos em outras linguagens.      |
| **Alocado**          | Classe origem está relacionada à classe destino, que representa um subsistema. |
| **Agregação**        | Indica "composição" de elementos.                                              |

<p style="text-align: left">Fonte: (<b>Sayão e Leite.</b> <em>Rastreabilidade de Requisitos</em>); (<b>Milene Serrano e Maurício Serrano.</b> <em>Requisitos – Aula 26</em>).</p>

## Conteúdo

### Requisitos Funcionais

#### RF02 – Deve verificar duplicação de cadastros

| Item                   | Descrição                                                                                                 |
| ---------------------- | --------------------------------------------------------------------------------------------------------- |
| Descrição do requisito | [RF02 – Deve verificar duplicação de cadastros](../03_elicitacao/artefatos/requisitos_elicitados.md#rf02) |
| Categoria              | Desenvolvimento                                                                                           |
| Elementos              | História de Usuário: [US03](../05_modelagem/05_Agil/01_historias_de_usuario.md#us03)                      |
| Elos Backward-from     | Recurso → <br>[AD02](../03_elicitacao/tecnicas/analise_documentos.md#ad02)                                |
| Elos Forward-from      | Representação → <br>História de Usuário: [US03](../05_modelagem/05_Agil/01_historias_de_usuario.md#us03)  |

**Fonte:** Samuel, 2025.

#### RF11 – Deve permitir envio e respostas a mensagens no fórum

| Item                   | Descrição                                                                                                                                                                                                                                                  |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito | [RF11 – Deve permitir envio e respostas a mensagens no fórum](../03_elicitacao/artefatos/requisitos_elicitados.md#rf11)                                                                                                                                    |
| Categoria              | Desenvolvimento                                                                                                                                                                                                                                            |
| Elementos              | Cenário: [CE11](../05_modelagem/01_cenarios/cenarios.md#ce11); <br>Caso de Uso: [UC09](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc09); <br>História de Usuário: [US01](../05_modelagem/05_Agil/01_historias_de_usuario.md#us01)                     |
| Elos Backward-from     | Recurso → <br>[AD11](../03_elicitacao/tecnicas/analise_documentos.md#ad11)                                                                                                                                                                                 |
| Elos Forward-from      | Representação → <br>Cenário: [CE11](../05_modelagem/01_cenarios/cenarios.md#ce11); <br>Caso de Uso: [UC09](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc09); <br>História de Usuário: [US01](../05_modelagem/05_Agil/01_historias_de_usuario.md#us01) |

**Fonte:** Samuel, 2025.

#### RF20 – Pesquisa de cartas pelo nome

| Item                   | Descrição                                                                                                                                                                                                                                                                                                                    |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito | [RF20 – Pesquisa de cartas pelo nome](../03_elicitacao/artefatos/requisitos_elicitados.md#rf20)                                                                                                                                                                                                                              |
| Categoria              | Desenvolvimento                                                                                                                                                                                                                                                                                                              |
| Elementos              | Cenário: [CE03](../05_modelagem/01_cenarios/cenarios.md#ce03); <br>Caso de Uso: [UC02](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc02); <br>Histórias de Usuário: [US04](../05_modelagem/05_Agil/01_historias_de_usuario.md#us04), [US08](../05_modelagem/05_Agil/01_historias_de_usuario.md#us08)                     |
| Elos Backward-from     | Recurso → <br>[OBS01](../03_elicitacao/tecnicas/observacao.md#obs01)                                                                                                                                                                                                                                                         |
| Elos Forward-from      | Representação → <br>Cenário: [CE03](../05_modelagem/01_cenarios/cenarios.md#ce03); <br>Caso de Uso: [UC02](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc02); <br>Histórias de Usuário: [US04](../05_modelagem/05_Agil/01_historias_de_usuario.md#us04), [US08](../05_modelagem/05_Agil/01_historias_de_usuario.md#us08) |

**Fonte:** Samuel, 2025.

#### RF21.1 – Filtrar cartas por preço

| Item                   | Descrição                                                                                                |
| ---------------------- | -------------------------------------------------------------------------------------------------------- |
| Descrição do requisito | [RF21.1 – Filtrar cartas por preço](../03_elicitacao/artefatos/requisitos_elicitados.md#rf21_1)          |
| Categoria              | Desenvolvimento                                                                                          |
| Elementos              | História de Usuário: [US05](../05_modelagem/05_Agil/01_historias_de_usuario.md#us05)                     |
| Elos Backward-from     | Recurso → <br>[OBS02](../03_elicitacao/tecnicas/observacao.md#obs02)                                     |
| Elos Forward-from      | Representação → <br>História de Usuário: [US05](../05_modelagem/05_Agil/01_historias_de_usuario.md#us05) |

**Fonte:** Samuel, 2025.

#### RF36 – Compartilhar carta

| Item                   | Descrição                                                                                                                                                                                                                                                  |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito | [RF36 – Compartilhar carta](../03_elicitacao/artefatos/requisitos_elicitados.md#rf36)                                                                                                                                                                      |
| Categoria              | Desenvolvimento                                                                                                                                                                                                                                            |
| Elementos              | Cenário: [CE12](../05_modelagem/01_cenarios/cenarios.md#ce12); <br>Caso de Uso: [UC10](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc10); <br>História de Usuário: [US02](../05_modelagem/05_Agil/01_historias_de_usuario.md#us02)                     |
| Elos Backward-from     | Recurso → <br>[OBS17](../03_elicitacao/tecnicas/observacao.md#obs17)                                                                                                                                                                                       |
| Elos Forward-from      | Representação → <br>Cenário: [CE12](../05_modelagem/01_cenarios/cenarios.md#ce12); <br>Caso de Uso: [UC10](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc10); <br>História de Usuário: [US02](../05_modelagem/05_Agil/01_historias_de_usuario.md#us02) |

**Fonte:** Samuel, 2025.

### Requisitos Não Funcionais

## Referências

> <p><a id="refs1"></a>1.  <b>SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado.</b> <em>Rastreabilidade de Requisitos.</em></p>
> <p><a id="refs2"></a>2.  <b>SERRANO, Milene; SERRANO, Maurício.</b> <em>Requisitos – Aula 26.</em></p>

## Agradecimentos

O Grupo 02 agradece o apoio das ferramentas de Inteligência Artificial Generativa — ChatGPT e Google Gemini — na revisão e padronização de nossos artefatos. Essas tecnologias foram utilizadas para auxiliar na organização do repositório. Todo o conteúdo, incluindo a precisão técnica e as ideias apresentadas, é de responsabilidade dos autores.

## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição |
| :----- | :---------------: |
| Samuel |                   |

## Histórico de versão

| Versão |    Data    | Descrição                                                      |   Autor(es)    | Revisor |
| :----: | :--------: | :------------------------------------------------------------- | :------------: | :-----: |
|  1.0   | 23/10/2025 | Criação inicial do documento                                   |     Samuel     |  Vera   |
|  1.1   | 25/10/2025 | Adição das seções (Introdução, Objetivo, Metodologia, Legenda) | Samuel, Thiago |  Vera   |
| 1.1.1  | 25/10/2025 | Adição dos elos (RF02, RF11, RF20, RF21.1, RF36)               |     Samuel     | Thiago  |
