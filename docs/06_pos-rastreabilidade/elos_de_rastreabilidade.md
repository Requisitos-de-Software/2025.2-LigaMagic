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

Para aplicar o modelo, cada requisito ou artefato rastreável do **LigaMagic** é documentado em um cartão estruturado. Este cartão detalha o nível de informação, a origem do requisito, os elementos envolvidos e os elos de rastreabilidade, conforme o modelo da Tabela 1. A partir desta versão:

- A origem do requisito (fonte de elicitação) é explicitada em campo próprio, preservando a evidência do vínculo.
- Os elos Backward-from e Forward-from registram o tipo do relacionamento e sua justificativa, sem listar diretamente os artefatos de destino.

<p style="text-align: center"><b>Tabela 1:</b> Modelo de cartão</p>

| Item                                      | Descrição                                                                                               |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | Qual requisito está sendo tratado (RFx, RNFx, etc.)                                                     |
| Categoria                                 | Nível de informação (Ambiental, Organizacional, Gerencial ou Desenvolvimento)                           |
| Origem do requisito                       | Técnica/fonte de elicitação e evidência (ex: ADx, OBSx, ENx)                                            |
| Elementos                                 | Elementos rastreáveis associados (ex: UCx, CEx, USx, Backlog)                                           |
| Elos Backward-from (tipo e justificativa) | Tipo do elo e por que se aplica à origem do requisito (ex: Recurso — a fonte fornece a evidência)       |
| Elos Forward-from (tipo e justificativa)  | Tipo do elo e por que se aplica à relação com artefatos de desenvolvimento (ex: Representação — modela) |

<p style="text-align: left">Fonte: Estrutura adaptada do Meta-modelo de Toranzo (<b>Sayão e Leite</b> <em>Rastreabilidade de Requisitos</em>; <b>Milene Serrano e Maurício Serrano</b> <em>Requisitos – Aula 26</em>).</p>

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

#### RF01 – Cadastro de usuário {#elo01}

