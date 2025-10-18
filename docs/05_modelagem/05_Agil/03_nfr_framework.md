# NFR

## Descrição

O NFR Framework é uma abordagem proposta por Chung et al.[¹]() para representar e analisar requisitos não funcionais em sistemas de software. Ele é importante porque esses requisitos — como desempenho, segurança e usabilidade — influenciam diretamente na qualidade do sistema, mas muitas vezes não são claramente definidos durante o desenvolvimento. Para aplicar o framework, é necessário compreender os softgoals, que representam objetivos de qualidade, e o grafo de interdependência (SIG), usado para mostrar como os requisitos se relacionam e se afetam. Dessa forma, o NFR Framework ajuda a visualizar e equilibrar as decisões de projeto, contribuindo para sistemas mais consistentes e de melhor qualidade.

### SIG - Softgoal Interdependency Graph

No NFR Framework, o funcionamento do modelo é representado por meio do Softgoal Interdependency Graph (SIG), um gráfico que ilustra a relação e a interdependência entre os softgoals (requisitos não funcionais). O SIG atua como um registro visual das decisões tomadas durante o processo de desenvolvimento, mostrando como cada requisito, alternativa e justificativa se conectam dentro do sistema. Esse gráfico permite uma análise incremental e iterativa das decisões, facilitando a revisão e a rastreabilidade dos impactos entre os softgoals. Além disso, o SIG possibilita a execução de procedimentos de avaliação para verificar se os requisitos de nível superior foram satisfeitos, contribuindo para uma visão clara e estruturada da lógica e das prioridades do projeto[¹]().

### Tipos de Softgoals

No NFR Framework, existem três tipos principais de softgoals:

- **Softgoals NFR**: representam os requisitos não funcionais, organizados de forma hierárquica e inter-relacionada.
- **Softgoals de Operacionalização**: correspondem às soluções práticas para satisfazer os softgoals NFR, incluindo processos, dados e restrições do sistema.
- **Softgoals de Afirmação**: refletem características do domínio e justificam decisões de priorização e refinamento dos softgoals, fortalecendo a rastreabilidade do projeto[¹]().

A forma como os softgoals são representados pode ser observada na Figura 1, que ilustra graficamente sua estrutura.

<p align="center"><strong>Figura 1 – Representação dos Softgoals no NFR Framework.</strong></p>

![Tipos de Softgoals](../../00_assets/images/nfr_framework/softgoal_nfr.png)

<p align="center"><em>Fonte: CHUNG et al., 2000.</em></p>

### Cartões de Especificação

Os cartões de especificação servem para registrar de forma detalhada cada requisito não funcional (softgoal) que identificamos. Eles oferecem um formato padronizado, o que torna mais fácil entender, analisar e acompanhar esses requisitos ao longo do projeto.

Abaixo está o modelo padrão para os cartões de especificação:

<div align="center"><strong>Tabela 1:</strong> Modelo padrão dos cartões</div>

| Item                      | Descrição                                                                             |
| ------------------------- | ------------------------------------------------------------------------------------- |
| **ID**                    | **[NFRx]** - Identificador único sequencial.                                          |
| **Requisito**             | **[RNFx]** - Identificador único sequencial.                                          |
| **Classificação**         | **[Categoria > Subcategoria]** - Classificação hierárquica do RNF (ex: SUP > COMP).   |
| **Descrição**             | Declaração clara, objetiva e única do requisito.                                      |
| **Justificativa**         | A razão de negócio ou técnica para a existência do requisito.                         |
| **Origem**                | A fonte do requisito (Técnicas de Elicitação).                                        |
| **Critério de Aceitação** | Uma métrica objetiva e testável que define quando o requisito é considerado atendido. |
| **Dependências**          | Relações com outros RNFs, indicando sinergias ou pré-requisitos.                      |
| **Prioridade**            | Nível de importância do requisito em uma escala de 1 (menor) a 10 (maior).            |
| **Conflitos**             | Lista de outros requisitos que podem ser negativamente impactados por este.           |
| **História**              | Registro de data de criação e alterações relevantes no requisito.                     |

**Fonte:** Samuel, 2025

## Objetivo

## Metodologia

## Conteúdo

### Tabela de contribuição

