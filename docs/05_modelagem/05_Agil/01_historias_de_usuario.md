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
| US07 a US12         | Thiago Accioly  |

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

### [US07] – Adicionar a Diferentes Listas

| Item                        | Descrição                                                                                                                                   |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| USx                         | US07                                                                                                                                        |
| Tema                        | Organização e Listas de Cartas                                                                                                              |
| Descrição                   | Eu, como **usuário colecionador**, desejo **adicionar uma carta a diferentes listas (coleção, deck, desejos e carrinho)** para **gerenciar melhor meus itens e planos de compra**. |
| Critérios de Aceitação      | - O sistema deve permitir selecionar múltiplas listas ao adicionar uma carta.<br>- O usuário pode criar listas personalizadas.<br>- A carta adicionada deve refletir em todas as listas escolhidas. |
| Prioridade Usuário          | Alta                                                                                                                                        |
| Status                      | Não Validada                                                                                                                                     |
| Rastreabilidade             | RF35 – Adicionar a diferentes listas.                                                                                                       |
| Validação                   | (#)                                                                                |

<div align="center"><strong>Tabela 7:</strong> História de Usuário – Adicionar a Diferentes Listas</div>  
**Fonte:** Thiago, 2025  

### [US08] – Oferecer Canal de Contato para Solicitações

| Item                        | Descrição                                                                                                                                   |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| USx                         | US08                                                                                                                                        |
| Tema                        | Privacidade e Comunicação                                                                                                                   |
| Descrição                   | Eu, como **usuário cadastrado**, desejo **ter acesso a um canal de contato (e-mail ou link)** para **enviar solicitações sobre meus dados pessoais** conforme a LGPD. |
| Critérios de Aceitação      | - O sistema deve disponibilizar link ou endereço de e-mail para contato.<br>- O canal deve estar acessível na área de configurações e rodapé.<br>- O envio deve gerar confirmação automática de recebimento. |
| Prioridade Usuário          | Alta                                                                                                                                        |
| Status                      | Não Validada                                                                                                                                     |
| Rastreabilidade             | RF16 – Oferecer canal de contato para solicitações.                                                                                         |
| Validação                   | (#)                                                                                    |

<div align="center"><strong>Tabela 8:</strong> História de Usuário – Oferecer Canal de Contato para Solicitações</div>  
**Fonte:** Thiago, 2025  

### [US09] – Criação de Páginas Pessoais

| Item                        | Descrição                                                                                                                                   |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| USx                         | US09                                                                                                                                        |
| Tema                        | Perfil e Personalização                                                                                                                     |
| Descrição                   | Eu, como **usuário do sistema**, desejo **criar e personalizar minha página pessoal/profissional** para **divulgar minhas informações e coleções publicamente**. |
| Critérios de Aceitação      | - O usuário deve poder editar foto, descrição e links pessoais.<br>- Deve ser possível escolher se a página será pública ou privada.<br>- As alterações devem ser salvas automaticamente. |
| Prioridade Usuário          | Média                                                                                                                                       |
| Status                      | Não Validada                                                                                                                                     |
| Rastreabilidade             | RF10 – Permitir criação de páginas pessoais.                                                                                                |
| Validação                   | (#)                                                                                 |

<div align="center"><strong>Tabela 9:</strong> História de Usuário – Criação de Páginas Pessoais</div>  
**Fonte:** Thiago, 2025  

### [US10] – Registro de Dados Pessoais

| Item                        | Descrição                                                                                                                                   |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| USx                         | US10                                                                                                                                        |
| Tema                        | Cadastro e Segurança de Dados                                                                                                               |
| Descrição                   | Eu, como **usuário novo**, desejo **registrar meus dados pessoais (Nome, RG, CPF, Telefone, E-mail, Data de Nascimento e Endereço)** para **completar meu perfil e garantir autenticidade no sistema**. |
| Critérios de Aceitação      | - Todos os campos obrigatórios devem estar disponíveis no formulário de cadastro.<br>- O sistema deve validar formato de CPF e e-mail.<br>- Os dados devem ser armazenados de forma segura. |
| Prioridade Usuário          | Alta                                                                                                                                        |
| Status                      | Não Validada                                                                                                                                     |
| Rastreabilidade             | RF12 – Registrar dados pessoais do usuário.                                                                                                 |
| Validação                   | (#)                                                                             |

<div align="center"><strong>Tabela 10:</strong> História de Usuário – Registro de Dados Pessoais</div>  
**Fonte:** Thiago, 2025  

### [US11] – Criação de Páginas Pessoais

| Item                        | Descrição                                                                                                                                   |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| USx                         | US11                                                                                                                                        |
| Tema                        | Perfil e Personalização                                                                                                                     |
| Descrição                   | Eu, como **usuário do sistema**, desejo **criar e personalizar minha página pessoal/profissional** para **divulgar minhas informações e coleções publicamente**. |
| Critérios de Aceitação      | - O usuário deve poder editar foto, descrição e links pessoais.<br>- Deve ser possível escolher se a página será pública ou privada.<br>- As alterações devem ser salvas automaticamente. |
| Prioridade Usuário          | Média                                                                                                                                       |
| Status                      | Não Validada                                                                                                                                     |
| Rastreabilidade             | RF10 – Permitir criação de páginas pessoais.                                                                                                |
| Validação                   | (#)                                                                                 |

<div align="center"><strong>Tabela 11:</strong> História de Usuário – Criação de Páginas Pessoais</div>  
**Fonte:** Thiago, 2025 

### [US12] – Registro de Dados Pessoais

| Item                        | Descrição                                                                                                                                   |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| USx                         | US12                                                                                                                                        |
| Tema                        | Cadastro e Segurança de Dados                                                                                                               |
| Descrição                   | Eu, como **usuário novo**, desejo **registrar meus dados pessoais (Nome, RG, CPF, Telefone, E-mail, Data de Nascimento e Endereço)** para **completar meu perfil e garantir autenticidade no sistema**. |
| Critérios de Aceitação      | - Todos os campos obrigatórios devem estar disponíveis no formulário de cadastro.<br>- O sistema deve validar formato de CPF e e-mail.<br>- Os dados devem ser armazenados de forma segura. |
| Prioridade Usuário          | Alta                                                                                                                                        |
| Status                      | Não Validada                                                                                                                                     |
| Rastreabilidade             | RF12 – Registrar dados pessoais do usuário.                                                                                                 |
| Validação                   | (#)                                                                             |

<div align="center"><strong>Tabela 12:</strong> História de Usuário – Registro de Dados Pessoais</div>  
**Fonte:** Thiago, 2025  



## Referências

> **PRESSMAN, Roger S.** _Engenharia de Software: uma abordagem profissional_. Cap. 3

## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição |
| ------ | ----------------- |
| Samuel |                   |
| Thiago |                   |

## Histórico de versão

| Versão |    Data    | Descrição                    |   Autor(es)    | Revisor |
| :----: | :--------: | :--------------------------- | :------------: | :-----: |
|  1.0   | 16/10/2025 | Criação inicial do documento | Samuel, Thiago |    -    |
|  1.0   | 17/10/2025 | Edição do documento | Samuel, Thiago |    -    |
