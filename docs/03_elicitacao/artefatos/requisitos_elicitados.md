# Requisitos Elicitados

## Introdução

Este documento consolida todos os requisitos funcionais e não funcionais identificados através das diferentes técnicas de elicitação aplicadas no projeto LigaMagic. O objetivo é fornecer uma visão unificada de todos os requisitos levantados, facilitando a rastreabilidade, análise e priorização.

## Técnicas de Elicitação Utilizadas

As seguintes técnicas de elicitação foram aplicadas para identificar os requisitos:

- **[Análise de Documentos](../tecnicas/analise_documentos.md)**: Análise dos Termos e Condições Gerais de Uso e Política de Proteção de Dados Pessoais
- **[Observação](../tecnicas/observacao.md)**: Observação do comportamento dos usuários na plataforma
- **[Entrevista](../tecnicas/entrevista.md)**: Entrevistas com usuários da plataforma
- **[Glossário](glossario.md)**: Definição de termos específicos do domínio

## Requisitos Funcionais Consolidados

### RF01 - RF19: Requisitos da Análise de Documentos {#rf01---rf19-requisitos-da-analise-de-documentos}

|      ID      | Requisitos                                                       |          Categoria          | Descrição                                                                                                                           | Fonte                                                      |
| :----------: | :--------------------------------------------------------------- | :-------------------------: | :---------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------- |
|  RF1 {#rf1}  | Permitir Cadastro de usuário                                     |  Gerenciamento de Usuários  | O sistema deve permitir que um novo usuário crie uma nova conta                                                                     | [Análise de Documentos](../tecnicas/analise_documentos.md) |
|  RF2 {#rf2}  | Deve verificar duplicação de cadastros                           |  Gerenciamento de Usuário   | O sistema deve verificar se já existe um cadastro para o usuario que está tentando fazer cadadastro                                 | [Análise de Documentos](../tecnicas/analise_documentos.md) |
|  RF3 {#rf3}  | Deve permitir acesso via login e senha                           |  Autenticação e Segurança   | O sistema deve permitir que o usuário acesse sua conta utilizando login e senha cadastrados                                         | [Análise de Documentos](../tecnicas/analise_documentos.md) |
|  RF4 {#rf4}  | Deve permitir apenas produtos relacionados a Magic               | Gestão de Produtos/Serviços | O sistema deve restringir anúncios a produtos e serviços relacionados ao jogo Magic: The Gathering                                  | [Análise de Documentos](../tecnicas/analise_documentos.md) |
|  RF5 {#rf5}  | Deve verificar veracidade de dados cadastrados                   |  Autenticação e Segurança   | O sistema deve implementar mecanismos de validação de informações fornecidas pelos usuários                                         | [Análise de Documentos](../tecnicas/analise_documentos.md) |
|  RF6 {#rf6}  | Deve permitir inclusão de textos, descrição e fotos nos anúncios |     Gestão de Anúncios      | O sistema deve permitir que usuários insiram descrições detalhadas e imagens em seus anúncios                                       | [Análise de Documentos](../tecnicas/analise_documentos.md) |
|  RF7 {#rf7}  | Deve facilitar contato direto com usuário                        |         Comunicação         | O sistema deve disponibilizar meios de contato direto (chat ou mensagens) entre usuários                                            | [Análise de Documentos](../tecnicas/analise_documentos.md) |
|  RF8 {#rf8}  | Deve implemetar cobrança de anúncios e venda                     |      Gestão Financeira      | O sistema deve permitir a cobrança de taxas sobre anúncios ou vendas realizadas pela plataforma                                     | [Análise de Documentos](../tecnicas/analise_documentos.md) |
|  RF9 {#rf9}  | Deve permitir troca de mensagens privadas                        |         Comunicação         | O sistema deve permitir que usuários troquem mensagens privadas de forma segura                                                     | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RF10 {#rf10} | Deve permitir criação de páginas pessoais                        |  Gerenciamento de Usuários  | O sistema deve permitir que cada usuário personalize e mantenha sua página pessoal/profissional                                     | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RF11 {#rf11} | Deve permitir envio e respostas a mensagens no fórum             |   Comunicação Comunitária   | O sistema deve possibilitar a participação dos usuários em fóruns de discussão (postagem e resposta)                                | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RF12 {#rf12} | Registrar dados pessoais do usuário                              |  Gerenciamento de Usuários  | O sistema deve permitir o registro de dados como Nome, RG, CPF, Telefone, E-mail, Data de Nascimento e Endereço.                    | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RF13 {#rf13} | Utilizar dados para finalidades específicas                      |     Gestão de Serviços      | O sistema deve usar os dados pessoais para identificação, contato, gestão contratual, melhoria de serviços e envio de comunicações. | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RF14 {#rf14} | Compartilhar dados com parceiros                                 |     Gestão de Serviços      | O sistema deve possibilitar o compartilhamento de dados pessoais com parceiros, respeitando finalidades declaradas.                 | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RF15 {#rf15} | Garantir direitos de titulares                                   |  Gerenciamento de Usuários  | O sistema deve permitir que o usuário solicite acesso, correção, exclusão ou anonimização de seus dados pessoais.                   | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RF16 {#rf16} | Oferecer canal de contato para solicitações                      |    Suporte e Atendimento    | O sistema deve disponibilizar canal (e-mail ou link) para o exercício dos direitos do titular.                                      | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RF17 {#rf17} | Utilizar cookies para personalização                             |       Personalização        | O sistema deve utilizar cookies para facilitar login e personalizar a experiência de navegação.                                     | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RF18 {#rf18} | Permitir controle de cookies                                     |       Personalização        | O sistema deve permitir que o usuário configure seu navegador para aceitar ou bloquear cookies.                                     | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RF19 {#rf19} | Solicitar atualização de dados pessoais                          |  Gerenciamento de Usuários  | O sistema deve permitir que o usuário atualize seus dados pessoais e comunicar alterações.                                          | [Análise de Documentos](../tecnicas/analise_documentos.md) |

### RF20 - RF37: Requisitos da Observação {#rf20---rf37-requisitos-da-observacao}

|      ID      | Requisitos                      |        Categoria         | Descrição                                                                                                     | Fonte                                   |
| :----------: | :------------------------------ | :----------------------: | :------------------------------------------------------------------------------------------------------------ | :-------------------------------------- |
| RF20 {#rf20} | Pesquisa de cartas pelo nome    |   Pesquisa e Filtragem   | Permitir que o usuário pesquise cartas pelo                                                                   | [Observação](../tecnicas/observacao.md) |
| RF21 {#rf21} | Filtrar cartas                  |   Pesquisa e Filtragem   | Permitir que o usuário filtre cartas por preço, condição e idioma                                             | [Observação](../tecnicas/observacao.md) |
| RF22 {#rf22} | Exibir resultados da pesquisa   |   Pesquisa e Filtragem   | Mostrar preço, condição, idioma e reputação do vendedor ao pesquisar uma carta                                | [Observação](../tecnicas/observacao.md) |
| RF23 {#rf23} | Realizar compra                 |     Compra de Cartas     | Permitir que o usuário compre cartas cadastradas, incluindo dados pessoais e endereço de entrega              | [Observação](../tecnicas/observacao.md) |
| RF24 {#rf24} | Histórico de compras            | Gerenciamento de Usuário | Permitir que o usuário acesse seu histórico de compras com informações detalhadas                             | [Observação](../tecnicas/observacao.md) |
| RF25 {#rf25} | Visualizar decks                |   Interação com Cartas   | Permitir que o usuário visualize decks publicados, com lista de cartas                                        | [Observação](../tecnicas/observacao.md) |
| RF26 {#rf26} | Fórum                           |  Interação com Usuários  | Permitir que o usuário busque tópicos, leia, responda e crie postagens no fórum                               | [Observação](../tecnicas/observacao.md) |
| RF27 {#rf27} | Detalhes da carta               |   Interação com Cartas   | Permitir que o usuário visualize detalhes de uma carta ao clicar no resultado da pesquisa                     | [Observação](../tecnicas/observacao.md) |
| RF28 {#rf28} | Adicionar a listas              | Gerenciamento de Usuário | Permitir que o usuário adicione cartas à lista de desejos, carrinho ou coleção                                | [Observação](../tecnicas/observacao.md) |
| RF29 {#rf29} | Avaliar ou dar feedback         |  Interação com Usuários  | Permitir que o usuário avalie ou dê feedback sobre vendedores ou decks                                        | [Observação](../tecnicas/observacao.md) |
| RF30 {#rf30} | Informações detalhadas da carta |   Interação com Cartas   | Mostrar edição, idioma, condição e preço médio de cada carta                                                  | [Observação](../tecnicas/observacao.md) |
| RF31 {#rf31} | Alerta de preço                 |   Relatórios e Alertas   | Permitir que o usuário defina um alerta de preço para a carta selecionada                                     | [Observação](../tecnicas/observacao.md) |
| RF32 {#rf32} | Buscar decks relacionados       |   Interação com Cartas   | Permitir que o usuário busque decks que utilizam a carta selecionada                                          | [Observação](../tecnicas/observacao.md) |
| RF33 {#rf33} | Preço médio por edição          |   Relatórios e Alertas   | Permitir que o usuário visualize o preço médio da carta em diferentes edições e condições                     | [Observação](../tecnicas/observacao.md) |
| RF34 {#rf34} | Histórico de preços             |   Relatórios e Alertas   | Permitir que o usuário acesse o histórico de preços da carta em formato gráfico                               | [Observação](../tecnicas/observacao.md) |
| RF35 {#rf35} | Adicionar a diferentes listas   | Gerenciamento de Usuário | Permitir que o usuário adicione a carta a diferentes listas (coleção, deck, lista de desejos, carrinho)       | [Observação](../tecnicas/observacao.md) |
| RF36 {#rf36} | Compartilhar carta              |  Interação com Usuários  | Permitir que o usuário compartilhe informações da carta em redes sociais ou por link direto                   | [Observação](../tecnicas/observacao.md) |
| RF37 {#rf37} | Reportar problemas              |  Interação com Usuários  | Permitir que o usuário reporte problemas relacionados à carta (erros de informação, anúncios suspeitos, etc.) | [Observação](../tecnicas/observacao.md) |

## Requisitos Não Funcionais Consolidados

### RNF01 - RNF07: Requisitos da Análise de Documentos {#rnf01---rnf07-requisitos-da-analise-de-documentos}

|       ID       | Requisitos                                         |        Categoria        | Descrição                                                                                                             | Fonte                                                      |
| :------------: | :------------------------------------------------- | :---------------------: | :-------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------- |
| RNF01 {#rnf01} | Cumprir legislações aplicáveis                     |   Legal e Regulatório   | O sistema deve cumprir a LGPD (Lei nº 13.709/2018), o Código de Defesa do Consumidor e demais legislações aplicáveis. | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RNF02 {#rnf02} | Adotar medidas de segurança                        | Segurança da Informação | O sistema deve implementar padrões de segurança e privacidade alinhados às diretrizes do Banco Central do Brasil.     | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RNF03 {#rnf03} | Definir procedimentos para incidentes de segurança | Segurança da Informação | O sistema deve prever ações em caso de incidente ou vazamento de dados pessoais.                                      | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RNF04 {#rnf04} | Notificar alterações de política                   |      Transparência      | O sistema deve informar os usuários sobre mudanças relevantes na política com antecedência razoável.                  | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RNF05 {#rnf05} | Exigir consentimento e concordância explícita      |   Legal e Regulatório   | O sistema deve garantir que o usuário declare ciência e concordância com a política ao usar o portal.                 | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RNF06 {#rnf06} | Atualização do Sistema                             |     Disponibilidade     | O sistema deve suportar alterações na configuração ou apresentação sem interromper o uso                              | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| RNF07 {#rnf07} | Informações Legais e Tributárias                   |     Confiabilidade      | Garantir que anúncios incluam informações fiscais corretas                                                            | [Análise de Documentos](../tecnicas/analise_documentos.md) |

### RNF08 - RNF16: Requisitos da Observação {#rnf08---rnf16-requisitos-da-observacao}

|       ID       | Requisitos                                  |       Categoria        | Descrição                                                                                                                                                                                                                         | Fonte                                   |
| :------------: | :------------------------------------------ | :--------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------- |
| RNF08 {#rnf08} | Responsividade                              |      Usabilidade      | O site deve ser totalmente responsivo, garantindo boa visualização e funcionalidade em computador, tablet e smartphone                                                                                                            | [Observação](../tecnicas/observacao.md) |
| RNF09 {#rnf09} | Organização visual                          |      Usabilidade      | As informações sobre cartas, anúncios e decks devem ser organizadas de forma clara, com boa legibilidade e espaçamento adequado, facilitando a navegação                                                                         | [Observação](../tecnicas/observacao.md) |
| RNF10 {#rnf10} | Tempo de resposta para busca               |      Performance       | O sistema deve retornar resultados de busca em no máximo 3 segundos                                                                                                                                                              | [Observação](../tecnicas/observacao.md) |
| RNF11 {#rnf11} | Disponibilidade                            |     Confiabilidade     | O sistema deve estar disponível 99,5% do tempo                                                                                                                                                                                   | [Observação](../tecnicas/observacao.md) |
| RNF12 {#rnf12} | Compatibilidade com navegadores            |   Compatibilidade     | A plataforma deve ser totalmente compatível com as versões mais recentes dos principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge e Safari), tanto em desktop quanto em dispositivos móveis | [Observação](../tecnicas/observacao.md) |
| RNF13 {#rnf13} | Segurança de dados                         | Segurança da Informação | O sistema deve criptografar todas as informações sensíveis dos usuários                                                                                                                                                          | [Observação](../tecnicas/observacao.md) |
| RNF14 {#rnf14} | Padronização de mensagens                  |      Usabilidade      | As mensagens de alerta, erro e confirmação devem aparecer de forma padronizada e visível, para evitar confusões                                                                                                                  | [Observação](../tecnicas/observacao.md) |
| RNF15 {#rnf15} | Backup de dados                            |     Confiabilidade     | O sistema deve realizar backup automático dos dados a cada 24 horas                                                                                                                                                              | [Observação](../tecnicas/observacao.md) |
| RNF16 {#rnf16} | Escalabilidade                             |      Performance       | O sistema deve suportar um aumento de 50% no número de usuários simultâneos sem degradação significativa de performance                                                                                                           | [Observação](../tecnicas/observacao.md) |

## Requisitos Não Funcionais Não Implementados

|      ID      | Requisitos                   |          Categoria           | Descrição                                                                                                                                                                                    | Fonte                                                      |
| :----------: | :--------------------------- | :--------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------- |
| NI01 {#ni01} | Armazenamento e Retenção     |    Base Legal Específica     | O documento não informa por quanto tempo os dados pessoais serão armazenados nem os critérios para definição desse prazo.                                                                    | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| NI02 {#ni02} | Procedimento para Incidentes | Procedimento para Incidentes | O documento não prevê ou detalha os procedimentos a serem adotados em caso de incidente de segurança ou vazamento de dados.                                                                  | [Análise de Documentos](../tecnicas/analise_documentos.md) |
| NI03 {#ni03} | Base Legal Específica        |  Parcialmente Implementado   | O documento afirma o cumprimento da LGPD, mas não explica claramente a base legal específica (ex: consentimento, contrato, legítimo interesse) para cada finalidade de tratamento declarada. | [Análise de Documentos](../tecnicas/analise_documentos.md) |

## Matriz de Rastreabilidade

| Técnica de Elicitação                                      | Requisitos Funcionais | Requisitos Não Funcionais | Requisitos Não Funcionais Não Implementados |
| :--------------------------------------------------------- | :-------------------: | :-----------------------: | :-----------------------------------------: |
| [Análise de Documentos](../tecnicas/analise_documentos.md) |      RF01 - RF19      |       RNF01 - RNF07       |                 NI01 - NI03                 |
| [Observação](../tecnicas/observacao.md)                    |      RF20 - RF37      |       RNF08 - RNF16       |                      -                      |

## Resumo Quantitativo

- **Total de Requisitos Funcionais**: 37
- **Total de Requisitos Não Funcionais**: 16
- **Total de Requisitos Não Funcionais Não Implementados**: 3
- **Total Geral**: 56 requisitos
- **[Requisitos Não Implementados no App](requisitos_nao_implementados.md)**: 15

## Bibliografia

> 1. LIGAMAGIC. _Termos e condições gerais de uso_. Disponível em: https://www.ligamagic.com.br/?view=contrato. Acesso em: 24/09/2025.
> 2. LIGAMAGIC. _Política de proteção de dados pessoais_. Disponível em: https://www.ligamagic.com.br/?view=privacidade. Acesso em: 25/09/2025.
> 3. Site LigaMagic. Disponível em: https://www.ligamagic.com.br/ Acesso em: 26/09/2025.
> 4. **VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira.** _Engenharia de requisitos: software orientado ao negócio._ Disponível em: [Aprender3](https://aprender3.unb.br/pluginfile.php/3210603/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf)

## Histórico de versão

| Versão |    Data    | Descrição                                      |                    Autor                    |                   Revisor                    |
| :----: | :--------: | :--------------------------------------------- | :-----------------------------------------: | :------------------------------------------: |
|  1.0   | 04/10/2025 | Criação do documento consolidado de requisitos | [Samuel](https://github.com/samuelncaetano) | [Vera Lucia](https://github.com/verabelucia) |
