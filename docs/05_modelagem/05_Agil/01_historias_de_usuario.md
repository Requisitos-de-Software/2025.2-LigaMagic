# Histórias de Usuário

## Descrição

Este artefato documenta as histórias de usuário desenvolvidas para o sistema, seguindo a metodologia ágil. As histórias são descritas na perspectiva do usuário final e incluem critérios de aceitação claros para orientar o desenvolvimento e validação das funcionalidades.

## Objetivo

O objetivo deste artefato é definir os requisitos funcionais do sistema através de histórias de usuário que representem as necessidades e expectativas dos usuários.

## Metodologia

As histórias de usuário foram criadas seguindo o padrão: "Como [tipo de usuário], eu quero [funcionalidade] para que [benefício]". Cada uma delas foi elaborada com critérios de aceitação claros, priorizadas com base no valor que trazem para o usuário e rastreáveis aos [requisitos elicitados](../../03_elicitacao/artefatos/requisitos_elicitados.md). Para garantir que as histórias estejam completas e bem feitas, usamos uma [lista de verificação](../../06_verificacao/entrega4/verificacao_historias_de_usuario.md) durante todo o processo de elaboração das histórias de usuário. A validação dessas histórias será feita por meio de revisões com usuários reais do sistema, garantindo que atendam às necessidades deles.

## Conteúdo

### Equipe e Distribuição das Histórias

| **História de Usuario** | **Desenvolvedor** |
| ----------------------- | ----------------- |
| US01 a US06             | Samuel Nogueira   |
| US07 a US012            | Angélica Campos   |
| US19 a US024            | Raissa Andrade   |

---

### Modelo de História de Usuário

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | USx                                                         |
| Tema                         | [Tema da história]                                          |
| Descrição                    | Eu, como [tipo de usuário], desejo [ação] para [benefício]. |
| Critérios de Aceitação       | - Critério 1 <br>- Critério 2 <br>- Critério 3              |
| Prioridade                   | [Alta, Média ou Baixa]                                      |
| Status                       | [Validada / Não validada]                                   |
| Rastreabilidade              | [Código do requisito relacionado]                           |
| Validação                    | [Link para vídeo de validação, se houver]                   |

---

### Histórias de Usuário

A seguir, apresentamos as histórias de usuário que descrevem as funcionalidades do sistema, elaboradas a partir da perspectiva do usuário e validadas de acordo com a [lista de verificação](../../06_verificacao/entrega4/verificacao_historias_de_usuario.md). Cada história detalha o resultado esperado, as características, as funcionalidade desejada e a prioridade de negócio definida pelo usuário.

#### [US01] - Participar de Fóruns de Discussão

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

<div align="center"><strong>Tabela 1:</strong> História de Usuário – Participar de Fóruns de Discussão</div>

**Fonte:** Samuel, 2025

#### [US02] - Compartilhar Carta por Link

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

<div align="center"><strong>Tabela 2:</strong> História de Usuário – Compartilhar Carta por Link</div>

**Fonte:** Samuel, 2025

#### [US03] - Verificar Cadastro Duplicado

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

<div align="center"><strong>Tabela 3:</strong> História de Usuário – Verificar Cadastro Duplicado</div>

**Fonte:** Samuel, 2025

#### [US04] - Pesquisar Cartas por Nome

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

<div align="center"><strong>Tabela 4:</strong> História de Usuário – Pesquisar Cartas por Nome</div>

**Fonte:** Samuel, 2025

#### [US05] - Filtrar Resultados de Busca de Cartas

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

<div align="center"><strong>Tabela 5:</strong> História de Usuário – Filtrar Resultados de Busca de Cartas</div>

**Fonte:** Samuel, 2025

#### [US06] - Visualizar Informações Relevantes nos Resultados

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

<div align="center"><strong>Tabela 6:</strong> História de Usuário – Visualizar Informações Relevantes nos Resultados</div>

**Fonte:** Samuel, 2025

