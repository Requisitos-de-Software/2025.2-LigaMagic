# Histórias de Usuário

## Descrição

Este artefato documenta as histórias de usuário desenvolvidas para o sistema, seguindo a metodologia ágil. As histórias são descritas na perspectiva do usuário final e incluem critérios de aceitação claros para orientar o desenvolvimento e validação das funcionalidades.
_(Pressman; Maxim, cap. 3)_.

## Objetivo

O objetivo deste artefato é definir os requisitos funcionais do sistema através de histórias de usuário que representem as necessidades e expectativas dos usuários.

## Metodologia

As histórias de usuário foram criadas seguindo o padrão:

**“Como [tipo de usuário], eu quero [funcionalidade] para que [benefício]”**,

em alinhamento com as práticas de levantamento de requisitos no desenvolvimento ágil, nas quais os usuários descrevem necessidades em forma de histórias que orientam a implementação incremental _(Pressman; Maxim, cap. 3)_.

Cada uma delas foi elaborada com critérios de aceitação claros, priorizadas com base no valor que trazem para o usuário e rastreáveis aos [requisitos elicitados](../../03_elicitacao/artefatos/requisitos_elicitados.md).

Para garantir que as histórias estejam completas e bem definidas, usamos uma [lista de verificação](../../06_verificacao/entrega4/verificacao_historias_de_usuario.md) durante todo o processo de elaboração.

A validação dessas histórias será feita por meio de revisões com usuários reais do sistema, garantindo que atendam às necessidades deles.

## Conteúdo

### Tabela de contribuição

| **História de Usuário** | **Desenvolvedor** |
| ----------------------- | ----------------- |
| US01 a US06             | Samuel Nogueira   |
| US07 a US012            | Angélica Campos   |
| US13 a US18             | Marcelo           |
| US19 a US24             | Thiago            |
| US25 a US30             | Raissa            |

<div align="center"><strong>Tabela 1:</strong> Distribuição das histórias de usuário</div>

**Fonte:** Samuel, 2025

---

### Modelo de História de Usuário

| **Item**                      | **Descrição**                                               |
| ----------------------------- | ----------------------------------------------------------- |
| USx (número de identificação) | USx                                                         |
| Tema                          | [Tema da história]                                          |
| Descrição                     | Eu, como [tipo de usuário], desejo [ação] para [benefício]. |
| Critérios de Aceitação        | - Critério 1 - Critério 2 - Critério 3                      |
| Prioridade                    | [Alta, Média ou Baixa]                                      |
| Status                        | [Validada / Não validada]                                   |
| Rastreabilidade               | [Código do requisito relacionado]                           |
| Validação                     | [Link para vídeo de validação, se houver]                   |

<div align="center"><strong>Tabela 2:</strong> Modelo de histórias de usuário</div>

**Fonte:** Samuel, 2025

---

### Histórias de Usuário

#### [US01] - Participar de Fóruns de Discussão {#us01}

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                        |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US01                                                                                                                                                                                                                                                                                                 |
| Tema                         | Participar de Fóruns de Discussão                                                                                                                                                                                                                                                                    |
| Descrição                    | Eu, como um jogador iniciante, desejo criar e responder tópicos em um fórum de discussão para poder tirar dúvidas e aprender com jogadores mais experientes.                                                                                                                                         |
| Critérios de Aceitação       | - O sistema deve me permitir visualizar uma lista de subfóruns. <br>- O sistema deve me permitir criar um novo tópico com título e mensagem em um subfórum. <br>- O sistema deve me permitir visualizar as respostas de um tópico. <br>- O sistema deve me permitir responder a um tópico existente. |
| Prioridade                   | -                                                                                                                                                                                                                                                                                                    |
| Status                       | Não validada                                                                                                                                                                                                                                                                                         |
| Rastreabilidade              | [RFNI02](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni02)                                                                                                                                                                                                                       |
| Validação                    | -                                                                                                                                                                                                                                                                                                    |

<div align="center"><strong>Tabela 3:</strong> História de Usuário – Participar de Fóruns de Discussão</div>

**Fonte:** Samuel, 2025

#### [US02] - Compartilhar Carta por Link {#us02}

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                 |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US02                                                                                                                                                                                                                                                                                          |
| Tema                         | Compartilhar Carta por Link                                                                                                                                                                                                                                                                   |
| Descrição                    | Eu, como um jogador, desejo compartilhar o link de uma carta específica para poder mostrar a um amigo ou pedir uma opinião de forma rápida e precisa.                                                                                                                                         |
| Critérios de Aceitação       | - O sistema deve me permitir buscar por uma carta pelo nome. <br>- Na tela de detalhes da carta, deve haver uma opção de "Compartilhar". <br>- Ao selecionar "Compartilhar", o sistema deve abrir o menu de compartilhamento nativo do meu celular com um link direto para a página da carta. |
| Prioridade                   | -                                                                                                                                                                                                                                                                                             |
| Status                       | Não validada                                                                                                                                                                                                                                                                                  |
| Rastreabilidade              | [RFNI06](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni06)                                                                                                                                                                                                                |
| Validação                    | -                                                                                                                                                                                                                                                                                             |

<div align="center"><strong>Tabela 4:</strong> História de Usuário – Compartilhar Carta por Link</div>

**Fonte:** Samuel, 2025

#### [US03] - Verificar Cadastro Duplicado {#us03}

| **Item**                     | **Descrição**                                                                                                                                                                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US03                                                                                                                                                                                                                                             |
| Tema                         | Verificar Cadastro Duplicado                                                                                                                                                                                                                     |
| Descrição                    | Eu, como um novo usuário, desejo ser informado se meu e-mail já está cadastrado ao tentar criar uma conta para evitar a criação de contas duplicadas e recuperar meu acesso, se necessário.                                                      |
| Critérios de Aceitação       | - Dado que eu preencha o formulário de cadastro com um e-mail que já existe no sistema, Quando eu tentar submeter o formulário, Então o sistema deve exibir a mensagem "Este e-mail já está em uso. Deseja fazer login ou recuperar sua senha?". |
| Prioridade                   | -                                                                                                                                                                                                                                                |
| Status                       | Não validada                                                                                                                                                                                                                                     |
| Rastreabilidade              | [RF2](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf2)                                                                                                                                                                                |
| Validação                    | -                                                                                                                                                                                                                                                |

