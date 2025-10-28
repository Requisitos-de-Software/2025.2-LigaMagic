# Matriz de Pós-Rastreabilidade

## Descrição
A rastreabilidade de requisitos permite acompanhar cada requisito ao longo de todo o desenvolvimento, conectando-os tanto aos documentos iniciais quanto aos resultados das etapas subsequentes. Essa prática é essencial para a gestão de requisitos¹, contribuindo para o desenvolvimento de software e sendo indispensável em atividades como análise de impacto e manutenção. Este documento apresenta uma matriz que centraliza as informações necessárias para rastrear os requisitos deste projeto.
## Objetivo
A matriz de rastreabilidade tem como finalidade apresentar de forma clara e organizada a relação entre os requisitos, suas fontes e os artefatos gerados a partir deles, garantindo transparência e facilitando a gestão do projeto¹.
## Metodologia

- A matriz está estruturada em 7 colunas principais:
- Requisito – Identificação do requisito
- Descrição – Detalhamento do requisito
- Implementado – Indica se o requisito foi implementado
- Versão – Versão do requisito ou do documento
- Documento de origem – Referência à fonte do requisito
- Artefatos – Artefatos de modelagem relacionados
- Elos – Conexões entre requisitos e artefatos derivados

Tabela 1: modelo da matriz de rastreabilidade

| Requisito  | Descrição  | Implementado  | Versão  | Documento de origem    |     Artefatos          | Elos | 
|:----------:|:----------:|:-------------:|:-------:|:----------------------:|:----------------------:|:-----|
|    RFxx    |     --     |    Sim/Não    |   x.x   |  OBxx/ISxx/QTxx/BTxx   | CENxx/UCxx/SE/USxx/NFR | Cxx  | 

## Conteúdo

#### Matriz Geral de Rastreabilidade - Requisitos Funcionais