#### US07 - Lista de Desejos (Wishlist)                      
| **Item**                   | **Descrição**|
| -------------------------- | ---------------------------------------------------------|
| **USx**                    | **US07**|
| **Tema**                   | Lista de Desejos (Wishlist)|
| **Descrição**              | Eu, como usuário comprador**, desejo salvar cartas em uma lista de desejos (wishlist) para poder comprá-las futuramente ou acompanhar mudanças de preço.|
| **Critérios de Aceitação** | - O sistema deve permitir adicionar uma carta à lista de desejos a partir da página de resultados ou detalhes da carta. <br> - O usuário deve poder visualizar todas as cartas salvas em uma seção dedicada (“Minha Wishlist”). <br> - O usuário deve conseguir remover cartas da lista de desejos.  |
| **Prioridade**             ||
| **Status**                 ||
| **Rastreabilidade**        | [RFNI14](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni14)|
| **Validação**              ||

<div align="center"><strong>Tabela 7:</strong> História de Usuário –  Lista de Desejos (Wishlist)                          </div>

**Fonte:** Angélica, 2025

#### US08 - Busca Rápida de Cartas                          
| **Item**                   | **Descrição**|
| -------------------------- | ---------------------------------------------- |
| **USx**                    | **US08**|
| **Tema**                   | Busca Rápida de Cartas|
| **Descrição**              | Eu, como usuário comprador, desejo realizar buscas por cartas específicas de forma eficiente e intuitiva, para encontrar rapidamente as cartas que desejo adquirir.|
| **Critérios de Aceitação** | - O sistema deve permitir a busca por nome, tipo ou categoria da carta. <br> - Os resultados devem ser exibidos de forma clara e organizada.<br> - A busca deve funcionar mesmo com pequenas variações de digitação (ex: acentos ou maiúsculas/minúsculas). |
| **Prioridade**             | |
| **Status**                 | |
| **Rastreabilidade**        | [RFNI15](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni15)|
| **Validação**              ||

<div align="center"><strong>Tabela 8:</strong> História de Usuário –  Busca Rápida de Cartas                            </div>


**Fonte:** Angélica, 2025

#### US09 - Cadastro de Usuário

| **Item**                   | **Descrição**|
| -------------------------- | -------------------------------------- |
| **USx**                    | **US09**|
| **Tema**                   | Cadastro de usuário|
| **Descrição**              | Eu, como usuário comprador desejo realizar meu cadastro na plataforma para acessar os recursos do sistema e salvar minhas informações pessoais de forma segura                     |
| **Critérios de Aceitação** | - O sistema deve permitir o cadastro com nome, e-mail e senha. <br> - O sistema deve validar se o e-mail já está cadastrado. <br> - O usuário deve receber confirmação de cadastro bem-sucedido. |
| **Prioridade**             ||
| **Status**                 ||
| **Rastreabilidade**        |[RF1](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf1)|
| **Validação**              | —|
<div align="center"><strong>Tabela 9:</strong> História de Usuário – Cadastro de usuário                          </div>

**Fonte:** Angélica, 2025

#### US10 - Login e Autenticação
| **Item**                   | **Descrição**|
| -------------------------- | -------------------------------|
| **USx**                    | **US10**|
| **Tema**                   | Login de usuário|
| **Descrição**              | Eu, como usuário comprador desejo acessar minha conta usando e-mail e senha para visualizar minhas informações e histórico de atividades                                                             |
| **Critérios de Aceitação** | - O sistema deve validar e autenticar o login do usuário. <br> - Em caso de erro, deve exibir mensagem clara de credenciais incorretas. <br> - O login deve redirecionar o usuário para a tela inicial do sistema. |
| **Prioridade**             ||
| **Status**                 ||
| **Rastreabilidade**        | [RF3](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf3)|
| **Validação**              | —|


<div align="center"><strong>Tabela 10:</strong> História de Usuário – Login e Autenticação                      </div>

**Fonte:** Angélica, 2025