<div align="center"><strong>Tabela 5:</strong> História de Usuário – Verificar Cadastro Duplicado</div>

**Fonte:** Samuel, 2025

#### [US04] - Pesquisar Cartas por Nome {#us04}

| **Item**                     | **Descrição**                                                                                                                                                                                                                 |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US04                                                                                                                                                                                                                          |
| Tema                         | Pesquisar Cartas por Nome                                                                                                                                                                                                     |
| Descrição                    | Eu, como um jogador, desejo pesquisar cartas pelo nome para encontrar rapidamente suas informações, edições disponíveis e preços de mercado.                                                                                  |
| Critérios de Aceitação       | - O sistema deve possuir um campo de busca de texto visível na tela principal ou na seção de cartas. <br>- Ao digitar o nome de uma carta e confirmar a busca, o sistema deve exibir uma lista de resultados correspondentes. |
| Prioridade                   | -                                                                                                                                                                                                                             |
| Status                       | Não validada                                                                                                                                                                                                                  |
| Rastreabilidade              | [RF20](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf20)                                                                                                                                                           |
| Validação                    | -                                                                                                                                                                                                                             |

<div align="center"><strong>Tabela 6:</strong> História de Usuário – Pesquisar Cartas por Nome</div>

**Fonte:** Samuel, 2025

#### [US05] - Filtrar Resultados de Busca de Cartas {#us05}

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                                                       |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US05                                                                                                                                                                                                                                                                                                                                |
| Tema                         | Filtrar Resultados de Busca de Cartas                                                                                                                                                                                                                                                                                               |
| Descrição                    | Eu, como um comprador, desejo filtrar os resultados da busca de cartas por preço, condição (ex: Nova, Usada) e idioma para encontrar ofertas que atendam exatamente às minhas necessidades e orçamento.                                                                                                                             |
| Critérios de Aceitação       | - Na tela de resultados da busca, deve haver uma opção para aplicar filtros. <br>- O sistema deve permitir que eu selecione um ou mais filtros de condição, idioma e defina uma faixa de preço. <br>- Ao aplicar os filtros, a lista de resultados deve ser atualizada para exibir apenas as cartas que correspondem aos critérios. |
| Prioridade                   | -                                                                                                                                                                                                                                                                                                                                   |
| Status                       | Não validada                                                                                                                                                                                                                                                                                                                        |
| Rastreabilidade              | [RF21](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf21)                                                                                                                                                                                                                                                                 |
| Validação                    | -                                                                                                                                                                                                                                                                                                                                   |

<div align="center"><strong>Tabela 7:</strong> História de Usuário – Filtrar Resultados de Busca de Cartas</div>

**Fonte:** Samuel, 2025

#### [US06] - Visualizar Informações Relevantes nos Resultados {#us06}

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                          |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US06                                                                                                                                                                                                                                                                                   |
| Tema                         | Visualizar Informações Relevantes nos Resultados                                                                                                                                                                                                                                       |
| Descrição                    | Eu, como um comprador, desejo ver o menor preço, a condição, o idioma e a reputação do vendedor diretamente na lista de resultados da pesquisa para poder comparar as opções disponíveis de forma eficiente, sem precisar clicar em cada item.                                         |
| Critérios de Aceitação       | - Cada item na lista de resultados da busca deve exibir o nome da carta, a imagem em miniatura, o menor preço disponível, a condição, o idioma e uma indicação da reputação do vendedor (ex: estrelas ou nota). <br>- As informações devem estar organizadas de forma clara e legível. |
| Prioridade                   | -                                                                                                                                                                                                                                                                                      |
| Status                       | Não validada                                                                                                                                                                                                                                                                           |
| Rastreabilidade              | [RF22](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf22)                                                                                                                                                                                                                    |
| Validação                    | -                                                                                                                                                                                                                                                                                      |

<div align="center"><strong>Tabela 8:</strong> História de Usuário – Visualizar Informações Relevantes nos Resultados</div>

**Fonte:** Samuel, 2025

#### [US07] - Lista de Desejos (Wishlist)

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

#### [US08] - Busca Rápida de Cartas

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

#### [US09] - Cadastro de Usuário

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

#### [US10] - Login e Autenticação

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

#### [US11] - Atualização de Dados do Usuário

| **Item**                   | **Descrição**                                                                                                                                                                                                                                                                  |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **USx**                    | **US11**                                                                                                                                                                                                                                                                       |
| **Tema**                   | Atualização de Dados do Usuário                                                                                                                                                                                                                                                |
| **Descrição**              | Eu, como usuário comprador desejo atualizar meus dados pessoais (como endereço, telefone e e-mail)para manter minhas informações corretas e facilitar futuras compras ou comunicações                                                                                          |
| **Critérios de Aceitação** | - O sistema deve permitir a edição de dados pessoais (nome, e-mail, telefone, endereço). <br> - As alterações devem ser salvas corretamente no perfil do usuário. <br> - Caso algum campo obrigatório não esteja preenchido, o sistema deve exibir uma mensagem de erro clara. |
| **Prioridade**             |                                                                                                                                                                                                                                                                                |
| **Status**                 | Não validada                                                                                                                                                                                                                                                                   |
| **Rastreabilidade**        | [RF19](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf19)                                                                                                                                                                                                            |
| **Validação**              |                                                                                                                                                                                                                                                                                |

<div align="center"><strong>Tabela 13:</strong> História de Usuário – Atualização de Dados do Usuário                  </div>

**Fonte:** Angélica, 2025

#### [US12] - Histórico de Compras

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

#### [US13] - Personalizar Página do Usuário

| **Item**                   | **Descrição**                                                                                                                                                                                                            |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **USx**                    | US13                                                                                                                                                                                                                     |
| **Tema**                   | Personalizar Página do Usuário                                                                                                                                                                                           |
| **Descrição**              | Eu, como usuário, desejo personalizar e manter minha página pessoal/profissional para exibir minhas informações e preferências dentro da plataforma.                                                                     |
| **Critérios de Aceitação** | - O sistema deve permitir que o usuário altere informações pessoais e profissionais. - O sistema deve permitir o upload de imagem de perfil. - O sistema deve permitir salvar e editar as informações da página pessoal. |
| **Prioridade**             | -                                                                                                                                                                                                                        |
| **Status**                 | Não validada                                                                                                                                                                                                             |
| **Rastreabilidade**        | [RFNI01](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni01)                                                                                                                                           |
| **Validação**              | -                                                                                                                                                                                                                        |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 15:</strong> História de Usuário – Filtragem de Cartas por Qualidade/Condição      </div>

