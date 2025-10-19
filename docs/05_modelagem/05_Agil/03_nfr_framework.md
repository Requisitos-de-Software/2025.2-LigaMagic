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

### Interdependências

As interdependências definem as relações entre os softgoals. No NFR Framework, essas relações são representadas por dois tipos principais de interdependência: os refinamentos e as contribuições.
Essas interdependências permitem visualizar como os softgoals se influenciam mutuamente dentro do sistema, revelando dependências hierárquicas e impactos entre diferentes requisitos de qualidade.

#### Decomposições (Refinamentos)

Os refinamentos representam o tipo de interdependência que ocorre de forma hierárquica (top-down), quando um softgoal ascendente (pai) gera um ou mais softgoals descendentes (filhos), que se relacionam com o objetivo principal.
Os refinamentos podem ocorrer por meio de decomposição, operacionalização e afirmação, permitindo detalhar gradualmente os requisitos não funcionais até níveis mais específicos e aplicáveis ao projeto (CHUNG et al., 2000).

Os quatro tipos de decomposição utilizados pelo NFR Framework são:

- **Decomposição de Softgoal NFR**: subdivide um softgoal NFR em outros mais específicos, ajudando a dividir grandes problemas em partes menores e mais manejáveis.

- **Decomposição de Operacionalização**: subdivide um softgoal de operacionalização em outros mais específicos, definindo soluções práticas e refinadas.

- **Decomposição de Afirmação (Claims)**: refina softgoals de afirmação, úteis para apoiar ou negar justificativas de projeto.

- **Priorização**: tipo especial de decomposição que refina um softgoal com o mesmo tipo, mas associado a diferentes níveis de prioridade.

Essas decomposições permitem representar, dentro do grafo SIG, a estrutura de refinamento dos requisitos não funcionais, auxiliando na rastreabilidade e na clareza das decisões de projeto.

<p align="center"><strong>Figura 2 – Tipos de decomposição</strong></p>

![Tipos de Decomposicao](../../00_assets/images/nfr_framework/InterdependenciasFig8.png)

<p align="center"><em>Fonte: CHUNG et al., 2000.</em></p>

### Contribuições

Durante o refinamento dos softgoals, cada elemento descendente pode contribuir total ou parcialmente, e de forma positiva ou negativa, para a satisfação do softgoal ascendente (CHUNG et al., 2000).
Essas contribuições permitem analisar o equilíbrio entre diferentes requisitos não funcionais — por exemplo, como melhorar o desempenho pode prejudicar a segurança, ou como aumentar a usabilidade pode impactar na eficiência.

Os principais tipos de contribuições do NFR Framework incluem:

- **AND**: todos os softgoals descendentes devem ser satisfeitos para que o ascendente também seja.

- **OR**: a satisfação de qualquer softgoal descendente é suficiente para satisfazer o ascendente.

<p align="center"><strong>Figura 3 – Exemplos de contribuições "AND" e "OR"</strong></p>

![Tipos de Decomposicao](../../00_assets/images/nfr_framework/contribuicaoAndOr.png)

<p align="center"><em>Fonte: Silva, Reinaldo Antônio da 
NFR4ES: um Catálogo de Requisitos Não-Funcionais para
Sistemas Embarcados/ Reinaldo Antônio da Silva – 2019.</em></p>

- **MAKE** (++): contribuição fortemente positiva.

- **BREAK** (--): contribuição fortemente negativa.

- **HELP** (+): contribuição parcialmente positiva.

- **HURT** (-): contribuição parcialmente negativa.

<p align="center"><strong>Figura 4 – Exemplos de contribuições ” MAKE", ”BREAK ", ”HELP" e ”HURT"</strong></p>

![Tipos de Decomposicao](../../00_assets/images/nfr_framework/contribuicaoAndOr.png)

<p align="center"><em>Fonte: Silva, Reinaldo Antônio da 
NFR4ES: um Catálogo de Requisitos Não-Funcionais para
Sistemas Embarcados/ Reinaldo Antônio da Silva – 2019.</em></p>

- **UNKNOWN** (?): contribuição desconhecida (pode ser positiva ou negativa).

- **EQUALS**: o softgoal descendente só será satisfeito se o ascendente também for.

- **SOME** (+/-): contribuição com sinal conhecido (positivo ou negativo), mas intensidade incerta.

Essas relações permitem que o analista compreenda como os softgoals se reforçam ou se contradizem dentro do sistema, servindo como base para o processo de propagação de impactos.


<p align="center"><strong>Figura 5 – Exemplos de contribuições"SOME", UNKNOWN e EQUALS</strong></p>

![Tipos de Decomposicao](../../00_assets/images/nfr_framework/contribuicaoAndOr.png)

<p align="center"><em>Fonte: Silva, Reinaldo Antônio da 
NFR4ES: um Catálogo de Requisitos Não-Funcionais para
Sistemas Embarcados/ Reinaldo Antônio da Silva – 2019.</em></p>

### Propagação de Impactos (Procedimento de Avaliação)

O procedimento de avaliação tem como objetivo determinar o grau de satisfação dos requisitos não funcionais a partir de um conjunto de decisões do projeto.
Durante esse processo, cada softgoal do SIG é rotulado de acordo com o nível de satisfação alcançado, permitindo avaliar se os objetivos de qualidade foram atingidos.

