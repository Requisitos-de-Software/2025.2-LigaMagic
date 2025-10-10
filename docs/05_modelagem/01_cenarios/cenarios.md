# Cenários

## Descrição
Este documento faz parte do projeto das disciplinas de Requisitos de Software e tem como objetivo principal a definição detalhada dos cenários de uso da plataforma LigaMagic. Os cenários auxiliam na análise e modelagem de requisitos ao descrever as interações e jornadas específicas que o sistema deve suportar para atender às necessidades de seus usuários.

## Objetivo
O objetivo desta etapa é criar narrativas concretas com detalhes contextuais  que descrevem situações de uso da plataforma LigaMagic.

## Metodologia

Foi utilizado um modelo em que o cenário deve conter os seguintes elementos característicos: ambiente ou contexto , atores , objetivos , planejamento , ações , eventos , e avaliação.

Cada cenário foi estruturado conforme a tabela 1.

A tabela 2 distribui as funcionalidades entre os integrantes.


# Tabela 1 - Estrutura de um cenário

---

| Item | Cenário |
|:----:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 | **Título** Um nome que identifica o cenário. |
| 2 | **Objetivo** A finalidade do cenário. |
| 3 | **Contexto** Descreve o estado inicial do cenário, suas pré-condições e locais físicos e tempo. |
| 4 | **Atores** Pessoa ou estruturaorganizacional que tem o papel no cenário. |
| 5 | **Recursos** Identifica os objetos passivos com os quais lidam os atores. |
| 6 | **Episódios** Cada episódio apresenta uma ação realizada por um ator, na qual participam outros atores utilizando os recursos disponíveis. Um episódio pode pertencer a outro cenário, e neles podemos ter restrições e exceções. As restrições são qualquer coisa que limite um episódio em um cenário. Uma exceção é o tratamento para uma ação excepcional ou de erro. |
| 7 | **Restrição** As características que o cenário deve seguir |
| 8 | **Exceção** O que impedem a realização do cenário |

---

# Tabela 2 - Distribuição de funcionalidades
 
---

| Integrante | Cenário |
|:----:|:-------------------------------------------------------------|
| 1 | **Marcelo de Araújo** : Sistema que personaliza e mantem a  página pessoal/profissional |
| 2 | **Marcelo de Araújo** : Sistema de filtragem de cartas por qualidade/condição |
| 3 | **Raissa Andrade**: Criar e Salvar Lista de Decks: Cenário 05: Criar e Salvar Lista de Decks |
| 4 | **Raissa Andrade**: Gerenciar Lista de Decks: Cenário 06|
| 5 | **Raissa Andrade**: Comprar por Lista: Cenário 07 |
| 6 | **Vera Lucia**: Permitir  definir um alerta de preço para a carta selecionada: Cenário 08|
| 7 |  **Vera Lucia** : Permitir reporte de problemas relacionados à carta ou anúncios: Cenário 09
| 8 | 
| 9 | 
| 10 | 
| 11 | 
| 12 | 
| 13 | 
| 14 | 

---

## Conteúdo

### Tabela 3: Cenário - Personalizar perfil de usuário

A tabela 3 descreve o cenário do requisito funcional Personalizar perfil de usuário , que foi rastreada pelas técnica de observação

| Item | Descrição |
| :--- | :--- |
| **Título** | Personalizar e manter o perfil de usuário |
| **Objetivo** | Permitir que o usuário personalize seu perfil com informações como avatar, endereço de envio e cards de interesse, a fim de agilizar futuras compras e customizar sua experiência na plataforma. |
| **Contexto** | **Local:** Aplicativo ou site da LigaMagic, na seção "Meu Perfil" ou "Minha Conta".**Tempo:** Em tempo real, quando o usuário desejar atualizar.**Pré-condição:** O usuário deve possuir um cadastro e estar logado na plataforma. |
| **Atores** | Usuários da plataforma LigaMagic (compradores, jogadores, colecionadores). |
| **Recursos** | Conexão com a internetDispositivo (PC/Smartphone) com acesso à LigaMagic. |
| **Episódios** |  O usuário acessa o menu e seleciona a opção "Meu Perfil". Clica em "Editar Avatar" e faz o upload de uma nova imagem pessoal.Acessa a seção "Meus Endereços" e cadastra ou atualiza seu endereço de envio principal. Vai para a seção "Want List" para adicionar os cards que tem interesse em adquirir. Salva as alterações em cada seção. Verifica se o novo avatar e as informações estão aparecendo corretamente. |
| **Restrição** | A imagem do avatar deve seguir um formato (ex: JPG, PNG) e tamanho máximo especificado.O cadastro de endereço deve seguir um formato de CEP válido. |
| **Exceção** | Falha no upload do avatar (formato/tamanho inválido).O CEP informado não é encontrado ou é inválido.Perda das alterações não salvas caso a conexão com a internet caia. |


### Tabela 4: Cenário - Filtrar busca por condição da carta

A tabela 4 descreve o cenário do requisito funcional Personalizar perfil de usuário , que foi rastreada pelas técnica de observação