#### US11 - Atualização de Dados do Usuário
| **Item**                   | **Descrição**|
| -------------------------- | ------------------------------------ |
| **USx**                    | **US11**|
| **Tema**                   | Atualização de Dados do Usuário|
| **Descrição**              | Eu, como usuário comprador desejo atualizar meus dados pessoais (como endereço, telefone e e-mail)para manter minhas informações corretas e facilitar futuras compras ou comunicações
| **Critérios de Aceitação** | - O sistema deve permitir a edição de dados pessoais (nome, e-mail, telefone, endereço). <br> - As alterações devem ser salvas corretamente no perfil do usuário. <br>  - Caso algum campo obrigatório não esteja preenchido, o sistema deve exibir uma mensagem de erro clara. |
| **Prioridade**             ||
| **Status**                 | Não validada|
| **Rastreabilidade**        | [RF19](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf19)|
| **Validação**              ||

<div align="center"><strong>Tabela 11:</strong> História de Usuário – Atualização de Dados do Usuário                  </div>

**Fonte:** Angélica, 2025

#### US12 - Histórico de Compras 
| **Item**| **Descrição**|
| ------- | -------------|
| **USx**                    | **US12**|
| **Tema**                   | Histórico de Compras|
| **Descrição**              | Eu, como usuário comprador desejo acessar meu histórico de compras com informações detalhadas para consultar produtos adquiridos, datas e valores pagos
| **Critérios de Aceitação** | - O sistema deve exibir uma lista com todas as compras realizadas pelo usuário. <br> - Cada item do histórico deve mostrar a data da compra, nome do produto, quantidade e valor pago. <br> - O usuário deve conseguir visualizar detalhes de cada compra ao clicar em um item da lista. |
| **Prioridade**             | |
| **Status**                 |   |
| **Rastreabilidade**        | [RF24](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf24)|
| **Validação**              | |


<div align="center"><strong>Tabela 12:</strong> História de Usuário – Histórico de Compras      </div>

**Fonte:** Angélica, 2025

<div align="center"><strong>Tabela 13:</strong> História de Usuário – Personalizar Página do Usuário      </div>

#### US13 - Personalizar Página do Usuário

| **Item** | **Descrição** |
|-----------|---------------|
| **USx** | US13 |
| **Tema** | Personalizar Página do Usuário |
| **Descrição** | Eu, como usuário, desejo personalizar e manter minha página pessoal/profissional para exibir minhas informações e preferências dentro da plataforma. |
| **Critérios de Aceitação** | - O sistema deve permitir que o usuário altere informações pessoais e profissionais.  - O sistema deve permitir o upload de imagem de perfil.  - O sistema deve permitir salvar e editar as informações da página pessoal. |
| **Prioridade** | - |
| **Status** | Não validada |
| **Rastreabilidade** | [RFNI01](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni01) |
| **Validação** | - |

**Fonte:** Marcelo, 2025
<div align="center"><strong>Tabela 14:</strong> História de Usuário – Filtragem de Cartas por Qualidade/Condição      </div>

####  US14 - Filtragem de Cartas por Qualidade/Condição

| **Item** | **Descrição** |
|-----------|---------------|
| **USx** | US14 |
| **Tema** | Filtragem de Cartas por Qualidade/Condição |
| **Descrição** | Eu, como usuário, desejo filtrar cartas por qualidade e condição para encontrar produtos que atendam melhor às minhas preferências. |
| **Critérios de Aceitação** | - O sistema deve oferecer filtros por qualidade (nova, usada, etc.). <br> - O sistema deve oferecer filtros por condição (ótima, boa, regular). <br> - O sistema deve atualizar a lista de cartas conforme os filtros aplicados. |
| **Prioridade** | - |
| **Status** | Não validada |
| **Rastreabilidade** | [RFNI03](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni03) |
| **Validação** | - |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 15:</strong> História de Usuário – Restrição de Produtos      </div>

####  US15 - Restrição de Produtos

