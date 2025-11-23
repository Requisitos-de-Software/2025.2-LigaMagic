# Calendário de Avaliação — Lista de Verificação — Elos de Pós-Rastreabilidade

## Metadados

- Lista: Elos de Pós-Rastreabilidade
- Versão/Referência: [Ver detalhes](../../../../08_inspecao/entrega5/03_inspecao_elos_de_rastreabilidade_grupo2.md)
- Data da Avaliação Final: [DD-MM-AAAA]
- Avaliadores: [Nomes/Equipes]
- Artefatos Avaliados: [Elos de Pós-Rastreabilidade](../../../../06_pos-rastreabilidade/elos_de_rastreabilidade.md)

## Legenda

- Resultado: C (Conforme), NC (Não Conforme)
- % Conformidade = (C / (C + NC)) × 100

## Checklist

| ID  | Resultado (C/NC/) | Ação Corretiva                                                                                                                                                         | Responsável |   Prazo    |  Status   |
| :-: | :---------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :--------: | :-------: |
| 04  |         C         | Adicionados elos de Recurso demonstrando dependências entre artefatos                                                                                                  |   Samuel    | 18/11/2025 | Concluído |
| 05  |         C         | Justificativas dos elos de Recurso explicam claramente por que o recurso é essencial (ex: verificação de cadastro depende da base de usuários existentes)              |   Samuel    | 18/11/2025 | Concluído |
| 11  |         C         | Implementados elos de Alocado designando requisitos a subsistemas específicos (RF01→Gerenciamento Usuário, RF23→E-commerce)                                            |   Samuel    | 18/11/2025 | Concluído |
| 12  |         C         | Subsistemas de destino claramente identificados: Gerenciamento de Usuário, Busca e Filtragem, E-commerce                                                               |   Samuel    | 18/11/2025 | Concluído |
| 13  |         C         | Criados sistemas agregados representando relação "parte-todo": Sistema de Gerenciamento de Usuário, Sistema de Busca e Interação com Cartas, Sistema de E-commerce     |   Samuel    | 18/11/2025 | Concluído |
| 14  |         C         | Cada sistema agregado lista claramente suas partes constituintes (ex: Sistema Usuário composto por RF01, RF02, RF03, RF12, RF15, RF19)                                 |   Samuel    | 18/11/2025 | Concluído |
| 15  |         C         | Decomposição completa e sem ambiguidades, com justificativas detalhadas para cada agregação                                                                            |   Samuel    | 18/11/2025 | Concluído |
| 18  |         C         | Elos de Recurso implementados entre artefatos que consomem e provêm recursos (ex: RF24 consome dados de RF23, RF31 consome dados de RF20)                              |   Samuel    | 18/11/2025 | Concluído |
| 22  |         C         | Adicionada seção "Classificação por Níveis de Informação" detalhando os quatro níveis: Ambiental, Organizacional, Gerencial e Desenvolvimento                          |   Samuel    | 18/11/2025 | Concluído |
| 27  |         C         | Criada tabela específica "Dependências entre Requisitos" mapeando dependências com tipos e justificativas                                                              |   Samuel    | 18/11/2025 | Concluído |
| 34  |         C         | Adicionada seção "Estratégias de Toranzo Aplicadas" listando as quatro estratégias: Classificação por Níveis, Tipos de Elo, Direcionamento e Perspectiva de Informação |   Samuel    | 18/11/2025 | Concluído |
| 37  |         C         | Registros de dependência de recurso incluídos na tabela de dependências e nos elos individuais dos requisitos                                                          |   Samuel    | 18/11/2025 | Concluído |

## Principais Não Conformidades:

- [04] — [O elo de Recurso foi utilizado para indicar que um artefato (origem) depende de um recurso provido por outro artefato (destino)?]
- [05] — [O recurso provido pelo artefato de destino é essencial para a elaboração ou existência do artefato de origem?]
- [11] — [O elo de Alocado foi utilizado para designar um requisito ou artefato a um subsistema, componente ou pacote de trabalho específico?]
- [12] — [O local (destino) para onde o artefato (origem) foi alocado está claramente identificado?]
- [13] — [O elo de Agregação foi empregado para representar uma relação de composição (“parte-todo”) entre artefatos?]
- [14] — [O artefato de origem (o “todo”) é claramente composto pelos artefatos de destino (as “partes”)?]
- [15] — [A decomposição do artefato de origem nos artefatos de destino está completa e sem ambiguidades?]
- [18] — [O elo de Recurso faz ligação entre, um artefato que consome, e um artefato que provê (Por exemplo: Backlog da Sprint ao Backlog do Produto)?]
- [22] — [Existe uma classificação composta por quatro níveis de informação — ambiental, organizacional, gerencial e de desenvolvimento]
- [27] — [A rastreabilidade entre requisitos mapeia dependências entre requisitos?]
- [34] — [Na proposta de Toranzo para rastreabilidade foram utilizadas quatro estratégias?]
- [37] — [Há registro de dependência de recurso entre requisitos?]

## Resumo da Lista

- Total de itens: 38
- Aplicáveis (C+NC): 28
- C: 28
- NC: 0
- % Conformidade: 100%

## Agradecimentos

O Grupo 02 agradece o apoio das ferramentas de Inteligência Artificial Generativa — ChatGPT e Google Gemini — na revisão e padronização de nossos artefatos. Essas tecnologias foram utilizadas para auxiliar na organização do repositório. Todo o conteúdo, incluindo a precisão técnica e as ideias apresentadas, é de responsabilidade dos autores.

## Histórico de versão

| Versão |    Data    | Descrição                                                                             | Autor(es) | Revisor |
| :----: | :--------: | :------------------------------------------------------------------------------------ | :-------: | :-----: |
|  1.0   | 11/11/2025 | Criação inicial do documento de protótipos                                            |  Samuel   | Thiago  |
|  1.1   | 18/11/2025 | Preenchimento da tabela com adequação às novas conformidades dos artefatos corrigidos |  Samuel   | Thiago  |