| Item | Descrição |
| :--- | :--- |
| **Título** | Filtrar busca de cartas por qualidade/condição |
| **Objetivo** | Permitir que o usuário (comprador) refine os resultados de uma busca de cartas, exibindo apenas as versões que se encontram em um estado de conservação específico (ex: Near Mint, Moderately Played), facilitando a compra para colecionadores e jogadores exigentes. |
| **Contexto** | **Local:** Aplicativo ou site da LigaMagic, na página de busca ou na página de um produto específico.                                                  **Tempo:** Em tempo real, durante a busca por cartas.**Pré-condição:** O usuário estar realizando uma busca por uma ou mais cartas. |
| **Atores** | Compradores, jogadores e colecionadores que utilizam a LigaMagic. |
| **Recursos** | Conexão com a internet Dispositivo (PC/Smartphone) com acesso à LigaMagic|
| **Episódios** | O usuário busca pelo nome de uma carta (ex: "Sol Ring") . Na página de resultados, ele localiza e seleciona a opção "Filtros" . Dentro dos filtros, ele encontra a seção "Condição" e marca a caixa "NM (Near Mint)" . Ele aplica o filtro . A página recarrega, mostrando apenas os anúncios da carta "Sol Ring" que os vendedores cadastraram como "Near Mint" . O usuário prossegue com a compra, confiante na qualidade do produto. |
| **Restrição** | O filtro depende da correta classificação feita pelo vendedor no momento do cadastro do card. Anúncios sem a classificação de condição podem ser omitidos do resultado. |
| **Exceção** | A aplicação do filtro resulta em um erro ou não altera a lista de resultado, reiniciando a busca nenhum vendedor possui a carta na condição desejada. |


### Cenário 05: Criar e Salvar Lista de Decks
**Requisito Associado:** [RI09] - Os jogadores devem ser capazes de criar, salvar e gerenciar listas de decks.

<div align="center"><strong>Tabela 1: Cenário 01</strong></div>

| **Elemento**        | **Descrição**  |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE09    |
| **Título**          | Criar e Salvar Lista de Decks  |
| **Metas/Objetivos** | Permitir que o jogador monte uma lista de decks, personalize com nome/descrição e salve para uso. |
| **Contexto**        | O jogador deseja organizar seus decks em listas, seja para colecionar, montar estratégias ou preparar compras futuras. |
| **Ator(es)**        | - Jogador Autenticado<br>- Sistema de gerenciamento de listas |
| **Recursos**        | - Banco de dados para armazenar listas<br>- Interface de criação/edição<br>- Campo de busca e adição de decks |
| **Exceções**        | - Deck não encontrado na base local.<br>- Erro ao salvar lista. |
| **Restrições**      | - O nome da lista deve ser único por jogador.<br>- Somente jogadoress autenticados podem criar ou salvar listas.<br>- Salvar a carta somente uma vez
| **Episódios**       | 1. Jogador acessa “Minhas Listas”.<br>2. Seleciona “Criar nova lista”.<br>3. Preenche nome/descrição.<br>4. Adiciona decks (busca/link).<br>5. Salva lista.<br>6. Sistema confirma criação. |

---

### Cenário 06: Gerenciar Lista de Decks
**Requisito Associado:** [RI09] - Os jogadores devem ser capazes de criar, salvar e gerenciar listas de decks.

<div align="center"><strong>Tabela 2: Cenário 02</strong></div>

| **Elemento**        | **Descrição**  |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE09    |
| **Título**          | Gerenciar Lista de Decks  |
| **Metas/Objetivos** | Permitir que o jogadores edite, exclua, ordene ou compartilhe suas listas de decks. |
| **Contexto**        | O jogador já possui uma lista criada e deseja alterar ou organizar seu conteúdo. |
| **Ator(es)**        | - Jogador Autenticado<br>- Sistema de gerenciamento de listas |
| **Recursos**        | - Banco de dados das listas<br>- Interface de edição<br>- Funcionalidade de compartilhamento/exportação |
| **Exceções**        | - Tentativa de exclusão de lista que não existe.<br>- Compartilhamento com link inválido.<br>- Erro ao salvar alterações. |
| **Restrições**      | - Somente o dono da lista pode editá-la ou excluí-la. |
| **Episódios**       | 1. Usuário acessa “Minhas Listas”.<br>2. Seleciona uma lista existente.<br>3. Edita quantidades, renomeia ou exclui itens.<br>4. Salva alterações.<br>5. Sistema atualiza e confirma mudanças. |

---

### Cenário 07: Comprar por Lista
**Requisito Associado:** [RI11] - O sistema deve fornecer a funcionalidade "comprar por lista".

<div align="center"><strong>Tabela 3: Cenário 03</strong></div>

