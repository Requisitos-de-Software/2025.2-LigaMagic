# Backlog

## Descrição

O backlog é uma lista organizada de funcionalidades ou requisitos do projeto, priorizados de acordo com o valor que entregam ao cliente. Ele serve como um guia para o que precisa ser desenvolvido, e pode ser atualizado a qualquer momento ao longo do projeto. Os itens do backlog são descritos em diferentes níveis de detalhamento: os temas representam as ideias mais amplas e genéricas, os épicos agrupam funcionalidades relacionadas, e as histórias de usuário detalham ações específicas esperadas pelo usuário final.

## Objetivo

O principal objetivo deste backlog é organizar e priorizar os requisitos do aplicativo LigaMagic de forma estruturada, lógica e orientada à entrega de valor. Essa organização facilita o planejamento do desenvolvimento, permitindo que as funcionalidades mais relevantes sejam entregues primeiro, garantindo uma evolução contínua e alinhada às expectativas dos usuários

## Metodologia



A construção do backlog seguiu uma abordagem iterativa e incremental, partindo dos resultados da fase de elicitação de requisitos.
Inicialmente, foram definidos temas para representar as áreas principais do sistema.
Em seguida, cada tema foi subdividido em épicos, agrupando funcionalidades relacionadas.
Por fim, esses épicos foram detalhados em histórias de usuário, que descrevem de forma clara e prática o que cada tipo de usuário deseja realizar e o valor obtido com isso.

Essa estrutura hierárquica facilita a compreensão do escopo total do projeto, melhora o processo de priorização e contribui para uma entrega gradual e eficiente das funcionalidades, assegurando que as primeiras versões do sistema tragam o maior impacto positivo possível para os usuários da plataforma. 

## Conteúdo

### Tabela de contribuição