| Requisito  | Descrição                                      | Implementado    | Versão   |                  Documento de origem                         |                                                                                                                                                                                                                               Artefato                             | Elos |
|:----------:|:-----------------------------------------------|:---------------:|:--------:|:------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----:|
|    RF01    | Permitir cadastro de usuário                   |       Sim       |          | [AD01](../03_elicitacao/tecnicas/analise_documentos.md#ad01) |  [L03](../05_modelagem/02_lexicos/lexicos.md#l03-cadastrar) <br/> [L01](../05_modelagem/02_lexicos/lexicos.md#l01-membro) <br/> [L02](../05_modelagem/02_lexicos/lexicos.md#l02-visitante) <br/> [US09](../05_modelagem/05_Agil/01_historias_de_usuario.md#us09)   |  -   |
|    RF02    | Verificar duplicação de cadastros              |       Sim       |          | [AD02](../03_elicitacao/tecnicas/analise_documentos.md#ad02) |                                   [L03](../05_modelagem/02_lexicos/lexicos.md#l03-cadastrar) <br/> [L01](../05_modelagem/02_lexicos/lexicos.md#l01-membro) <br/> [US03](../05_modelagem/05_Agil/01_historias_de_usuario.md#us03)                                   |  -   |
|    RF03    | Permitir acesso via login e senha              |       Sim       |          | [AD03](../03_elicitacao/tecnicas/analise_documentos.md#ad03) |                                     [L04](../05_modelagem/02_lexicos/lexicos.md#l04-login) <br/> [L01](../05_modelagem/02_lexicos/lexicos.md#l01-membro) <br/> [US10](../05_modelagem/05_Agil/01_historias_de_usuario.md#us10)                                     |  -   |
|    RF04    | Restringir anúncios a produtos de Magic        |       Sim       |          | [AD04](../03_elicitacao/tecnicas/analise_documentos.md#ad04) |                                                                    [L08](../05_modelagem/02_lexicos/lexicos.md#l08-carta) <br/> [US15](../05_modelagem/05_Agil/01_historias_de_usuario.md#us15)                                                                    |  -   |
|    RF05    | Verificar veracidade de dados cadastrados      |       Sim       |          | [AD05](../03_elicitacao/tecnicas/analise_documentos.md#ad05) |                                   [L03](../05_modelagem/02_lexicos/lexicos.md#l03-cadastrar) <br/> [L01](../05_modelagem/02_lexicos/lexicos.md#l01-membro) <br/> [US37](../05_modelagem/05_Agil/01_historias_de_usuario.md#us37)                                   |  -   |
|    RF06    | Incluir textos, descrição e fotos nos anúncios |       Sim       |          | [AD06](../03_elicitacao/tecnicas/analise_documentos.md#ad06) |                                                                                                  [US34](../05_modelagem/05_Agil/01_historias_de_usuario.md#us34)                                                                                                   |  -   |
|    RF07    | Facilitar contato direto com usuário           |       Sim       |          | [AD07](../03_elicitacao/tecnicas/analise_documentos.md#ad07) |                                                                                                                                 -                                                                                                                                  |  -   |
|    RF08    | Implementar cobrança de anúncios e venda       |       Sim       |          | [AD08](../03_elicitacao/tecnicas/analise_documentos.md#ad08) |                                                                                                                                 -                                                                                                                                  |  -   |
|    RF09    | Permitir troca de mensagens privadas           |       Sim       |          | [AD09](../03_elicitacao/tecnicas/analise_documentos.md#ad09) |                                                                                                  [US38](../05_modelagem/05_Agil/01_historias_de_usuario.md#us38)                                                                                                   |  -   |
|    RF10    | Permitir criação de páginas pessoais           |       Não       |          | [AD10](../03_elicitacao/tecnicas/analise_documentos.md#ad10) | [US13](../05_modelagem/05_Agil/01_historias_de_usuario.md#us13) <br/> [US22](../05_modelagem/05_Agil/01_historias_de_usuario.md#us22) <br/> [C05](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc05) <br/> [CE06](../05_modelagem/01_cenarios/cenarios.md#ce06) |  -   |
|    RF11    | Enviar e responder mensagens no fórum          |       Não       |          | [AD11](../03_elicitacao/tecnicas/analise_documentos.md#ad11) |     [US01](../05_modelagem/05_Agil/01_historias_de_usuario.md#us01) <br/> [C09](../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc09) <br/> [L13](../05_modelagem/02_lexicos/lexicos.md#l13-forum) <br/> [CE11](../05_modelagem/01_cenarios/cenarios.md#ce11)      |  -   |
|    RF12    | Registrar dados pessoais do usuário            |       Sim       |          | [AD12](../03_elicitacao/tecnicas/analise_documentos.md#ad12) |                                                                   [US21](../05_modelagem/05_Agil/01_historias_de_usuario.md#us21) <br/> [L01](../05_modelagem/02_lexicos/lexicos.md#l01-membro)                                                                    |  -   |
|    RF13    | Utilizar dados para finalidades específicas    |       Sim       |          | [AD13](../03_elicitacao/tecnicas/analise_documentos.md#ad13) |                                                                                                  [US41](../05_modelagem/05_Agil/01_historias_de_usuario.md#us41)                                                                                                   |  -   |
|    RF14    | Compartilhar dados com parceiros               |       Sim       |          | [AD14](../03_elicitacao/tecnicas/analise_documentos.md#ad14) |                                                                                                                                 -                                                                                                                                  |  -   |
|    RF15    | Garantir direitos de titulares                 |       Sim       |          | [AD15](../03_elicitacao/tecnicas/analise_documentos.md#ad15) |                                                                                                  [US39](../05_modelagem/05_Agil/01_historias_de_usuario.md#us39)                                                                                                   |  -   |
|    RF16    | Oferecer canal de contato para solicitações    |       Sim       |          | [AD16](../03_elicitacao/tecnicas/analise_documentos.md#ad16) |                                                               [US16](../05_modelagem/05_Agil/01_historias_de_usuario.md#us16) <br/> [US24](../05_modelagem/05_Agil/01_historias_de_usuario.md#us24)                                                                |  -   |
|    RF17    | Utilizar cookies para personalização           |       Sim       |          | [AD17](../03_elicitacao/tecnicas/analise_documentos.md#ad17) |                                                                                                  [US40](../05_modelagem/05_Agil/01_historias_de_usuario.md#us40)                                                                                                   |  -   |
|    RF18    | Permitir controle de cookies                   |       Sim       |          | [AD18](../03_elicitacao/tecnicas/analise_documentos.md#ad18) |                                                                                                  [US25](../05_modelagem/05_Agil/01_historias_de_usuario.md#us25)                                                                                                   |  -   |
|    RF19    | Solicitar atualização de dados pessoais        |       Sim       |          | [AD19](../03_elicitacao/tecnicas/analise_documentos.md#ad19) |                                                                                                  [US11](../05_modelagem/05_Agil/01_historias_de_usuario.md#us11)                                                                                                   | -    |

Fonte: Vera, 2025



#### Matriz Geral de Rastreabilidade - Requisitos não Funcionais

| Requisito   | Descrição                                          | Implementado  | Versão   |                     Documento de origem                      |                                                                                         Artefato                                                                                         | Elos |
|:-----------:|:---------------------------------------------------|:-------------:|:--------:|:------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----:|
|    RNF01    | Cumprir legislações aplicáveis                     |      Sim      |          | [AD20](../03_elicitacao/tecnicas/analise_documentos.md#ad20) |                                                                [NFR04](../05_modelagem/05_Agil/03_nfr_framework.md#nfr04)                                                                |      |
|    RNF02    | Adotar medidas de segurança                        |      Sim      |          | [AD21](../03_elicitacao/tecnicas/analise_documentos.md#ad21) |                                                                                                                                                                                          |      |
|    RNF03    | Definir procedimentos para incidentes de segurança |      Sim      |          | [AD22](../03_elicitacao/tecnicas/analise_documentos.md#ad22) |                                                                                                                                                                                          |      |
|    RNF04    | Notificar alterações de política                   |      Sim      |          | [AD23](../03_elicitacao/tecnicas/analise_documentos.md#ad23) |                                                                                                                                                                                          |      |
|    RNF05    | Exigir consentimento e concordância explícita      |      Sim      |          | [AD24](../03_elicitacao/tecnicas/analise_documentos.md#ad24) |                                                                [NFR06](../05_modelagem/05_Agil/03_nfr_framework.md#nfr06)                                                                |      |
|    RNF06    | Atualização do Sistema                             |      Sim      |          | [AD25](../03_elicitacao/tecnicas/analise_documentos.md#ad25) |                                  [Especificação Suplementar](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md#Suportabilidade)                                  |      |
|    RNF07    | Informações Legais e Tributárias                   |      Sim      |          | [AD26](../03_elicitacao/tecnicas/analise_documentos.md#ad26) |    [Especificação Suplementar](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md#confiabilidade ), [NFR02](../05_modelagem/05_Agil/03_nfr_framework.md#nfr02)    |      |
|    RNF08    | Responsividade                                     |      Sim      |          |    [OBS19](../03_elicitacao/tecnicas/observacao.md#obs19)    | [Especificação Suplementar](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md#usabilidade-usability), [NFR07](../05_modelagem/05_Agil/03_nfr_framework.md#nfr08) |      |
|    RNF09    | Organização visual                                 |      Sim      |          |    [OBS20](../03_elicitacao/tecnicas/observacao.md#obs20)    | [Especificação Suplementar](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md#usabilidade-usability), [NFR09](../05_modelagem/05_Agil/03_nfr_framework.md#nfr09) |      |
|    RNF10    | Tempo de resposta para busca                       |      Sim      |          |    [OBS21](../03_elicitacao/tecnicas/observacao.md#obs20)    |                                                                                                                                                                                          |      |
|    RNF11    | Disponibilidade                                    |      Sim      |          |    [OBS22](../03_elicitacao/tecnicas/observacao.md#obs20)    |                                                                                                                                                                                          |      |
|    RNF12    | Compatibilidade com navegadores                    |      Sim      |          |    [OBS23](../03_elicitacao/tecnicas/observacao.md#obs20)    |    [Especificação Suplementar](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md#confiabilidade ), [NFR01](../05_modelagem/05_Agil/03_nfr_framework.md#nfr01)    |      |
|    RNF13    | Segurança de dados                                 |      Sim      |          |    [OBS24](../03_elicitacao/tecnicas/observacao.md#obs20)    |                                                                                                                                                                                          |      |
|    RNF14    | Padronização de mensagens                          |      Sim      |          |    [OBS25](../03_elicitacao/tecnicas/observacao.md#obs20)    | [Especificação Suplementar](../05_modelagem/04_especificacao_suplementar/especificacao_suplementar.md#usabilidade-usability), [NFR03](../05_modelagem/05_Agil/03_nfr_framework.md#nfr03) |      |
|    RNF15    | Backup de dados                                    |      Sim      |          |    [OBS26](../03_elicitacao/tecnicas/observacao.md#obs20)    |                                                                                                                                                                                          |      |
|    RNF16    | Escalabilidade                                     |      Sim      |          |    [OBS27](../03_elicitacao/tecnicas/observacao.md#obs20)    |                                                                                                                                                                                          |      |
|    RNF17    | Armazenamento e Retenção                           |      Não      |          |                              -                               |                                                                                                                                                                                          |      |
|    RNF18    | Procedimento para Incidentes                       |      Não      |          |                              -                               |                                                                                                                                                                                          |      |
|    RNF19    | Base Legal Específica                              |      Não      |          |                              -                               |                                                                                                                                                                                          |      |

Fonte: Vera, 2025



## Referências

> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 19/10/2025.


## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição |
|:-------| :---------------: |
| Samuel |                   |
| Vera   |                   |

## Agradecimento

O Grupo 02 agradece o apoio das ferramentas de Inteligência Artificial Generativa — ChatGPT e Google Gemini — na revisão e padronização de nossos artefatos. Essas tecnologias foram utilizadas para auxiliar na organização do repositório. Todo o conteúdo, incluindo a precisão técnica e as ideias apresentadas, é de responsabilidade dos autores.


## Histórico de versão

| Versão |    Data    | Descrição                    | Autor(es) | Revisor |
|:------:|:----------:|:-----------------------------|:---------:|:-------:|
|  1.0   | 23/10/2025 | Criação inicial do documento |  Samuel   |    -    |
|  1.2   | 28/10/2025 | Adição das matrizes          |   Vera    | Sameul  |
