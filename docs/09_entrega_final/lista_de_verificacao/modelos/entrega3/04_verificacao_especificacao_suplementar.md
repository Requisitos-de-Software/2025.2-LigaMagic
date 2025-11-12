# Calendário de Avaliação — Lista de Verificação — Especificação Suplementar

## Metadados

- Lista: Especificação Suplementar
- Versão/Referência: [Ver detalhes](../../../../08_inspecao/entrega3/inspecao_especificacao_suplementar.md)
- Data da Avaliação Final: 12-11-2025
- Avaliadores: Grupo 2
- Artefatos Avaliados: [Especificação Suplementar](../../../../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md)

## Legenda

- Resultado: C (Conforme), NC (Não Conforme), NA (Não Aplicável)
- % Conformidade = (C / (C + NC)) × 100

## Checklist

Principais Não Conformidades:

- **ID 04** — A seção de Desempenho não especifica requisitos de tempo de resposta, throughput ou MTBF
- **ID 08** — Não há especificação de tempo de resposta para operações do sistema
- **ID 09** — Não há especificação de throughput ou taxa de transações do sistema

| ID  | Resultado | Ação Corretiva                                                                                  | Responsável | Prazo | Status  |
| :-: | :-------: | :---------------------------------------------------------------------------------------------- | :---------: | :---: | :------ |
| 04  |    NC     | Preencher seção de Desempenho com requisitos de tempo de resposta, throughput e MTBF           |   Grupo 2   |   —   | A fazer |
| 08  |    NC     | Especificar tempo de resposta para operações críticas do sistema (ex: busca, login, transações) |   Grupo 2   |   —   | A fazer |
| 09  |    NC     | Definir taxa de throughput ou número de transações que o sistema deve suportar                 |   Grupo 2   |   —   | A fazer |

## Resumo da Lista

- Total de itens: 12
- Aplicáveis (C+NC): 7
- C: 4
- NC: 3
- NA: 5
- % Conformidade: 57,1%

Principais Não Conformidades:

- **ID 04** — A seção de Desempenho do modelo FURPS+ está completamente vazia, sem nenhum requisito especificado. O modelo FURPS+ exige que sejam definidos requisitos de desempenho como tempo de resposta, throughput e MTBF (Mean Time Between Failures).
- **ID 08** — Não há especificação de tempo de resposta para operações do sistema. É fundamental definir tempos máximos de resposta para operações críticas como buscas, autenticação e transações para garantir boa experiência do usuário.
- **ID 09** — Não há especificação de throughput ou taxa de transações que o sistema deve suportar. É necessário definir quantas operações simultâneas ou requisições por segundo o sistema deve ser capaz de processar.

## Histórico de versão

| Versão |    Data    | Descrição                                  | Autor(es) | Revisor |
| :----: | :--------: | :----------------------------------------- | :-------: | :-----: |
|  1.0   | 11/11/2025 | Criação inicial do documento de protótipos |  Samuel   | Thiago  |
|  1.1   | 12/11/2025 | Adição das não conformidades |  Thiago   | Samuel  |
