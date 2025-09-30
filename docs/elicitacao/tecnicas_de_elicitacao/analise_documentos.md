# Analise de Documentos 

## Introdução 
A análise de documento é uma técnica de elicitação de requisitos que consiste em examinar materiais já existentes, como contratos, políticas de uso, manuais ou regulamentos, para identificar regras, restrições, requisitos funcionais e não funcionais que impactam o sistema.
Documentos analisados: [Termos e Condições Gerais de Uso](https://www.ligamagic.com.br/?view=contrato) e [Política de Proteção de Dados Pessoais](https://www.ligamagic.com.br/?view=privacidade).

---
## Questões que orientaram a Análise dos Documentos
Para orientar a análise do documento, foram elaboradas questões para ajudar e direcionar a leitura e a identificação de requisitos funcionais e não funcionais, feita com foco nos objetivos do sistema.


| N°  | Questões                                                                                                               |
|:---:|:-----------------------------------------------------------------------------------------------------------------------|
| 01  | Quais informações são obrigatórias para o cadastro de um novo usuário e como esses dados são validados pelo sistema    |
| 02  | Existem restrições sobre o tipo de produto/serviço que pode ser anunciado na plataforma?                               |
| 03  | O sistema possui mecanismos para prevenir cadastros duplicados ou fraudulentos?                                        |
| 04  | Quais canais de comunicação entre usuários são suportados pelo sistema (mensagens privadas, fórum, chat)?              |
| 05  | Como é realizada a cobrança de taxas sobre anúncios e transações?                                                      |
| 06  | Quais responsabilidades legais a plataforma assume em relação às transações entre usuários?                            |
| 07  | O documento especifica medidas de proteção à privacidade e à segurança dos dados pessoais?                             |
| 08  | O sistema permite diferentes formas de pagamento (cartão, boleto, transferência)?                                      |
| 09  | Existe diferenciação entre tipos de usuários (ex.: gratuito e premium)?                                                |
| 10  | Quais controles o usuário possui sobre o conteúdo que publica (ex.: editar/remover anúncios, apagar posts no fórum)?   |
| 11  | A plataforma assume alguma responsabilidade por falhas no sistema, perda de dados ou indisponibilidade do serviço?     |

Fonte: [Vera Lucia](https://github.com/verabelucia), 2025

---

## Questões que orientaram a análise do documento de Política de Proteção de Dados Pessoais
Para orientar a análise do documento, as questões foram formuladas para examinar criticamente os elementos essenciais que uma política de privacidade deve conter, garantindo a transparência perante os usuários e o tratamento adequado de seus dados pessoais. O roteiro de análise abrange desde a coleta e finalidade do uso dos dados até aspectos específicos como segurança, direitos dos titulares e mecanismos de controle.

| N°   | Questões                                                                                                                   |
|:----:|:---------------------------------------------------------------------------------------------------------------------------|
|  01  | O documento informa quais dados pessoais são coletados?                                                                    |
|  02  | São descritas as finalidades do uso de cada dado coletado?                                                                 |
|  03  | O documento explica a base legal para o tratamento de dados ?                                                              |
|  04  | Há informações sobre armazenamento e tempo de retenção dos dados pessoais?                                                 |
|  05  | O documento detalha com quem os dados podem ser compartilhados?                                                            |
|  06  | O usuário é informado sobre seus direitos garantidos pela LGPD?                                                            |
|  07  | Existe um canal de contato para o usuário exercer seus direitos de titular de dados?                                       |
|  08  | O documento menciona medidas de segurança adotadas para proteger os dados pessoais?                                        |
|  09  | Estão previstos procedimentos em caso de incidente de segurança ou vazamento de dados?                                     |
|  10  | O documento explica como os usuários serão avisados sobre alterações na política de dados?                                 |
|  11  | O uso de cookies está descrito, com explicação sobre finalidade?                                                           |
|  12  | O usuário é informado que pode configurar seu navegador para controlar ou bloquear cookies?                                |
|  13  | O documento esclarece que o usuário deve manter seus dados atualizados e corretos, assumindo essa responsabilidade?        |
|  14  | O usuário declara ciência e concordância explícita com a política ao utilizar o portal?                                    |                                   

Fonte: [Angélica](https://github.com/angelicaccampos), 2025

---

## Requisitos Funcionais (RF)
Os requisitos funcionais representam as funcionalidades específicas que o sistema deve executar para atender às necessidades dos usuários e aos objetivos do negócio. Esta tabela consolida os requisitos identificados através da análise documental, descrevendo as capacidades essenciais que a plataforma deve possuir para operar eficientemente no contexto de comercialização de produtos relacionados ao app LigaMagic.
Os requisitos foram organizados em categorias temáticas que refletem os principais módulos do sistema, abrangendo desde o gerenciamento de usuários e autenticação até a gestão de anúncios, comunicação entre usuários e aspectos de conformidade com a legislação de proteção de dados. Cada requisito foi formulando para garantir que todas as funcionalidades críticas para a operação da plataforma estejam devidamente especificadas e rastreáveis.


| ID   | Requisitos                                                       |         Categoria           | Descrição                                                                                                                           |
|:----:|:-----------------------------------------------------------------|:---------------------------:|:------------------------------------------------------------------------------------------------------------------------------------|
| RF1  | Permitir Cadastro de usuário                                     |  Gerenciamento de Usuários  | O sistema deve permitir que um novo usuário crie uma nova conta                                                                     |
| RF2  | Deve verificar duplicação de cadastros                           |  Gerenciamento de Usuário   | O sistema deve verificar se já existe um cadastro para o usuario que está tentando fazer cadadtro                                   |
| RF3  | Deve permitir acesso via login e senha                           |  Autenticação e Segurança   | O sistema deve permitir que o usuário acesse sua conta utilizando login e senha cadastrados                                         | | 
| RF4  | Deve permitir apenas produtos relacionados a Magic               | Gestão de Produtos/Serviços | O sistema deve restringir anúncios a produtos e serviços relacionados ao jogo Magic: The Gathering                                  | |
| RF5  | Deve verificar veracidade de dados cadastrados                   |  Autenticação e Segurança   | O sistema deve implementar mecanismos de validação de informações fornecidas pelos usuários                                         |
| RF6  | Deve permitir inclusão de textos, descrição e fotos nos anúncios |     Gestão de Anúncios      | O sistema deve permitir que usuários insiram descrições detalhadas e imagens em seus anúncios                                       |
| RF7  | Deve facilitar contato direto com usuário                        |         Comunicação         | O sistema deve disponibilizar meios de contato direto (chat ou mensagens) entre usuários                                            |
| RF8  | Deve implemetar cobrança de anúncios e venda                     |      Gestão Financeira      | O sistema deve permitir a cobrança de taxas sobre anúncios ou vendas realizadas pela plataforma                                     |
| RF9  | Deve permitir troca de mensagens privadas                        |         Comunicação         | O sistema deve permitir que usuários troquem mensagens privadas de forma segura                                                     |
| RF10 | Deve permitir criação de páginas pessoais                        |  Gerenciamento de Usuários  | O sistema deve permitir que cada usuário personalize e mantenha sua página pessoal/profissional                                     |
| RF11 | Deve permitir envio e respostas a mensagens no fórum             |   Comunicação Comunitária   | O sistema deve possibilitar a participação dos usuários em fóruns de discussão (postagem e resposta)                                |
| RF12 | Registrar dados pessoais do usuário                              |   Gerenciamento de Usuários | O sistema deve permitir o registro de dados como Nome, RG, CPF, Telefone, E-mail, Data de Nascimento e Endereço.                    |
| RF13 | Utilizar dados para finalidades específicas                      |   Gestão de Serviços        | O sistema deve usar os dados pessoais para identificação, contato, gestão contratual, melhoria de serviços e envio de comunicações. |
| RF14 | Compartilhar dados com parceiros                                 |   Gestão de Serviços        | O sistema deve possibilitar o compartilhamento de dados pessoais com parceiros, respeitando finalidades declaradas.                 |
| RF15 | Garantir direitos de titulares                                   |   Gerenciamento de Usuários | O sistema deve permitir que o usuário solicite acesso, correção, exclusão ou anonimização de seus dados pessoais.                   |
| RF16 | Oferecer canal de contato para solicitações                      |   Suporte e Atendimento     | O sistema deve disponibilizar canal (e-mail ou link) para o exercício dos direitos do titular.                                      |
| RF17 | Utilizar cookies para personalização                             |   Personalização            | O sistema deve utilizar cookies para facilitar login e personalizar a experiência de navegação.                                     |
| RF18 | Permitir controle de cookies                                     |   Personalização            | O sistema deve permitir que o usuário configure seu navegador para aceitar ou bloquear cookies.                                     |
| RF19 | Solicitar atualização de dados pessoais                          |   Gerenciamento de Usuários | O sistema deve permitir que o usuário atualize seus dados pessoais e comunicar alterações.                                          |

 Fonte: [Vera Lucia](https://github.com/verabelucia) e [Angélica](https://github.com/angelicaccampos), 2025

---

## Requisitos Não Funcionais (RNF)
Os requisitos não funcionais descrevem restrições e qualidades que o sistema deve atender para garantir sua conformidade legal, segurança, desempenho e confiabilidade. No contexto do sistema analisado, destacam-se requisitos relacionados ao cumprimento de legislações como a LGPD e o Código de Defesa do Consumidor, à adoção de medidas de segurança da informação, à transparência na comunicação com os usuários e à garantia de disponibilidade e confiabilidade do serviço.

|  ID   | Requisitos                                         |        Categoria        | Descrição                                                                                                             |
|:-----:|:---------------------------------------------------|:-----------------------:|:----------------------------------------------------------------------------------------------------------------------|
| RNF1  | Cumprir legislações aplicáveis                     |   Legal e Regulatório   | O sistema deve cumprir a LGPD (Lei nº 13.709/2018), o Código de Defesa do Consumidor e demais legislações aplicáveis. |
| RNF2  | Adotar medidas de segurança                        | Segurança da Informação | O sistema deve implementar padrões de segurança e privacidade alinhados às diretrizes do Banco Central do Brasil.     |
| RNF3  | Definir procedimentos para incidentes de segurança | Segurança da Informação | O sistema deve prever ações em caso de incidente ou vazamento de dados pessoais.                                      |
| RNF4  | Notificar alterações de política                   |      Transparência      | O sistema deve informar os usuários sobre mudanças relevantes na política com antecedência razoável.                  |
| RNF5  | Exigir consentimento e concordância explícita      |   Legal e Regulatório   | O sistema deve garantir que o usuário declare ciência e concordância com a política ao usar o portal.                 |
| RNF6  | Atualização do Sistema                             |     Disponibilidade     | O sistema deve suportar alterações na configuração ou apresentação sem interromper o uso                              |
| RNF07 | Informações Legais e Tributárias                   |     Confiabilidade      | Garantir que anúncios incluam informações fiscais corretas                                                            |

Fonte: [Vera Lucia](https://github.com/verabelucia) e [Angélica](https://github.com/angelicaccampos), 2025

---

## Requisitos Não Implementados (NI)
Os requisitos não implementados representam lacunas ou ausências identificadas durante a análise documental. Diferentemente dos requisitos funcionais e não funcionais já implementados, esses pontos sinalizam aspectos que deveriam estar descritos ou especificados, mas não foram abordados de forma clara ou completa no documento analisado.

| ID   | Requisitos                   |          Categoria           | Descrição                                                                                                                                                                                    |
|:----:|:-----------------------------|:----------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| NI01 | Armazenamento e Retenção     |    Base Legal Específica     | O documento não informa por quanto tempo os dados pessoais serão armazenados nem os critérios para definição desse prazo.                                                                    |
| NI02 | Procedimento para Incidentes | Procedimento para Incidentes | O documento não prevê ou detalha os procedimentos a serem adotados em caso de incidente de segurança ou vazamento de dados.                                                                  |
| NI03 | Base Legal Específica        |  Parcialmente Implementado   | O documento afirma o cumprimento da LGPD, mas não explica claramente a base legal específica (ex: consentimento, contrato, legítimo interesse) para cada finalidade de tratamento declarada. |

 Fonte: [Vera Lucia](https://github.com/verabelucia) e [Angélica](https://github.com/angelicaccampos), 2025

---

## Bibliografias

1. LIGAMAGIC. *Política de proteção de dados pessoais*. Disponível em: [https://www.ligamagic.com.br/?view=privacidade](https://www.ligamagic.com.br/?view=privacidade). Acesso em: 25 set. 2025.
2. LIGAMAGIC. *Termos e condições gerais de uso*. Disponível em: [https://www.ligamagic.com.br/?view=contrato](https://www.ligamagic.com.br/?view=contrato). Acesso em: 24/09/2025.

## Histórico de versão

| Versão |    Data     |                        Descrição                        |                     Autor                     |                     Revisor                     |
|:------:|:-----------:|:-------------------------------------------------------:|:---------------------------------------------:|:-----------------------------------------------:|
|  1.0   | 24/09/2025  | Criação da estrutura da página de Analise de Documentos | [Vera Lucia](https://github.com/verabelucia)  | [Angélica](https://github.com/angelicaccampos)  |
|  1.1   | 24/09/2025  |           Criação dos Requisitos Funcionais             | [Vera Lucia](https://github.com/verabelucia)  | [Angélica](https://github.com/angelicaccampos)  |
|  1.2   | 26/09/2025  |           Criação dos Requisitos não Funcionais e não implementados             | [Angélica](https://github.com/angelicaccampos)  |  [Vera Lucia](https://github.com/verabelucia) |