#### [US14] - Filtragem de Cartas por Qualidade/Condição

| **Item**                   | **Descrição**                                                                                                                                                                                                                    |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US14                                                                                                                                                                                                                             |
| **Tema**                   | Filtragem de Cartas por Qualidade/Condição                                                                                                                                                                                       |
| **Descrição**              | Eu, como usuário, desejo filtrar cartas por qualidade e condição para encontrar produtos que atendam melhor às minhas preferências.                                                                                              |
| **Critérios de Aceitação** | - O sistema deve oferecer filtros por qualidade (nova, usada, etc.). <br> - O sistema deve oferecer filtros por condição (ótima, boa, regular). <br> - O sistema deve atualizar a lista de cartas conforme os filtros aplicados. |
| **Prioridade**             | -                                                                                                                                                                                                                                |
| **Status**                 | Não validada                                                                                                                                                                                                                     |
| **Rastreabilidade**        | [RFNI03](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni03)                                                                                                                                                   |
| **Validação**              | -                                                                                                                                                                                                                                |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 16:</strong> História de Usuário – Restrição de Produtos      </div>

#### [US15] - Restrição de Produtos

| **Item**                   | **Descrição**                                                                                                                                                                                   |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US15                                                                                                                                                                                            |
| **Tema**                   | Restrição de Produtos                                                                                                                                                                           |
| **Descrição**              | Eu, como administrador do sistema, desejo garantir que apenas produtos relacionados a Magic: The Gathering sejam cadastrados na plataforma, para manter a relevância e integridade do conteúdo. |
| **Critérios de Aceitação** | - O sistema deve bloquear o cadastro de produtos que não pertençam ao universo de Magic. <br> - O sistema deve validar o tipo de produto antes de permitir sua publicação.                      |
| **Prioridade**             | -                                                                                                                                                                                               |
| **Status**                 | Não validada                                                                                                                                                                                    |
| **Rastreabilidade**        | [RF04](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf04)                                                                                                                             |
| **Validação**              | -                                                                                                                                                                                               |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 17:</strong> História de Usuário – Visualização de Detalhes da Carta      </div>

#### [US16] - Visualização de Detalhes da Carta

| **Item**                   | **Descrição**                                                                                                                                                                                                          |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US16                                                                                                                                                                                                                   |
| **Tema**                   | Visualização de Detalhes da Carta                                                                                                                                                                                      |
| **Descrição**              | Eu, como usuário, desejo visualizar detalhes de uma carta ao clicar no resultado da pesquisa para conhecer mais sobre ela antes de comprar ou trocar.                                                                  |
| **Critérios de Aceitação** | - O sistema deve exibir informações completas da carta selecionada. <br> - O sistema deve apresentar uma interface clara e organizada para os detalhes. <br> - O sistema deve permitir retornar à lista de resultados. |
| **Prioridade**             | -                                                                                                                                                                                                                      |
| **Status**                 | Não validada                                                                                                                                                                                                           |
| **Rastreabilidade**        | [RF27](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf27)                                                                                                                                                    |
| **Validação**              | -                                                                                                                                                                                                                      |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 18:</strong> História de Usuário – Exibição de Informações Detalhadas da Carta     </div>

#### [US17] - Exibição de Informações Detalhadas da Carta

| **Item**                   | **Descrição**                                                                                                                                                                                                          |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **USx**                    | US17                                                                                                                                                                                                                   |
| **Tema**                   | Exibição de Informações Detalhadas da Carta                                                                                                                                                                            |
| **Descrição**              | Eu, como usuário, desejo visualizar informações detalhadas de cada carta, incluindo edição, idioma, condição e preço médio, para tomar decisões mais informadas.                                                       |
| **Critérios de Aceitação** | - O sistema deve mostrar a edição, idioma, condição e preço médio da carta. <br> - As informações devem estar visíveis na tela de detalhes. <br> - Os dados devem ser consistentes com o banco de dados da plataforma. |
| **Prioridade**             | -                                                                                                                                                                                                                      |
| **Status**                 | Não validada                                                                                                                                                                                                           |
| **Rastreabilidade**        | [RF30](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf30)                                                                                                                                                    |
| **Validação**              | -                                                                                                                                                                                                                      |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 19:</strong> História de Usuário – Buscar Decks Relacionados </div>

#### [US18] - Buscar Decks Relacionados

| **Item**                   | **Descrição**                                                                                                                                                                                                      |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **USx**                    | US18                                                                                                                                                                                                               |
| **Tema**                   | Buscar Decks Relacionados                                                                                                                                                                                          |
| **Descrição**              | Eu, como usuário, desejo buscar decks que utilizam a carta selecionada para entender como ela é usada em diferentes estratégias.                                                                                   |
| **Critérios de Aceitação** | - O sistema deve permitir buscar decks que incluam a carta selecionada. <br> - O sistema deve apresentar uma lista com os decks encontrados. <br> - O sistema deve permitir acessar detalhes de cada deck listado. |
| **Prioridade**             | -                                                                                                                                                                                                                  |
| **Status**                 | Não validada                                                                                                                                                                                                       |
| **Rastreabilidade**        | [RF32](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf32)                                                                                                                                                |
| **Validação**              | -                                                                                                                                                                                                                  |

**Fonte:** Marcelo, 2025

#### [US19] - Avaliação de Vendedor

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                                                    |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US19                                                                                                                                                                                                                                                                                                                             |
| Tema                         | Feedback e Reputação                                                                                                                                                                                                                                                                                                             |
| Descrição                    | Eu, como Comprador, desejo avaliar um vendedor após uma compra concluída para ajudar outros usuários a tomar decisões e fornecer feedback ao vendedor.                                                                                                                                                                           |
| Critérios de Aceitação       | - O usuário só pode avaliar um vendedor após um pedido ter o status "Entregue". <br>- O sistema deve permitir uma avaliação de 1 a 5 estrelas. <br>- O sistema deve permitir um campo de comentário opcional (limite 500 caracteres). <br>- A avaliação (nota e comentário) deve ser exibida publicamente no perfil do vendedor. |
| Prioridade                   | Alta                                                                                                                                                                                                                                                                                                                             |
| Status                       | Não validada                                                                                                                                                                                                                                                                                                                     |
| Rastreabilidade              | [RFNI04](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni04)                                                                                                                                                                                                                                                   |
| Validação                    | N/A                                                                                                                                                                                                                                                                                                                              |

