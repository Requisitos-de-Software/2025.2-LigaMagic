# Cenários

## Descrição

Este documento faz parte do projeto das disciplinas de Requisitos de Software e tem como objetivo principal a definição detalhada dos cenários de uso da plataforma LigaMagic. Os cenários auxiliam na análise e modelagem de requisitos ao descrever as interações e jornadas específicas que o sistema deve suportar para atender às necessidades de seus consumidores.

## Objetivo

O objetivo desta etapa é criar narrativas concretas com detalhes contextuais que descrevem situações de uso da plataforma LigaMagic.

## Metodologia

Foi utilizado um modelo em que o cenário deve conter os seguintes elementos característicos: ambiente ou contexto , atores , objetivos , planejamento , ações , eventos , e avaliação.

Cada cenário foi estruturado conforme a tabela 1.

A tabela 2 distribui as funcionalidades entre os integrantes.

| Item | Cenário                                                                                                                                                                                                                                                                                                                                                                   |
| :--: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  1   | **Título** Um nome que identifica o cenário.                                                                                                                                                                                                                                                                                                                              |
|  2   | **Objetivo** A finalidade do cenário.                                                                                                                                                                                                                                                                                                                                     |
|  3   | **Contexto** Descreve o estado inicial do cenário, suas pré-condições e locais físicos e tempo.                                                                                                                                                                                                                                                                           |
|  4   | **Atores** Pessoa ou estruturaorganizacional que tem o papel no cenário.                                                                                                                                                                                                                                                                                                  |
|  5   | **Recursos** Identifica os objetos passivos com os quais lidam os atores.                                                                                                                                                                                                                                                                                                 |
|  6   | **Episódios** Cada episódio apresenta uma ação realizada por um ator, na qual participam outros atores utilizando os recursos disponíveis. Um episódio pode pertencer a outro cenário, e neles podemos ter restrições e exceções. As restrições são qualquer coisa que limite um episódio em um cenário. Uma exceção é o tratamento para uma ação excepcional ou de erro. |
|  7   | **Restrição** As características que o cenário deve seguir                                                                                                                                                                                                                                                                                                                |
|  8   | **Exceção** O que impedem a realização do cenário                                                                                                                                                                                                                                                                                                                         |

<div align="center"><strong>Tabela 1:</strong> Estrutura de um cenário</div>

