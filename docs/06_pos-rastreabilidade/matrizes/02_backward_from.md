# Backward-from

## Descrição
Este artefato documenta a rastreabilidade backward-from, detalhando as conexões entre os requisitos e suas origens. A rastreabilidade backward-from (para trás, a partir de) refere-se ao processo de conectar cada requisito às suas respectivas fontes. De modo geral, a rastreabilidade de requisitos é uma característica essencial em sistemas, na qual os requisitos são claramente ligados tanto às suas fontes quanto aos artefatos criados durante o ciclo de vida de desenvolvimento. (SAYÃO; LEITE, 2005).
## Objetivo
Examinar e documentar o processo de rastreabilidade backward-from, destacando como os requisitos do sistema são sistematicamente associados às suas origens. Isso permite descobrir quem sugeriu o requisito (a fonte), por que o requisito existe (o rationale) e quais outros requisitos estão relacionados a ele.
## Metodologia
A abordagem backward-from foca em estabelecer conexões claras entre os requisitos e suas fontes. O processo  é dividido em três etapas principais:




* Definição do Modelo: Nesta etapa inicial, são definidas as entidades a serem rastreadas (requisitos e suas fontes, como documentos, stakeholders ou atas de reuniões) e os tipos de relacionamentos. Também são selecionadas ferramentas de apoio para o registro, como Matrizes de Rastreabilidade ou RichPictures.





* Execução do Rastreamento: Os vínculos entre os requisitos e suas fontes são explicitamente registrados. Isso é geralmente realizado por meio do preenchimento da matriz de rastreabilidade, documentando a origem e a justificativa (rationale) de cada requisito.



* Utilização e Manutenção: As informações de rastreabilidade são utilizadas para consultar a origem dos requisitos , apoiar a análise de impacto de mudanças e auxiliar na resolução de requisitos em conflito, ao permitir a identificação das fontes. É fundamental manter esses vínculos atualizados caso haja alterações nas entidades ou nos próprios relacionamentos.
## Conteúdo

### Legenda

- ADx - Analise de Documentos
- OBSx - Observação
- RFNIx - Requisitos Funcionais Não Implementados
- RNFNIx - Requisitos Não Funcionais Não Implementados

### Requisitos Funcionais