<div align="center"><strong>Tabela 20:</strong> História de Usuário – Avaliação de Vendedor</div>

**Fonte:** Thiago, 2025

#### [US20] - Adicionar Carta à Coleção Pessoal

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US20                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Tema                         | Gerenciamento de Coleção                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Descrição                    | Eu, como Colecionador, desejo adicionar cartas à minha coleção pessoal para manter um inventário digital do que eu possuo.                                                                                                                                                                                                                                                                                                                                            |
| Critérios de Aceitação       | - O usuário deve ter uma seção "Minha Coleção" em seu perfil.<br>- Na "Minha Coleção", deve existir um botão "Adicionar Carta".<br>- O sistema deve fornecer uma busca (pelo nome da carta) para encontrar a carta no banco de dados global do sistema.<br>- Ao selecionar a carta, o usuário deve poder informar: Quantidade, Condição (Mint, Near Mint, Played, etc.) e Idioma.<br>- A carta adicionada (com seus detalhes) deve aparecer na lista "Minha Coleção". |
| Prioridade                   | Alta                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Status                       | Não validada                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Rastreabilidade              | [RFNI10](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni10)                                                                                                                                                                                                                                                                                                                                                                                        |
| Validação                    | N/A                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

<div align="center"><strong>Tabela 21:</strong> História de Usuário – Adicionar Carta à Coleção Pessoal</div>

**Fonte:** Thiago, 2025

#### [US21] - Registro de Conta de Usuário

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| USx(número de identificação) | US21                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Tema                         | Gerenciamento de Conta                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Descrição                    | Eu, como Visitante, desejo me registrar na plataforma fornecendo meus dados pessoais (Nome, E-mail, CPF, etc.) para criar uma conta e acessar as funcionalidades restritas.                                                                                                                                                                                                                                                                                                                                                                      |
| Critérios de Aceitação       | - O formulário de registro deve solicitar: Nome Completo, E-mail, CPF, Data de Nascimento e Senha.<br>- O sistema deve validar o formato do E-mail e a unicidade (não pode estar em uso).<br>- O sistema deve validar o formato do CPF (ex: 11 dígitos numéricos).<br>- Os campos de Endereço (CEP, Rua, etc.) e Telefone podem ser solicitados no primeiro acesso ao perfil, após o registro.<br>- (O RG não será obrigatório no registro inicial).<br>- Após o registro, o usuário deve ser autenticado ou direcionado para a página de login. |
| Prioridade                   | Alta                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Status                       | Não validada                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Rastreabilidade              | [RF12](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf12)                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Validação                    | N/A                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

<div align="center"><strong>Tabela 22:</strong> História de Usuário – Registro de Conta de Usuário</div>

**Fonte:** Thiago, 2025

#### [US22] - Personalização do Perfil Público

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                             |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US22                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Tema                         | Perfil de Usuário                                                                                                                                                                                                                                                                                                                                                                                                         |
| Descrição                    | Eu, como Usuário Cadastrado (Vendedor ou Colecionador), desejo personalizar minha página de perfil público com foto e descrição para me apresentar à comunidade.                                                                                                                                                                                                                                                          |
| Critérios de Aceitação       | - O usuário deve ter uma área "Editar Perfil" na sua conta.<br>- O usuário deve poder carregar uma foto de perfil (avatar).<br>- O usuário deve poder escrever um texto de "Biografia" ou "Sobre mim" (limite 1000 caracteres).<br>- O usuário deve poder definir se sua coleção (ver US20) é pública ou privada.<br>- As informações salvas (foto, biografia) devem ser exibidas na página de perfil público do usuário. |
| Prioridade                   | Média                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Status                       | Não validada                                                                                                                                                                                                                                                                                                                                                                                                              |
| Rastreabilidade              | [RF10](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf10)                                                                                                                                                                                                                                                                                                                                                       |
| Validação                    | N/A                                                                                                                                                                                                                                                                                                                                                                                                                       |

<div align="center"><strong>Tabela 23:</strong> História de Usuário – Personalização do Perfil Público</div>

**Fonte:** Thiago, 2025

#### [US23] - Adicionar Carta a Múltiplas Listas

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US23                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Tema                         | Gerenciamento de Listas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Descrição                    | Eu, como Usuário Logado, desejo poder adicionar uma carta (encontrada na busca) a diferentes listas (Coleção, Deck, Lista de Desejos, Carrinho) para organizar minhas atividades.                                                                                                                                                                                                                                                                                                                                                                                 |
| Critérios de Aceitação       | - Ao visualizar uma carta, deve haver botões ou um menu de "Adicionar a...".<br>- A opção "Adicionar ao Carrinho" deve direcionar para a seleção de uma oferta/vendedor daquela carta.<br>- A opção "Adicionar à Coleção" deve abrir o formulário simplificado de adição à coleção (conforme US20, mas talvez direto).<br>- A opção "Adicionar à Lista de Desejos" deve adicionar a carta-base à "Wishlist" do usuário.<br>- A opção "Adicionar ao Deck" deve permitir ao usuário selecionar um de seus decks existentes (ou criar um novo) para incluir a carta. |
| Prioridade                   | Alta                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Status                       | Não validada                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Rastreabilidade              | [RF35](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf35)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Validação                    | N/A                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |

<div align="center"><strong>Tabela 24:</strong> História de Usuário – Adicionar Carta a Múltiplas Listas</div>

**Fonte:** Thiago, 2025

