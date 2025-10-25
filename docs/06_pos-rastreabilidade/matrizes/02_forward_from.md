# Forward-from

## Descrição

A rastreabilidade forward-from (para frente, a partir de) diz respeito à ligação entre os requisitos e os artefatos de desenho e implementação. Esta abordagem, também conhecida como pós-rastreabilidade , permite acompanhar o percurso de cada requisito desde sua definição até sua efetiva implementação e validação , ligando-os a artefatos como componentes de arquitetura, código e casos de teste. (SAYÃO; LEITE, 2005).

## Objetivo

A análise da rastreabilidade forward-from tem como principal finalidade garantir que todos os requisitos identificados estejam corretamente refletidos nas fases seguintes do projeto. Esse tipo de rastreabilidade assegura a verificação de que um requisito foi de fato implementado no sistema , permitindo identificar requisitos ainda não alocados a componentes de software ou que não possuem casos de teste previstos.

Além disso, esse processo facilita a análise de impacto de mudanças e contribui para a validação final do sistema, possibilitando demonstrar aos clientes que a implementação atende à baseline de requisitos acordada.

## Metodologia

Para realizar a análise de rastreabilidade forward-from, foram considerados os vínculos estabelecidos entre os requisitos e diferentes artefatos gerados durante o projeto. Abaixo estão listados os tipos de artefatos utilizados na documentação e validação dos requisitos, junto às respectivas siglas utilizadas para identificá-los:

- UC – Casos de Uso (Use Case)

- US – Histórias de Usuário

- NFR – NFR Framework (Requisitos Não Funcionais)

- ESP – Especificação Suplementar

- CN – Cenários

- LX – Léxico

- EP – Épicos

## Conteúdo

### Requisitos Funcionais