|                           Id                            | Cenário                                                                                                |       Autor       |                              Requisito Associado                               |
| :-----------------------------------------------------: | :----------------------------------------------------------------------------------------------------- | :---------------: | :----------------------------------------------------------------------------: |
| [CE01](../../05_modelagem/01_cenarios/cenarios.md#ce01) | Salvar carta para compra futura                                                                        |     Angélica      | [RF28](./requisitos_elicitados.md#rf28) - [RFNI14](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni14) |
| [CE02](../../05_modelagem/01_cenarios/cenarios.md#ce02) | Gerenciar Wishlist Existente                                                                           |     Angélica      | [RF28](./requisitos_elicitados.md#rf28) - [RFNI14](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni14) |
| [CE03](../../05_modelagem/01_cenarios/cenarios.md#ce03) | Encontrar carta específica rapidamente                                                                 |     Angélica      | [RF20](./requisitos_elicitados.md#rf20) - [RFNI15](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni15) |
| [CE04](../../05_modelagem/01_cenarios/cenarios.md#ce04) | Permitir definir um alerta de preço para a carta selecionada                                           |    Vera Lucia     | [RF31](./requisitos_elicitados.md#rf31) - [RFNI05](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni05) |
| [CE05](../../05_modelagem/01_cenarios/cenarios.md#ce05) | Permitir reporte de problemas relacionados à carta ou anúncios                                         |    Vera Lucia     | [RF37](./requisitos_elicitados.md#rf37) - [RFNI07](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni07) |
| [CE06](../../05_modelagem/01_cenarios/cenarios.md#ce06) | Sistema que personaliza e mantem a página pessoal/profissional                                         | Marcelo de Araújo | [RF10](./requisitos_elicitados.md#rf10) - [RFNI01](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni01) |
| [CE07](../../05_modelagem/01_cenarios/cenarios.md#ce07) | Sistema de filtragem de cartas por qualidade/condição                                                  | Marcelo de Araújo | [RF21](./requisitos_elicitados.md#rf21) - [RFNI03](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni03) |
| [CE08](../../05_modelagem/01_cenarios/cenarios.md#ce08) | Criar e Salvar Lista de Decks                                                                          |  Raissa Andrade   | [RF](./requisitos_elicitados.md#rf) - [RFNI09](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni09) |
| [CE09](../../05_modelagem/01_cenarios/cenarios.md#ce09) | Gerenciar Lista de Decks                                                                               |  Raissa Andrade   | [RF](./requisitos_elicitados.md#rf) - [RFNI09](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni09) |
| [CE10](../../05_modelagem/01_cenarios/cenarios.md#ce10) | Comprar por Lista                                                                                      |  Raissa Andrade   | [RF](./requisitos_elicitados.md#rf) - [RFNI11](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni11) |
| [CE11](../../05_modelagem/01_cenarios/cenarios.md#ce11) | O sistema deve possibilitar participação dos consumidores em fóruns de discussão (postagem e resposta) |      Samuel       | [RF11](./requisitos_elicitados.md#rf11) - [RFNI02](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni02) |
| [CE12](../../05_modelagem/01_cenarios/cenarios.md#ce12) | Permitir que o jogador compartilhe informações da carta por link direto                                |      Samuel       | [RF36](./requisitos_elicitados.md#rf36) - [RFNI06](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni06) |
| [CE13](../../05_modelagem/01_cenarios/cenarios.md#ce13) | Permitir que o jogadores avalie ou dê feedback sobre vendedores ou decks                               |      Thiago       | [RF29](./requisitos_elicitados.md#rf29) - [RFNI04](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni04) |
| [CE14](../../05_modelagem/01_cenarios/cenarios.md#ce14) | Os jogadores devem ser capazes de catalogar e gerenciar sua **coleção** pessoal de cartas.             |      Thiago       | [RF](./requisitos_elicitados.md#rf) - [RFNI10](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni10) |

<div align="center"><strong>Tabela 2:</strong> Distribuição de funcionalidades</div>

## Conteúdo

### Cenário 01: Adicionar à Wishlist {#ce01}

| **Elemento**        | **Descrição**                                                                                                                                          |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **ID**              | CE01                                                                                                                                                   |
| **Título**          | Adicionar à Wishlist.                                                                                                                                  |
| **Metas/Objetivos** | Salvar carta para compra futura.                                                                                                                       |
| **Contexto**        | Jogador encontra carta de interesse, mas não pode comprar agora.                                                                                       |
| **Ator(es)**        | Jogador                                                                                                                                                |
| **Recursos**        | - Sistema autenticação <br>- Banco dados wishlist <br>- Storage jogador.                                                                               |
| **Exceções**        | - Sessão expirada <br>- Erro servidor <br>- Carta já na lista.                                                                                         |
| **Restrições**      | - Jogador deve estar logado <br>- Limite de 1000 cartas <br>- Dados persistentes                                                                       |
| **Episódios**       | 1. Visualizar carta <br>2. Clicar ícone em formato de estrela <br>3. Sistema valida adição <br>4. Feedback visual confirma <br>5. Carta salva na lista |

<div align="center"><strong>Tabela 02:</strong> Cenário 01</div>

**Fonte:** Angélica, 2025

### Cenário 02: Gerenciar Wishlist Existente {#ce02}

| **Elemento**        | **Descrição**                                                                                                                                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE02                                                                                                                                                                                                                                  |
| **Título**          | Gerenciar Wishlist Existente.                                                                                                                                                                                                         |
| **Metas/Objetivos** | Organizar e manter lista de desejos atualizada.                                                                                                                                                                                       |
| **Contexto**        | Jogador precisa revisar e organizar cartas salvas na wishlist.                                                                                                                                                                        |
| **Ator(es)**        | Jogador                                                                                                                                                                                                                               |
| **Recursos**        | - Lista de cartas salvas <br>- Sistema de filtros <br>- Opções de ordenação.                                                                                                                                                          |
| **Exceções**        | - Wishlist vazia <br>- Erro ao carregar itens <br>- Falha ao aplicar filtros <br>- Sessão expirada.                                                                                                                                   |
| **Restrições**      | - Wishlist deve ter itens <br>- Conexão para sincronização <br>- Limite de 1000 cartas.                                                                                                                                               |
| **Episódios**       | 1. Acessar seção "Minha Wishlist" <br>2. Visualizar cartas organizadas <br>3. Aplicar filtros (tipo, raridade, preço) <br>4. Ordenar por critério desejado <br>5. Navegar entre páginas <br>6. Realizar ações (remover, ver detalhes) |

<div align="center"><strong>Tabela 03:</strong> Cenário 02</div>

**Fonte:** Angélica, 2025

### Cenário 03: Pesquisar Cartas {#ce03}

| **Elemento**        | **Descrição**                                                                                                                                               |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE03                                                                                                                                                        |
| **Título**          | Pesquisar Cartas                                                                                                                                            |
| **Metas/Objetivos** | Encontrar carta específica rapidamente.                                                                                                                     |
| **Contexto**        | Jogador precisa localizar carta para compra ou consultar.                                                                                                   |
| **Ator(es)**        | Jogador                                                                                                                                                     |
| **Recursos**        | - Conexão internet <br>- Banco dados das cartas <br>- Serviço de busca                                                                                      |
| **Exceções**        | - Falha retorno resultados                                                                                                                                  |
| **Restrições**      | - Conexão internet obrigatória <br>- Dados das cartas atualizados                                                                                           |
| **Episódios**       | 1. Acessar aba pesquisa <br>2. Digitar termo de busca <br>3. Sistema processa as requisição <br>4. Exibir os resultados <br>5. Jogador visualiza as opções. |

<div align="center"><strong>Tabela 04:</strong> Cenário 03</div>

**Fonte:** Angélica, 2025

### Cenário 04: Permitir definir um alerta de preço para a carta selecionada {#ce04}

| **Elemento**        | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **ID**              | CE04                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Título**          | Permitir que o comprador defina um alerta de preço para a carta selecionada                                                                                                                                                                                                                                                                                                                                                          |
| **Metas/Objetivos** | Notificar o comprador quando o preço da carta atingir o valor definido..                                                                                                                                                                                                                                                                                                                                                             |
| **Contexto**        | **Local:** qualquer lugar onde o comprador possa acessar o aplicativo. <br>**Tempo:** em tempo real.                                                                                                                                                                                                                                                                                                                                 |
| **Ator(es)**        | - Jogador Autenticado                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Recursos**        | - Smartphone com o app da LigaMagic, conexão com a internet                                                                                                                                                                                                                                                                                                                                                                          |
| **Exceções**        | - Falta de conexão com a internet.<br>- Valor inválido inserido.<br>- Jogador não está logado em sua conta.                                                                                                                                                                                                                                                                                                                          |
| **Restrições**      | - Valor do alerta deve estar dentro do limite permitido pelo sistema.<br>- Apenas cartas existentes na plataforma podem ter alertas definidos.                                                                                                                                                                                                                                                                                       |
| **Episódios**       | 1. Comprador decide acompanhar o preço de uma carta.<br>2. Abre o aplicativo.<br>3. Realiza login, caso ainda não esteja autenticado.<br>4. Acessa a busca ou lista de cartas.<br>5. Localiza a carta desejada.<br>6. Abre a página detalhada da carta.<br>7. Clica no botão “Definir alerta”.<br>8. Insere o valor desejado para o alerta.<br>9. Sistema valida o valor informado.<br>10. Sistema confirma a criação do alerta.<br> |

<div align="center"><strong>Tabela 04:</strong> Cenário 04</div>

**Fonte:** [Vera Lucia](https://github.com/verabelucia), 2025

### Cenário 05: Permitir reporte problemas relacionados à carta ou anúncios {#ce05}

| **Elemento**        | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE05                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Título**          | Permitir que reporte problemas relacionados à carta ou anúncios                                                                                                                                                                                                                                                                                                                                                               |
| **Metas/Objetivos** | Permitir que o comprador comunique erros ou irregularidades encontradas em cartas ou anúncios                                                                                                                                                                                                                                                                                                                                 |
| **Contexto**        | **Local:** qualquer lugar onde o jogador possa acessar o aplicativo.<br>**Tempo:** Em tempo real                                                                                                                                                                                                                                                                                                                              |
| **Ator(es)**        | - Comprador Autenticado                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Recursos**        | - Smartphone com o app da LigaMagic, conexão com a internet                                                                                                                                                                                                                                                                                                                                                                   |
| **Exceções**        | - Falta de conexão com a internet.<br>- Valor inválido inserido.<br>- Jogador não está logado em sua conta.                                                                                                                                                                                                                                                                                                                   |
| **Restrições**      | - O comprador deve selecionar um tipo de problema antes de enviar.<br>- O comprador deve descrever o problema antes de enviar.                                                                                                                                                                                                                                                                                                |
| **Episódios**       | 1. Jogador identifica um possível erro ou anúncio suspeito.<br>2. Abre o aplicativo.<br>3. Realiza login, se necessário.<br>4. Acessa a página da carta.<br>5. Clica em “Reportar problema”.<br>6. Sistema apresenta opções de tipos de problema.<br>7. Jogador seleciona o tipo adequado.<br>8. Descreve o problema em detalhes.<br>9. Envia o reporte.<br>10. Sistema registra o reporte e confirma o envio ao jogador.<br> |

<div align="center"><strong>Tabela 06:</strong> Cenário 05</div>

**Fonte:** [Vera Lucia](https://github.com/verabelucia), 2025

### Cenário 06: Personalizar perfil de jogador {#ce06}

| Item          | Descrição                                                                                                                                                                                                                                                                                                                                                                                                             |
| :------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**        | CE06                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Título**    | Personalizar e manter o perfil de jogador                                                                                                                                                                                                                                                                                                                                                                             |
| **Objetivo**  | Permitir que o jogador personalize seu perfil com informações como avatar, endereço de envio e cards de interesse, a fim de agilizar futuras compras e customizar sua experiência na plataforma.                                                                                                                                                                                                                      |
| **Contexto**  | **Local:** Aplicativo ou site da LigaMagic, na seção "Meu Perfil" ou "Minha Conta".<br>**Tempo:** Em tempo real, quando o consumidor desejar atualizar.<br>**Pré-condição:** O consumidor deve possuir um cadastro e estar logado na plataforma.                                                                                                                                                                      |
| **Atores**    | Consumidores da plataforma LigaMagic (compradores, jogadores, colecionadores).                                                                                                                                                                                                                                                                                                                                        |
| **Recursos**  | Conexão com a internetDispositivo (PC/Smartphone) com acesso à LigaMagic.                                                                                                                                                                                                                                                                                                                                             |
| **Episódios** | O jogador acessa o menu e seleciona a opção "Meu Perfil". Clica em "Editar Avatar" e faz o upload de uma nova imagem pessoal.Acessa a seção "Meus Endereços" e cadastra ou atualiza seu endereço de envio principal. Vai para a seção "Want List" para adicionar os cards que tem interesse em adquirir. Salva as alterações em cada seção. Verifica se o novo avatar e as informações estão aparecendo corretamente. |
| **Restrição** | A imagem do avatar deve seguir um formato (ex: JPG, PNG) e tamanho máximo especificado.O cadastro de endereço deve seguir um formato de CEP válido.                                                                                                                                                                                                                                                                   |
| **Exceção**   | Falha no upload do avatar (formato/tamanho inválido).O CEP informado não é encontrado ou é inválido.Perda das alterações não salvas caso a conexão com a internet caia.                                                                                                                                                                                                                                               |

<div align="center"><strong>Tabela 07:</strong> Cenário 06</div>

**Fonte:** Marcelo, 2025

### Cenário 07: Filtrar busca por condição da carta {#ce07}

| Item          | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| :------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **ID**        | CE07                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Título**    | Filtrar busca de cartas por qualidade/condição                                                                                                                                                                                                                                                                                                                                                                                              |
| **Objetivo**  | Permitir que o jogador (comprador) refine os resultados de uma busca de cartas, exibindo apenas as versões que se encontram em um estado de conservação específico (ex: Near Mint, Moderately Played), facilitando a compra para colecionadores e jogadores exigentes.                                                                                                                                                                      |
| **Contexto**  | **Local:** Aplicativo ou site da LigaMagic, na página de busca ou na página de um produto específico. <br>**Tempo:** Em tempo real, durante a busca por cartas.<br>**Pré-condição:** O comprador estar realizando uma busca por uma ou mais cartas.                                                                                                                                                                                         |
| **Atores**    | Compradores, jogadores e colecionadores que utilizam a LigaMagic.                                                                                                                                                                                                                                                                                                                                                                           |
| **Recursos**  | Conexão com a internet Dispositivo (PC/Smartphone) com acesso à LigaMagic                                                                                                                                                                                                                                                                                                                                                                   |
| **Episódios** | O comprador busca pelo nome de uma carta (ex: "Sol Ring") . Na página de resultados, ele localiza e seleciona a opção "Filtros" . Dentro dos filtros, ele encontra a seção "Condição" e marca a caixa "NM (Near Mint)" . Ele aplica o filtro . A página recarrega, mostrando apenas os anúncios da carta "Sol Ring" que os vendedores cadastraram como "Near Mint" . O comprador prossegue com a compra, confiante na qualidade do produto. |
| **Restrição** | O filtro depende da correta classificação feita pelo vendedor no momento do cadastro do card. Anúncios sem a classificação de condição podem ser omitidos do resultado.                                                                                                                                                                                                                                                                     |
| **Exceção**   | A aplicação do filtro resulta em um erro ou não altera a lista de resultado, reiniciando a busca nenhum vendedor possui a carta na condição desejada.                                                                                                                                                                                                                                                                                       |

<div align="center"><strong>Tabela 08:</strong> Cenário 07</div>

**Fonte:** Marcelo, 2025

### Cenário 08: Criar e Salvar Lista de Decks {#ce08}

| **Elemento**        | **Descrição**                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE08                                                                                                                                                                                        |
| **Título**          | Criar e Salvar Lista de Decks                                                                                                                                                               |
| **Metas/Objetivos** | Permitir que o jogador monte uma lista de decks, personalize com nome/descrição e salve para uso.                                                                                           |
| **Contexto**        | O jogador deseja organizar seus decks em listas, seja para colecionar, montar estratégias ou preparar compras futuras.                                                                      |
| **Ator(es)**        | - Jogador Autenticado<br>- Sistema de gerenciamento de listas                                                                                                                               |
| **Recursos**        | - Banco de dados para armazenar listas<br>- Interface de criação/edição<br>- Campo de busca e adição de decks                                                                               |
| **Exceções**        | - Deck não encontrado na base local.<br>- Erro ao salvar lista.                                                                                                                             |
| **Restrições**      | - O nome da lista deve ser único por jogador.<br>- Somente jogadoress autenticados podem criar ou salvar listas.<br>- Salvar a carta somente uma vez                                        |
| **Episódios**       | 1. Jogador acessa “Minhas Listas”.<br>2. Seleciona “Criar nova lista”.<br>3. Preenche nome/descrição.<br>4. Adiciona decks (busca/link).<br>5. Salva lista.<br>6. Sistema confirma criação. |

<div align="center"><strong>Tabela 09:</strong> Cenário 08</div>

**Fonte:** Raissa, 2025

### Cenário 09: Gerenciar Lista de Decks {#ce09}

| **Elemento**        | **Descrição**                                                                                                                                                                                    |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **ID**              | CE09                                                                                                                                                                                             |
| **Título**          | Gerenciar Lista de Decks                                                                                                                                                                         |
| **Metas/Objetivos** | Permitir que o jogadores edite, exclua, ordene ou compartilhe suas listas de decks.                                                                                                              |
| **Contexto**        | O jogador já possui uma lista criada e deseja alterar ou organizar seu conteúdo.                                                                                                                 |
| **Ator(es)**        | - Jogador Autenticado<br>- Sistema de gerenciamento de listas                                                                                                                                    |
| **Recursos**        | - Banco de dados das listas<br>- Interface de edição<br>- Funcionalidade de compartilhamento/exportação                                                                                          |
| **Exceções**        | - Tentativa de exclusão de lista que não existe.<br>- Compartilhamento com link inválido.<br>- Erro ao salvar alterações.                                                                        |
| **Restrições**      | - Somente o dono da lista pode editá-la ou excluí-la.                                                                                                                                            |
| **Episódios**       | 1. Comprador acessa “Minhas Listas”.<br>2. Seleciona uma lista existente.<br>3. Edita quantidades, renomeia ou exclui itens.<br>4. Salva alterações.<br>5. Sistema atualiza e confirma mudanças. |

<div align="center"><strong>Tabela 10:</strong> Cenário 09</div>

**Fonte:** Raissa, 2025

### Cenário 10: Comprar por Lista {#ce10}

| **Elemento**        | **Descrição**                                                                                                                                                                                                   |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE10                                                                                                                                                                                                            |
| **Título**          | Comprar por Lista                                                                                                                                                                                               |
| **Metas/Objetivos** | Permitir que o jogador compre todos os itens de uma lista de decks com integração ao site LigaMagic.                                                                                                            |
| **Contexto**        | O jogador possui uma lista pronta e deseja adquirir os decks diretamente, sem buscar um por um no site.                                                                                                         |
| **Ator(es)**        | - Jogador Autenticado<br>- Sistema de integração<br>- Fornecedor (LigaMagic)                                                                                                                                    |
| **Recursos**        | - Banco de dados da lista<br>- Mecanismo de matching com catálogo LigaMagic<br>- API/integração para redirecionamento ao carrinho                                                                               |
| **Exceções**        | - Produto não encontrado.<br>- Indisponibilidade de integração com LigaMagic.<br>                                                                                                                               |
| **Restrições**      | - Somente listas salvas podem ser compradas.<br>- O processo deve mostrar os itens correspondidos e os não encontrados.<br>- Ter todas cartas disponíveis.                                                      |
| **Episódios**       | 1. Jogador acessa uma lista salva.<br>2. Clica em “Comprar por lista”.<br>3. Exibe resumo com preços, itens indisponíveis e total estimado.<br>4. Jogador confirma e é redirecionado ao carrinho do fornecedor. |

<div align="center"><strong>Tabela 11:</strong> Cenário 10</div>

**Fonte:** Raissa, 2025

### Cenário 11: Participação em Fóruns de Discussão {#ce11}

| Item          | Descrição                                                                                                                                                                                                                                                                                                                                                                    |
| :------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**        | CE11                                                                                                                                                                                                                                                                                                                                                                         |
| **Título**    | Pedindo Ajuda para Montar um Primeiro Deck Commander                                                                                                                                                                                                                                                                                                                         |
| **Objetivo**  | Permitir que o jogador iniciante obtenha sugestões de comandantes e listas de decks de baixo custo através do fórum da comunidade, facilitando o aprendizado e entrada no formato Commander.                                                                                                                                                                                 |
| **Contexto**  | **Local:** Aplicativo Liga Magic, no intervalo entre aulas no pátio da universidade.<br>**Tempo:** Durante o intervalo das aulas, utilizando Wi-Fi da faculdade.<br>**Pré-condição:** O jogador deve ter o aplicativo instalado e acesso à internet.                                                                                                                         |
| **Ator(es)**  | Jogador                                                                                                                                                                                                                                                                                                                                                                      |
| **Recursos**  | Smartphone com aplicativo Liga Magic instalado, conexão Wi-Fi da faculdade, seção de fórum do aplicativo.                                                                                                                                                                                                                                                                    |
| **Episódios** | O jogador acessa a seção "Fórum" no aplicativo. Seleciona o subfórum "Commander (Mesão)". Clica em "Novo Tópico" e cria uma postagem explicando sua situação como iniciante e pedindo sugestões de deck budget. Publica a postagem no fórum. Recebe notificações de respostas. Lê as sugestões da comunidade e interage fazendo perguntas pontuais sobre cartas específicas. |
| **Restrição** | O jogador deve estar cadastrado na plataforma para participar do fórum. As postagens devem seguir as regras de conduta da comunidade.                                                                                                                                                                                                                                        |
| **Exceção**   | Falha na conexão com a internet impedindo o carregamento do fórum. Nenhum membro da comunidade responde à postagem. Postagem removida por violar regras da comunidade.                                                                                                                                                                                                       |

<div align="center"><strong>Tabela 12:</strong> Cenário 11</div>

**Fonte:** Samuel, 2025

### Cenário 12: Compartilhamento de Informações de Carta {#ce12}

| Item          | Descrição                                                                                                                                                                                                                                                                                                                                                                                              |
| :------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**        | CE12                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Título**    | Tirando Dúvida sobre uma Carta com um Amigo                                                                                                                                                                                                                                                                                                                                                            |
| **Objetivo**  | Permitir que o jogador compartilhe informações detalhadas de uma carta específica através de link direto, facilitando a comunicação e esclarecimento de dúvidas com outros jogadores.                                                                                                                                                                                                                  |
| **Contexto**  | **Local:** Quarto do jogador, organizando coleção de cartas.<br>**Tempo:** Momento de organização da coleção, quando surge uma dúvida.<br>**Pré-condição:** O consumidor deve ter o aplicativo Liga Magic instalado e acesso a um aplicativo de mensagens.                                                                                                                                             |
| **Ator(es)**  | Jogador                                                                                                                                                                                                                                                                                                                                                                                                |
| **Recursos**  | Smartphone com aplicativo Liga Magic, aplicativo de mensagens (WhatsApp/Telegram), conexão com internet, função de busca e compartilhamento do aplicativo.                                                                                                                                                                                                                                             |
| **Episódios** | O jogador busca pelo nome da carta ("O Anel Um") na barra de busca do aplicativo. Acessa a página de detalhes da carta visualizando imagem e texto completo. Toca no ícone "Compartilhar" na tela de detalhes. O sistema gera automaticamente um link direto para a carta. Seleciona o aplicativo de mensagens e envia o link para o amigo com sua dúvida. O amigo acessa o link e esclarece a dúvida. |
| **Restrição** | A carta deve estar cadastrada na base de dados do aplicativo. O link gerado deve ser acessível por consumidores externos ao aplicativo.                                                                                                                                                                                                                                                                |
| **Exceção**   | Carta não encontrada na busca. Falha na geração do link de compartilhamento. Aplicativo de mensagens não disponível para compartilhamento. Link compartilhado não funciona corretamente.                                                                                                                                                                                                               |

<div align="center"><strong>Tabela 13:</strong> Cenário 12</div>

**Fonte:** Samuel, 2025

### Cenário 13: Avaliar Vendedor Após Receber Compra {#ce13}

| Item          | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                           |
| :------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**        | CE13                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Título**    | Avaliar Vendedor Após Receber Compra                                                                                                                                                                                                                                                                                                                                                                                                |
| **Objetivo**  | Permitir que o comprador avalie e forneça feedback sobre vendedores após receber uma compra, contribuindo para a confiabilidade da comunidade e ajudando outros compradores a tomar decisões informadas.                                                                                                                                                                                                                            |
| **Contexto**  | **Local:** Aplicativo Liga Magic, durante o intervalo de almoço na faculdade.<br>**Tempo:** Após receber as cartas compradas, no mesmo dia da entrega.<br>**Pré-condição:** O jogador deve ter realizado uma compra, recebido as cartas e estar logado no aplicativo.                                                                                                                                                               |
| **Ator(es)**  | - Jogador<br>- Vendedor                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Recursos**  | Smartphone com aplicativo Liga Magic instalado, conexão com internet, seção "Minhas Compras", sistema de avaliação por estrelas e campo de feedback textual.                                                                                                                                                                                                                                                                        |
| **Episódios** | O jogador abre o aplicativo Liga Magic. Navega até a seção "Minhas Compras". Localiza o pedido do vendedor "CardHunterBR" e toca em "Confirmar Recebimento". O sistema exibe pop-up "Avaliar Vendedor" e o comprador a seleciona. Avalia "Velocidade de Envio" com 5 estrelas e "Qualidade das Cartas" com 5 estrelas. Escreve feedback conciso: "Cartas em ótimo estado e entrega super rápida. Recomendo!". Confirma a avaliação. |
| **Restrição** | O comprador só pode avaliar após confirmar o recebimento das cartas. Cada pedido pode ser avaliado apenas uma vez. O feedback deve seguir as regras de conduta da plataforma.                                                                                                                                                                                                                                                       |
| **Exceção**   | Falha na conexão impedindo o envio da avaliação. Pedido não encontrado na seção "Minhas Compras". Sistema não exibe a opção de avaliação. Feedback rejeitado por violar regras da comunidade.                                                                                                                                                                                                                                       |

<div align="center"><strong>Tabela 14:</strong> Cenário 13</div>

**Fonte:** Thiago, 2025

### Cenário 14: Adicionar Cartas à Coleção via Lista de Desejos {#ce14}

| Item          | Descrição                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| :------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**        | CE14                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Título**    | Adicionar Cartas à Coleção via Lista de Desejos                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Objetivo**  | Permitir que o jogador transfira cartas adquiridas da Lista de Desejos para sua Coleção Pessoal, mantendo o controle organizado do inventário e atualizando automaticamente o valor total da coleção.                                                                                                                                                                                                                                                                                     |
| **Contexto**  | **Local:** Aplicativo Liga Magic, após efetuar a compra de uma carta desejada.<br>**Tempo:** Momento pós-compra, quando o jogador deseja atualizar seu inventário.<br>**Pré-condição:** O jogador deve ter uma Lista de Desejos criada com cartas cadastradas e ter efetuado a compra de uma dessas cartas.                                                                                                                                                                               |
| **Ator(es)**  | - Jogador                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Recursos**  | Smartphone com aplicativo Liga Magic instalado, conexão com internet, seção "Minha Lista de Desejos", seção "Minha Coleção", sistema de gerenciamento de inventário.                                                                                                                                                                                                                                                                                                                      |
| **Episódios** | O jogador abre o aplicativo e navega para "Minha Lista de Desejos". Localiza o item "Lorde Vampiro" (Edição Innistrad). Pressiona e segura o item para abrir o menu de contexto. Seleciona "Mover para Coleção Pessoal" no menu. O sistema solicita informações de "Condição" e "Preço Pago". Jogador insere "Near Mint" e "R$ 55,00". O sistema move a carta, atualiza a Coleção Pessoal e recalcula o valor total. O comprador confirma a transferência navegando para "Minha Coleção". |
| **Restrição** | A carta deve estar previamente cadastrada na Lista de Desejos. O comprador deve informar condição e preço pago para a transferência. O sistema deve manter a integridade dos dados entre as seções.                                                                                                                                                                                                                                                                                       |
| **Exceção**   | Falha na conexão impedindo a sincronização dos dados. Erro no sistema ao mover a carta entre seções. Informações de condição ou preço em formato inválido. Carta não encontrada na Lista de Desejos.                                                                                                                                                                                                                                                                                      |

<div align="center"><strong>Tabela 15:</strong> Cenário 14</div>

**Fonte:** Thiago, 2025

## Video de validação feita com um comprador

Para a validação dos cenários, cada integrante do grupo foi responsável por validar os cenários que criou. A seguir, estão os vídeos realizados durante as validações.

- [Assista ao vídeo no YouTube](https://youtu.be/6mkG1ma1Wf4). Este video é referente à validação dos cenários 1.0, 1.1 e 02 e foi produzido pela aluna Angélica Campos.
- [Assista ao vídeo no YouTube](https://youtu.be/9G1eUtgW3nE). Este video é referente à validação dos cenários 06 e 07 e foi produzido pela aluna Vera Lucia
- [Assista ao vídeo no YouTube](https://youtu.be/1lxHnaYfWR4). Este video é referente á validação dos cenários 01 e 02 e foi produzido pelo aluno Marcelo.
- [Assista ao vídeo no YouTube](https://www.youtube.com/watch?v=YXONTjL32WU) Este vídeo foi produzido pelo aluno Samuel, sendo referente à validação dos cenários 11 e 12 (Os minutos estão na descrição).
- [Assista ao vídeo no YouTube](https://www.youtube.com/watch?v=YXONTjL32WU) Este vídeo foi produzido pelo aluno Thiago, sendo referente à validação dos cenários 13 e 14 (Os minutos estão na descrição).
- [Assista ao vídeo no YouTube](https://www.youtube.com/watch?v=ZlX_tKeczd8) Este vídeo foi produzido pela aluna Raissa, sendo referente à validação dos cenários 03, 04 e 05 (Os minutos estão na descrição).

## Bibliografia

> BARBOSA, S. D. J.; SILVA, B. S. da; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## Nível de Contribuição dos Integrantes

| Nome     | % de Contribuição |
| :------- | :---------------: |
| Marcelo  |      16,67%       |
| Raissa   |      16,67%       |
| Vera     |      16,67%       |
| Angélica |      16,67%       |
| Samuel   |      16,67%       |
| Thiago   |      16,67%       |

## Histórico de versão

| Versão |    Data    | Descrição                                                                  |                  Autor(es)                  |                Revisor                |
| :----: | :--------: | :------------------------------------------------------------------------- | :-----------------------------------------: | :-----------------------------------: |
|  1.0   | 08/10/2025 | Adição de cenários                                                         |                   Marcelo                   |                Raissa                 |
|  1.1   | 09/10/2025 | Adição de cenários 05, 06 e 07                                             |                   Raissa                    |                 Vera                  |
|  1.2   | 09/10/2025 | Adição de cenários 08 e 09                                                 |                    Vera                     |                Raissa                 |
|  1.3   | 10/10/2025 | Adição de cenários 10, 11 e 12                                             |                  Angélica                   |                Marcelo                |
|  1.4   | 10/10/2025 | Adição de cenários 13, 14, 15 e 16                                         |               Samuel e Thiago               |                 Vera                  |
|  1.5   | 10/10/2025 | Retirada de "usuários"                                                     |                   Thiago                    |                Samuel                 |
|  1.6   | 11/10/2025 | Adição da tabela de autoria                                                |                   Samuel                    |                Thiago                 |
|  1.7   | 11/10/2025 | Adição do vídeo de validação                                               |                    Vera                     |               Angélica                |
|  1.8   | 11/10/2025 | Adição do vídeo de validação 01 e 02                                       |                   Marcelo                   |                 Vera                  |
| 1.8.1  | 11/10/2025 | Adição do vídeo de validação dos integrantes e corrigindo nomes de tabelas |                   Thiago                    |                Marcelo                |
|  1.9   | 12/10/2025 | Melhorada a rastreabilidade dos requisitos                                 | [Samuel](https://github.com/samuelncaetano) |                Thiago                 |
|  1.10  | 13/10/2025 | Correção da orem dos cenarios                                              |                  Angélica                   | Thiago, Marcelo, Vera, Raissa, Samuel |