#### [US24] - Acesso ao Canal de Direitos do Titular

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                                                                   |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| USx(número de identificação) | US24                                                                                                                                                                                                                                                                                                                                            |
| Tema                         | Privacidade e Suporte (LGPD)                                                                                                                                                                                                                                                                                                                    |
| Descrição                    | Eu, como Titular dos Dados (Usuário), desejo encontrar facilmente um canal de contato (e-mail ou link) para exercer meus direitos de privacidade (ex: solicitar meus dados ou exclusão).                                                                                                                                                        |
| Critérios de Aceitação       | - O rodapé do site deve conter um link visível para a "Política de Privacidade".<br>- A página "Política de Privacidade" deve conter uma seção específica sobre "Direitos do Titular" (conforme LGPD/GDPR).<br>- Nessa seção, deve ser disponibilizado um e-mail de contato (ex: dpo@dominio.com) ou um link para um formulário de solicitação. |
| Prioridade                   | Média                                                                                                                                                                                                                                                                                                                                           |
| Status                       | Não validada                                                                                                                                                                                                                                                                                                                                    |
| Rastreabilidade              | [RF16](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf16)                                                                                                                                                                                                                                                                             |
| Validação                    | N/A                                                                                                                                                                                                                                                                                                                                             |

<div align="center"><strong>Tabela 25:</strong> História de Usuário – Acesso ao Canal de Direitos do Titular</div>

**Fonte:** Thiago, 2025


<div align="center"><strong>Tabela 26:</strong> Permitir controle de cookies </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | US25                                                        |
| Tema                         | Controle de Configurações de Cookies                                         |
| Descrição                    | Eu, como usuário preocupado com privacidade, desejo poder configurar minhas preferências de cookies no sistema, para ter controle sobre quais tipos de cookies são aceitos e proteger minha privacidade durante a navegação. |
| Critérios de Aceitação       | - O sistema deve permitir que o usuário aceite todos os cookies com um clique. <br> - O sistema deve permitir que o usuário rejeite todos os cookies com um clique. <br> - O sistema deve oferecer opções avançadas para selecionar tipos específicos de cookies. <br> - O sistema deve salvar as preferências do usuário e não exibir o banner novamente para escolhas já feitas. <br> - O sistema deve permitir que o usuário altere suas configurações de cookies a qualquer momento através do perfil.          |
| Prioridade                   | Média                                    |
| Status                       | -                            |
| Rastreabilidade              | [RF18](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf18)                         |
| Validação                    | -                 |

**Fonte:** Raissa, 2025


<div align="center"><strong>Tabela 27:</strong> Visualizar decks </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | US26                                                         |
| Tema                         | Visualização de Decks Publicados     |
| Descrição                    | Eu, como jogador de Magic, desejo visualizar decks publicados por outros usuários, com a lista completa de cartas, para ter como referência e fazer nosas estratégias, aprender sobre combinações de cartas populares.  |
| Critérios de Aceitação       | - O sistema deve permitir filtrar decks por formato (Standard, Modern, Commander, etc.). <br> - Ao selecionar um deck, o sistema deve mostrar a lista completa de cartas organizadas por tipo (criaturas, feitiços, terrenos, etc.). <br> - O sistema deve exibir informações do deck: nome, descrição, criador, data de criação e formato. <br> - O sistema deve calcular e mostrar o custo médio total do deck baseado nos preços atuais das cartas. <br> - O sistema deve permitir copiar a lista de cartas do deck para minha coleção pessoal.             |
| Prioridade                | Alta                                     |
| Status                       | -                                 |
| Rastreabilidade              | [RF25](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf25)                         |
| Validação                    | -                  |

**Fonte:** Raissa, 2025

<div align="center"><strong>Tabela 28:</strong> Fórum </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | US27                                                          |
| Tema                         | Participação em Fórum de Discussão             |
| Descrição                    | Eu, como membro da comunidade Magic, desejo buscar tópicos, ler discussões, responder postagens e criar novos tópicos no fórum, para poder compartilhar conhecimento, tirar dúvidas e interagir com outros jogadores.|
| Critérios de Aceitação       | - O sistema deve exibir lista de tópicos ordenados por data de última resposta ou relevância <br> - O sistema deve permitir visualizar o conteúdo completo de um tópico com todas as respostas <br>  - O sistema deve permitir criar novo tópico com título, categoria e conteúdo <br>  - O sistema deve permitir responder a tópicos existentes com mensagens formatadas <br> - O sistema deve mostrar informações do autor e data de cada postagem <br>  - O sistema deve permitir marcar tópicos como favoritos e receber notificações de novas respostas              |
| Prioridade                   | Alta   |
| Status                       | -                   |
| Rastreabilidade              | [RF26](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf26)                          |
| Validação                    | -             |

**Fonte:** Raissa, 2025


<div align="center"><strong>Tabela 29:</strong> Reportar problemas </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | U28                                                         |
| Tema                         | Reportar problemas em cartas e anúncios                     |
| Descrição                    |  Eu, como usuário ativo da plataforma, desejo reportar problemas relacionados a cartas e anúncios, como informações incorretas, preços discrepantes ou anúncios suspeitos, para contribuir com a qualidade e confiabilidade do sistema para toda a comunidade. |
| Critérios de Aceitação       | - O sistema deve oferecer categorias pré-definidas de problemas (informação incorreta, preço errado, anúncio suspeito, imagem de baixa qualidade e afins) <br> - O sistema deve permitir que o usuário descreva detalhadamente o problema encontrado. <br> - O sistema deve permitir anexar fotos, prints ou imagens que comprovem o problema <br> - O sistema deve enviar confirmação do reporte registrado com número de protocolo <br> - O sistema deve notificar a equipe de moderação sobre novos reportes  <br>  - O sistema deve permitir acompanhar o status do reporte na área do usuário. <br>      |
| Prioridade                   | Média                  |
| Status                       | -                   |
| Rastreabilidade              | [RF37](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf37)                        |
| Validação                    | -                  |

**Fonte:** Raissa, 2025