Os principais rótulos utilizados são:
- **Satisfeito**
- **Fracamente satisfeito**
- **Negado**
- **Fracamente negado**
- **Conflitante**
- **Indeterminado**

<p align="center"><strong>Figura 6 – Tipos de rótulos utilizados pelos softgoals</strong></p>

![Tipos de Decomposicao](../../00_assets/images/nfr_framework/rotulosSoftgoals.png)

<p align="center"><em>Fonte: CHUNG et al., 2000.</em></p>

Esses rótulos são aplicados de forma iterativa, começando pelos softgoals de nível mais baixo na hierarquia e propagando os resultados até os softgoals de nível superior.
Esse procedimento permite compreender o impacto cumulativo das decisões sobre a qualidade do sistema, facilitando ajustes e priorizações ao longo do desenvolvimento.

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

<div align="center"><strong>Tabela 4:</strong> Informações Legais e Tributárias</div>

| **Item**                  | **Descrição** |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **ID**                    | NRF02 |
| **Requisito**             | [RNF07](https://requisitos-de-software.github.io/2025.2-LigaMagic/03_elicitacao/artefatos/requisitos_elicitados/#rnf07) |
| **Classificação**         | Performance > Confiabilidade de Dados Fiscais |
| **Descrição**             | A plataforma deve garantir que todos os anúncios incluam informações fiscais e tributárias corretas e obrigatórias, de acordo com a legislação brasileira, assegurando a exatidão e integridade desses dados durante todo o processo de venda. |
| **Justificativa**         | A exibição de informações fiscais corretas é essencial para garantir transparência, confiança entre usuários e conformidade com normas legais. Evita fraudes, melhora a reputação da plataforma e assegura o cumprimento de obrigações fiscais. |
| **Origem**                | [Análise de Documentos](../tecnicas/analise_legislacao.md) |
| **Critério de Aceitação** | **Validação de Dados Fiscais:** <br>- O sistema deve exigir que todo anunciante informe um CNPJ ou CPF válido ao cadastrar um anúncio. <br>- O sistema deve validar o formato e autenticidade do CNPJ/CPF informado, impedindo o cadastro de anúncios inválidos. <br>- Cada anúncio deve apresentar o CNPJ/CPF do vendedor e o valor total com impostos inclusos. <br>- O sistema deve permitir anexar ou gerar uma Nota Fiscal Eletrônica (NF-e) quando aplicável. <br>- Em transações entre pessoas físicas, deve ser exibido um aviso informando que a plataforma não é responsável por obrigações fiscais entre as partes. <br><br> **Conformidade Legal:** <br>- O sistema deve estar de acordo com a Lei nº 12.965/2014 (Marco Civil da Internet), o Decreto nº 7.962/2013 (Comércio Eletrônico) e a Lei nº 13.709/2018 (LGPD). |
| **Dependências**          | - **RF03 – Cadastro de Usuário:** necessário para associar CNPJ/CPF aos vendedores. <br>- **RF05 – Criar Anúncios:** utilizado para incluir e exibir informações fiscais no processo de anúncio. <br>- **RNF04 – Segurança e Privacidade:** dependência para garantir o armazenamento seguro e tratamento adequado dos dados fiscais. <br>- **Integração com API de validação fiscal (Receita Federal):** necessária para verificar autenticidade dos CNPJs/CPFs informados. |
| **Prioridade**            | **9** |
| **Conflitos**             | - **Usabilidade (𝒲-)**: A obrigatoriedade de preencher dados fiscais pode tornar o processo de criação de anúncios mais demorado e menos intuitivo. <br>- **Desempenho (𝒲-)**: A validação externa de dados fiscais pode aumentar o tempo de resposta do sistema. <br>- **Privacidade (𝒲-)**: A exibição pública de dados fiscais pode conflitar com as restrições da LGPD e deve ser tratada com anonimização parcial. <br>- **Disponibilidade (𝒲-)**: Caso a API externa de validação fiscal esteja fora do ar, o cadastro de anúncios poderá ser temporariamente interrompido. |
| **História**              | Criado em 18/10/2025 |


**Fonte:** Marcelo, 2025

## Bibliografia

> CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

## Nível de Contribuição dos Integrantes

| Nome     | % de Contribuição |
| :------- | :---------------: |
| Angélica |                   |
| Samuel   |                   |

|Marcelo |                     |

## Histórico de versão

| Versão |    Data    | Descrição                                                                         | Autor(es) |  Revisor  |
| :----: | :--------: | :-------------------------------------------------------------------------------- | :-------: | :-------: |
|  1.1   | 15/10/2025 | Adição da tabela                                                                  | Angélica  | Guilherme |
|  1.2   | 17/10/2025 | Adição da introdução                                                              |   Vera    |  Raissa   |
|  1.3   | 18/10/2025 | Adição da tabela de contribuição, do modelo do cartão de especificação e do NFR01 |  Samuel   |   Vera    |
|  1.4 | 18/10/2025 | Adição da tabela de contribuição, do modelo do cartão de especificação e do NFR02 |  Marcelo  |   Thiago   |
|  1.5 | 18/10/2025 | Adição de parte da introdução |  Guilherme  |   Vera   |