|   ID   | Requisito                                      |          Categoria          | Descrição                                                                                                                          | Fonte                                                           |
| :----: | :--------------------------------------------- | :-------------------------: | :--------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------- |
|  RF01  | Permitir cadastro de usuário                   |  Gerenciamento de Usuários  | O sistema deve permitir que um novo usuário crie uma nova conta                                                                    | [AD01](../../03_elicitacao/tecnicas/analise_documentos.md#ad01) |
|  RF02  | Verificar duplicação de cadastros              |  Gerenciamento de Usuários  | O sistema deve verificar se já existe um cadastro para o usuário que está tentando fazer cadastro                                  | [AD02](../../03_elicitacao/tecnicas/analise_documentos.md#ad02) |
|  RF03  | Permitir acesso via login e senha              |  Autenticação e Segurança   | O sistema deve permitir que o usuário acesse sua conta utilizando login e senha cadastrados                                        | [AD03](../../03_elicitacao/tecnicas/analise_documentos.md#ad03) |
|  RF04  | Restringir anúncios a produtos de Magic        | Gestão de Produtos/Serviços | O sistema deve restringir anúncios a produtos e serviços relacionados ao jogo Magic: The Gathering                                 | [AD04](../../03_elicitacao/tecnicas/analise_documentos.md#ad04) |
|  RF05  | Verificar veracidade de dados cadastrados      |  Autenticação e Segurança   | O sistema deve implementar mecanismos de validação de informações fornecidas pelos usuários                                        | [AD05](../../03_elicitacao/tecnicas/analise_documentos.md#ad05) |
|  RF06  | Incluir textos, descrição e fotos nos anúncios |     Gestão de Anúncios      | O sistema deve permitir que usuários insiram descrições detalhadas e imagens em seus anúncios                                      | [AD06](../../03_elicitacao/tecnicas/analise_documentos.md#ad06) |
|  RF07  | Facilitar contato direto com usuário           |         Comunicação         | O sistema deve disponibilizar meios de contato direto (chat ou mensagens) entre usuários                                           | [AD07](../../03_elicitacao/tecnicas/analise_documentos.md#ad07) |
|  RF08  | Implementar cobrança de anúncios e venda       |      Gestão Financeira      | O sistema deve permitir a cobrança de taxas sobre anúncios ou vendas realizadas pela plataforma                                    | [AD08](../../03_elicitacao/tecnicas/analise_documentos.md#ad08) |
|  RF09  | Permitir troca de mensagens privadas           |         Comunicação         | O sistema deve permitir que usuários troquem mensagens privadas de forma segura                                                    | [AD09](../../03_elicitacao/tecnicas/analise_documentos.md#ad09) |
|  RF10  | Permitir criação de páginas pessoais           |  Gerenciamento de Usuários  | O sistema deve permitir que cada usuário personalize e mantenha sua página pessoal/profissional                                    | [AD10](../../03_elicitacao/tecnicas/analise_documentos.md#ad10) |
|  RF11  | Enviar e responder mensagens no fórum          |   Comunicação Comunitária   | O sistema deve possibilitar a participação dos usuários em fóruns de discussão (postagem e resposta)                               | [AD11](../../03_elicitacao/tecnicas/analise_documentos.md#ad11) |
|  RF12  | Registrar dados pessoais do usuário            |  Gerenciamento de Usuários  | O sistema deve permitir o registro de dados como Nome, RG, CPF, Telefone, E-mail, Data de Nascimento e Endereço                    | [AD12](../../03_elicitacao/tecnicas/analise_documentos.md#ad12) |
|  RF13  | Utilizar dados para finalidades específicas    |     Gestão de Serviços      | O sistema deve usar os dados pessoais para identificação, contato, gestão contratual, melhoria de serviços e envio de comunicações | [AD13](../../03_elicitacao/tecnicas/analise_documentos.md#ad13) |
|  RF14  | Compartilhar dados com parceiros               |     Gestão de Serviços      | O sistema deve possibilitar o compartilhamento de dados pessoais com parceiros, respeitando finalidades declaradas                 | [AD14](../../03_elicitacao/tecnicas/analise_documentos.md#ad14) |
|  RF15  | Garantir direitos de titulares                 |  Gerenciamento de Usuários  | O sistema deve permitir que o usuário solicite acesso, correção, exclusão ou anonimização de seus dados pessoais                   | [AD15](../../03_elicitacao/tecnicas/analise_documentos.md#ad15) |
|  RF16  | Oferecer canal de contato para solicitações    |    Suporte e Atendimento    | O sistema deve disponibilizar canal (e-mail ou link) para o exercício dos direitos do titular                                      | [AD16](../../03_elicitacao/tecnicas/analise_documentos.md#ad16) |
|  RF17  | Utilizar cookies para personalização           |       Personalização        | O sistema deve utilizar cookies para facilitar login e personalizar a experiência de navegação                                     | [AD17](../../03_elicitacao/tecnicas/analise_documentos.md#ad17) |
|  RF18  | Permitir controle de cookies                   |       Personalização        | O sistema deve permitir que o usuário configure seu navegador para aceitar ou bloquear cookies                                     | [AD18](../../03_elicitacao/tecnicas/analise_documentos.md#ad18) |
|  RF19  | Solicitar atualização de dados pessoais        |  Gerenciamento de Usuários  | O sistema deve permitir que o usuário atualize seus dados pessoais e comunique alterações                                          | [AD19](../../03_elicitacao/tecnicas/analise_documentos.md#ad19) |
|  RF20  | Pesquisar cartas pelo nome                     |    Pesquisa e Filtragem     | Permitir que o usuário pesquise cartas pelo nome                                                                                   | [OBS01](../../03_elicitacao/tecnicas/observacao.md#obs01)       |
| RF21.1 | Filtrar cartas                                 |    Pesquisa e Filtragem     | Permitir que o usuário filtre cartas por preço                                                                                     | [OBS02](../../03_elicitacao/tecnicas/observacao.md#obs02)       |
| RF21.2 | Filtrar cartas                                 |    Pesquisa e Filtragem     | Permitir que o usuário filtre cartas por condição                                                                                  | [OBS02](../../03_elicitacao/tecnicas/observacao.md#obs02)       |
| RF21.3 | Filtrar cartas                                 |    Pesquisa e Filtragem     | Permitir que o usuário filtre cartas por idioma                                                                                    | [OBS02](../../03_elicitacao/tecnicas/observacao.md#obs02)       |
|  RF22  | Exibir resultados da pesquisa                  |    Pesquisa e Filtragem     | Mostrar preço, condição, idioma e reputação do vendedor ao pesquisar uma carta                                                     | [OBS03](../../03_elicitacao/tecnicas/observacao.md#obs03)       |
|  RF23  | Realizar compra                                |      Compra de Cartas       | Permitir que o usuário compre cartas cadastradas, incluindo dados pessoais e endereço de entrega                                   | [OBS04](../../03_elicitacao/tecnicas/observacao.md#obs04)       |
|  RF24  | Histórico de compras                           |  Gerenciamento de Usuários  | Permitir que o usuário acesse seu histórico de compras com informações detalhadas                                                  | [OBS05](../../03_elicitacao/tecnicas/observacao.md#obs05)       |
|  RF25  | Visualizar decks                               |    Interação com Cartas     | Permitir que o usuário visualize decks publicados, com lista de cartas                                                             | [OBS06](../../03_elicitacao/tecnicas/observacao.md#obs06)       |
|  RF26  | Fórum                                          |   Interação com Usuários    | Permitir que o usuário busque tópicos, leia, responda e crie postagens no fórum                                                    | [OBS07](../../03_elicitacao/tecnicas/observacao.md#obs07)       |
|  RF27  | Detalhar carta                                 |    Interação com Cartas     | Permitir que o usuário visualize detalhes de uma carta ao clicar no resultado da pesquisa                                          | [OBS08](../../03_elicitacao/tecnicas/observacao.md#obs08)       |
|  RF28  | Adicionar a listas                             |  Gerenciamento de Usuários  | Permitir que o usuário adicione cartas à lista de desejos, carrinho ou coleção                                                     | [OBS09](../../03_elicitacao/tecnicas/observacao.md#obs09)       |
|  RF29  | Avaliar ou dar feedback                        |   Interação com Usuários    | Permitir que o usuário avalie ou dê feedback sobre vendedores ou decks                                                             | [OBS10](../../03_elicitacao/tecnicas/observacao.md#obs10)       |
|  RF30  | Mostrar informações detalhadas da carta        |    Interação com Cartas     | Mostrar edição, idioma, condição e preço médio de cada carta                                                                       | [OBS11](../../03_elicitacao/tecnicas/observacao.md#obs11)       |
|  RF31  | Definir alerta de preço                        |    Relatórios e Alertas     | Permitir que o usuário defina um alerta de preço para a carta selecionada                                                          | [OBS12](../../03_elicitacao/tecnicas/observacao.md#obs12)       |
|  RF32  | Buscar decks relacionados                      |    Interação com Cartas     | Permitir que o usuário busque decks que utilizam a carta selecionada                                                               | [OBS13](../../03_elicitacao/tecnicas/observacao.md#obs13)       |
|  RF33  | Visualizar preço médio por edição              |    Relatórios e Alertas     | Permitir que o usuário visualize o preço médio da carta em diferentes edições e condições                                          | [OBS14](../../03_elicitacao/tecnicas/observacao.md#obs14)       |
|  RF34  | Acessar histórico de preços                    |    Relatórios e Alertas     | Permitir que o usuário acesse o histórico de preços da carta em formato gráfico                                                    | [OBS15](../../03_elicitacao/tecnicas/observacao.md#obs15)       |
|  RF35  | Adicionar a diferentes listas                  |  Gerenciamento de Usuários  | Permitir que o usuário adicione a carta a diferentes listas (coleção, deck, lista de desejos, carrinho)                            | [OBS16](../../03_elicitacao/tecnicas/observacao.md#obs16)       |
|  RF36  | Compartilhar carta                             |   Interação com Usuários    | Permitir que o usuário compartilhe informações da carta em redes sociais ou por link direto                                        | [OBS17](../../03_elicitacao/tecnicas/observacao.md#obs17)       |
|  RF37  | Reportar problemas                             |   Interação com Usuários    | Permitir que o usuário reporte problemas relacionados à carta (erros de informação, anúncios suspeitos, etc.)                      | [OBS18](../../03_elicitacao/tecnicas/observacao.md#obs18)       |

**Fonte:** Samuel, 2025

### Requisitos Não Funcionais

|  ID   | Requisito                                          |        Categoria        | Descrição                                                                                                                                                                                    | Fonte                                                           |
| :---: | :------------------------------------------------- | :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------- |
| RNF01 | Cumprir legislações aplicáveis                     |   Legal e Regulatório   | O sistema deve cumprir a LGPD (Lei nº 13.709/2018), o Código de Defesa do Consumidor e demais legislações aplicáveis                                                                         | [AD20](../../03_elicitacao/tecnicas/analise_documentos.md#ad20) |
| RNF02 | Adotar medidas de segurança                        | Segurança da Informação | O sistema deve implementar padrões de segurança e privacidade alinhados às diretrizes do Banco Central do Brasil                                                                             | [AD21](../../03_elicitacao/tecnicas/analise_documentos.md#ad21) |
| RNF03 | Definir procedimentos para incidentes de segurança | Segurança da Informação | O sistema deve prever ações em caso de incidente ou vazamento de dados pessoais                                                                                                              | [AD22](../../03_elicitacao/tecnicas/analise_documentos.md#ad22) |
| RNF04 | Notificar alterações de política                   |      Transparência      | O sistema deve informar os usuários sobre mudanças relevantes na política com antecedência razoável                                                                                          | [AD23](../../03_elicitacao/tecnicas/analise_documentos.md#ad23) |
| RNF05 | Exigir consentimento e concordância explícita      |   Legal e Regulatório   | O sistema deve garantir que o usuário declare ciência e concordância com a política ao usar o portal                                                                                         | [AD24](../../03_elicitacao/tecnicas/analise_documentos.md#ad24) |
| RNF06 | Atualização do sistema                             |     Disponibilidade     | O sistema deve suportar alterações na configuração ou apresentação sem interromper o uso                                                                                                     | [AD25](../../03_elicitacao/tecnicas/analise_documentos.md#ad25) |
| RNF07 | Informações legais e tributárias                   |   Legal e Regulatório   | Garantir que anúncios incluam informações fiscais corretas                                                                                                                                   | [AD26](../../03_elicitacao/tecnicas/analise_documentos.md#ad26) |
| RNF08 | Responsividade                                     |       Usabilidade       | O site deve ser totalmente responsivo, garantindo boa visualização e funcionalidade em computador, tablet e smartphone                                                                       | [OBS19](../../03_elicitacao/tecnicas/observacao.md#obs19)       |
| RNF09 | Organização visual                                 |       Usabilidade       | As informações sobre cartas, anúncios e decks devem ser organizadas de forma clara, com boa legibilidade e espaçamento adequado, facilitando a navegação                                     | [OBS20](../../03_elicitacao/tecnicas/observacao.md#obs20)       |
| RNF10 | Tempo de resposta para busca                       |       Performance       | O sistema deve retornar resultados de busca em no máximo 3 segundos                                                                                                                          | [OBS21](../../03_elicitacao/tecnicas/observacao.md#obs21)       |
| RNF11 | Disponibilidade                                    |     Confiabilidade      | O sistema deve estar disponível 99,5% do tempo                                                                                                                                               | [OBS22](../../03_elicitacao/tecnicas/observacao.md#obs22)       |
| RNF12 | Compatibilidade com navegadores                    |     Compatibilidade     | A plataforma deve ser compatível com as versões mais recentes dos principais navegadores (Chrome, Firefox, Edge e Safari), em desktop e dispositivos móveis                                  | [OBS23](../../03_elicitacao/tecnicas/observacao.md#obs23)       |
| RNF13 | Segurança de dados                                 | Segurança da Informação | O sistema deve criptografar todas as informações sensíveis dos usuários                                                                                                                      | [OBS24](../../03_elicitacao/tecnicas/observacao.md#obs24)       |
| RNF14 | Padronização de mensagens                          |       Usabilidade       | As mensagens de alerta, erro e confirmação devem aparecer de forma padronizada e visível, para evitar confusões                                                                              | [OBS25](../../03_elicitacao/tecnicas/observacao.md#obs25)       |
| RNF15 | Backup de dados                                    |     Confiabilidade      | O sistema deve realizar backup automático dos dados a cada 24 horas                                                                                                                          | [OBS26](../../03_elicitacao/tecnicas/observacao.md#obs26)       |
| RNF16 | Escalabilidade                                     |       Performance       | O sistema deve suportar um aumento de 50% no número de usuários simultâneos sem degradação significativa de performance                                                                      | [OBS27](../../03_elicitacao/tecnicas/observacao.md#obs27)       |
| RNF17 | Armazenamento e retenção                           |   Governança de Dados   | O documento não informa por quanto tempo os dados pessoais serão armazenados nem os critérios para definição desse prazo                                                                     | [AD27](../../03_elicitacao/tecnicas/analise_documentos.md#ad27) |
| RNF18 | Procedimentos para incidentes                      | Segurança da Informação | O documento não prevê ou detalha os procedimentos a serem adotados em caso de incidente de segurança ou vazamento de dados                                                                   | [AD28](../../03_elicitacao/tecnicas/analise_documentos.md#ad28) |
| RNF19 | Base legal específica                              |   Legal e Regulatório   | O documento afirma o cumprimento da LGPD, mas não explica claramente a base legal específica (ex.: consentimento, contrato, legítimo interesse) para cada finalidade de tratamento declarada | [AD29](../../03_elicitacao/tecnicas/analise_documentos.md#ad29) |

**Fonte:** Samuel, 2025

## Referências

<a id="PRESSMAN"></a>
> 1. SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. *Rastreabilidade de Requisitos*. Monografias em Ciência da Computação, n° 20/05. 2005.


## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição |
| :----- | :---------------: |
| Samuel |                   |
| Thiago |                   |

## Histórico de versão

| Versão |    Data    | Descrição                    | Autor(es) | Revisor |
| :----: | :--------: | :--------------------------- | :-------: | :-----: |
|  1.0   | 23/10/2025 | Criação inicial do documento |  Samuel   |    -    |
|  1.1   | 24/10/2025 | Edição inicial do documento |  Thiago   |    Samuel    |
