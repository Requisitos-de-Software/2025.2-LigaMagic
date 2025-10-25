# Requisitos Não Implementados no Aplicativo LigaMagic

## Introdução

Este documento apresenta os requisitos que foram elicitados através da análise do site da LigaMagic mas que não estão implementados no aplicativo móvel da plataforma. A identificação destes requisitos foi realizada através da comparação entre as funcionalidades disponíveis no site web e aquelas presentes no aplicativo, evidenciando gaps funcionais que podem impactar a experiência do usuário móvel.

## Metodologia

Os requisitos não implementados foram identificados através de:

1. **Elicitação de requisitos** do site web utilizando técnicas de análise de documentos e observação
2. **Comparação** entre as funcionalidades do site e do aplicativo
3. **Documentação** dos gaps identificados

## Legenda

- ADx - Analise de Documentos
- OBSx - Observação
- RFNIx - Requisitos Funcionais Não Implementados
- RNFNIx - Requisitos Não Funcionais Não Implementados

## Requisitos Não Implementados

### Requisitos Funcionais Não Implementados

|      **ID**      | **Descrição**                                                                                                 |           **Técnica de Elicitação**            |         **Requisito Original**          |
| :--------------: | :------------------------------------------------------------------------------------------------------------ | :--------------------------------------------: | :-------------------------------------: |
| RFNI01 {#rfni01} | O sistema deve permitir que cada usuário personalize e mantenha sua página pessoal/profissional               | [AD10](../tecnicas/analise_documentos.md#ad10) | [RF10](./requisitos_elicitados.md#rf10) |
| RFNI02 {#rfni02} | O sistema deve possibilitar participação dos usuários em fóruns de discussão (postagem e resposta)            | [AD11](../tecnicas/analise_documentos.md#ad11) | [RF11](./requisitos_elicitados.md#rf11) |
| RFNI03 {#rfni03} | Permitir que o usuário filtre cartas por qualidade/condição                                                   |    [OBS02](../tecnicas/observacao.md#obs02)    | [RF21](./requisitos_elicitados.md#rf21) |
| RFNI04 {#rfni04} | Permitir que o usuário avalie ou dê feedback sobre vendedores ou decks                                        |    [OBS10](../tecnicas/observacao.md#obs10)    | [RF29](./requisitos_elicitados.md#rf29) |
| RFNI05 {#rfni05} | Permitir que o usuário defina um alerta de preço para a carta selecionada                                     |    [OBS12](../tecnicas/observacao.md#obs12)    | [RF31](./requisitos_elicitados.md#rf31) |
| RFNI06 {#rfni06} | Permitir que o usuário compartilhe informações da carta por link direto                                       |    [OBS17](../tecnicas/observacao.md#obs17)    | [RF36](./requisitos_elicitados.md#rf36) |
| RFNI07 {#rfni07} | Permitir que o usuário reporte problemas relacionados à carta (erros de informação, anúncios suspeitos, etc.) |    [OBS18](../tecnicas/observacao.md#obs18)    | [RF37](./requisitos_elicitados.md#rf37) |
| RFNI08 {#rfni08} | O sistema deve fornecer um módulo completo de **leilões**                                                     |                                                |                                         |
| RFNI09 {#rfni09} | Os usuários devem ser capazes de criar, salvar e gerenciar listas de **decks**                                |                                                |                                         |
| RFNI10 {#rfni10} | Os usuários devem ser capazes de catalogar e gerenciar sua **coleção** pessoal de cartas                      |     [EN01](../tecnicas/entrevista.md#en01)     | [RF38](./requisitos_elicitados.md#rf38) |
| RFNI11 {#rfni11} | O sistema deve fornecer a funcionalidade "**Compra por Lista**"                                               |                                                |                                         |
| RFNI14 {#rfni14} | Permitir que o usuário salve cartas para compra futura (wishlist)                                             |    [OBS09](../tecnicas/observacao.md#obs09)    | [RF28](./requisitos_elicitados.md#rf28) |
| RFNI15 {#rfni15} | Permitir busca rápida e eficiente de cartas específicas                                                       |    [OBS01](../tecnicas/observacao.md#obs01)    | [RF20](./requisitos_elicitados.md#rf20) |

### Requisitos Não Funcionais Não Implementados

|       **ID**       | **Descrição**                                                                                                              |           **Técnica de Elicitação**            |         **Requisito Original**          |
| :----------------: | :------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------: | :-------------------------------------: |
| RNFNI12 {#rnfni12} | O documento não informa por quanto tempo os dados pessoais serão armazenados nem os critérios para definição desse prazo   | [AD27](../tecnicas/analise_documentos.md#ad27) | [NI01](./requisitos_elicitados.md#ni01) |
| RNFNI13 {#rnfni13} | O documento não prevê ou detalha os procedimentos a serem adotados em caso de incidente de segurança ou vazamento de dados | [AD28](../tecnicas/analise_documentos.md#ad28) | [NI02](./requisitos_elicitados.md#ni02) |

## Distribuição por Técnica de Elicitação

|      **Técnica**      | **Quantidade de Requisitos** |
| :-------------------: | :--------------------------: |
| Análise de Documentos |         4 requisitos         |
|      Observação       |         7 requisitos         |
|      Entrevista       |         1 requisito          |

## Bibliografia

> 1. LIGAMAGIC. _Site oficial_. Disponível em: https://www.ligamagic.com.br/. Acesso em: outubro/2025.
> 2. LIGAMAGIC. _Aplicativo móvel_. Disponível nas lojas de aplicativos. Acesso em: outubro/2025.
> 3. Requisitos Elicitados - Documento consolidado de requisitos do site.

## Histórico de Versão

| Versão |    Data    | Descrição                                            |                    Autor                    | Revisor |
| :----: | :--------: | :--------------------------------------------------- | :-----------------------------------------: | :-----: |
|  1.0   | 11/10/2025 | Criação do documento de requisitos não implementados |                   Samuel                    | Thiago  |
|  1.1   | 12/10/2025 | Melhorada a rastreabilidade dos requisitos           | [Samuel](https://github.com/samuelncaetano) | Thiago  |
|  1.2   | 25/10/2025 | Arrumando o requisito RFNI10                         |    [Thiago](https://github.com/Acciolyy)    | Samuel  |