|    ID    | Requisito                                                        | Implementado |  Cenário   | Léxico | Caso de Uso | Épico | Elos | História de Usuário |
| :------: | :--------------------------------------------------------------- | :----------: | :--------: | :----: | :---------: | :---: | :--: | :-----------------: |
|   RF01   | Permitir Cadastro de usuário                                     |     Sim      |     -      |        |      -      |       |      |        US09         |
|   RF02   | Deve verificar duplicação de cadastros                           |     Sim      |     -      |        |      -      |       |      |        US03         |
|   RF03   | Deve permitir acesso via login e senha                           |     Sim      |     -      |        |      -      |       |      |        US10         |
|   RF04   | Deve permitir apenas produtos relacionados a Magic               |     Sim      |     -      |        |      -      |       |      |        US15         |
|   RF05   | Deve verificar veracidade de dados cadastrados                   |     Sim      |     -      |        |      -      |       |      |        US37         |
|   RF06   | Deve permitir inclusão de textos, descrição e fotos nos anúncios |     Sim      |     -      |        |      -      |       |      |        US34         |
|   RF07   | Deve facilitar contato direto com usuário                        |     Sim      |     -      |        |      -      |       |      |          -          |
|   RF08   | Deve implemetar cobrança de anúncios e venda                     |     Sim      |     -      |        |      -      |       |      |          -          |
|   RF09   | Deve permitir troca de mensagens privadas                        |     Sim      |     -      |        |      -      |       |      |        US38         |
|   RF10   | Deve permitir criação de páginas pessoais                        |     Não      |    CE06    |        |    UC05     |       |      |     US13, US22      |
|   RF11   | Deve permitir envio e respostas a mensagens no fórum             |     Não      |    CE11    |        |    UC09     |       |      |        US01         |
|   RF12   | Registrar dados pessoais do usuário                              |     Sim      |     -      |        |      -      |       |      |        US21         |
|   RF13   | Utilizar dados para finalidades específicas                      |     Sim      |     -      |        |      -      |       |      |        US41         |
|   RF14   | Compartilhar dados com parceiros                                 |     Sim      |     -      |        |      -      |       |      |          -          |
|   RF15   | Garantir direitos de titulares                                   |     Sim      |     -      |        |      -      |       |      |        US39         |
|   RF16   | Oferecer canal de contato para solicitações                      |     Sim      |     -      |        |      -      |       |      |     US16, US24      |
|   RF17   | Utilizar cookies para personalização                             |     Sim      |     -      |        |      -      |       |      |        US40         |
|   RF18   | Permitir controle de cookies                                     |     Sim      |     -      |        |      -      |       |      |        US25         |
|   RF19   | Solicitar atualização de dados pessoais                          |     Sim      |     -      |        |      -      |       |      |        US11         |
| **RF20** | Pesquisa de cartas pelo nome                                     |     Não      |    CE03    |        |    UC02     |       |      |     US04, US08      |
|  RF21.1  | Filtrar cartas por preço                                         |     Sim      |     -      |        |      -      |       |      |        US05         |
|  RF21.2  | Filtrar cartas por condição                                      |     Não      |    CE07    |        |    UC06     |       |      |        US14         |
|  RF21.3  | Filtrar cartas por idioma                                        |     Não      |     -      |        |      -      |       |      |          -          |
|   RF22   | Exibir resultados da pesquisa                                    |     Sim      |     -      |        |      -      |       |      |        US06         |
|   RF23   | Realizar compra                                                  |     Sim      |     -      |        |      -      |       |      |        US31         |
|   RF24   | Histórico de compras                                             |     Sim      |     -      |        |      -      |       |      |        US12         |
|   RF25   | Visualizar decks                                                 |     Sim      |     -      |        |      -      |       |      |        US26         |
|   RF26   | Fórum                                                            |     Sim      |     -      |        |      -      |       |      |        US27         |
|   RF27   | Detalhes da carta                                                |     Sim      |     -      |        |      -      |       |      |          -          |
|   RF28   | Adicionar a listas                                               |     Não      | CE01, CE02 |        |    UC01     |       |      |        US07         |
|   RF29   | Avaliar ou dar feedback                                          |     Não      |    CE13    |        |    UC11     |       |      |        US19         |
|   RF30   | Informações detalhadas da carta                                  |     Sim      |     -      |        |      -      |       |      |        US17         |
|   RF31   | Alerta de preço                                                  |     Não      |    CE04    |        |    UC03     |       |      |        US36         |
|   RF32   | Buscar decks relacionados                                        |     Sim      |     -      |        |      -      |       |      |        US18         |
|   RF33   | Preço médio por edição                                           |     Sim      |     -      |        |      -      |       |      |        US33         |
|   RF34   | Histórico de preços                                              |     Sim      |     -      |        |      -      |       |      |        US32         |
|   RF35   | Adicionar a diferentes listas                                    |     Sim      |     -      |        |      -      |       |      |        US23         |
|   RF36   | Compartilhar carta                                               |     Não      |    CE12    |        |    UC10     |       |      |        US02         |
|   RF37   | Reportar problemas                                               |     Não      |    CE05    |        |    UC04     |       |      |     US28, US35      |
|   RF38   |   Gerenciar e Catalogar Cartas                                                               |     Não      |    [CE14](../../05_modelagem/01_cenarios/cenarios.md#ce14)        |        |  [UC12](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc12)            |       |      |               [US20](/05_modelagem/05_agil/01_historias_de_usuario/#us20)      |

### Requisitos Não Funcionais

|  ID   | Requisito                                          | Implementado | Elos | NFR Framework |
| :---: | :------------------------------------------------- | :----------: | :--: | :-----------: |
| RNF01 | Cumprir legislações aplicáveis                     |     Sim      |
| RNF02 | Adotar medidas de segurança                        |     Sim      |
| RNF03 | Definir procedimentos para incidentes de segurança |     Sim      |
| RNF04 | Notificar alterações de política                   |     Sim      |
| RNF05 | Exigir consentimento e concordância explícita      |     Sim      |
| RNF06 | Atualização do Sistema                             |     Sim      |
| RNF07 | Informações Legais e Tributárias                   |     Sim      |
| RNF08 | Responsividade                                     |     Sim      |
| RNF09 | Organização visual                                 |     Sim      |
| RNF10 | Tempo de resposta para busca                       |     Sim      |
| RNF11 | Disponibilidade                                    |     Sim      |
| RNF12 | Compatibilidade com navegadores                    |     Sim      |
| RNF13 | Segurança de dados                                 |     Sim      |
| RNF14 | Padronização de mensagens                          |     Sim      |
| RNF15 | Backup de dados                                    |     Sim      |
| RNF16 | Escalabilidade                                     |     Sim      |
| RNF17 | Armazenamento e Retenção                           |     Não      |
| RNF18 | Procedimento para Incidentes                       |     Não      |
| RNF19 | Base Legal Específica                              |     Não      |

## Referências

<a id="PRESSMAN"></a>

> 1. SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. _Rastreabilidade de Requisitos_. Monografias em Ciência da Computação, n° 20/05. 2005.

## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição |
| :----- | :---------------: |
| Samuel |                   |
| Thiago |                   |

## Histórico de versão

| Versão |    Data    | Descrição                    | Autor(es) | Revisor |
| :----: | :--------: | :--------------------------- | :-------: | :-----: |
|  1.0   | 23/10/2025 | Criação inicial do documento |  Samuel   |    -    |
|  1.1   | 24/10/2025 | Edição inicial do documento  |  Thiago   | Samuel  |