| **Item** | **Descrição** |
|-----------|---------------|
| **USx** | US15 |
| **Tema** | Restrição de Produtos |
| **Descrição** | Eu, como administrador do sistema, desejo garantir que apenas produtos relacionados a Magic: The Gathering sejam cadastrados na plataforma, para manter a relevância e integridade do conteúdo. |
| **Critérios de Aceitação** | - O sistema deve bloquear o cadastro de produtos que não pertençam ao universo de Magic. <br> - O sistema deve validar o tipo de produto antes de permitir sua publicação. |
| **Prioridade** | - |
| **Status** | Não validada |
| **Rastreabilidade** | [RF04](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf04) |
| **Validação** | - |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 16:</strong> História de Usuário – Visualização de Detalhes da Carta      </div>

####  US16 - Visualização de Detalhes da Carta

| **Item** | **Descrição** |
|-----------|---------------|
| **USx** | US16 |
| **Tema** | Visualização de Detalhes da Carta |
| **Descrição** | Eu, como usuário, desejo visualizar detalhes de uma carta ao clicar no resultado da pesquisa para conhecer mais sobre ela antes de comprar ou trocar. |
| **Critérios de Aceitação** | - O sistema deve exibir informações completas da carta selecionada. <br> - O sistema deve apresentar uma interface clara e organizada para os detalhes. <br> - O sistema deve permitir retornar à lista de resultados. |
| **Prioridade** | - |
| **Status** | Não validada |
| **Rastreabilidade** | [RF27](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf27) |
| **Validação** | - |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 17:</strong> História de Usuário – Exibição de Informações Detalhadas da Carta     </div>

####  US17 - Exibição de Informações Detalhadas da Carta

| **Item** | **Descrição** |
|-----------|---------------|
| **USx** | US17 |
| **Tema** | Exibição de Informações Detalhadas da Carta |
| **Descrição** | Eu, como usuário, desejo visualizar informações detalhadas de cada carta, incluindo edição, idioma, condição e preço médio, para tomar decisões mais informadas. |
| **Critérios de Aceitação** | - O sistema deve mostrar a edição, idioma, condição e preço médio da carta. <br> - As informações devem estar visíveis na tela de detalhes. <br> - Os dados devem ser consistentes com o banco de dados da plataforma. |
| **Prioridade** | - |
| **Status** | Não validada |
| **Rastreabilidade** | [RF30](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf30) |
| **Validação** | - |

**Fonte:** Marcelo, 2025

<div align="center"><strong>Tabela 18:</strong> História de Usuário – Buscar Decks Relacionados </div>

####  US18 - Buscar Decks Relacionados

| **Item** | **Descrição** |
|-----------|---------------|
| **USx** | US18 |
| **Tema** | Buscar Decks Relacionados |
| **Descrição** | Eu, como usuário, desejo buscar decks que utilizam a carta selecionada para entender como ela é usada em diferentes estratégias. |
| **Critérios de Aceitação** | - O sistema deve permitir buscar decks que incluam a carta selecionada. <br> - O sistema deve apresentar uma lista com os decks encontrados. <br> - O sistema deve permitir acessar detalhes de cada deck listado. |
| **Prioridade** | - |
| **Status** | Não validada |
| **Rastreabilidade** | [RF32](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf32) |
| **Validação** | - |

**Fonte:** Marcelo, 2025



<div align="center"><strong>Tabela 19:</strong> Permitir controle de cookies </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | US19                                                         |
| Tema                         | Controle de Configurações de Cookies                                         |
| Descrição                    | Eu, como usuário preocupado com privacidade, desejo poder configurar minhas preferências de cookies no sistema, para ter controle sobre quais tipos de cookies são aceitos e proteger minha privacidade durante a navegação. |
| Critérios de Aceitação       | - O sistema deve permitir que o usuário aceite todos os cookies com um clique. <br> - O sistema deve permitir que o usuário rejeite todos os cookies com um clique. <br> - O sistema deve oferecer opções avançadas para selecionar tipos específicos de cookies. <br> - O sistema deve salvar as preferências do usuário e não exibir o banner novamente para escolhas já feitas. <br> - O sistema deve permitir que o usuário altere suas configurações de cookies a qualquer momento através do perfil.          |
| Prioridade                   | Média                                    |
| Status                       | -                            |
| Rastreabilidade              | [RF18](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf18)                         |
| Validação                    | -                 |