| Histórias de Usuário                                                                     |    Autor     |
|:-----------------------------------------------------------------------------------------|:------------:|
|                                                                                          |              |
| [US13](#us13), [US14](#us14), [US15](#us15), [US16](#us16), [US17](#us17), [US18](#us18) |   Marcelo    |
| [US25](#us25), [US26](#us26), [US27](#us27), [US28](#us28), [US29](#us29), [US30](#us30) |    Raissa    |
| [US01](#us01), [US02](#us02), [US03](#us03), [US04](#us04), [US05](#us05), [US06](#us06) |    Samuel    |
| US13, US14, US15, US16, US17, US18                                                       |    Thiago    |                                                                                    
| [US31](#us31), [US32](#us32), [US33](#us33), [US34](#us34), [US35](#us35), [US36](#us36) |     Vera     |
| [US07](#us07), [US08](#us08), [US09](#us09), [US10](#us10), [US11](#us11), [US12](#us12) |   Angélica   |
| [US37](#us37), [US38](#us38), [US39](#us39), [US40](#us40), [US41](#us41), [US42](#us42) |   Guilherme  |

<div align="center"><strong>Tabela 1:</strong> Tabela de contribuição</div>

**Fonte:** Samuel, Thiago 2025

### Estrutura das Histórias de Usuário

O formato padrão para cada história de usuário é:

- **USxx:** Eu, como [tipo de usuário], desejo [ação desejada] para [benefício ou propósito]. _(RFxx)_

### Temas do Backlog

A seguir estão os temas que agrupam as funcionalidades do backlog do produto.

#### Tema 1: Interação Social e Comunidade

Este tema engloba todas as funcionalidades que permitem aos usuários interagir, compartilhar conhecimento e formar uma comunidade dentro do aplicativo.

##### Épico 1.1: Funcionalidades do Fórum

Este épico contém as histórias de usuário relacionadas à criação, visualização e interação com os fóruns de discussão.

<a id="us01"></a>

- [US01](../05_Agil/01_historias_de_usuario.md#us01): Eu, como um jogador iniciante, desejo criar um novo tópico em um fórum para poder tirar dúvidas sobre regras e montagem de decks. [RFNI02](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni02)

##### Épico 1.2: Sistema de Feedback e Reputação

Este épico contém as histórias de usuário focadas na avaliação e reputação dos vendedores dentro da plataforma.

<a id="us13"></a>

- [US13]: Eu, como Comprador, desejo avaliar um vendedor após uma compra concluída para ajudar outros usuários a tomar decisões e fornecer feedback ao vendedor. [RFNI04](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni04)

---

#### Tema 2: Gerenciamento de Cartas e Coleção

Este tema abrange as funcionalidades focadas na busca, visualização e compartilhamento de informações sobre as cartas de _Magic: The Gathering_.

##### Épico 2.1: Ferramentas de Consulta de Cartas

Este épico contém as histórias de usuário relacionadas à interação com o banco de dados de cartas do aplicativo.

[US16](../05_Agil/01_historias_de_usuario.md#us16): Eu, como usuário, desejo visualizar detalhes de uma carta ao clicar no resultado da pesquisa para conhecer mais sobre ela antes de comprar ou trocar. [RF27](../../03_elicitacao/artefatos/requisitos_elicitados.md)

[US17](../05_Agil/01_historias_de_usuario.md#us17): Eu, como usuário, desejo visualizar informações detalhadas de cada carta, incluindo edição, idioma, condição e preço médio, para tomar decisões mais informadas. [RF30](../../03_elicitacao/artefatos/requisitos_elicitados.md)

[US18](../05_Agil/01_historias_de_usuario.md#us18): Eu, como jogador, desejo buscar decks que utilizam a carta selecionada para entender como ela é usada em diferentes estratégias. [RF32](../../03_elicitacao/artefatos/requisitos_elicitados.md)

<a id="us14"></a>

- [US02](../05_Agil/01_historias_de_usuario.md#us02): Eu, como um jogador, desejo compartilhar o link de uma carta específica para poder mostrar a um amigo ou pedir uma opinião de forma rápida e precisa. [RFNI06](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni06)

##### Épico 2.2: Inventário Pessoal de Cartas

Este épico contém as histórias de usuário para o gerenciamento da coleção pessoal do usuário.

[US14](../05_Agil/01_historias_de_usuario.md#us14): Eu, como usuário, desejo filtrar cartas por qualidade e condição para encontrar produtos que atendam melhor às minhas preferências. [RFNI03](../../03_elicitacao/artefatos/requisitos_nao_implementados.md)

<a id="us14"></a>

- [US14]: Eu, como Colecionador, desejo adicionar cartas à minha coleção pessoal para manter um inventário digital do que eu possuo. [RFNI10](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni10)

##### Épico 2.3: Organização de Listas de Cartas

Este épico foca nas ferramentas que permitem ao usuário organizar cartas em diferentes listas funcionais.

[US15](../05_Agil/01_historias_de_usuario.md#us15): Eu, como administrador do sistema, desejo garantir que apenas produtos relacionados a Magic: The Gathering sejam cadastrados na plataforma, para manter a relevância e integridade do conteúdo. [RF04](../../03_elicitacao/artefatos/requisitos_elicitados.md)

<a id="us17"></a>

- [US17]: Eu, como Jogador Logado, desejo poder adicionar uma carta (encontrada na busca) a diferentes listas [RF35](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rf35)

---

#### Tema 3: Gerenciamento de Usuário

Este tema engloba todas as funcionalidades relacionadas ao ciclo de vida do usuário, desde o cadastro até a autenticação e gerenciamento de perfil.

##### Épico 3.1: Cadastro e Autenticação

Este épico contém as histórias de usuário focadas em garantir um processo de registro seguro e sem atritos para novos usuários.

<a id="us03"></a>

- [US03](../05_Agil/01_historias_de_usuario.md#us03): Eu, como um novo usuário, desejo ser informado se meu e-mail já está cadastrado ao tentar criar uma conta para evitar a criação de contas duplicadas e recuperar meu acesso, se necessário. [RF2](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf2)

<a id="us15"></a>

- [US15](../05_Agil/01_historias_de_usuario.md#us15): Eu, como Visitante, desejo me registrar na plataforma fornecendo meus dados pessoais (Nome, E-mail, CPF, etc.) para criar uma conta e acessar as funcionalidades restritas. [RF12](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf12)

<a id="us09"></a>

- [US09](../05_Agil/01_historias_de_usuario.md#us09): Eu, como usuário comprador, desejo realizar meu cadastro na plataforma para acessar os recursos do sistema e salvar minhas informações pessoais de forma segura. [RF1](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf1)

<a id="us10"></a>

- [US10](../05_Agil/01_historias_de_usuario.md#us10): Eu, como usuário comprador, desejo acessar minha conta usando e-mail e senha para visualizar minhas informações e histórico de atividades. [RF3](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf3)

<a id="us16"></a>

- [US16](../05_Agil/01_historias_de_usuario.md#us16): Eu, como Jogador Cadastrado (Vendedor ou Colecionador), desejo personalizar minha página de perfil público com foto e descrição para me apresentar à comunidade. [RF10](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf10)


##### Épico 3.2: Gerenciamento de Perfil e Dados Pessoais
Este épico contém as histórias de usuário relacionadas à atualização e visualização das informações pessoais do usuário.

<a id="us11"></a>

- [US11](../05_Agil/01_historias_de_usuario.md#us11): Eu, como usuário comprador, desejo atualizar meus dados pessoais (como endereço, telefone e e-mail) para manter minhas informações corretas e facilitar futuras compras ou comunicações. [RF19](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf19)

<a id="us12"></a>

- [US12](../05_Agil/01_historias_de_usuario.md#us11): Eu, como usuário comprador, desejo atualizar meus dados pessoais (como endereço, telefone e e-mail) para manter minhas informações corretas e facilitar futuras compras ou comunicações. [RF24](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf24)

---

#### Tema 4: Pesquisa e Filtragem de Cartas

Este tema abrange as funcionalidades centrais de busca, filtragem e visualização de cartas, permitindo que os usuários encontrem produtos de forma eficiente.

##### Épico 4.1: Busca Avançada de Cartas

Este épico contém as histórias de usuário relacionadas à experiência de pesquisa, desde a busca inicial até a aplicação de filtros e a visualização detalhada dos resultados.

<a id="us04"></a>

- [US04](../05_Agil/01_historias_de_usuario.md#us04): Eu, como um jogador, desejo pesquisar cartas pelo nome para encontrar rapidamente suas informações, edições disponíveis e preços de mercado. [RF20](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf20)

<a id="us05"></a>

- [US05](../05_Agil/01_historias_de_usuario.md#us05): Eu, como um comprador, desejo filtrar os resultados da busca de cartas por preço, condição (ex: Nova, Usada) e idioma para encontrar ofertas que atendam exatamente às minhas necessidades e orçamento. [RF21](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf21)

<a id="us06"></a>

- [US06](../05_Agil/01_historias_de_usuario.md#us06): Eu, como um comprador, desejo ver o preço, a condição, o idioma e a reputação do vendedor diretamente na lista de resultados da pesquisa para poder comparar as opções disponíveis de forma eficiente, sem precisar clicar em cada item. [RF22](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf22)


<a id="us08"></a>

- [US08](../05_Agil/01_historias_de_usuario.md#us08) : Eu, como usuário comprador, desejo realizar buscas por cartas específicas de forma eficiente e intuitiva, para encontrar rapidamente as cartas que desejo adquirir. [RFNI15](../../03_elicitacao/artefatos/requisitos_elicitados.md#rfni15)

##### Épico 4.2: Lista de Desejos (Wishlist)
Este épico contém as histórias de usuário relacionadas ao gerenciamento da lista de desejos, permitindo que o usuário salve cartas de interesse para acompanhamento futuro.

<a id="us07"></a>

- [US07](../05_Agil/01_historias_de_usuario.md#us07) : Eu, como usuário comprador, desejo salvar cartas em uma lista de desejos (wishlist) para poder comprá-las futuramente ou acompanhar mudanças de preço. [RFNI14](../../03_elicitacao/artefatos/requisitos_elicitados.md#rfni14)

---

#### Tema 5: Privacidade e Conformidade

Este tema engloba as funcionalidades relacionadas à segurança dos dados do consumidor e à conformidade com leis de privacidade (LGPD).

##### Épico 5.1: Canal de Direitos do Titular (LGPD)

Este épico foca em fornecer ao usuário acesso claro para exercer seus direitos de dados.

<a id="us18"></a>

- [US18]: Eu, como Titular dos Dados (Jogador), desejo encontrar facilmente um canal de contato (e-mail ou link) para exercer meus direitos de privacidade (ex: solicitar meus dados ou exclusão). [RF16](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf16)

<a id="us39"></a>

- [US39](../05_Agil/01_historias_de_usuario.md#us39): Eu, como usuário do sistema, desejo solicitar o acesso, a correção, a exclusão ou a anonimização dos meus dados pessoais para garantir meus direitos de privacidade e conformidade com a LGPD. [RF15](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf01---rf19-requisitos-da-análise-de-documentos-rf01---rf19-requisitos-da-analise-de-documentos)

##### Épico 5.2: Verificação e Segurança de Dados

Este épico foca em garantir a autenticidade e integridade das informações fornecidas pelos usuários, assegurando que os dados cadastrados sejam válidos e verdadeiros.

<a id="us37"></a>

- [US37](../05_Agil/01_historias_de_usuario.md#us37): Eu, como administrador do sistema, desejo que os dados cadastrados sejam verificados automaticamente para garantir a autenticidade das informações e proteger a plataforma contra falsos cadastros. [RF05](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf01---rf19-requisitos-da-análise-de-documentos-rf01---rf19-requisitos-da-analise-de-documentos)

##### Épico 5.3: Gestão de Uso de Dados Pessoais

Este épico tem como foco o uso responsável dos dados pessoais, garantindo que sejam utilizados apenas para finalidades específicas e comunicadas ao usuário.

<a id="us41"></a>

- [US41](../05_Agil/01_historias_de_usuario.md#us41): Eu, como usuário do sistema, desejo que meus dados pessoais sejam utilizados apenas para finalidades específicas, como identificação, contato, gestão contratual e melhoria de serviços, para garantir transparência e segurança no tratamento das minhas informações. [RF13](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf01---rf19-requisitos-da-análise-de-documentos-rf01---rf19-requisitos-da-analise-de-documentos)

---


#### Tema 6: Gestão de Decks e Listas

Este tema engloba as funcionalidades relacionadas à criação, organização e compartilhamento de decks e listas de cartas.

##### Épico 6.1: Criação e Gerenciamento de Decks

Este épico contém as histórias de usuário para criação, edição e organização de decks pessoais.

<a id="us26"></a>

- **US29:** Eu, como jogador de Magic, desejo visualizar decks publicados por outros usuários, com a lista completa de cartas, para poder me inspirar em novas estratégias e aprender sobre combinações de cartas populares. [RF25](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf25)

<a id="us29"></a>

- **US29:** Eu, como jogador dedicado de Magic, desejo criar, salvar e gerenciar minhas próprias listas de decks, para poder organizar minhas estratégias, acompanhar evoluções e ter acesso rápido aos meus decks favoritos. [RFNI09](../../03_elicitacao/artefatos/requisitos_elicitados.md#rfni09)

---

#### Tema 7: Comunicação e Suporte

Este tema abrange as funcionalidades de comunicação entre usuários e mecanismos de suporte da plataforma.

##### Épico 7.1: Sistema de Mensagens e Contato

Este épico contém as histórias de usuário para comunicação direta entre usuários.

<a id="us27"></a>

- **US27:** Eu, como membro da comunidade Magic, desejo buscar tópicos, ler discussões, responder postagens e criar novos tópicos no fórum, para poder compartilhar conhecimento, tirar dúvidas e interagir com outros jogadores. [RF26](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf26)

<a id="us38"></a>

- [US38](../05_Agil/01_historias_de_usuario.md#us38): Eu, como usuário cadastrado, desejo trocar mensagens privadas com outros usuários para me comunicar de forma direta e segura.[RF09](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf01---rf19-requisitos-da-análise-de-documentos-rf01---rf19-requisitos-da-analise-de-documentos)

##### Épico 7.2: Reporte e Moderação

Este épico foca em mecanismos para manter a qualidade e segurança do conteúdo.

<a id="us28"></a>

- **US28:** Eu, como usuário ativo da plataforma, desejo reportar problemas relacionados a cartas e anúncios, como informações incorretas, preços discrepantes ou anúncios suspeitos, para contribuir com a qualidade e confiabilidade do sistema para toda a comunidade. [RF37](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf37)

---

#### Tema 8: Processos de Compra Otimizados

Este tema engloba funcionalidades avançadas para facilitar e agilizar transações na plataforma.

##### Épico 8.1: Compras em Lote e Listas

Este épico contém as histórias de usuário para compras otimizadas de múltiplos itens.

<a id="us30"></a>

- **US30:** Eu, como comprador frequente, desejo utilizar a funcionalidade "Compra por Lista" para adicionar múltiplas cartas de uma vez ao carrinho, para poder agilizar minhas compras de decks completos ou listas específicas. [RFNI11](../../03_elicitacao/artefatos/requisitos_elicitados.md#rfni11)

---

#### Tema 9: Privacidade e Configurações

Este tema abrange as funcionalidades relacionadas ao controle de privacidade e personalização da experiência.

##### Épico 9.1: Controle de Cookies e Preferências

Este épico foca no gerenciamento de configurações de privacidade.

<a id="us25"></a>

- **US25:** Eu, como usuário preocupado com privacidade, desejo poder configurar minhas preferências de cookies no sistema, para ter controle sobre quais tipos de cookies são aceitos e proteger minha privacidade durante a navegação. [RF18](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf18)

<a id="us40"></a>

- [US40](../05_Agil/01_historias_de_usuario.md#us40): Eu, como usuário do sistema, desejo que sejam utilizados cookies para facilitar o login e personalizar minha experiência de navegação, tornando o uso da plataforma mais prático e adaptado às minhas preferências. [RF17](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf01---rf19-requisitos-da-análise-de-documentos-rf01---rf19-requisitos-da-analise-de-documentos)

---

#### Tema 10: Gestão de Anúncios
Este tema engloba funcionalidades que permitem aos vendedores criar, gerenciar e melhorar anúncios de cartas para atrair compradores.

##### Épico 10.1: Criação e Edição de Anúncios
Este épico contém as histórias de usuário relacionadas à adição de informações detalhadas e imagens nos anúncios.

- [US34](../05_Agil/01_historias_de_usuario.md#us34) Eu, como vendedor, desejo incluir textos, descrições e fotos detalhadas nos meus anúncios para atrair compradores e fornecer informações completas sobre a carta ofertada. [RF06](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf06)

---

#### Tema 11: Suporte e Qualidade de Dados
Este tema abrange funcionalidades para garantir a confiabilidade das informações sobre cartas e anúncios e proteger a comunidade de conteúdo inadequado.

##### Épico 11.1: Reporte de Problemas
Este épico contém as histórias de usuário relacionadas ao reporte de problemas de cartas e anúncios.

- [US35](../05_Agil/01_historias_de_usuario.md#us35) Eu, como usuário cadastrado, desejo reportar problemas relacionados a uma carta (como erros de informação ou anúncios suspeitos) para garantir que os dados estejam corretos e a comunidade seja protegida de conteúdo inadequado. [RFNI07](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni07)  

---

#### Tema 12: Processos de Compra Otimizados
Este tema engloba funcionalidades avançadas para facilitar e agilizar transações na plataforma.

##### Épico 12.1: Compras de Cartas
Este épico contém as histórias de usuário relacionadas à compra de cartas cadastradas e transações seguras.

[US31](../05_Agil/01_historias_de_usuario.md#us31) Eu, como comprador, desejo realizar a compra de cartas cadastradas informando meus dados pessoais e endereço de entrega para finalizar a transação de forma segura e prática. [RFNI05](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni05)

##### Épico 12.2: Alertas de Preço
Este épico contém as histórias de usuário relacionadas à configuração de alertas para monitoramento de preços de cartas.

- [US36](../05_Agil/01_historias_de_usuario.md#us36)Eu, como usuário interessado em monitorar preços de cartas, desejo definir um alerta de preço para uma carta específica para ser notificado quando o valor atingir ou ficar abaixo do limite que determinei. [RFNI05](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#rfni05)

---

#### Tema 13: Relatórios e Análise de Mercado
Este tema abrange funcionalidades focadas em oferecer informações detalhadas sobre os preços das cartas para auxiliar decisões de compra e venda.

##### Épico 13.1: Histórico de Preços
Este épico contém as histórias de usuário relacionadas à visualização do histórico de preços das cartas.

- [US32](../05_Agil/01_historias_de_usuario.md#us32) Eu, como jogador, desejo acessar o histórico de preços de uma carta em formato gráfico para visualizar a variação de valores ao longo do tempo e identificar o melhor momento para comprar ou vender. [RF34](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf34)

##### Épico 13.2: Preço Médio por Edição
Este épico contém as histórias de usuário relacionadas à visualização de preços médios das cartas por edição, permitindo comparações e decisões estratégicas.

- [US33](../05_Agil/01_historias_de_usuario.md#us33) Eu, como jogador e colecionador, desejo visualizar o preço médio e a variação histórica de uma carta em diferentes edições, para comparar tendências e identificar qual versão apresenta o melhor custo-benefício.  [RF33](../../03_elicitacao/artefatos/requisitos_elicitados.md#rf33) 

---

#### Tema 14: Módulo de Leilões

Este tema abrange as funcionalidades voltadas para criação, gerenciamento e participação em leilões online.

##### Épico 14.1: Sistema de Leilões Online

Este épico foca em oferecer um módulo completo de leilões, permitindo que os usuários anunciem, participem e acompanhem lances em tempo real.

<a id="us42"></a>

- [US42](../05_Agil/01_historias_de_usuario.md#us42): Eu, como usuário do sistema, desejo acessar um módulo completo de leilões para poder anunciar, participar e acompanhar disputas por produtos ou serviços em tempo real.[RFNI08](../../03_elicitacao/artefatos/requisitos_nao_implementados.md#requisitos-funcionais-não-implementados)

---

## Referências

- Ordem Alfabetica

## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição |
| ------ | ----------------- |
| Samuel |                   |
| Thiago |                   |
|Marcelo |                   |
|Raissa |  14,28%            |
| Angélica |                   |
|Guilherme|                  |

## Histórico de versão

| Versão |    Data    | Descrição                                   | Autor(es) | Revisor  |
|:------:|:----------:|:--------------------------------------------|:---------:|:--------:|
|  1.0   | 18/10/2025 | Início da documentação                      |  Samuel   | Angélica |
|  1.1   | 18/10/2025 | Editando                                    |  Thiago   |  Samuel  |
|  1.2   | 19/10/2025 | adição de descrição, objetivo e metodologia |  Marcelo  |  Raissa  |
|  1.3   | 19/10/2025 | Adicionando Backlogs                        |  Raissa   |    -     |
|  1.4   | 19/10/2025 | Adicionando Backlogs (temas 10 ao 13)       |   Vera    |  Thiago  |
|  1.5   | 19/10/2025 | Adicionando Backlogs                        |  Angélica |    Thiago, Raissa, Samuel, Marcelo, Vera, Guilherme     |
|  1.6   | 20/10/2025 | Adicionando Backlogs das US37-42            | Guilherme |    -     |
