# Analise de Documentos 

## Introdução 
A análise de documento é uma técnica de elicitação de requisitos que consiste em examinar materiais já existentes, como contratos, políticas de uso, manuais ou regulamentos, para identificar regras, restrições, requisitos funcionais e não funcionais que impactam o sistema.
Documentos analisados: [Termos e Condições Gerais de Uso](https://www.ligamagic.com.br/?view=contrato) e [Política de Proteção de Dados Pessoais](https://www.ligamagic.com.br/?view=privacidade)

---
## Questões que orientaram a Análise dos Documentos
Para orientar a análise do documento, foram elaboradas questões para ajudar e direcionar a leitura e a identificação de requisitos funcionais e não funcionais, feita com foco nos objetivos do sistema.

| N°   | Questões                                                                                                   |
|:----:|:-----------------------------------------------------------------------------------------------------------|
|  01  | Quais informações são obrigatórias para o cadastro de um novo usuário e como o sistema valida esses dados? |
|  02  | Existem restrições sobre o tipo de produto/serviço que pode ser anunciado na plataforma?                   |
|  03  | O sistema possui mecanismos para prevenir cadastros duplicados ou fraudulentos?                            |
|  04  | Quais canais de comunicação entre usuários são suportados pelo sistema (mensagens privadas, fórum, chat)?  |
|  05  | Como é realizada a cobrança de taxas sobre anúncios e transações?                                          |
|  06  | Quais responsabilidades legais a plataforma assume em relação às transações entre usuários?                |
|  07  | O documento especifica medidas de proteção à privacidade e à segurança dos dados pessoais?                 |
|  08  | O sistema permite diferentes formas de pagamento (cartão, boleto, transferência)?                          |
|  09  | Existe diferenciação entre tipos de usuários (ex.: gratuito e premium)?                                    |

Fonte: [Vera Lucia](https://github.com/verabelucia), 2025

---

## Questões que orientaram a Análise do Documento Política de Proteção de Dados Pessoais
Para orientar a análise do documento, foram elaboradas questões para ajudar e direcionar a leitura e a identificação de requisitos funcionais e não funcionais, feita com foco nos objetivos do sistema.

| N°   | Questões                                                                                                   |
|:----:|:-----------------------------------------------------------------------------------------------------------|
|  01  | O documento informa quais dados pessoais são coletados?  |
|  02  | São descritas as finalidades do uso de cada dado coletado?                    |
|  03  | O documento explica a base legal para o tratamento de dados ?                             |
|  04  | Há informações sobre armazenamento e tempo de retenção dos dados pessoais?   |
|  05  | O documento detalha com quem os dados podem ser compartilhados?                                           |
|  06  | O usuário é informado sobre seus direitos garantidos pela LGPD?                 |
|  07  | Existe um canal de contato para o usuário exercer seus direitos de titular de dados?                   |
|  08  | O documento menciona medidas de segurança adotadas para proteger os dados pessoais?                           |
|  09  | Estão previstos procedimentos em caso de incidente de segurança ou vazamento de dados?                                     |
|  10  | O documento explica como os usuários serão avisados sobre alterações na política de dados?                                      |
|  11  | O uso de cookies está descrito, com explicação sobre finalidade?                                      |
|  12  | O usuário é informado que pode configurar seu navegador para controlar ou bloquear cookies?                                       |
|  13  | O documento esclarece que o usuário deve manter seus dados atualizados e corretos, assumindo essa responsabilidade?                                    |
|  14  | O usuário declara ciência e concordância explícita com a política ao utilizar o portal?                                    |                                   

Fonte: [Angélica](https://github.com/angelicaccampos), 2025

---

## Requisitos Funcionais 

| ID   | Requisitos                                                       |         Categoria           | Descrição                                                                                            |
|:----:|:-----------------------------------------------------------------|:---------------------------:|:-----------------------------------------------------------------------------------------------------|
| RF1  | Permitir Cadastro de usuário                                     |  Gerenciamento de Usuários  | O sistema deve permitir que um novo usuário crie uma nova conta                                      |
| RF2  | Deve verificar duplicação de cadastros                           |  Gerenciamento de Usuário   | O sistema deve verificar se já existe um cadastro para o usuaria que está tentando fazer cadadtro    |
| RF3  | Deve permitir acesso via login e senha                           |  Autenticação e Segurança   | O sistema deve permitir que o usuário acesse sua conta utilizando login e senha cadastrados          | | 
| RF4  | Deve permitir apenas produtos relacionados a Magic               | Gestão de Produtos/Serviços | O sistema deve restringir anúncios a produtos e serviços relacionados ao jogo Magic: The Gathering   | |
| RF5  | Deve verificar veracidade de dados cadastrados                   |  Autenticação e Segurança   | O sistema deve implementar mecanismos de validação de informações fornecidas pelos usuários          | 
| RF6  | Deve permitir inclusão de textos, descrição e fotos nos anúncios |     Gestão de Anúncios      | O sistema deve permitir que usuários insiram descrições detalhadas e imagens em seus anúncios        |
| RF7  | Deve facilitar contato direto com usuário                        |         Comunicação         | O sistema deve disponibilizar meios de contato direto (chat ou mensagens) entre usuários             |
| RF8  | Deve implemetar cobrança de anúncios e venda                     |      Gestão Financeira      | O sistema deve permitir a cobrança de taxas sobre anúncios ou vendas realizadas pela plataforma      |
| RF9  | Deve permitir troca de mensagens privadas                        |         Comunicação         | O sistema deve permitir que usuários troquem mensagens privadas de forma segura                      |
| RF10 | Deve permitir criação de páginas pessoais                        |  Gerenciamento de Usuários  | O sistema deve permitir que cada usuário personalize e mantenha sua página pessoal/profissional      |
| RF11 | Deve permitir envio e respostas a mensagens no fórum             |   Comunicação Comunitária   | O sistema deve possibilitar a participação dos usuários em fóruns de discussão (postagem e resposta) |

 Fonte: [Vera Lucia](https://github.com/verabelucia), 2025

---

## Bibliografia

> 1. Site LigaMagic. Disponível em: https://www.ligamagic.com.br/?view=contrato. Acesso em: 24/09/2025.

## Histórico de versão

| Versão |    Data     |                        Descrição                        |                     Autor                     |                     Revisor                     |
|:------:|:-----------:|:-------------------------------------------------------:|:---------------------------------------------:|:-----------------------------------------------:|
|  1.0   | 24/09/2025  | Criação da estrutura da página de Analise de Documentos | [Vera Lucia](https://github.com/verabelucia)  | [Angélica](https://github.com/angelicaccampos)  |
|  1.1   | 24/09/2024  |           Criação dos Requisitos Funcionais             | [Vera Lucia](https://github.com/verabelucia)  | [Angélica](https://github.com/angelicaccampos)  |