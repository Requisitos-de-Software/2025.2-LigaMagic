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
| 3 | 
| 4 | 
| 5 | 
| 6 | 
| 7 | 
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


## Bibliografia

BARBOSA, S. D. J.; SILVA, B. S. da; SILVEIRA, M. S.; GASPARINI, I.; DARIN, T.; BARBOSA, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## Nível de Contribuição dos Integrantes

| Nome | % de Contribuição |
| :--- | :---------------: |
|   Marcelo   |          14,29%         |

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
| :----: | :--: | :-------- | :-------: | :-----: |
|    1.0    |   08/10/2025   |     Adição de cenários      |   Marcelo     |     Raissa    |