| ID  | NFR                          | Autor  |                          Requisito Associado                          |
| :-: | :--------------------------- | :----: | :-------------------------------------------------------------------: |
| 01  | Responsividade da plataforma | Samuel | [RNF12](../../03_elicitacao/artefatos/requisitos_elicitados.md#rnf12) |

<div align="center"><strong>Tabela 2:</strong> Tabela de contribuição</div>

### Classificação dos RNFs

#### **Usabilidade**

- **RNF08** – O site deve ser totalmente responsivo, garantindo boa visualização e funcionalidade em computador, tablet e smartphone.
- **RNF09** – As informações sobre cartas, anúncios e decks devem ser organizadas de forma clara e legível.
- **RNF14** – As mensagens de alerta, erro e confirmação devem aparecer de forma padronizada e visível.
- **RNF04** – O sistema deve informar os usuários sobre mudanças relevantes na política com antecedência razoável (transparência contribui para melhor experiência do usuário).

#### **Performance**

- **RNF10** – O sistema deve retornar resultados de busca em no máximo 3 segundos.
- **RNF16** – O sistema deve suportar um aumento de 50% no número de usuários simultâneos sem degradação significativa de performance.
- **RNF07** – Garantir que anúncios incluam informações fiscais corretas (precisão contribui para confiabilidade no desempenho).
- **RNF01** – O sistema deve cumprir legislações aplicáveis, assegurando conformidade e funcionamento correto (correção é base para desempenho confiável).

#### **Portabilidade**

- **RNF08** – O site deve ser totalmente responsivo (também relacionado à usabilidade, mas afeta portabilidade).
- **RNF12** – A plataforma deve ser compatível com as versões mais recentes dos principais navegadores (Google Chrome, Firefox, Edge e Safari).
- **RNF06** – O sistema deve suportar alterações na configuração ou apresentação sem interromper o uso (flexibilidade e adaptação).

#### **Disponibilidade**

- **RNF11** – O sistema deve estar disponível 99,5% do tempo.
- **RNF15** – O sistema deve realizar backup automático dos dados a cada 24 horas (garante continuidade e recuperação).
- **RNF06** – O sistema deve suportar alterações sem interrupção de uso (também relacionado à manutenibilidade).

### NFRs

<div align="center"><strong>Tabela 3:</strong> Responsividade da plataforma</div>

| Item                      | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                    | NFR01                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Requisito**             | [RNF12](../../03_elicitacao/artefatos/requisitos_elicitados.md#rnf12)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Classificação**         | Suportabilidade > Compatibilidade                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Descrição**             | A plataforma deve ser totalmente compatível com as versões mais recentes dos principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge e Safari), tanto em suas versões para desktop quanto para dispositivos móveis (Android e iOS).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Justificativa**         | Garantir que a vasta e diversificada base de usuários de _Magic: The Gathering_ possa acessar a plataforma sem barreiras técnicas, independentemente do dispositivo ou navegador de sua preferência. A compatibilidade ampla maximiza o alcance do produto, aumenta a satisfação e reduz a taxa de abandono por frustração técnica.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Origem**                | [Observação](../tecnicas/observacao.md)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Critério de Aceitação** | **Compatibilidade do aplicativo mobile:** <br>- O aplicativo deve ser instalável e totalmente funcional nas duas últimas versões estáveis dos sistemas operacionais Android e iOS. <br>- A interface deve seguir as diretrizes de design de cada plataforma para garantir uma experiência nativa e intuitiva. <br>- O layout deve ser fluido e adaptar-se a diferentes tamanhos e densidades de tela de smartphones, sem perda de funcionalidade. <br>- Todas as funcionalidades (fóruns, busca, etc.) devem operar sem erros e com performance otimizada para o ambiente mobile. <br><br>**Compatibilidade Desktop:** <br>- A versão web da plataforma deve operar sem erros nas últimas versões estáveis dos navegadores Google Chrome, Mozilla Firefox, Microsoft Edge e Safari. <br>- A interface deve ser renderizada corretamente, sem quebras de layout ou sobreposição de elementos, em todos os navegadores suportados. |
| **Dependências**          | Nenhum                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Prioridade**            | **9**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Conflitos**             | - **Manutenibilidade (𝒲-)**: A gestão de bases de código distintas (Android, iOS, Web) aumenta a complexidade da manutenção. Corrigir um bug pode exigir implementações separadas para cada plataforma, e a introdução de novas funcionalidades torna-se um processo mais lento e propenso a inconsistências. <br>- **Tempo de Lançamento no Mercado (𝒲-)**: A necessidade de desenvolver, testar e aprovar o aplicativo em duas lojas de aplicativos distintas (Google Play Store e Apple App Store) pode atrasar o lançamento de novas funcionalidades em comparação com uma simples atualização no lado do servidor de uma aplicação web. <br>- **Complexidade Técnica (𝒲-)**: Aumenta a complexidade geral do projeto, exigindo conhecimento sobre SDKs nativos, processos de compilação específicos, diretrizes de publicação de cada loja e gestão de diferentes ciclos de vida da aplicação.                                       |
| **História**              | Criado em 18/10/2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |

**Fonte:** Samuel, 2025

## Bibliografia

> CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

## Nível de Contribuição dos Integrantes

| Nome     | % de Contribuição |
| :------- | :---------------: |
| Angélica |                   |
| Samuel   |                   |

## Histórico de versão

| Versão |    Data    | Descrição                                                                         | Autor(es) |  Revisor  |
| :----: | :--------: | :-------------------------------------------------------------------------------- | :-------: | :-------: |
|  1.1   | 15/10/2025 | Adição da tabela                                                                  | Angélica  | Guilherme |
|  1.2   | 17/10/2025 | Adição da introdução                                                              |   Vera    |  Raissa   |
|  1.3   | 18/10/2025 | Adição da tabela de contribuição, do modelo do cartão de especificação e do NFR01 |  Samuel   |   Vera    |