| **Elemento**        | **Descrição**  |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE11    |
| **Título**          | Comprar por Lista  |
| **Metas/Objetivos** | Permitir que o jogador compre todos os itens de uma lista de decks com integração ao site LigaMagic. |
| **Contexto**        | O jogador possui uma lista pronta e deseja adquirir os decks diretamente, sem buscar um por um no site. |
| **Ator(es)**        | - Jogador Autenticado<br>- Sistema de integração<br>- Fornecedor (LigaMagic) |
| **Recursos**        | - Banco de dados da lista<br>- Mecanismo de matching com catálogo LigaMagic<br>- API/integração para redirecionamento ao carrinho |
| **Exceções**        | - Produto não encontrado.<br>- Indisponibilidade de integração com LigaMagic.<br>|
| **Restrições**      | - Somente listas salvas podem ser compradas.<br>- O processo deve mostrar os itens correspondidos e os não encontrados.<br>- Ter todas cartas disponíveis.  |
| **Episódios**       | 1. Jogador acessa uma lista salva.<br>2. Clica em “Comprar por lista”.<br>3. Exibe resumo com preços, itens indisponíveis e total estimado.<br>4. Jogador confirma e é redirecionado ao carrinho do fornecedor. |

### Cenário 08:Permitir definir um alerta de preço para a carta selecionada
**Requisito Associado:** [RI05] - O sistema deve permitir que defina um alerta de preço para a carta selecionada.

<div align="center"><strong>Tabela 8: Cenário 08</strong></div>

| **Elemento**        | **Descrição**  |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE05    |
| **Título**          | Permitir que o comprador defina um alerta de preço para a carta selecionada  |
| **Metas/Objetivos** | Notificar o comprador quando o preço da carta atingir o valor definido.. |
| **Contexto**        | Local: qualquer lugar onde o usuário possa acessar o aplicativo.
Tempo: em tempo real. |
| **Ator(es)**        | - Jogador Autenticado |
| **Recursos**        | - Smartphone com o app da LigaMagic, conexão com a internet |
| **Exceções**        | - Falta de conexão com a internet.- Valor inválido inserido.- Usuário não está logado em sua conta.|
| **Restrições**      | - Valor do alerta deve estar dentro do limite permitido pelo sistema.<br>- Apenas cartas existentes na plataforma podem ter alertas definidos.  |
| **Episódios**       |1. Comprador decide acompanhar o preço de uma carta.<br>2. Abre o aplicativo.<br>3. Realiza login, caso ainda não esteja autenticado.<br>4. Acessa a busca ou lista de cartas.<br>5. Localiza a carta desejada.<br>6. Abre a página detalhada da carta.<br>7. Clica no botão “Definir alerta”.<br>8. Insere o valor desejado para o alerta.<br>9. Sistema valida o valor informado.<br>10. Sistema confirma a criação do alerta.<br> |

Fonte: [Vera Lucia](https://github.com/verabelucia), 2025

### Cenário 09:Permitir reporte problemas relacionados à carta ou anúncios
**Requisito Associado:** [RI07] - O sistema deve permitir que defina um alerta de preço para a carta selecionada.

<div align="center"><strong>Tabela 9: Cenário 09</strong></div>

| **Elemento**        | **Descrição**  |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE07    |
| **Título**          | Permitir que reporte problemas relacionados à carta ou anúncios  |
| **Metas/Objetivos** | Permitir que o comprador comunique erros ou irregularidades encontradas em cartas ou anúncios |
| **Contexto**        |  Local: qualquer lugar onde o usuário possa acessar o aplicativo.<br>Tempo: Em tempo real|
| **Ator(es)**        | - Comprador  Autenticado|
| **Recursos**        | - Smartphone com o app da LigaMagic, conexão com a internet |
| **Exceções**        | - Falta de conexão com a internet.- Valor inválido inserido.- Usuário não está logado em sua conta.|
| **Restrições**      | O comprador deve selecionar um tipo de problema antes de enviar.<br>- O comprador deve descrever o problema antes de enviar. |.  |
| **Episódios**       |1. Usuário identifica um possível erro ou anúncio suspeito.<br>2. Abre o aplicativo.<br>3. Realiza login, se necessário.<br>4. Acessa a página da carta.<br>5. Clica em “Reportar problema”.<br>6. Sistema apresenta opções de tipos de problema.<br>7. Usuário seleciona o tipo adequado.<br>8. Descreve o problema em detalhes.<br>9. Envia o reporte.<br>10. Sistema registra o reporte e confirma o envio ao usuário.<br> |

Fonte: [Vera Lucia](https://github.com/verabelucia), 2025



## Bibliografia

BARBOSA, S. D. J.; SILVA, B. S. da; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## Nível de Contribuição dos Integrantes

| Nome | % de Contribuição |
| :--- | :---------------: |
|   Marcelo   |          14,29%         |
|   Raissa   |          14,29%         |
|   Vera   |          14,29%         |

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
| :----: | :--: | :-------- | :-------: | :-----: |
|    1.0    |   08/10/2025   |     Adição de cenários      |   Marcelo     |     Raissa    |
|    1.1    |   09/10/2025   |     Adição de cenários  05, 06 e 07    |   Raissa    |   Vera      |
|    1.2    |   09/10/2025   |     Adição de cenários 08 e09          |    Vera     |   Raissa    |