<div align="center"><strong>Tabela 30:</strong> Os usuarios devem ser capazes de criar, salvar e gerenciar listas de decks </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | US29                                                        |
| Tema                         | Gerenciamento de Listas de Decks Pessoais                                      |
| Descrição                    | Eu, como jogador dedicado de Magic, desejo criar, salvar e gerenciar minhas próprias listas de decks, para poder organizar minhas estratégias, acompanhar evoluções e ter acesso rápido aos meus decks favoritos. |
| Critérios de Aceitação       | - O sistema deve permitir criar novo deck com nome, descrição, formato e lista de cartas. <br> - O sistema deve validar se o deck atende às regras do formato selecionado (número mínimo/máximo de cartas). <br> - O sistema deve permitir salvar múltiplos decks na coleção pessoal do usuário. <br> - O sistema deve permitir editar decks existentes (adicionar/remover cartas, alterar informações). <br> - O sistema deve permitir duplicar decks existentes para criar variações. <br> - O sistema deve permitir organizar decks em pastas ou categorias personalizadas. <br> - O sistema deve oferecer opção de tornar deck público ou mantê-lo privado. <br> - O sistema deve calcular automaticamente o custo total do deck baseado nos preços atuais. <br>           |
| Prioridade                   | Alta                                     |
| Status                       | Não Implementada                       |
| Rastreabilidade              | [RFNI09](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni09)                           |
| Validação                    |             |

**Fonte:** Raissa, 2025

<div align="center"><strong>Tabela 31:</strong> O sistema deve fornecer a funcionalidade "Comprar por lista" </div>

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| USx(número de identificação) | US30                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Tema                         | Compra por Lista de Cartas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Descrição                    | Eu, como comprador frequente, desejo utilizar a funcionalidade "Compra por Lista" para adicionar múltiplas cartas de uma vez ao carrinho, para poder agilizar minhas compras de decks completos ou listas específicas.                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Critérios de Aceitação       | -  O sistema deve permitir importar lista de cartas a partir de texto ou arquivo. <br> - O sistema deve identificar automaticamente cada carta da lista e suas quantidades. <br> - O sistema deve buscar os anúncios disponíveis para cada carta da lista. <br> - O sistema deve sugerir opções de compra consolidada com menor número de vendedores. <br> - O sistema deve calcular o custo total e frete consolidado. <br> - O sistema deve permitir ajustar quantidades e selecionar vendedores antes de adicionar ao carrinho. <br> - O sistema deve salvar listas de compra frequentes para reutilização. <br> - O sistema deve mostrar economia potencial em relação à compra individual. <br> |
| Prioridade                   | Média                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Status                       | Não Implementada                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Rastreabilidade              | [RFNI11](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni11)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Validação                    | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |

**Fonte:** Raissa, 2025

#### [US31] - Permitir que o usuário realize a compra de cartas cadastradas

<div align="center"><strong>Tabela 32:</strong> O sistema deve permitir que o usuário realize a compra de cartas cadastradas</div>

| **Item**               | **Descrição**                                                                                                                                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US31                   | Realizar compra de cartas                                                                                                                                                                                                  |
| Tema                   | Comércio e Transações de Cartas                                                                                                                                                                                            |
| Descrição              | Eu, como comprador, desejo realizar a compra de cartas cadastradas informando meus dados pessoais e endereço de entrega para finalizar a transação de forma segura e prática.                                              |
| Critérios de Aceitação | - O sistema deve permitir que o usuário adicione cartas ao carrinho.<br>- Deve ser possível inserir e confirmar dados pessoais e endereço de entrega.<br>- A compra só deve ser concluída após a confirmação do pagamento. |
| Prioridade             | Alta                                                                                                                                                                                                                       |
| Status                 | Não validada                                                                                                                                                                                                               |
| Rastreabilidade        | [RF23](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf23)                                                                                                                                                        |
| Validação              | -                                                                                                                                                                                                                          |

**Fonte:** Vera, 2025

####  [US32] – Visualizar gráfico de histórico de preços

<div align="center"><strong>Tabela 33:</strong> O sistema deve permitir que o usuário visualize o histórico de preços em formato gráfico</div>

| **Item**               | **Descrição**                                                                                                                                                                                                   |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US32                   | Visualizar histórico de preços em gráfico                                                                                                                                                                       |
| Tema                   | Relatórios e Análise de Mercado                                                                                                                                                                                 |
| Descrição              | Eu, como jogador, desejo acessar o histórico de preços de uma carta em formato gráfico para visualizar a variação de valores ao longo do tempo e identificar o melhor momento para comprar ou vender.           |
| Critérios de Aceitação | - O gráfico deve exibir a variação de preços ao longo do tempo.<br>- O usuário deve conseguir selecionar o período desejado (mês/ano).<br>- Os valores devem estar apresentados em reais (R$) no eixo vertical. |
| Prioridade             | Alta                                                                                                                                                                                                            |
| Status                 | Não validada                                                                                                                                                                                                    |
| Rastreabilidade        | [RF34](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf34)                                                                                                                                             |
| Validação              | -                                                                                                                                                                                                               |

**Fonte:** Vera, 2025

####  [US33] – Permitir visualizar preço médio de uma carta por edição

<div align="center"><strong>Tabela 34:</strong> O sistema deve permitir que o usuário visualize o preço médio de cartas por edição</div>

| **Item**               | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US33                   | Exibir preço médio e histórico comparativo por edição                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Tema                   | Relatórios e Análise de Mercado                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Descrição              | Eu, como jogador e colecionador, desejo **visualizar o preço médio e a variação histórica de uma carta em diferentes edições , para comparar tendências e identificar qual versão apresenta o melhor custo-benefício.                                                                                                                                                                                                                                                   |
| Critérios de Aceitação | - O sistema deve exibir um gráfico comparativo com o histórico de preços médios por edição.<br>- Deve permitir selecionar o tipo de preço a visualizar (menor, médio ou maior).<br>- O usuário deve poder definir um intervalo de tempo personalizado para análise.<br>- O gráfico deve apresentar legenda identificando cada edição e condição (ex: normal, foil, extended art, borderless).<br>- O sistema deve atualizar o gráfico dinamicamente ao aplicar filtros. |
| Prioridade             | Alta                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Status                 | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Rastreabilidade        | [RF33](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf33)                                                                                                                                                                                                                                                                                                                                                                                                     |
| Validação              | -                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

**Fonte:** Vera, 2025

#### [US34] – Permitir adicionar textos e imagens em anúncios

<div align="center"><strong>Tabela 35:</strong> O sistema deve permitir a inclusão de textos e fotos nos anúncios</div>

