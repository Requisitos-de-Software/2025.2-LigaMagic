# NFR

## Descrição
O NFR Framework é uma abordagem proposta por Chung et al.[¹]() para representar e analisar requisitos não funcionais em sistemas de software. Ele é importante porque esses requisitos — como desempenho, segurança e usabilidade — influenciam diretamente na qualidade do sistema, mas muitas vezes não são claramente definidos durante o desenvolvimento. Para aplicar o framework, é necessário compreender os softgoals, que representam objetivos de qualidade, e o grafo de interdependência (SIG), usado para mostrar como os requisitos se relacionam e se afetam. Dessa forma, o NFR Framework ajuda a visualizar e equilibrar as decisões de projeto, contribuindo para sistemas mais consistentes e de melhor qualidade.

###  SIG - Softgoal Interdependency Graph

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




## Objetivo
## Metodologia

## Conteúdo

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

## Bibliografia

> CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

## Nível de Contribuição dos Integrantes

| Nome     | % de Contribuição |
| :------- | :---------------: |
| Angélica |                   |

## Histórico de versão

| Versão |    Data     | Descrição            | Autor(es) |  Revisor  |
|:------:|:-----------:|:---------------------|:---------:|:---------:|
|  1.1   | 15/10/2025  | Adição da tabela     | Angélica  | Guilherme |
|  1.2   | 17/10/2025  | Adição da introdução |   Vera    |  Raissa   |