**Fonte:** Raissa, 2025


<div align="center"><strong>Tabela 20:</strong> Visualizar decks </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | US20                                                         |
| Tema                         | Visualização de Decks Publicados     |
| Descrição                    | Eu, como jogador de Magic, desejo visualizar decks publicados por outros usuários, com a lista completa de cartas, para ter como referência e fazer nosas estratégias, aprender sobre combinações de cartas populares.  |
| Critérios de Aceitação       | - O sistema deve permitir filtrar decks por formato (Standard, Modern, Commander, etc.). <br> - Ao selecionar um deck, o sistema deve mostrar a lista completa de cartas organizadas por tipo (criaturas, feitiços, terrenos, etc.). <br> - O sistema deve exibir informações do deck: nome, descrição, criador, data de criação e formato. <br> - O sistema deve calcular e mostrar o custo médio total do deck baseado nos preços atuais das cartas. <br> - O sistema deve permitir copiar a lista de cartas do deck para minha coleção pessoal.             |
| Prioridade                | Alta                                     |
| Status                       | -                                 |
| Rastreabilidade              | [RF25](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf25)                         |
| Validação                    | -                  |

**Fonte:** Raissa, 2025

<div align="center"><strong>Tabela 21:</strong> Fórum </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | US21                                                          |
| Tema                         | Participação em Fórum de Discussão             |
| Descrição                    | Eu, como membro da comunidade Magic, desejo buscar tópicos, ler discussões, responder postagens e criar novos tópicos no fórum, para poder compartilhar conhecimento, tirar dúvidas e interagir com outros jogadores.|
| Critérios de Aceitação       | - O sistema deve exibir lista de tópicos ordenados por data de última resposta ou relevância <br> - O sistema deve permitir visualizar o conteúdo completo de um tópico com todas as respostas <br>  - O sistema deve permitir criar novo tópico com título, categoria e conteúdo <br>  - O sistema deve permitir responder a tópicos existentes com mensagens formatadas <br> - O sistema deve mostrar informações do autor e data de cada postagem <br>  - O sistema deve permitir marcar tópicos como favoritos e receber notificações de novas respostas              |
| Prioridade                   | Alta   |
| Status                       | -                   |
| Rastreabilidade              | [RF26](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf26)                          |
| Validação                    | -             |

**Fonte:** Raissa, 2025


<div align="center"><strong>Tabela 22:</strong> Reportar problemas </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | U22                                                         |
| Tema                         | Reportar problemas em cartas e anúncios                     |
| Descrição                    |  Eu, como usuário ativo da plataforma, desejo reportar problemas relacionados a cartas e anúncios, como informações incorretas, preços discrepantes ou anúncios suspeitos, para contribuir com a qualidade e confiabilidade do sistema para toda a comunidade. |
| Critérios de Aceitação       | - O sistema deve oferecer categorias pré-definidas de problemas (informação incorreta, preço errado, anúncio suspeito, imagem de baixa qualidade e afins) <br> - O sistema deve permitir que o usuário descreva detalhadamente o problema encontrado. <br> - O sistema deve permitir anexar fotos, prints ou imagens que comprovem o problema <br> - O sistema deve enviar confirmação do reporte registrado com número de protocolo <br> - O sistema deve notificar a equipe de moderação sobre novos reportes  <br>  - O sistema deve permitir acompanhar o status do reporte na área do usuário. <br>      |
| Prioridade                   | Média                  |
| Status                       | -                   |
| Rastreabilidade              | [RF37](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf37)                        |
| Validação                    | -                  |