| **Item**               | **Descrição**                                                                                                                                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **US34**               | Incluir textos e fotos em anúncios                                                                                                                                                                                |
| Tema                   | Gestão de Anúncios                                                                                                                                                                                                |
| Descrição              | Eu, como vendedor, desejo incluir textos, descrições e fotos detalhadas nos meus anúncios para atrair compradores e fornecer informações completas sobre a carta ofertada.                                        |
| Critérios de Aceitação | - O sistema deve permitir inserir uma descrição textual do produto.<br>- Deve permitir adicionar ao menos uma imagem do item.<br>- As informações inseridas devem ser exibidas corretamente no anúncio publicado. |
| Prioridade             | Alta                                                                                                                                                                                                              |
| Status                 | Não validada                                                                                                                                                                                                      |
| Rastreabilidade        | [RF06](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf06)                                                                                                                                               |
| Validação              | -                                                                                                                                                                                                                 |

**Fonte:** Vera, 2025

#### [US35] – Permitir reportar problemas relacionados a cartas

<div align="center"><strong>Tabela 36:</strong> O sistema deve permitir que o usuário reporte problemas relacionados à carta</div> 

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                          |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| USx(número de identificação) | US35                                                                                                                                                                                                                                                                   |
| Tema                         | Suporte e Qualidade de Dados                                                                                                                                                                                                                                           |
| Descrição                    | Eu, como usuário cadastrado, desejo reportar problemas relacionados a uma carta (como erros de informação ou anúncios suspeitos) para garantir que os dados estejam corretos e a comunidade seja protegida de conteúdo inadequado.                                     |
| Critérios de Aceitação       | - O sistema deve permitir que o usuário selecione a carta e descreva o problema.<br>- O relatório deve ser enviado para análise e armazenado no sistema.<br>- O usuário deve receber uma confirmação de envio e, opcionalmente, acompanhamento do status do relatório. |
| Prioridade                   | Alta                                                                                                                                                                                                                                                                   |
| Status                       | -                                                                                                                                                                                                                                                                      |
| Rastreabilidade              | [RFNI07](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni07)                                                                                                                                                                                         |
| Validação                    |                                                                                                                                                                                                                                                                        |


####  [US36] – Definir alerta de preço para carta

<div align="center"><strong>Tabela 37:</strong> O sistema deve permitir que o usuário defina um alerta de preço para uma carta específica</div>

| **Item**                     | **Descrição**                                                                                                                                                                                                                                                                                                  |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| USx(número de identificação) | US36                                                                                                                                                                                                                                                                                                           |
| Tema**                       | Alertas e Notificações                                                                                                                                                                                                                                                                                         |
| Descrição                    | Eu, como usuário interessado em monitorar preços de cartas, desejo definir um alerta de preço para uma carta específica para ser notificado quando o valor atingir ou ficar abaixo do limite que determinei**.                                                                                                 |
| Critérios de Aceitação       | - O sistema deve permitir ao usuário definir um preço-alvo para uma carta específica.<br>- Quando o preço da carta atingir ou ficar abaixo do valor definido, o sistema deve notificar o usuário (por e-mail ou notificação interna).<br>- O usuário deve poder editar ou remover o alerta a qualquer momento. |
| Prioridade                   | Alta                                                                                                                                                                                                                                                                                                           |
| Status                       | Validada                                                                                                                                                                                                                                                                                                       |
| Rastreabilidade              | [RFNI05](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni05)                                                                                                                                                                                                                                 |
| Validação                    |                                                                                                                                                                                                                                                                                                                |

####  [US37] – Verificação de Dados Cadastrados {#us37}

| **Item**                      | **Descrição**                                               |
| ----------------------------- | ----------------------------------------------------------- |
| USx  | US37                                                        |
| Tema                          | Privacidade e Conformidade                                        |
| Descrição                     | Eu, como um usuário do sistema, desejo que as informações inseridas durante o cadastro sejam verificadas automaticamente para garantir que os dados sejam autênticos e válidos, evitando erros e fraudes. |
| Critérios de Aceitação        | <br>- O sistema deve validar os campos obrigatórios durante o cadastro.<br>- O sistema deve identificar e rejeitar informações inválidas (ex: CPF inexistente, e-mail incorreto).<br>- O sistema deve exibir mensagens claras informando o motivo da rejeição dos dados.<br>- O sistema deve impedir o cadastro até que todos os dados sejam válidos.                    |
| Prioridade                    | -                                     |
| Status                        | Não validada                                   |
| Rastreabilidade               | [RF05](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf01---rf19-requisitos-da-análise-de-documentos-rf01---rf19-requisitos-da-analise-de-documentos)                          |
| Validação                     |-                  |

<div align="center"><strong>Tabela 38:</strong> Verificação de Dados Cadastrados</div>

**Fonte:** Guilherme, 2025

####  [US38] – Troca de Mensagens Privadas {#us38}

| **Item**                      | **Descrição**                                               |
| ----------------------------- | ----------------------------------------------------------- |
| USx  | US38                                                         |
| Tema                          | Comunicação e Suporte                                        |
| Descrição                     | Eu, como um usuário do sistema, desejo enviar e receber mensagens privadas com outros usuários para poder me comunicar de forma direta e segura.|
| Critérios de Aceitação        | <br>- O sistema deve permitir o envio e recebimento de mensagens privadas entre dois usuários.<br>- As mensagens devem ser armazenadas de forma segura, garantindo a privacidade dos usuários.<br>- O sistema deve notificar o usuário ao receber uma nova mensagem.<br>- O sistema deve exibir o histórico de mensagens trocadas.                    |
| Prioridade                    | -                                     |
| Status                        | Não validada                                   |
| Rastreabilidade               | [RF09](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf01---rf19-requisitos-da-análise-de-documentos-rf01---rf19-requisitos-da-analise-de-documentos)                           |
| Validação                     | -                 |

<div align="center"><strong>Tabela 39:</strong> Troca de Mensagens Privadas </div>

**Fonte:** Guilherme, 2025

####  [US39] – Verificação de Dados Cadastrados {#us39}

