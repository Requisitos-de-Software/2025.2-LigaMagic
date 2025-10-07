# Lista de Verificação - Casos de Uso

## Descrição
Este documento apresenta uma lista de verificação consolidada para inspeção de Diagramas de Casos de Uso UML. A lista foi elaborada a partir da análise e comparação de checklists desenvolvidos por dois autores independentes - Guilherme Oliveira e Angélica da Costa Campos.


## Objetivo
Os objetivos desta lista de verificação são:

- Padronizar a qualidade: Estabelecer critérios objetivos para avaliação de diagramas de casos de uso, garantindo consistência na modelagem de requisitos
- Identificar não conformidades: Detectar erros, omissões e desvios em relação às boas práticas de modelagem UML
- Facilitar a revisão: Fornecer um instrumento estruturado que oriente revisores e desenvolvedores durante a inspeção de diagramas
- Promover aprendizado: Servir como material de referência educacional sobre os elementos e relacionamentos corretos em diagramas de casos de uso
- Consolidar conhecimento: Integrar perspectivas complementares de diferentes autores, cobrindo tanto aspectos técnicos quanto conceituais da modelagem

## Metodologia
A metodologia utilizada para elaboração desta lista de verificação seguiu as seguintes etapas:
1. Coleta de Dados
Foram analisadas duas listas de verificação independentes desenvolvidas por:

* Guilherme Oliveira (Matrícula: 222008682) - 32 itens de verificação
* Angélica da Costa Campos (Matrícula: 221031256) - 28 itens de verificação

2. Fundamentação Teórica
Ambas as listas basearam-se em fontes reconhecidas:

> Fonte principal: Tutorial de Caso de Uso UML do Lucid Software Português (YouTube, 2019/2020)
Fonte complementar:

> SOMMERVILLE, Ian. Engenharia de Software, 9ª ed. (Capítulo 4)
SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 13: Modelagem, Eliciação, Análise (UnB-FGA)

3. Análise Comparativa
Foi realizada uma comparação sistemática entre as duas listas para:
* Identificar perguntas comuns (que validam conceitos consensuais)
* Identificar perguntas únicas de cada autor (que trazem perspectivas complementares)


## Conteúdo

### Tabela de Verificação
|  | Perguntas | Autor|
|---|----------|----------|
| 1 | O diagrama possui sistemas? |Guilherme |
| 2 | O diagrama possui atores? |Guilherme |
| 3 | O diagrama possui casos de uso? |Guilherme |
| 4 | O diagrama possui relacionamentos? |Guilherme |
| 5 | Representação do Sistema O sistema foi representado por um retângulo? |Guilherme |
| 6 | O diagrama apresenta uma visão geral sem entrar em muitos detalhes? |Guilherme |
| 7 | Os atores foram definidos como classes ou categorias, evitando ser muito específicos? |Guilherme |
| 8 | Foram definidos atores primários e secundários? |Guilherme |
| 9 | Os atores primários foram colocados à esquerda do sistema?  |Guilherme |
| 10 | Os atores secundários foram posicionados à direita do sistema? |Guilherme |
| 11 | Os casos de uso foram organizados em sequência lógica ou cronológica? |Guilherme |
| 12 | O caso de uso foi posicionado dentro do retângulo do sistema? |Guilherme |
| 13 | Foram definidos os tipos de relacionamentos entre atores e casos de uso (associação, inclusão, extensão, generalização)? |Guilherme |
| 14 | No relacionamento de inclusão, foram definidos o caso de uso base e o incluído? |Guilherme |
| 15 | Foi escrito no relacionamento de inclusão a palavra << incluir >>? |Guilherme |
| 16 | No caso de uso de extensão, foram definidos o caso de uso base e o estendido? |Guilherme |
| 17 | O caso de uso de extensão foi representado por uma linha tracejada, partindo do caso de uso estendido até o caso de uso base com uma seta no final? |Guilherme |
| 18 | Foi escrito no relacionamento de extensão a palavra << estender >>? |Guilherme |
| 19 | No relacionamento de generalização, foram definidos o caso de uso geral e os especializados (ou primário e secundário)? |Guilherme |
| 20 | O relacionamento de generalização foi feito com atores ou casos de uso? |Guilherme |
| 21 | No relacionamento de generalização, foi utilizada uma seta contínua ligando o caso de uso especializado ao caso de uso geral, com um triângulo na ponta voltado para o caso de uso geral? |Guilherme |
| 22 | O sistema representa um site, software, processos de negócio ou aplicativo? | Angélica|
| 23 | O sistema tem nome? |Angélica|
| 24 | O nome do sistema está no topo? |Angélica|
| 25 | Tudo que acontece fora do app está representado fora do sistema (retângulo)? |Angélica|
| 26 | Tudo que acontece no app está representado dentro do sistema (retângulo)? |Angélica|
| 27 | Os atores são representados por bonecos? |Angélica|
| 28 | Os atores estão fora do sistema (retângulo)?|Angélica|
| 29 | Os atores secundários, que são aqueles que reagem após a ação do ator secundário, estão posicionados a direita do sistema? |Angélica|
| 30 | As elipses representam uma ação que realiza uma tarefa dentro do sistema (retângulo)? |Angélica|
| 31 | Os casos de uso representam cada uma das ações que o sistema faz? |Angélica|
| 32 | Os casos de uso são suficientemente descritivos? |Angélica|
| 33 | Os casos de uso são executados pelos atores? |Angélica|
| 34 | Cada ator se relaciona com pelo menos um caso?  |Angélica|
| 35 | As setas dos relacionamentos de inclusão e exclusão apontam para sentidos opostos? |Angélica|
| 36 | O caso de uso descreve o que o usuário espera de um sistema? |Angélica|
| 37 | Cada caso de uso possui apenas um fluxo principal, o que o ator realiza primeiro para usar a função? |Angélica|
| 38 | Os relacionamentos de include sempre que um caso de uso depende da execução de outro caso? |Angélica|
| 39 | Os relacionamentos de extend são utilizados quando um caso de uso se estende a outro caso de uso? |Angélica|
| 40 | Os casos de uso são inicialmente descritos por verbos no infinitivo?  |Angélica|


[Lista de verificação Guilherme – Verificação - Casos de Uso com referencia completa de cada pergunta disponivel em PDF](../../../00_assets/pdfs/verificacao/NroGrupo2GuilhermeOliveiraLVUCProj01.pdf)

[Lista de verificação Angélica – Verificação - Casos de Uso com referencia completa de cada pergunta disponivel em PDF.](../../../00_assets/pdfs/verificacao/Grupo2AngelicadaCostaCampos%20LVEspSuplProj01%20(1).pdf)


## Bibliografia
> Lucid Software Português. Tutorial de Caso de Uso UML. YouTube, 25 abr. 2019. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 26 set. 2025.


## Nível de Contribuição dos Integrantes

| Nome | % de Contribuição |
| :--- | :---------------: |
|   Angélica    |            50%       |
|   Guilherme   |            50%       |

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
| :----: | :--: | :-------- | :-------: | :-----: |
|1.1|	07/10/2025|	Adição da tabela de verificação |	Angélica	|Guilherme       
