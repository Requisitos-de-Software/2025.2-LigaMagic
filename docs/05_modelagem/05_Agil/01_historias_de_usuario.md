# Histórias de Usuário

## Descrição

Este artefato documenta as histórias de usuário desenvolvidas para o sistema, seguindo a metodologia ágil. As histórias são descritas na perspectiva do usuário final e incluem critérios de aceitação claros para orientar o desenvolvimento e validação das funcionalidades.
_(PRESSMAN, cap. 3)_[¹](#PRESSMAN).

## Objetivo

O objetivo deste artefato é definir os requisitos funcionais do sistema através de histórias de usuário que representem as necessidades e expectativas dos usuários.

## Metodologia

As histórias de usuário foram criadas seguindo o padrão:

**“Como [tipo de usuário], eu quero [funcionalidade] para que [benefício]”**,

em alinhamento com as práticas de levantamento de requisitos no desenvolvimento ágil, nas quais os usuários descrevem necessidades em forma de histórias que orientam a implementação incremental _(PRESSMAN, cap. 3)_[¹](#PRESSMAN).

Cada uma delas foi elaborada com critérios de aceitação claros, priorizadas com base no valor que trazem para o usuário e rastreáveis aos [requisitos elicitados](../../03_elicitacao/artefatos/requisitos_elicitados.md).

Para garantir que as histórias estejam completas e bem definidas, usamos uma [lista de verificação](../../06_verificacao/entrega4/verificacao_historias_de_usuario.md) durante todo o processo de elaboração.

A validação dessas histórias será feita por meio de revisões com usuários reais do sistema, garantindo que atendam às necessidades deles.

## Conteúdo

### Tabela de contribuição

| Histórias de Usuário                                                                     |   Autor   |
| :--------------------------------------------------------------------------------------- | :-------: |
| [US01](#us01), [US02](#us02), [US03](#us03), [US04](#us04), [US05](#us05), [US06](#us06) |  Samuel   |
| [US07](#us07), [US08](#us08), [US09](#us09), [US10](#us10), [US11](#us11), [US12](#us12) | Angélica  |
| [US13](#us13), [US14](#us14), [US15](#us15), [US16](#us16), [US17](#us17), [US18](#us18) |  Marcelo  |
| [US19](#us19), [US20](#us20), [US21](#us21), [US22](#us22), [US23](#us23), [US24](#us24) |  Thiago   |
| [US25](#us25), [US26](#us26), [US27](#us27), [US28](#us28), [US29](#us29), [US30](#us30) |  Raissa   |
| [US31](#us31), [US32](#us32), [US33](#us33), [US34](#us34), [US35](#us35), [US36](#us36) |   Vera    |
| [US37](#us37), [US38](#us38), [US39](#us39), [US40](#us40), [US41](#us41), [US42](#us42) | Guilherme |

<div align="center"><strong>Tabela 1:</strong> Distribuição das histórias de usuário</div>

**Fonte:** Samuel, 2025

---

### Modelo de História de Usuário

| **Item**                          | **Descrição**                                               |
| --------------------------------- | ----------------------------------------------------------- |
| **USx (número de identificação)** | USx                                                         |
| **Tema**                          | [Tema da história]                                          |
| **Descrição**                     | Eu, como [tipo de usuário], desejo [ação] para [benefício]. |
| **Critérios de Aceitação**        | - Critério 1 <br>- Critério 2 <br>- Critério 3              |
| **Prioridade**                    | [Alta, Média ou Baixa]                                      |
| **Status**                        | [Validada / Não Validada]                                   |
| **Rastreabilidade**               | [Código do requisito relacionado]                           |
| **Validação**                     | [Link para vídeo de validação, se houver]                   |

<div align="center"><strong>Tabela 2:</strong> Modelo de histórias de usuário</div>

**Fonte:** Samuel, 2025

---

### Histórias de Usuário

#### [US01] - Participar de Fóruns de Discussão {#us01}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                                        |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US01                                                                                                                                                                                                                                                                                                 |
| **Tema**                   | Participar de Fóruns de Discussão                                                                                                                                                                                                                                                                    |
| **Descrição**              | Eu, como um jogador iniciante, desejo criar e responder tópicos em um fórum de discussão para poder tirar dúvidas e aprender com jogadores mais experientes.                                                                                                                                         |
| **Critérios de Aceitação** | - O sistema deve me permitir visualizar uma lista de subfóruns. <br>- O sistema deve me permitir criar um novo tópico com título e mensagem em um subfórum. <br>- O sistema deve me permitir visualizar as respostas de um tópico. <br>- O sistema deve me permitir responder a um tópico existente. |
| **Prioridade**             | Média                                                                                                                                                                                                                                                                                                |
| **Status**                 | Validada                                                                                                                                                                                                                                                                                             |
| **Rastreabilidade**        | [RFNI02](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni02)                                                                                                                                                                                                                       |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                                                                          |

<div align="center"><strong>Tabela 3:</strong> História de Usuário – Participar de Fóruns de Discussão</div>

**Fonte:** Samuel, 2025

#### [US02] - Compartilhar Carta por Link {#us02}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                                 |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US02                                                                                                                                                                                                                                                                                          |
| **Tema**                   | Compartilhar Carta por Link                                                                                                                                                                                                                                                                   |
| **Descrição**              | Eu, como um jogador, desejo compartilhar o link de uma carta específica para poder mostrar a um amigo ou pedir uma opinião de forma rápida e precisa.                                                                                                                                         |
| **Critérios de Aceitação** | - O sistema deve me permitir buscar por uma carta pelo nome. <br>- Na tela de detalhes da carta, deve haver uma opção de "Compartilhar". <br>- Ao selecionar "Compartilhar", o sistema deve abrir o menu de compartilhamento nativo do meu celular com um link direto para a página da carta. |
| **Prioridade**             | Alta                                                                                                                                                                                                                                                                                          |
| **Status**                 | Validada                                                                                                                                                                                                                                                                                      |
| **Rastreabilidade**        | [RFNI06](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni06)                                                                                                                                                                                                                |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                                                                   |

<div align="center"><strong>Tabela 4:</strong> História de Usuário – Compartilhar Carta por Link</div>

**Fonte:** Samuel, 2025

#### [US03] - Verificar Cadastro Duplicado {#us03}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                    |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **USx**                    | US03                                                                                                                                                                                                                                             |
| **Tema**                   | Verificar Cadastro Duplicado                                                                                                                                                                                                                     |
| **Descrição**              | Eu, como um novo usuário, desejo ser informado se meu e-mail já está cadastrado ao tentar criar uma conta para evitar a criação de contas duplicadas e recuperar meu acesso, se necessário.                                                      |
| **Critérios de Aceitação** | - Dado que eu preencha o formulário de cadastro com um e-mail que já existe no sistema, Quando eu tentar submeter o formulário, Então o sistema deve exibir a mensagem "Este e-mail já está em uso. Deseja fazer login ou recuperar sua senha?". |
| **Prioridade**             | Alta                                                                                                                                                                                                                                             |
| **Status**                 | Validada                                                                                                                                                                                                                                         |
| **Rastreabilidade**        | [RF2](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf2)                                                                                                                                                                                |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                      |

<div align="center"><strong>Tabela 5:</strong> História de Usuário – Verificar Cadastro Duplicado</div>

**Fonte:** Samuel, 2025

#### [US04] - Pesquisar Cartas por Nome {#us04}

| **Item**                   | **Descrição**                                                                                                                                                                                                                 |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US04                                                                                                                                                                                                                          |
| **Tema**                   | Pesquisar Cartas por Nome                                                                                                                                                                                                     |
| **Descrição**              | Eu, como um jogador, desejo pesquisar cartas pelo nome para encontrar rapidamente suas informações, edições disponíveis e preços de mercado.                                                                                  |
| **Critérios de Aceitação** | - O sistema deve possuir um campo de busca de texto visível na tela principal ou na seção de cartas. <br>- Ao digitar o nome de uma carta e confirmar a busca, o sistema deve exibir uma lista de resultados correspondentes. |
| **Prioridade**             | Alta                                                                                                                                                                                                                          |
| **Status**                 | Validada                                                                                                                                                                                                                      |
| **Rastreabilidade**        | [RF20](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf20)                                                                                                                                                           |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                   |

<div align="center"><strong>Tabela 6:</strong> História de Usuário – Pesquisar Cartas por Nome</div>

**Fonte:** Samuel, 2025

#### [US05] - Filtrar Resultados de Busca de Cartas {#us05}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                                                                       |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US05                                                                                                                                                                                                                                                                                                                                |
| **Tema**                   | Filtrar Resultados de Busca de Cartas                                                                                                                                                                                                                                                                                               |
| **Descrição**              | Eu, como um comprador, desejo filtrar os resultados da busca de cartas por preço, condição (ex: Nova, Usada) e idioma para encontrar ofertas que atendam exatamente às minhas necessidades e orçamento.                                                                                                                             |
| **Critérios de Aceitação** | - Na tela de resultados da busca, deve haver uma opção para aplicar filtros. <br>- O sistema deve permitir que eu selecione um ou mais filtros de condição, idioma e defina uma faixa de preço. <br>- Ao aplicar os filtros, a lista de resultados deve ser atualizada para exibir apenas as cartas que correspondem aos critérios. |
| **Prioridade**             | Média                                                                                                                                                                                                                                                                                                                               |
| **Status**                 | Validada                                                                                                                                                                                                                                                                                                                            |
| **Rastreabilidade**        | [RF21](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf21)                                                                                                                                                                                                                                                                 |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                                                                                                         |

<div align="center"><strong>Tabela 7:</strong> História de Usuário – Filtrar Resultados de Busca de Cartas</div>

**Fonte:** Samuel, 2025

#### [US06] - Visualizar Informações Relevantes nos Resultados {#us06}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                          |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US06                                                                                                                                                                                                                                                                                   |
| **Tema**                   | Visualizar Informações Relevantes nos Resultados                                                                                                                                                                                                                                       |
| **Descrição**              | Eu, como um comprador, desejo ver o menor preço, a condição, o idioma e a reputação do vendedor diretamente na lista de resultados da pesquisa para poder comparar as opções disponíveis de forma eficiente, sem precisar clicar em cada item.                                         |
| **Critérios de Aceitação** | - Cada item na lista de resultados da busca deve exibir o nome da carta, a imagem em miniatura, o menor preço disponível, a condição, o idioma e uma indicação da reputação do vendedor (ex: estrelas ou nota). <br>- As informações devem estar organizadas de forma clara e legível. |
| **Prioridade**             | Alta                                                                                                                                                                                                                                                                                   |
| **Status**                 | Validada                                                                                                                                                                                                                                                                               |
| **Rastreabilidade**        | [RF22](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf22)                                                                                                                                                                                                                    |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                                                            |

<div align="center"><strong>Tabela 8:</strong> História de Usuário – Visualizar Informações Relevantes nos Resultados</div>

**Fonte:** Samuel, 2025

#### [US07] - Lista de Desejos (Wishlist) {#us07}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                                       |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | **US07**                                                                                                                                                                                                                                                                                            |
| **Tema**                   | Lista de Desejos (Wishlist)                                                                                                                                                                                                                                                                         |
| **Descrição**              | Eu, como usuário comprador\*\*, desejo salvar cartas em uma lista de desejos (wishlist) para poder comprá-las futuramente ou acompanhar mudanças de preço.                                                                                                                                          |
| **Critérios de Aceitação** | - O sistema deve permitir adicionar uma carta à lista de desejos a partir da página de resultados ou detalhes da carta. <br> - O usuário deve poder visualizar todas as cartas salvas em uma seção dedicada (“Minha Wishlist”). <br> - O usuário deve conseguir remover cartas da lista de desejos. |
| **Prioridade**             |                                                                                                                                                                                                                                                                                                     |
| **Status**                 |                                                                                                                                                                                                                                                                                                     |
| **Rastreabilidade**        | [RFNI14](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni14)                                                                                                                                                                                                                      |
| **Validação**              |                                                                                                                                                                                                                                                                                                     |

<div align="center"><strong>Tabela 9:</strong> História de Usuário –  Lista de Desejos (Wishlist)                          </div>

**Fonte:** Angélica, 2025

#### [US08] - Busca Rápida de Cartas {#us08}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                               |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | **US08**                                                                                                                                                                                                                                                    |
| **Tema**                   | Busca Rápida de Cartas                                                                                                                                                                                                                                      |
| **Descrição**              | Eu, como usuário comprador, desejo realizar buscas por cartas específicas de forma eficiente e intuitiva, para encontrar rapidamente as cartas que desejo adquirir.                                                                                         |
| **Critérios de Aceitação** | - O sistema deve permitir a busca por nome, tipo ou categoria da carta. <br> - Os resultados devem ser exibidos de forma clara e organizada.<br> - A busca deve funcionar mesmo com pequenas variações de digitação (ex: acentos ou maiúsculas/minúsculas). |
| **Prioridade**             |                                                                                                                                                                                                                                                             |
| **Status**                 |                                                                                                                                                                                                                                                             |
| **Rastreabilidade**        | [RFNI15](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni15)                                                                                                                                                                              |
| **Validação**              |                                                                                                                                                                                                                                                             |

<div align="center"><strong>Tabela 10:</strong> História de Usuário –  Busca Rápida de Cartas                            </div>

**Fonte:** Angélica, 2025

#### [US09] - Cadastro de Usuário {#us09}

| **Item**                   | **Descrição**                                                                                                                                                                                    |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **USx**                    | **US09**                                                                                                                                                                                         |
| **Tema**                   | Cadastro de usuário                                                                                                                                                                              |
| **Descrição**              | Eu, como usuário comprador desejo realizar meu cadastro na plataforma para acessar os recursos do sistema e salvar minhas informações pessoais de forma segura                                   |
| **Critérios de Aceitação** | - O sistema deve permitir o cadastro com nome, e-mail e senha. <br> - O sistema deve validar se o e-mail já está cadastrado. <br> - O usuário deve receber confirmação de cadastro bem-sucedido. |
| **Prioridade**             |                                                                                                                                                                                                  |
| **Status**                 |                                                                                                                                                                                                  |
| **Rastreabilidade**        | [RF1](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf1)                                                                                                                                |
| **Validação**              | —                                                                                                                                                                                                |

<div align="center"><strong>Tabela 11:</strong> História de Usuário – Cadastro de usuário                          </div>

**Fonte:** Angélica, 2025

#### [US10] - Login e Autenticação {#us10}

| **Item**                   | **Descrição**                                                                                                                                                                                                      |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **USx**                    | **US10**                                                                                                                                                                                                           |
| **Tema**                   | Login de usuário                                                                                                                                                                                                   |
| **Descrição**              | Eu, como usuário comprador desejo acessar minha conta usando e-mail e senha para visualizar minhas informações e histórico de atividades                                                                           |
| **Critérios de Aceitação** | - O sistema deve validar e autenticar o login do usuário. <br> - Em caso de erro, deve exibir mensagem clara de credenciais incorretas. <br> - O login deve redirecionar o usuário para a tela inicial do sistema. |
| **Prioridade**             |                                                                                                                                                                                                                    |
| **Status**                 |                                                                                                                                                                                                                    |
| **Rastreabilidade**        | [RF3](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf3)                                                                                                                                                  |
| **Validação**              | —                                                                                                                                                                                                                  |

<div align="center"><strong>Tabela 12:</strong> História de Usuário – Login e Autenticação                      </div>

**Fonte:** Angélica, 2025

#### [US11] - Atualização de Dados do Usuário {#us11}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                  |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **USx**                    | **US11**                                                                                                                                                                                                                                                                       |
| **Tema**                   | Atualização de Dados do Usuário                                                                                                                                                                                                                                                |
| **Descrição**              | Eu, como usuário comprador desejo atualizar meus dados pessoais (como endereço, telefone e e-mail)para manter minhas informações corretas e facilitar futuras compras ou comunicações                                                                                          |
| **Critérios de Aceitação** | - O sistema deve permitir a edição de dados pessoais (nome, e-mail, telefone, endereço). <br> - As alterações devem ser salvas corretamente no perfil do usuário. <br> - Caso algum campo obrigatório não esteja preenchido, o sistema deve exibir uma mensagem de erro clara. |
| **Prioridade**             |                                                                                                                                                                                                                                                                                |
| **Status**                 | Não Validada                                                                                                                                                                                                                                                                   |
| **Rastreabilidade**        | [RF19](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf19)                                                                                                                                                                                                            |
| **Validação**              |                                                                                                                                                                                                                                                                                |

<div align="center"><strong>Tabela 13:</strong> História de Usuário – Atualização de Dados do Usuário                  </div>

**Fonte:** Angélica, 2025

#### [US12] - Histórico de Compras {#us12}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                            |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | **US12**                                                                                                                                                                                                                                                                                 |
| **Tema**                   | Histórico de Compras                                                                                                                                                                                                                                                                     |
| **Descrição**              | Eu, como usuário comprador desejo acessar meu histórico de compras com informações detalhadas para consultar produtos adquiridos, datas e valores pagos                                                                                                                                  |
| **Critérios de Aceitação** | - O sistema deve exibir uma lista com todas as compras realizadas pelo usuário. <br> - Cada item do histórico deve mostrar a data da compra, nome do produto, quantidade e valor pago. <br> - O usuário deve conseguir visualizar detalhes de cada compra ao clicar em um item da lista. |
| **Prioridade**             |                                                                                                                                                                                                                                                                                          |
| **Status**                 |                                                                                                                                                                                                                                                                                          |
| **Rastreabilidade**        | [RF24](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf24)                                                                                                                                                                                                                      |
| **Validação**              |                                                                                                                                                                                                                                                                                          |

<div align="center"><strong>Tabela 14:</strong> História de Usuário – Histórico de Compras      </div>

**Fonte:** Angélica, 2025

<div align="center"><strong>Tabela 13:</strong> História de Usuário – Personalizar Página do Usuário      </div>

#### [US13] - Personalizar Página do Usuário {#us13}

| **Item**                   | **Descrição**                                                                                                                                                                                                            |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **USx**                    | US13                                                                                                                                                                                                                     |
| **Tema**                   | Personalizar Página do Usuário                                                                                                                                                                                           |
| **Descrição**              | Eu, como usuário, desejo personalizar e manter minha página pessoal/profissional para exibir minhas informações e preferências dentro da plataforma.                                                                     |
| **Critérios de Aceitação** | - O sistema deve permitir que o usuário altere informações pessoais e profissionais. - O sistema deve permitir o upload de imagem de perfil. - O sistema deve permitir salvar e editar as informações da página pessoal. |
| **Prioridade**             | -                                                                                                                                                                                                                        |
| **Status**                 | Não Validada                                                                                                                                                                                                             |
| **Rastreabilidade**        | [RFNI01](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni01)                                                                                                                                           |
| **Validação**              | -                                                                                                                                                                                                                        |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 15:</strong> História de Usuário – Filtragem de Cartas por Qualidade/Condição      </div>

#### [US14] - Filtragem de Cartas por Qualidade/Condição {#us14}

| **Item**                   | **Descrição**                                                                                                                                                                                                                    |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US14                                                                                                                                                                                                                             |
| **Tema**                   | Filtragem de Cartas por Qualidade/Condição                                                                                                                                                                                       |
| **Descrição**              | Eu, como usuário, desejo filtrar cartas por qualidade e condição para encontrar produtos que atendam melhor às minhas preferências.                                                                                              |
| **Critérios de Aceitação** | - O sistema deve oferecer filtros por qualidade (nova, usada, etc.). <br> - O sistema deve oferecer filtros por condição (ótima, boa, regular). <br> - O sistema deve atualizar a lista de cartas conforme os filtros aplicados. |
| **Prioridade**             | -                                                                                                                                                                                                                                |
| **Status**                 | Não Validada                                                                                                                                                                                                                     |
| **Rastreabilidade**        | [RFNI03](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni03)                                                                                                                                                   |
| **Validação**              | -                                                                                                                                                                                                                                |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 16:</strong> História de Usuário – Restrição de Produtos      </div>

#### [US15] - Restrição de Produtos {#us15}

| **Item**                   | **Descrição**                                                                                                                                                                                   |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US15                                                                                                                                                                                            |
| **Tema**                   | Restrição de Produtos                                                                                                                                                                           |
| **Descrição**              | Eu, como administrador do sistema, desejo garantir que apenas produtos relacionados a Magic: The Gathering sejam cadastrados na plataforma, para manter a relevância e integridade do conteúdo. |
| **Critérios de Aceitação** | - O sistema deve bloquear o cadastro de produtos que não pertençam ao universo de Magic. <br> - O sistema deve validar o tipo de produto antes de permitir sua publicação.                      |
| **Prioridade**             | -                                                                                                                                                                                               |
| **Status**                 | Não Validada                                                                                                                                                                                    |
| **Rastreabilidade**        | [RF04](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf04)                                                                                                                             |
| **Validação**              | -                                                                                                                                                                                               |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 17:</strong> História de Usuário – Visualização de Detalhes da Carta      </div>

#### [US16] - Visualização de Detalhes da Carta {#us16}

| **Item**                   | **Descrição**                                                                                                                                                                                                          |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US16                                                                                                                                                                                                                   |
| **Tema**                   | Visualização de Detalhes da Carta                                                                                                                                                                                      |
| **Descrição**              | Eu, como usuário, desejo visualizar detalhes de uma carta ao clicar no resultado da pesquisa para conhecer mais sobre ela antes de comprar ou trocar.                                                                  |
| **Critérios de Aceitação** | - O sistema deve exibir informações completas da carta selecionada. <br> - O sistema deve apresentar uma interface clara e organizada para os detalhes. <br> - O sistema deve permitir retornar à lista de resultados. |
| **Prioridade**             | -                                                                                                                                                                                                                      |
| **Status**                 | Não Validada                                                                                                                                                                                                           |
| **Rastreabilidade**        | [RF27](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf27)                                                                                                                                                    |
| **Validação**              | -                                                                                                                                                                                                                      |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 18:</strong> História de Usuário – Exibição de Informações Detalhadas da Carta     </div>

#### [US17] - Exibição de Informações Detalhadas da Carta {#us17}

| **Item**                   | **Descrição**                                                                                                                                                                                                          |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US17                                                                                                                                                                                                                   |
| **Tema**                   | Exibição de Informações Detalhadas da Carta                                                                                                                                                                            |
| **Descrição**              | Eu, como usuário, desejo visualizar informações detalhadas de cada carta, incluindo edição, idioma, condição e preço médio, para tomar decisões mais informadas.                                                       |
| **Critérios de Aceitação** | - O sistema deve mostrar a edição, idioma, condição e preço médio da carta. <br> - As informações devem estar visíveis na tela de detalhes. <br> - Os dados devem ser consistentes com o banco de dados da plataforma. |
| **Prioridade**             | -                                                                                                                                                                                                                      |
| **Status**                 | Não Validada                                                                                                                                                                                                           |
| **Rastreabilidade**        | [RF30](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf30)                                                                                                                                                    |
| **Validação**              | -                                                                                                                                                                                                                      |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 19:</strong> História de Usuário – Buscar Decks Relacionados </div>

#### [US18] - Buscar Decks Relacionados {#us18}

| **Item**                   | **Descrição**                                                                                                                                                                                                      |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **USx**                    | US18                                                                                                                                                                                                               |
| **Tema**                   | Buscar Decks Relacionados                                                                                                                                                                                          |
| **Descrição**              | Eu, como usuário, desejo buscar decks que utilizam a carta selecionada para entender como ela é usada em diferentes estratégias.                                                                                   |
| **Critérios de Aceitação** | - O sistema deve permitir buscar decks que incluam a carta selecionada. <br> - O sistema deve apresentar uma lista com os decks encontrados. <br> - O sistema deve permitir acessar detalhes de cada deck listado. |
| **Prioridade**             | -                                                                                                                                                                                                                  |
| **Status**                 | Não Validada                                                                                                                                                                                                       |
| **Rastreabilidade**        | [RF32](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf32)                                                                                                                                                |
| **Validação**              | -                                                                                                                                                                                                                  |

**Fonte:** Marcelo, 2025

#### [US19] - Avaliação de Vendedor {#us19}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                                                                    |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US19                                                                                                                                                                                                                                                                                                                             |
| **Tema**                   | Feedback e Reputação                                                                                                                                                                                                                                                                                                             |
| **Descrição**              | Eu, como Comprador, desejo avaliar um vendedor após uma compra concluída para ajudar outros usuários a tomar decisões e fornecer feedback ao vendedor.                                                                                                                                                                           |
| **Critérios de Aceitação** | - O usuário só pode avaliar um vendedor após um pedido ter o status "Entregue". <br>- O sistema deve permitir uma avaliação de 1 a 5 estrelas. <br>- O sistema deve permitir um campo de comentário opcional (limite 500 caracteres). <br>- A avaliação (nota e comentário) deve ser exibida publicamente no perfil do vendedor. |
| **Prioridade**             | Média                                                                                                                                                                                                                                                                                                                            |
| **Status**                 | Validada                                                                                                                                                                                                                                                                                                                         |
| **Rastreabilidade**        | [RFNI04](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni04)                                                                                                                                                                                                                                                   |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                                                                                                      |

<div align="center"><strong>Tabela 20:</strong> História de Usuário – Avaliação de Vendedor</div>

**Fonte:** Thiago, 2025

#### [US20] - Adicionar Carta à Coleção Pessoal {#us20}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US20                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Tema**                   | Gerenciamento de Coleção                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Descrição**              | Eu, como Colecionador, desejo adicionar cartas à minha coleção pessoal para manter um inventário digital do que eu possuo.                                                                                                                                                                                                                                                                                                                                            |
| **Critérios de Aceitação** | - O usuário deve ter uma seção "Minha Coleção" em seu perfil.<br>- Na "Minha Coleção", deve existir um botão "Adicionar Carta".<br>- O sistema deve fornecer uma busca (pelo nome da carta) para encontrar a carta no banco de dados global do sistema.<br>- Ao selecionar a carta, o usuário deve poder informar: Quantidade, Condição (Mint, Near Mint, Played, etc.) e Idioma.<br>- A carta adicionada (com seus detalhes) deve aparecer na lista "Minha Coleção". |
| **Prioridade**             | Média                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Status**                 | Validada                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Rastreabilidade**        | [RFNI10](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni10)                                                                                                                                                                                                                                                                                                                                                                                        |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                                                                                                                                                                                                                                           |

<div align="center"><strong>Tabela 21:</strong> História de Usuário – Adicionar Carta à Coleção Pessoal</div>

**Fonte:** Thiago, 2025

#### [US21] - Registro de Conta de Usuário {#us21}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **USx**                    | US21                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Tema**                   | Gerenciamento de Conta                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Descrição**              | Eu, como Visitante, desejo me registrar na plataforma fornecendo meus dados pessoais (Nome, E-mail, CPF, etc.) para criar uma conta e acessar as funcionalidades restritas.                                                                                                                                                                                                                                                                                                                                                                      |
| **Critérios de Aceitação** | - O formulário de registro deve solicitar: Nome Completo, E-mail, CPF, Data de Nascimento e Senha.<br>- O sistema deve validar o formato do E-mail e a unicidade (não pode estar em uso).<br>- O sistema deve validar o formato do CPF (ex: 11 dígitos numéricos).<br>- Os campos de Endereço (CEP, Rua, etc.) e Telefone podem ser solicitados no primeiro acesso ao perfil, após o registro.<br>- (O RG não será obrigatório no registro inicial).<br>- Após o registro, o usuário deve ser autenticado ou direcionado para a página de login. |
| **Prioridade**             | Alta                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Status**                 | Validada                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Rastreabilidade**        | [RF12](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf12)                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |

<div align="center"><strong>Tabela 22:</strong> História de Usuário – Registro de Conta de Usuário</div>

**Fonte:** Thiago, 2025

#### [US22] - Personalização do Perfil Público {#us22}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                             |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US22                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Tema**                   | Perfil de Usuário                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Descrição**              | Eu, como Usuário Cadastrado (Vendedor ou Colecionador), desejo personalizar minha página de perfil público com foto e descrição para me apresentar à comunidade.                                                                                                                                                                                                                                                          |
| **Critérios de Aceitação** | - O usuário deve ter uma área "Editar Perfil" na sua conta.<br>- O usuário deve poder carregar uma foto de perfil (avatar).<br>- O usuário deve poder escrever um texto de "Biografia" ou "Sobre mim" (limite 1000 caracteres).<br>- O usuário deve poder definir se sua coleção (ver US20) é pública ou privada.<br>- As informações salvas (foto, biografia) devem ser exibidas na página de perfil público do usuário. |
| **Prioridade**             | Média                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Status**                 | Validada                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Rastreabilidade**        | [RF10](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf10)                                                                                                                                                                                                                                                                                                                                                       |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                                                                                                                                                                                               |

<div align="center"><strong>Tabela 23:</strong> História de Usuário – Personalização do Perfil Público</div>

**Fonte:** Thiago, 2025

#### [US23] - Adicionar Carta a Múltiplas Listas {#us23}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US23                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Tema**                   | Gerenciamento de Listas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Descrição**              | Eu, como Usuário Logado, desejo poder adicionar uma carta (encontrada na busca) a diferentes listas (Coleção, Deck, Lista de Desejos, Carrinho) para organizar minhas atividades.                                                                                                                                                                                                                                                                                                                                                                                 |
| **Critérios de Aceitação** | - Ao visualizar uma carta, deve haver botões ou um menu de "Adicionar a...".<br>- A opção "Adicionar ao Carrinho" deve direcionar para a seleção de uma oferta/vendedor daquela carta.<br>- A opção "Adicionar à Coleção" deve abrir o formulário simplificado de adição à coleção (conforme US20, mas talvez direto).<br>- A opção "Adicionar à Lista de Desejos" deve adicionar a carta-base à "Wishlist" do usuário.<br>- A opção "Adicionar ao Deck" deve permitir ao usuário selecionar um de seus decks existentes (ou criar um novo) para incluir a carta. |
| **Prioridade**             | Alta                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Status**                 | Validada                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Rastreabilidade**        | [RF35](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf35)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

<div align="center"><strong>Tabela 24:</strong> História de Usuário – Adicionar Carta a Múltiplas Listas</div>

**Fonte:** Thiago, 2025

#### [US24] - Acesso ao Canal de Direitos do Titular {#us24}

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                                                                                   |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US24                                                                                                                                                                                                                                                                                                                                            |
| **Tema**                   | Privacidade e Suporte (LGPD)                                                                                                                                                                                                                                                                                                                    |
| **Descrição**              | Eu, como Titular dos Dados (Usuário), desejo encontrar facilmente um canal de contato (e-mail ou link) para exercer meus direitos de privacidade (ex: solicitar meus dados ou exclusão).                                                                                                                                                        |
| **Critérios de Aceitação** | - O rodapé do site deve conter um link visível para a "Política de Privacidade".<br>- A página "Política de Privacidade" deve conter uma seção específica sobre "Direitos do Titular" (conforme LGPD/GDPR).<br>- Nessa seção, deve ser disponibilizado um e-mail de contato (ex: dpo@dominio.com) ou um link para um formulário de solicitação. |
| **Prioridade**             | Alta                                                                                                                                                                                                                                                                                                                                            |
| **Status**                 | Validada                                                                                                                                                                                                                                                                                                                                        |
| **Rastreabilidade**        | [RF16](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf16)                                                                                                                                                                                                                                                                             |
| **Validação**              | https://www.youtube.com/watch?v=ITKe7Txs100                                                                                                                                                                                                                                                                                                     |

<div align="center"><strong>Tabela 25:</strong> História de Usuário – Acesso ao Canal de Direitos do Titular</div>

**Fonte:** Thiago, 2025

## Referências

<a id="PRESSMAN"></a>

> **1. PRESSMAN, Roger S.** _Engenharia de Software: uma abordagem profissional_. Cap. 3

## Nível de Contribuição dos Integrantes

| Nome     | % de Contribuição |
| -------- | ----------------- |
| Samuel   |                   |
| Thiago   |                   |
| Angélica |                   |
| Marcelo  |                   |

## Histórico de versão

| Versão |    Data    | Descrição                                  |   Autor(es)    |    Revisor     |
| :----: | :--------: | :----------------------------------------- | :------------: | :------------: |
|  1.0   | 16/10/2025 | Criação inicial do documento               | Samuel, Thiago |       -        |
| 1.0.1  | 16/10/2025 | Adicionar histórias de usuário (US01–US06) |     Samuel     |     Thiago     |
|  1.1   | 18/10/2025 | Adicionar histórias de usuário (US07–US12) |    Angélica    | Samuel, Thiago |
|  1.2   | 18/10/2025 | Adicionar histórias de usuário (US13–US18) |    Marcelo     |     Raissa     |
|  1.3   | 18/10/2025 | Adicionar histórias de usuário (US19–US24) |     Thiago     |     Samuel     |
|  1.4   | 16/10/2025 | Adicionar as citações bibliográficas       |     Samuel     |     Thiago     |