**Fonte:** Raissa, 2025

<div align="center"><strong>Tabela 23:</strong> Os usuarios devem ser capazes de criar, salvar e gerenciar listas de decks </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | US23                                                        |
| Tema                         | Gerenciamento de Listas de Decks Pessoais                                      |
| Descrição                    | Eu, como jogador dedicado de Magic, desejo criar, salvar e gerenciar minhas próprias listas de decks, para poder organizar minhas estratégias, acompanhar evoluções e ter acesso rápido aos meus decks favoritos. |
| Critérios de Aceitação       | - O sistema deve permitir criar novo deck com nome, descrição, formato e lista de cartas. <br> - O sistema deve validar se o deck atende às regras do formato selecionado (número mínimo/máximo de cartas). <br> - O sistema deve permitir salvar múltiplos decks na coleção pessoal do usuário. <br> - O sistema deve permitir editar decks existentes (adicionar/remover cartas, alterar informações). <br> - O sistema deve permitir duplicar decks existentes para criar variações. <br> - O sistema deve permitir organizar decks em pastas ou categorias personalizadas. <br> - O sistema deve oferecer opção de tornar deck público ou mantê-lo privado. <br> - O sistema deve calcular automaticamente o custo total do deck baseado nos preços atuais. <br>           |
| Prioridade                   | Alta                                     |
| Status                       | Não Implementada                       |
| Rastreabilidade              | [RFNI09](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni09)                           |
| Validação                    |             |

**Fonte:** Raissa, 2025

<div align="center"><strong>Tabela 24:</strong> O sistema deve fornecer a funcionalidade "Comprar por lista" </div>

| **Item**                     | **Descrição**                                               |
| ---------------------------- | ----------------------------------------------------------- |
| USx(número de identificação) | US24                                                         |
| Tema                         | Compra por Lista de Cartas                                         |
| Descrição                    | Eu, como comprador frequente, desejo utilizar a funcionalidade "Compra por Lista" para adicionar múltiplas cartas de uma vez ao carrinho, para poder agilizar minhas compras de decks completos ou listas específicas. |
| Critérios de Aceitação       | -  O sistema deve permitir importar lista de cartas a partir de texto ou arquivo. <br> - O sistema deve identificar automaticamente cada carta da lista e suas quantidades. <br> - O sistema deve buscar os anúncios disponíveis para cada carta da lista. <br> - O sistema deve sugerir opções de compra consolidada com menor número de vendedores. <br> - O sistema deve calcular o custo total e frete consolidado. <br> - O sistema deve permitir ajustar quantidades e selecionar vendedores antes de adicionar ao carrinho. <br> - O sistema deve salvar listas de compra frequentes para reutilização. <br> - O sistema deve mostrar economia potencial em relação à compra individual. <br>          |
| Prioridade                   |  Média             |
| Status                       | Não Implementada                                 |
| Rastreabilidade              | [RFNI11](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni11)                         |
| Validação                    |           -        |

**Fonte:** Raissa, 2025

## Referências

> **PRESSMAN, Roger S.** _Engenharia de Software: uma abordagem profissional_. Cap. 3

## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição |
| ------ | ----------------- |
| Samuel |                   |
| Thiago |                   |
| Angélica |                   |
| Marcelo |                 |
| Raissa |     14,28%            |
## Histórico de versão

| Versão |    Data    | Descrição                    |   Autor(es)    | Revisor |
| :----: | :--------: | :--------------------------- | :------------: | :-----: |
|  1.0   | 16/10/2025 | Criação inicial do documento | Samuel, Thiago |    -    |
|  1.1   | 18/10/2025 | adicionar histórias de usuário (US07–US12) | Angélica |    Samuel, Thiago    |
|  1.2  | 18/10/2025 | adicionar histórias de usuário (US13–US18) | Marcelo |   Raissa  |
|  1.3  | 19/10/2025 | adicionar histórias de usuário (US19–US24) | Raissa |   -  |