| Item                                      | Descrição                                                                                                                                       |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF01 – Cadastro de usuário](../03_elicitacao/artefatos/requisitos_elicitados.md#rf01)                                                          |
| Categoria                                 | Gerenciamento de Usuários                                                                                                                       |
| Origem do requisito                       | [AD01](../03_elicitacao/tecnicas/analise_documentos.md#ad01)                                                                                    |
| Elementos                                 | História de Usuário: [US09](../05_modelagem/05_Agil/01_historias_de_usuario.md#us09)                                                            |
| Elos Backward-from (tipo e justificativa) | Recurso — A Análise de Documentos (AD01) demonstra a necessidade do cadastro como requisito básico de acesso, servindo como fonte de evidência. |
| Elos Forward-from (tipo e justificativa)  | Representação — A história de usuário modela o comportamento esperado para o processo de cadastro, descrevendo etapas e validações necessárias. |

**Fonte:** Angélica, 2025.

#### RF02 – Deve verificar duplicação de cadastros {#elo02}

| Item                                      | Descrição                                                                                                                                                                                                       |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF02 – Deve verificar duplicação de cadastros](../03_elicitacao/artefatos/requisitos_elicitados.md#rf02)                                                                                                       |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                 |
| Origem do requisito                       | [AD02](../03_elicitacao/tecnicas/analise_documentos.md#ad02)                                                                                                                                                    |
| Elementos                                 | História de Usuário: [US03](../05_modelagem/05_Agil/01_historias_de_usuario.md#us03)                                                                                                                            |
| Elos Backward-from (tipo e justificativa) | Recurso — A Análise de Documentos (AD02) fornece a evidência necessária para a formulação do requisito, caracterizando dependência de recurso. Não é Representação (não modela) nem Satisfação (não é solução). |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem descrevem como a verificar de cadastros deve operar. Opta-se por Representação em vez de Satisfação, pois a modelagem descreve o comportamento esperado.              |

**Fonte:** Samuel, 2025.

#### RF03 – Permitir acesso via login e senha {#elo03}

| Item                                      | Descrição                                                                                                                                                               |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF03 – Cadastro de usuário](../03_elicitacao/artefatos/requisitos_elicitados.md#rf03)                                                                                  |
| Categoria                                 | Autenticação e Segurança                                                                                                                                                |
| Origem do requisito                       | [AD03](../03_elicitacao/tecnicas/analise_documentos.md#ad03)                                                                                                            |
| Elementos                                 | História de Usuário: [US10](../05_modelagem/05_Agil/01_historias_de_usuario.md#us10)                                                                                    |
| Elos Backward-from (tipo e justificativa) | Recurso — A Análise de Documentos (AD03) evidencia que apenas usuários autenticados podem acessar áreas privadas do sistema.                                            |
| Elos Forward-from (tipo e justificativa)  | Representação — A história de usuário modela o comportamento esperado para o processo de autenticação, garantindo acesso seguro às funcionalidades privadas do sistema. |

**Fonte:** Angélica, 2025.

#### RF04 – O sistema deve restringir anúncios a produtos e serviços relacionados ao jogo Magic: The Gathering {#elo04}

| Item                                      | Descrição                                                                                                                                                                                                 |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF04 – O sistema deve restringir anúncios a produtos e serviços relacionados ao jogo Magic: The Gathering](../03_elicitacao/artefatos/requisitos_elicitados.md#rf04)                                     |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                           |
| Origem do requisito                       | [AD04](../03_elicitacao/tecnicas/analise_documentos.md#ad04)                                                                                                                                              |
| Elementos                                 | História de Usuário: [US15](../05_modelagem/05_Agil/01_historias_de_usuario.md#us15)                                                                                                                      |
| Elos Backward-from (tipo e justificativa) | A análise de documento (AD04) identificou a necessidade de manter a integridade temática do sistema, limitando os anúncios apenas a produtos e serviços relacionados ao universo de Magic: The Gathering. |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem descrevem como o sistema deve validar e limitar o conteúdo dos anúncios antes da publicação.                                                                    |

**Fonte:** Marcelo. 2025.

#### RF06 – Inclusão de textos, descrição e fotos nos anúncios {#elo06}

| Item                                          | Descrição                                                                                                                                                                                                                    |
| :-------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do Requisito                        | [RF06 – Deve permitir inclusão de textos, descrição e fotos nos anúncios](../03_elicitacao/artefatos/requisitos_elicitados.md#rf06)                                                                                          |
| Categoria                                     | Desenvolvimento                                                                                                                                                                                                              |
| Origem do Requisito                           | [AD06](../03_elicitacao/tecnicas/analise_documentos.md#ad06)                                                                                                                                                                 |
| Elementos                                     | História de Usuário: [US34](../05_modelagem/05_Agil/01_historias_de_usuario.md#us34)                                                                                                                                         |
| Elos Backward-from</br>(tipo e justificativa) | Recurso — O requisito depende de serviços de upload de imagens, armazenamento de textos e gerenciamento de dados do anúncio para funcionar corretamente. Esses recursos foram identificados na Análise de Documentos (AD06). |
| Elos Forward-from</br>(tipo e justificativa)  | Representação — A história de usuário representa o comportamento de inclusão de textos, descrição e fotos nos anúncios. Opta-se por Representação pois descreve a interação esperada sem comprovar implementação técnica.    |

**Fonte:** Vera. 2025.

#### RF10 – Deve permitir criação de páginas pessoais {#elo10}

| Item                                      | Descrição                                                                                                                                                                                                                              |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF10 – Deve permitir criação de páginas pessoais: O sistema deve permitir que cada usuário personalize e mantenha sua página pessoal/profissional](../03_elicitacao/artefatos/requisitos_elicitados.md#rf10)                          |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                        |
| Origem do requisito                       | [AD10](../03_elicitacao/tecnicas/analise_documentos.md#ad10)                                                                                                                                                                           |
| Elementos                                 | Cenário: [CE06](../05_modelagem/01_cenarios/cenarios.md#ce06); <br>Caso de Uso: [UC05](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc05); <br>História de Usuário: [US22](../05_modelagem/05_Agil/01_historias_de_usuario.md#us22) |
| Elos Backward-from (tipo e justificativa) | Recurso — A Análise de Documentos (AD10) fornece evidência da necessidade de personalização de páginas pessoais/profissionais pelos usuários.                                                                                          |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem descrevem como a funcionalidade de personalização de perfil deve operar. Prefere-se Representação pois modela o comportamento sem comprovar implementação.                                   |

**Fonte:** Marcelo, 2025.

#### RF11 – Deve permitir envio e respostas a mensagens no fórum {#elo11}

| Item                                      | Descrição                                                                                                                                                                                                                              |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF11 – Deve permitir envio e respostas a mensagens no fórum](../03_elicitacao/artefatos/requisitos_elicitados.md#rf11)                                                                                                                |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                        |
| Origem do requisito                       | [AD11](../03_elicitacao/tecnicas/analise_documentos.md#ad11)                                                                                                                                                                           |
| Elementos                                 | Cenário: [CE11](../05_modelagem/01_cenarios/cenarios.md#ce11); <br>Caso de Uso: [UC09](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc09); <br>História de Usuário: [US01](../05_modelagem/05_Agil/01_historias_de_usuario.md#us01) |
| Elos Backward-from (tipo e justificativa) | Recurso — A fonte documental AD11 sustenta a existência do requisito, logo o requisito depende do recurso informacional. Não é Representação (não traduz o requisito) nem Satisfação (não implementa a solução).                       |
| Elos Forward-from (tipo e justificativa)  | Representação — Os modelos (cenários, casos de uso e histórias) representam o comportamento de fórum. Preferido a Satisfação, pois ainda não atesta implementação, apenas formaliza o entendimento.                                    |

**Fonte:** Samuel, 2025.

#### RF12 – Registrar dados pessoais do usuário {#elo12}

| Item                                      | Descrição                                                                                                                                                                                                               |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF12 – Registrar dados pessoais do usuário: O sistema deve permitir o registro de dados como Nome, RG, CPF, Telefone, E-mail, Data de Nascimento e Endereço](../03_elicitacao/artefatos/requisitos_elicitados.md#rf12) |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                         |
| Origem do requisito                       | [AD12](../03_elicitacao/tecnicas/analise_documentos.md#ad12)                                                                                                                                                            |
| Elementos                                 | História de Usuário: [US21](../05_modelagem/05_Agil/01_historias_de_usuario.md#us21)                                                                                                                                    |
| Elos Backward-from (tipo e justificativa) | Recurso — A Análise de Documentos (AD12) fornece evidência da necessidade de coleta de dados pessoais para identificação e gestão de usuários.                                                                          |
| Elos Forward-from (tipo e justificativa)  | Representação — A história de usuário representa o processo de registro de dados pessoais. Opta-se por Representação pois descreve os campos e validações esperadas sem atestar implementação técnica.                  |

**Fonte:** Thiago, 2025.

#### RF16 – Oferecer canal de contato para solicitações {#elo16}

| Item                                      | Descrição                                                                                                                                                                                                     |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF16 – Oferecer canal de contato para solicitações: O sistema deve disponibilizar canal (e-mail ou link) para o exercício dos direitos do titular](../03_elicitacao/artefatos/requisitos_elicitados.md#rf16) |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                               |
| Origem do requisito                       | [AD16](../03_elicitacao/tecnicas/analise_documentos.md#ad16)                                                                                                                                                  |
| Elementos                                 | História de Usuário: [US24](../05_modelagem/05_Agil/01_historias_de_usuario.md#us24)                                                                                                                          |
| Elos Backward-from (tipo e justificativa) | Recurso — A Análise de Documentos (AD16) fornece evidência legal (LGPD) da necessidade de canal de contato para exercício de direitos do titular.                                                             |
| Elos Forward-from (tipo e justificativa)  | Representação — A história de usuário representa como o canal de contato deve ser disponibilizado. Opta-se por Representação pois formaliza o requisito legal sem atestar implementação.                      |

**Fonte:** Thiago, 2025.

#### RF19 – Solicitar atualização de dados pessoais {#elo19}

| Item                                      | Descrição                                                                                                                                                          |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Descrição do requisito                    | [RF19 – Solicitar atualização de dados pessoais ](../03_elicitacao/artefatos/requisitos_elicitados.md#rf19)                                                        |
| Categoria                                 | Gerenciamento de Usuários                                                                                                                                          |
| Origem do requisito                       | [AD19](../03_elicitacao/tecnicas/analise_documentos.md#ad19)                                                                                                       |
| Elementos                                 | Cenário: [CE06](../05_modelagem/01_cenarios/cenarios.md#ce06); <br>História de Usuário: [US11](../05_modelagem/05_Agil/01_historias_de_usuario.md#us11)            |
| Elos Backward-from (tipo e justificativa) | Recurso — A Análise de Documentos (AD19) indica que usuários precisam alterar dados cadastrais para manter suas informações atualizadas, justificando o requisito. |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem representam como o requisito será atendido, descrevendo comportamento esperado e validação funcional.                    |

**Fonte:** Angélica, 2025.

#### RF20 – Pesquisa de cartas pelo nome {#elo20}

| Item                                      | Descrição                                                                                                                                                                                                                                                                                                |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF20 – Pesquisa de cartas pelo nome](../03_elicitacao/artefatos/requisitos_elicitados.md#rf20)                                                                                                                                                                                                          |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                                                                                          |
| Origem do requisito                       | [OBS01](../03_elicitacao/tecnicas/observacao.md#obs01)                                                                                                                                                                                                                                                   |
| Elementos                                 | Cenário: [CE03](../05_modelagem/01_cenarios/cenarios.md#ce03); <br>Caso de Uso: [UC02](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc02); <br>Histórias de Usuário: [US04](../05_modelagem/05_Agil/01_historias_de_usuario.md#us04), [US08](../05_modelagem/05_Agil/01_historias_de_usuario.md#us08) |
| Elos Backward-from (tipo e justificativa) | Recurso — A Observação (OBS01) provê evidência do contexto de uso e necessidade do usuário.                                                                                                                                                                                                              |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem descrevem como a busca deve operar. Não é Satisfação, pois não demonstra implementação/teste; é a formalização do comportamento requerido.                                                                                                                     |

**Fonte:** Samuel, 2025.

#### RF21.1 – Filtrar cartas por preço {#elo21_1}

| Item                                      | Descrição                                                                                                                                                              |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF21.1 – Filtrar cartas por preço](../03_elicitacao/artefatos/requisitos_elicitados.md#rf21_1)                                                                        |
| Categoria                                 | Desenvolvimento                                                                                                                                                        |
| Origem do requisito                       | [OBS02](../03_elicitacao/tecnicas/observacao.md#obs02)                                                                                                                 |
| Elementos                                 | História de Usuário: [US05](../05_modelagem/05_Agil/01_historias_de_usuario.md#us05)                                                                                   |
| Elos Backward-from (tipo e justificativa) | Recurso — A Observação (OBS02) identifica a necessidade real de filtragem por preço.                                                                                   |
| Elos Forward-from (tipo e justificativa)  | Representação — A história descreve a regra de filtragem. Representação é adequada pois comunica a lógica esperada, sem atestar implementação (logo não é Satisfação). |

**Fonte:** Samuel, 2025.

#### RF21.2 – Filtragem de Cartas por Qualidade/Condição {#elo21_2}

| Item                                      | Descrição                                                                                                                                                                                                                              |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF21.2 – Filtragem de Cartas por Qualidade/Condição](../03_elicitacao/artefatos/requisitos_elicitados.md#rf21.2)                                                                                                                      |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                        |
| Origem do requisito                       | [OBS02](../03_elicitacao/tecnicas/observacao.md#obs02)                                                                                                                                                                                 |
| Elementos                                 | Cenário: [CE07](../05_modelagem/01_cenarios/cenarios.md#ce07); <br>Caso de Uso: [UC06](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc06); <br>História de Usuário: [US14](../05_modelagem/05_Agil/01_historias_de_usuario.md#us14) |
| Elos Backward-from (tipo e justificativa) | Recurso — A observação (OBS02) identificou a necessidade de os usuários filtrarem cartas com base em sua qualidade física e condição de conservação, otimizando a experiência de busca.                                                |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem descrevem a forma como o sistema deve aplicar e exibir os filtros de condição de carta.                                                                                                      |

**Fonte:** Marcelo. 2025.

#### RF23 – Realizar compra de cartas {#elo23}

| Item                                          | Descrição                                                                                                                                                                                                                                                           |
| :-------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Descrição do Requisito                        | [RF23 – Realizar compra de cartas: Deve permitir que o usuário compre cartas cadastradas, incluindo dados pessoais e endereço de entrega](../03_elicitacao/artefatos/requisitos_elicitados.md#rf23)                                                                 |
| Categoria                                     | Desenvolvimento                                                                                                                                                                                                                                                     |
| Origem do Requisito                           | [OBS27](../03_elicitacao/tecnicas/observacao.md#obs27)                                                                                                                                                                                                              |
| Elementos                                     | História de Usuário: [US31](../05_modelagem/05_Agil/01_historias_de_usuario.md#us31)                                                                                                                                                                                |
| Elos Backward-from</br>(tipo e justificativa) | Recurso — O requisito depende de serviços de autenticação do usuário, do banco de dados de produtos e do sistema de pagamento para que a compra seja processada corretamente. Esses elementos são fundamentais para permitir a execução completa da funcionalidade. |
| Elos Forward-from</br>(tipo e justificativa)  | Representação — A história de usuário representa o comportamento de realização de compra de cartas. Opta-se por Representação pois descreve a interação esperada sem comprovar implementação técnica.                                                               |

**Fonte:** Vera. 2025.

#### RF24 – Histórico de compras {#elo24}

| Item                                      | Descrição                                                                                                                                              |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Descrição do requisito                    | [RF24 – Histórico de compras](../03_elicitacao/artefatos/requisitos_elicitados.md#rf24)                                                                |
| Categoria                                 | Gerenciamento de Usuários                                                                                                                              |
| Origem do requisito                       | [OBS05](../03_elicitacao/tecnicas/observacao.md#obs05)                                                                                                 |
| Elementos                                 | História de Usuário: [US12](../05_modelagem/05_Agil/01_historias_de_usuario.md#us12)                                                                   |
| Elos Backward-from (tipo e justificativa) | Recurso — A Observação (OBS05) evidenciou o padrão de comportamento dos usuários que consultam compras anteriores para acompanhar transações e gastos. |
| Elos Forward-from (tipo e justificativa)  | Representação — A história de usuário modela a funcionalidade necessária para exibição e detalhe das compras realizadas, representando o requisito.    |

**Fonte:** Angélica, 2025.

#### RF27 – Visualização de Detalhes da Carta {#elo27}

| Item                                      | Descrição                                                                                                                                                                |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Descrição do requisito                    | [RF27 – Visualização de Detalhes da Carta](../03_elicitacao/artefatos/requisitos_elicitados.md#rf27)                                                                     |
| Categoria                                 | Desenvolvimento                                                                                                                                                          |
| Origem do requisito                       | [OBS08](../03_elicitacao/tecnicas/observacao.md#obs08)                                                                                                                   |
| Elementos                                 | História de Usuário: [US16](../05_modelagem/05_Agil/01_historias_de_usuario.md#us16)                                                                                     |
| Elos Backward-from (tipo e justificativa) | Recurso — A observação (OBS08) mostrou que os usuários desejam visualizar informações completas das cartas, justificando a necessidade de uma página ou modal detalhado. |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem demonstram o comportamento esperado da interface ao exibir detalhes da carta, como imagem, edição, tipo e raridade.            |

**Fonte:** Marcelo. 2025.

#### RF29 – Permitir que o usuário avalie ou dê feedback sobre vendedores ou decks {#elo29}

| Item                                      | Descrição                                                                                                                                                                                                                              |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF29 – Permitir que o usuário avalie ou dê feedback sobre vendedores ou decks](../03_elicitacao/artefatos/requisitos_elicitados.md#rf29)                                                                                              |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                        |
| Origem do requisito                       | [OBS10](../03_elicitacao/tecnicas/observacao.md#obs10)                                                                                                                                                                                 |
| Elementos                                 | Cenário: [CE13](../05_modelagem/01_cenarios/cenarios.md#ce13); <br>Caso de Uso: [UC11](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc11); <br>História de Usuário: [US19](../05_modelagem/05_Agil/01_historias_de_usuario.md#us19) |
| Elos Backward-from (tipo e justificativa) | Recurso — A Observação (OBS10) fornece a evidência da necessidade de avaliação e feedback dos usuários, caracterizando dependência de recurso informacional.                                                                           |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem descrevem como o sistema de avaliação deve operar. Opta-se por Representação em vez de Satisfação, pois a modelagem descreve o comportamento esperado da funcionalidade de feedback.         |

**Fonte:** Thiago, 2025.

#### RF30 – Exibição de Informações Detalhadas da Carta {#elo30}

| Item                                      | Descrição                                                                                                                                                             |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF30 – Exibição de Informações Detalhadas da Carta](../03_elicitacao/artefatos/requisitos_elicitados.md#rf30)                                                        |
| Categoria                                 | Desenvolvimento                                                                                                                                                       |
| Origem do requisito                       | [OBS11](../03_elicitacao/tecnicas/observacao.md#obs11)                                                                                                                |
| Elementos                                 | História de Usuário: [US17](../05_modelagem/05_Agil/01_historias_de_usuario.md#us17)                                                                                  |
| Elos Backward-from (tipo e justificativa) | Recurso — A observação (OBS11) indicou a importância de apresentar informações detalhadas sobre cada carta, como histórico de versões, preço médio e disponibilidade. |
| Elos Forward-from (tipo e justificativa)  | Representação — Os elementos de modelagem descrevem como o sistema exibe informações aprofundadas da carta selecionada.                                               |

**Fonte:** Marcelo. 2025.

#### RF31 – Alerta de preço {#elo31}

| Item                                          | Descrição                                                                                                                                                                                                                            |
| :-------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do Requisito                        | [RF31 – Alerta de preço: Deve permitir que o usuário defina um alerta de preço para a carta selecionada](../03_elicitacao/artefatos/requisitos_elicitados.md#rf31)                                                                   |
| Categoria                                     | Desenvolvimento                                                                                                                                                                                                                      |
| Origem do Requisito                           | [OBS12](../03_elicitacao/tecnicas/observacao.md#obs12)                                                                                                                                                                               |
| Elementos                                     | Cenário: [CE04](../05_modelagem/01_cenarios/cenarios.md#ce04)</br>Caso de Uso: [UC03](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc03)</br>História de Usuário: [US36](../05_modelagem/05_Agil/01_historias_de_usuario.md#us36) |
| Elos Backward-from</br>(tipo e justificativa) | Recurso — O requisito depende de um serviço de monitoramento de preços e de notificações, além de dados de preço das cartas. Esses recursos são necessários para verificar variações e enviar alertas aos usuários.                  |
| Elos Forward-from</br>(tipo e justificativa)  | Representação — A história de usuário representa o comportamento de configuração de alertas de preço. Opta-se por Representação pois descreve a interação esperada sem comprovar implementação técnica.                              |

**Fonte:** Vera. 2025.

#### RF32 – Permitir que o usuário busque decks que utilizam a carta selecionada {#elo32}

| Item                                      | Descrição                                                                                                                                                                             |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF32 – Permitir que o usuário busque decks que utilizam a carta selecionada](../03_elicitacao/artefatos/requisitos_elicitados.md#rf32)                                               |
| Categoria                                 | Desenvolvimento                                                                                                                                                                       |
| Origem do requisito                       | [OBS13](../03_elicitacao/tecnicas/observacao.md#obs13)                                                                                                                                |
| Elementos                                 | [US18](../05_modelagem/05_Agil/01_historias_de_usuario.md#us18)                                                                                                                       |
| Elos Backward-from (tipo e justificativa) | Recurso — A observação (OBS11) destacou o interesse dos usuários em explorar decks existentes que utilizam uma carta específica, justificando o desenvolvimento da busca relacionada. |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem descrevem o comportamento da busca e a exibição dos decks correspondentes.                                                                  |

**Fonte:** Marcelo. 2025.

#### RF33 – Preço médio por edição {#elo33}

| Item                                          | Descrição                                                                                                                                                                                                                                 |
| :-------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do Requisito                        | [RF33 –Preço médio por edição: Deve permitir que o usuário visualize o preço médio da carta em diferentes edições e condições](../03_elicitacao/artefatos/requisitos_elicitados.md#rf33)                                                  |
| Categoria                                     | Desenvolvimento                                                                                                                                                                                                                           |
| Origem do Requisito                           | [OBS14](../03_elicitacao/tecnicas/observacao.md#obs14)                                                                                                                                                                                    |
| Elementos                                     | História de Usuário: [US33](../05_modelagem/05_Agil/01_historias_de_usuario.md#us33)                                                                                                                                                      |
| Elos Backward-from</br>(tipo e justificativa) | Recurso — O requisito depende de dados consolidados de preços por edição e condição de carta, obtidos de fontes de mercado ou base interna. Esses dados são essenciais para gerar os cálculos de média e exibir os resultados ao usuário. |
| Elos Forward-from</br>(tipo e justificativa)  | Representação — A história de usuário representa o comportamento de exibição de preços médios por edição. Opta-se por Representação pois descreve a interação esperada sem comprovar implementação técnica.                               |

**Fonte:** Vera. 2025.

#### RF34 – Histórico de preços {#elo34}

| Item                                          | Descrição                                                                                                                                                                                                                                            |
| :-------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do Requisito                        | [RF34 – Histórico de preços: Deve permitir que o usuário acesse o histórico de preços da carta em formato gráfico](../03_elicitacao/artefatos/requisitos_elicitados.md#rf34)                                                                         |
| Categoria                                     | Desenvolvimento                                                                                                                                                                                                                                      |
| Origem do Requisito                           | [OBS15](../03_elicitacao/tecnicas/observacao.md#obs15)                                                                                                                                                                                               |
| Elementos                                     | História de Usuário: [US32](../05_modelagem/05_Agil/01_historias_de_usuario.md#us32)                                                                                                                                                                 |
| Elos Backward-from</br>(tipo e justificativa) | Recurso — O requisito depende de registros históricos de preços armazenados em banco de dados e de um componente gráfico para exibição visual. Esses recursos são necessários para gerar e apresentar a evolução dos valores de forma compreensível. |
| Elos Forward-from</br>(tipo e justificativa)  | Representação — A história de usuário representa o comportamento de visualização do histórico de preços. Opta-se por Representação pois descreve a interação esperada sem comprovar implementação técnica.                                           |

**Fonte:** Vera. 2025.

#### RF35 – Adicionar a diferentes listas: Permitir que o usuário adicione a carta a diferentes listas {#elo35}

| Item                                      | Descrição                                                                                                                                                                                                        |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF35 – Adicionar a diferentes listas: Permitir que o usuário adicione a carta a diferentes listas (coleção, deck, lista de desejos, carrinho)](../03_elicitacao/artefatos/requisitos_elicitados.md#rf35)        |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                  |
| Origem do requisito                       | [OBS16](../03_elicitacao/tecnicas/observacao.md#obs16)                                                                                                                                                           |
| Elementos                                 | História de Usuário: [US23](../05_modelagem/05_Agil/01_historias_de_usuario.md#us23)                                                                                                                             |
| Elos Backward-from (tipo e justificativa) | Recurso — A Observação (OBS16) fornece evidência do comportamento dos usuários ao organizar cartas em diferentes contextos (compra, desejo, coleção, deck).                                                      |
| Elos Forward-from (tipo e justificativa)  | Representação — A história de usuário representa o comportamento de organização de cartas em múltiplas listas. Opta-se por Representação pois descreve a interação esperada sem comprovar implementação técnica. |

**Fonte:** Thiago, 2025.

#### RF36 – Compartilhar carta {#elo36}

| Item                                      | Descrição                                                                                                                                                                                                                              |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF36 – Compartilhar carta](../03_elicitacao/artefatos/requisitos_elicitados.md#rf36)                                                                                                                                                  |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                        |
| Origem do requisito                       | [OBS17](../03_elicitacao/tecnicas/observacao.md#obs17)                                                                                                                                                                                 |
| Elementos                                 | Cenário: [CE12](../05_modelagem/01_cenarios/cenarios.md#ce12); <br>Caso de Uso: [UC10](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc10); <br>História de Usuário: [US02](../05_modelagem/05_Agil/01_historias_de_usuario.md#us02) |
| Elos Backward-from (tipo e justificativa) | Recurso — A Observação (OBS17) fornece a necessidade de compartilhar por link direto; é insumo e não uma representação/solução.                                                                                                        |
| Elos Forward-from (tipo e justificativa)  | Representação — Os modelos capturam como o compartilhamento deve ocorrer. Prefere-se Representação, pois descrevem a interação esperada ao invés de comprovar implementação.                                                           |

**Fonte:** Samuel, 2025.

#### RF37 – Reportar problemas {#elo37}

| Item                                          | Descrição                                                                                                                                                                                                                            |
| :-------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do Requisito                        | [RF37 – Reportar problemas: Deve permitir que o usuário reporte problemas relacionados à carta (erros de informação, anúncios suspeitos, etc.)](../03_elicitacao/artefatos/requisitos_elicitados.md#rf37)                            |
| Categoria                                     | Desenvolvimento                                                                                                                                                                                                                      |
| Origem do Requisito                           | [OBS18](../03_elicitacao/tecnicas/observacao.md#obs18)                                                                                                                                                                               |
| Elementos                                     | Cenário: [CE05](../05_modelagem/01_cenarios/cenarios.md#ce05)</br>Caso de Uso: [UC04](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc04)</br>História de Usuário: [US35](../05_modelagem/05_Agil/01_historias_de_usuario.md#us35) |
| Elos Backward-from</br>(tipo e justificativa) | Recurso — O requisito depende de um sistema de registro de feedbacks e de comunicação com a equipe administrativa. Esses recursos são essenciais para receber, armazenar e tratar os relatórios enviados pelos usuários.             |
| Elos Forward-from</br>(tipo e justificativa)  | Representação — A história de usuário representa o comportamento de envio de reportes de problemas. Opta-se por Representação pois descreve a interação esperada sem comprovar implementação técnica.                                |

**Fonte:** Vera. 2025.

#### RF38 – Os usuários devem ser capazes de catalogar e gerenciar sua coleção pessoal de cartas {#elo38}

| Item                                      | Descrição                                                                                                                                                                                                                              |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF38 – Os usuários devem ser capazes de catalogar e gerenciar sua coleção pessoal de cartas](../03_elicitacao/artefatos/requisitos_elicitados.md#rf38)                                                                                |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                        |
| Origem do requisito                       | [EN01](../03_elicitacao/tecnicas/entrevista.md#en01)                                                                                                                                                                                   |
| Elementos                                 | Cenário: [CE14](../05_modelagem/01_cenarios/cenarios.md#ce14); <br>Caso de Uso: [UC12](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc12); <br>História de Usuário: [US20](../05_modelagem/05_Agil/01_historias_de_usuario.md#us20) |
| Elos Backward-from (tipo e justificativa) | Recurso — A Entrevista (EN01) identifica a necessidade dos usuários de gerenciar suas coleções pessoais, fornecendo a base informacional para o requisito.                                                                             |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem descrevem como a funcionalidade de catalogação e gerenciamento de coleção deve operar. Prefere-se Representação, pois formaliza o comportamento esperado sem atestar implementação.          |

**Fonte:** Thiago, 2025.

#### RF39 – Os usuários devem ser capazes de visualizar decks {#elo39}

| Item                                      | Descrição                                                                                                                                                                                                                              |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF25 – Os usuários devem ser capazes de visualizar decks publicados, com lista de cartas](../03_elicitacao/artefatos/requisitos_elicitados.md#rf25)                                                                                   |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                        |
| Origem do requisito                       | [OBS06](../03_elicitacao/observação)                                                                                                                                                                                                   |
| Elementos                                 | Cenário: [CE08](../05_modelagem/01_cenarios/cenarios.md#ce08); <br>Caso de Uso: [UC07](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc07); <br>História de Usuário: [US30](../05_modelagem/05_Agil/01_historias_de_usuario.md#us30) |
| Elos Backward-from (tipo e justificativa) | Fonte — A estrutura de níveis de informação (Ambiental, Organizacional, Gerencial, Desenvolvimento) serve como base conceitual para a organização e visualização dos decks, estabelecendo a fundamentação teórica.                     |
| Elos Forward-from (tipo e justificativa)  | Representação — A visualização de decks materializa a estrutura conceitual em interface prática, permitindo aos usuários navegar e compreender as informações conforme os níveis estabelecidos.                                        |

**Fonte:** Raissa, 2025.

#### RF40 – Os usuários devem ser capazes de responder no fórum {#elo40}

| Item                                      | Descrição                                                                                                                                                                                                                              |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF26 – Os usuários devem ser capazes de visualizar decks publicados, com lista de cartas](../03_elicitacao/artefatos/requisitos_elicitados.md#rf26)                                                                                   |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                        |
| Origem do requisito                       | [OBS07](../03_elicitacao/observação)                                                                                                                                                                                                   |
| Elementos                                 | Cenário: [CE11](../05_modelagem/01_cenarios/cenarios.md#ce11); <br>Caso de Uso: [UC09](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc09); <br>História de Usuário: [US27](../05_modelagem/05_Agil/01_historias_de_usuario.md#us27) |
| Elos Backward-from (tipo e justificativa) | Recurso — A Observação evidencia a necessidade de um espaço colaborativo para discussão e troca de informações entre os usuários do sistema.                                                                                           |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem definem como as funcionalidades do fórum devem operar, incluindo criação de tópicos, respostas e moderação, modelando o comportamento esperado.                                              |

**Fonte:** Raissa, 2025.

#### RF41 – Os usuários devem ser capazes de reportar problemas {#elo41}

| Item                                      | Descrição                                                                                                                                                                                                                              |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF37 – Os usuários devem ser capazes de reportar problemas relacionados à carta](../03_elicitacao/artefatos/requisitos_elicitados.md#rf37)                                                                                            |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                        |
| Origem do requisito                       | [OBS18](../03_elicitacao/observação)                                                                                                                                                                                                   |
| Elementos                                 | Cenário: [CE05](../05_modelagem/01_cenarios/cenarios.md#ce05); <br>Caso de Uso: [UC04](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc04); <br>História de Usuário: [US28](../05_modelagem/05_Agil/01_historias_de_usuario.md#us28) |
| Elos Backward-from (tipo e justificativa) | Recurso — A Observação demonstra a necessidade de um canal estruturado para coleta e tratamento de problemas reportados pelos usuários.                                                                                                |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem especificam o fluxo de reporte de problemas, incluindo categorização, priorização e acompanhamento, modelando o comportamento esperado do sistema.                                           |

**Fonte:** Raissa, 2025.

#### RF42 – Os usuários devem ser capazes de permitir controle de cookies {#elo42}

| Item                                      | Descrição                                                                                                                                                                                                                          |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RF38 – O sistema deve permitir que o usuário configure seu navegador para aceitar ou bloquear cookies](../03_elicitacao/artefatos/requisitos_elicitados.md#rf18)                                                                  |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                    |
| Origem do requisito                       | [AD17](../03_elicitacao/observação)                                                                                                                                                                                                |
| Elementos                                 | Cenário: [--](../05_modelagem/01_cenarios/cenarios.md#ce05); <br>Caso de Uso: [--](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc04); <br>História de Usuário: [US25](../05_modelagem/05_Agil/01_historias_de_usuario.md#us25) |
| Elos Backward-from (tipo e justificativa) | Recurso — A Análise de Documentos (AD18) comprova a necessidade de conformidade com leis de proteção de dados e privacidade, exigindo controle explícito de cookies.                                                               |
| Elos Forward-from (tipo e justificativa)  | Representação — Os artefatos de modelagem definem a interface e fluxos para gerenciamento de cookies, modelando as interações do usuário com as configurações de privacidade.                                                      |

**Fonte:** Raissa, 2025.

### Requisitos Não Funcionais

#### RNF05 – Exigir consentimento e concordância explícita {#elon05}

| Item                                      | Descrição                                                                                                                                                                                                                          |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RNF05 – O sistema deve garantir que o usuário declare ciência e concordância com a política ao usar o portal. ](../03_elicitacao/artefatos/requisitos_elicitados.md#rnf05)                                                        |
| Categoria                                 | Legal e Regulatório                                                                                                                                                                                                                |
| Origem do requisito                       | [AD24](../03_elicitacao/tecnicas/analise_documentos.md#ad24)                                                                                                                                                                       |
| Elementos                                 | NFR Framework: [NFR06](../05_modelagem/05_Agil/03_nfr_framework.md#nfr06)                                                                                                                                                          |
| Elos Backward-from (tipo e justificativa) | Recurso — Analise de documentos(AD24) apontou necessidade de aderência legal (ex.: LGPD), garantindo consentimento informado para uso e tratamento de dados pessoais.                                                              |
| Elos Forward-from (tipo e justificativa)  | Representação — Conecta com RF19 e os casos de uso de criação/gerenciamento de usuário, pois o consentimento deve ser explicitamente solicitado antes do processamento dos dados. Também está detalhado no NFR06 do NFR Framework. |

**Fonte:** Angélica, 2025.

#### RNF07 – Garantir que anúncios incluam informações fiscais corretas {#elon07}

| Item                                      | Descrição                                                                                                                                                                                                                                           |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RNF07 – Garantir que anúncios incluam informações fiscais corretas](../03_elicitacao/artefatos/requisitos_elicitados.md#rnf07)                                                                                                                     |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                                                     |
| Origem do requisito                       | [AD26](../03_elicitacao/tecnicas/analise_documentos.md#ad26)                                                                                                                                                                                        |
| Elementos                                 | Especificação Suplementar: [Con01](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md#confiabilidade)<br>NFR Framework: [NFR02](../05_modelagem/05_Agil/03_nfr_framework.md#nfr07)                                           |
| Elos Backward-from (tipo e justificativa) | Restrição — A Análise de Documento (AD26) identificou a necessidade de que os anúncios incluam informações fiscais corretas, assegurando conformidade com as normas legais e tributárias aplicáveis.                                                |
| Elos Forward-from (tipo e justificativa)  | Representação — A especificação suplementar e o NFR Framework descrevem os mecanismos de verificação das informações fiscais nos anúncios. Prefere-se Representação, pois formaliza o comportamento esperado sem comprovar a implementação técnica. |

**Fonte:** Marcelo, 2025.

#### RNF08 – Responsividade: O site deve ser totalmente responsivo {#elon08}

| Item                                      | Descrição                                                                                                                                                                                                              |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RNF08 – Responsividade: O site deve ser totalmente responsivo, garantindo boa visualização e funcionalidade em computador, tablet e smartphone](../03_elicitacao/artefatos/requisitos_elicitados.md#rnf08)            |
| Categoria                                 | Desenvolvimento                                                                                                                                                                                                        |
| Origem do requisito                       | [OBS19](../03_elicitacao/tecnicas/observacao.md#obs19)                                                                                                                                                                 |
| Elementos                                 | Especificação Suplementar: [US03](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md#usabilidade-usability); <br>NFR Framework: [NFR07](../05_modelagem/05_Agil/03_nfr_framework.md#nfr07)      |
| Elos Backward-from (tipo e justificativa) | Recurso — A Observação (OBS19) fornece evidência do comportamento dos usuários em diferentes dispositivos e a necessidade de adaptação responsiva da interface.                                                        |
| Elos Forward-from (tipo e justificativa)  | Representação — A especificação suplementar e o NFR Framework descrevem os requisitos de usabilidade relacionados à responsividade. Prefere-se Representação pois formaliza as características esperadas da interface. |

**Fonte:** Thiago, 2025.

#### RNF09 – Organização visual {#elon09}

| Item                                          | Descrição                                                                                                                                                                                                                                                    |
| :-------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                        | [RNF09 – Organização visual: As informações sobre cartas, anúncios e decks devem ser organizadas de forma clara, com boa legibilidade e espaçamento adequado, facilitando a navegação](../03_elicitacao/artefatos/requisitos_elicitados.md#rnf09)            |
| Categoria                                     | Usabilidade                                                                                                                                                                                                                                                  |
| Origem do requisito                           | [OBS20](../03_elicitacao/tecnicas/observacao.md#obs20)                                                                                                                                                                                                       |
| Elementos                                     | Especificação Suplementar: [US01](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md#usabilidade-usability); <br>NFR Framework: [NFR05](../05_modelagem/05_Agil/03_nfr_framework.md#nfr05)                                            |
| Elos Backward-from</br>(tipo e justificativa) | Recurso — O requisito depende de diretrizes de design de interface, padrões de espaçamento e organização visual, identificados na Observação (OBS20). Esses recursos garantem clareza e legibilidade durante a navegação do usuário.                         |
| Elos Forward-from</br>(tipo e justificativa)  | Representação — A especificação suplementar e o NFR Framework representam o comportamento esperado de organização visual das informações. Opta-se por Representação pois descrevem a interação e a disposição esperadas sem comprovar implementação técnica. |

**Fonte:** Vera, 2025.

#### RNF14 – Padronização de mensagens {#elon14}

| Item                                      | Descrição                                                                                                                                                                                                                                                                                                      |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrição do requisito                    | [RNF14 – As mensagens de alerta, erro e confirmação devem aparecer de forma padronizada e visível, para evitar confusões ](../03_elicitacao/artefatos/requisitos_elicitados.md#rnf14)                                                                                                                          |
| Categoria                                 | Usabilidade                                                                                                                                                                                                                                                                                                    |
| Origem do requisito                       | [OBS25](../03_elicitacao/tecnicas/observacao.md#obs25)                                                                                                                                                                                                                                                         |
| Elementos                                 | Especificação Suplementar: [US02](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md#usabilidade-usability)                                                                                                                                                                             |
| Elos Backward-from (tipo e justificativa) | Recurso — OBS25 identificou a necessidade de manter consistência visual e textual nas mensagens para facilitar compreensão do usuário.                                                                                                                                                                         |
| Elos Forward-from (tipo e justificativa)  | Representação — Esse requisito impacta qualquer funcionalidade que exiba alertas e mensagens ao usuário, como feedbacks de ações em RF19 (atualização de dados) e RF24 (histórico de compras). Também impacta a conformidade da Especificação Suplementar US02, garantindo diretrizes de mensagens unificadas. |

**Fonte:** Raissa, 2025.

## Referências

> <p><a id="refs1"></a>1.  <b>SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado.</b> <em>Rastreabilidade de Requisitos.</em></p>
> <p><a id="refs2"></a>2.  <b>SERRANO, Milene; SERRANO, Maurício.</b> <em>Requisitos – Aula 26.</em></p>

## Agradecimentos

O Grupo 02 agradece o apoio das ferramentas de Inteligência Artificial Generativa — ChatGPT e Google Gemini — na revisão e padronização de nossos artefatos. Essas tecnologias foram utilizadas para auxiliar na organização do repositório. Todo o conteúdo, incluindo a precisão técnica e as ideias apresentadas, é de responsabilidade dos autores.

## Nível de Contribuição dos Integrantes

| Nome     | % de Contribuição |

|:---------|:-----------------:|
| Samuel   |       16,67       |
| Thiago   |       16,67       |
| Angélica |       16,67       |
| Vera     |       16,67       |      
| Marcelo  |       16,67       |



## Histórico de versão

| Versão |    Data    | Descrição                                                      |   Autor(es)    | Revisor  |
| :----: | :--------: | :------------------------------------------------------------- | :------------: | :------: |
|  1.0   | 23/10/2025 | Criação inicial do documento                                   |     Samuel     |   Vera   |
|  1.1   | 25/10/2025 | Adição das seções (Introdução, Objetivo, Metodologia, Legenda) | Samuel, Thiago |   Vera   |
| 1.1.1  | 25/10/2025 | Adição dos elos (RF02, RF11, RF20, RF21.1, RF36)               |     Samuel     |  Thiago  |
| 1.1.2  | 25/10/2025 | Adição dos elos (RF29, RF38, RF35, RF16, RF10, RF12, RNF08)    |     Thiago     |  Samuel  |
|  1.2   | 26/10/2025 | Adição dos elos (RF06, RF23, RF31, RF33, RF34, RF37 E RNF09)   |      Vera      | Angélica |
|  1.3   | 26/10/2025 | Adição dos elos (RF04, RF21.2, RF27, RF30, RF32 E RNF07)       |    Marcelo     |  Thiago  |
|  1.4   | 27/10/2025 | Adição dos elos (RF01, RF03, RF19, RF24, RNF05 E RNF14)        |    Angélica    |  Samuel  |
|  1.5   | 28/10/2025 | Adição dos elos 39 a 41                                        |     Raissa     |   Vera   |