| **Item**                      | **Descrição**                                               |
| ----------------------------- | ----------------------------------------------------------- |
| USx | US39                                                         |
| Tema                          | Privacidade e Conformidade                                        |
| Descrição                     | Eu, como um usuário do sistema, desejo solicitar o acesso, a correção, a exclusão ou a anonimização dos meus dados pessoais para garantir meus direitos de privacidade e conformidade com a Lei Geral de Proteção de Dados (LGPD). |
| Critérios de Aceitação        | <br>- O sistema deve permitir que o usuário visualize todas as informações pessoais armazenadas.<br>- O sistema deve permitir que o usuário solicite a correção de dados incorretos.<br>- O sistema deve permitir que o usuário solicite a exclusão ou anonimização de seus dados pessoais.<br>- O sistema deve confirmar a execução da solicitação ao usuário.                     |
| Prioridade                    | -                                    |
| Status                        | Não validada                                   |
| Rastreabilidade               | [RF15](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf01---rf19-requisitos-da-análise-de-documentos-rf01---rf19-requisitos-da-analise-de-documentos)                             |
| Validação                     | -                  |

<div align="center"><strong>Tabela 40:</strong> Verificação de Dados Cadastrados</div>

**Fonte:** Guilherme, 2025

####  [US40] – Utilizar Cookies para Personalização {#us40}

| **Item**                      | **Descrição**                                               |
| ----------------------------- | ----------------------------------------------------------- |
| USx | US40                                                         |
| Tema                          | Privacidade e Configurações                                        |
| Descrição                     | Eu, como um usuário do sistema, desejo que sejam utilizados cookies para facilitar meu login e personalizar minha experiência de navegação, tornando o uso da plataforma mais prático e adaptado às minhas preferências.|
| Critérios de Aceitação        | <br>- O sistema deve utilizar cookies para manter o usuário autenticado entre sessões.<br>- O sistema deve permitir a personalização de conteúdo com base nas preferências do usuário.<br>- O sistema deve solicitar consentimento do usuário para o uso de cookies.<br>- O sistema deve permitir a exclusão dos cookies a qualquer momento.                     |
| Prioridade                    | -                                    |
| Status                        | Não validada                                   |
| Rastreabilidade               | [RF17](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf01---rf19-requisitos-da-análise-de-documentos-rf01---rf19-requisitos-da-analise-de-documentos)                           |
| Validação                     |               |

<div align="center"><strong>Tabela 41:</strong> Utilizar Cookies para Personalização </div>

**Fonte:** Guilherme, 2025

####  [US41] – Utilização de Dados para Finalidades Específicas {#us41}

| **Item**                      | **Descrição**                                               |
| ----------------------------- | ----------------------------------------------------------- |
| USx | US41                                                         |
| Tema                          |  Privacidade e Conformidade                |
| Descrição                     | Eu, como um usuário do sistema, desejo que meus dados pessoais sejam utilizados apenas para finalidades específicas, como identificação, contato, gestão contratual, melhoria de serviços e envio de comunicações, para garantir transparência e segurança no tratamento das minhas informações.|
| Critérios de Aceitação        |    <br>- O sistema deve utilizar os dados pessoais apenas para as finalidades descritas.<br>- O sistema deve informar ao usuário de forma clara as finalidades do uso dos dados.<br>- O sistema deve permitir que o usuário gerencie suas preferências de uso de dados.<br>- O sistema deve registrar o consentimento do usuário antes de qualquer uso adicional dos dados.                 |
| Prioridade                    | -                                   |
| Status                        | Não validada                                   |
| Rastreabilidade               |  [RF13](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf01---rf19-requisitos-da-análise-de-documentos-rf01---rf19-requisitos-da-analise-de-documentos)                          |
| Validação                     | -                   |

<div align="center"><strong>Tabela 42:</strong> Utilização de Dados para Finalidades Específicas</div>

**Fonte:** Guilherme, 2025

####  [US42] – Módulo de Leilões {#us42}

| **Item**                      | **Descrição**                                               |
| ----------------------------- | ----------------------------------------------------------- |
| USx | US42                                                         |
| Tema                          | Módulo de Leilões                                          |
| Descrição                     | Eu, como um usuário do sistema, desejo acessar um módulo completo de leilões para poder anunciar, participar e acompanhar disputas por produtos ou serviços em tempo real. |
| Critérios de Aceitação        | <br>- O sistema deve permitir a criação de leilões com título, descrição e valor inicial.<br>- O sistema deve permitir que outros usuários façam lances em tempo real.<br>- O sistema deve atualizar automaticamente o valor mais alto do lance.<br>- O sistema deve encerrar o leilão quando o tempo limite for atingido e registrar o vencedor.                    |
| Prioridade                    | -                                     |
| Status                        | Não validada                                   |
| Rastreabilidade               | [RFNI08](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#requisitos-funcionais-não-implementados)                           |
| Validação                     | -                  |

<div align="center"><strong>Tabela 43:</strong> Módulo de Leilões</div>

**Fonte:** Guilherme, 2025

## Referências

> **PRESSMAN, Roger S.** _Engenharia de Software: uma abordagem profissional_. Cap. 3

## Nível de Contribuição dos Integrantes

| Nome     | % de Contribuição |
| -------- | ----------------- |
| Samuel   |                   |
| Thiago   |                   |
| Angélica |                   |
| Marcelo  |                   |
| Raissa   |     14,28%        |
|Vera      |                   |
|Guilherme |                   |



## Histórico de versão

| Versão |    Data    | Descrição                                  |   Autor(es)    |    Revisor     |
|:------:|:----------:|:-------------------------------------------|:--------------:|:--------------:|
|  1.0   | 16/10/2025 | Criação inicial do documento               | Samuel, Thiago |       -        |
| 1.0.1  | 16/10/2025 | Adicionar histórias de usuário (US01–US06) |     Samuel     |     Thiago     |
|  1.1   | 18/10/2025 | Adicionar histórias de usuário (US07–US12) |    Angélica    | Samuel, Thiago |
|  1.2   | 18/10/2025 | Adicionar histórias de usuário (US13–US18) |    Marcelo     |     Raissa     |
|  1.3   | 18/10/2025 | Adicionar histórias de usuário (US19–US24) |     Thiago     |     Samuel     |
|  1.4   | 16/10/2025 | Adicionar as citações bibliográficas       |     Samuel     |     Thiago     |
|  1.5   | 19/10/2025 | adicionar histórias de usuário (US25–US30) |     Raissa     |       -        |
|  1.6   | 19/10/2025 | adicionar histórias de usuário (US31–US36) |      Vera      |   Guilherme    |
|  1.7   | 19/10/2025 | adicionar histórias de usuário (US37–US42) |      Guilherme     |   Vera   |
