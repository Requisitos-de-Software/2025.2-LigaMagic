# Forward-from

## Descrição

A rastreabilidade forward-from (para frente, a partir de) diz respeito à ligação entre os requisitos e os artefatos de desenho e implementação. Esta abordagem, também conhecida como pós-rastreabilidade , permite acompanhar o percurso de cada requisito desde sua definição até sua efetiva implementação e validação , ligando-os a artefatos como componentes de arquitetura, código e casos de teste. (SAYÃO; LEITE, 2005).

## Objetivo

A análise da rastreabilidade forward-from tem como principal finalidade garantir que todos os requisitos identificados estejam corretamente refletidos nas fases seguintes do projeto. Esse tipo de rastreabilidade assegura a verificação de que um requisito foi de fato implementado no sistema , permitindo identificar requisitos ainda não alocados a componentes de software ou que não possuem casos de teste previstos.

Além disso, esse processo facilita a análise de impacto de mudanças e contribui para a validação final do sistema, possibilitando demonstrar aos clientes que a implementação atende à baseline de requisitos acordada.

## Metodologia

Para realizar a análise de rastreabilidade forward-from, foram considerados os vínculos estabelecidos entre os requisitos e diferentes artefatos gerados durante o projeto. Abaixo estão listados os tipos de artefatos utilizados na documentação e validação dos requisitos, junto às respectivas siglas utilizadas para identificá-los:

- UCx – Casos de Uso (Use Case)
- USx – Histórias de Usuário
- NFRx – NFR Framework (Requisitos Não Funcionais)
- ESPx – Especificação Suplementar
- CNx – Cenários
- LX – Léxico

## Conteúdo


| ID Requisito | Descrição | Implementado | Cenário | Caso de Uso | Épico | Elos | História de Usuário |
|:---:|:---|:---:|:---|:---|:---|:---:|:---|
| **RF01** | **Permitir cadastro de usuário**<br>O sistema deve permitir que um novo usuário crie uma nova conta através do [cadastro](../../05_modelagem/02_lexicos/lexicos.md#l03-cadastrar), podendo ser [ membro](../../05_modelagem/02_lexicos/lexicos.md#l01-membro) ou [ visitante](../../05_modelagem/02_lexicos/lexicos.md#l02-visitante) | Sim | - | - | [Épico 3.1](../../05_modelagem/05_Agil/02_backlogs.md#bus09) | - | [US09](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us09) |
| **RF02** | **Verificar duplicação de cadastros**<br>O sistema deve verificar se já existe um [cadastro](../../05_modelagem/02_lexicos/lexicos.md#l03-cadastrar) para o usuario ([membro](../../05_modelagem/02_lexicos/lexicos.md#l01-membro)) que está tentando fazer cadastro | Sim | - | - | [Épico 3.1](../../05_modelagem/05_Agil/02_backlogs.md#bus03) | - | [US03](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us03) |
| **RF03** | **Permitir acesso via login e senha**<br>O sistema deve permitir que  usuario ([membro](../../05_modelagem/02_lexicos/lexicos.md#l01-membro)) acesse sua conta utilizando o [login](../../05_modelagem/02_lexicos/lexicos.md#l04-login) e senha cadastrados | Sim | - | - | [Épico 3.1](../../05_modelagem/05_Agil/02_backlogs.md#bus10) | - | [US10](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us10) |
| **RF04** | **Restringir anúncios a produtos de Magic**<br>O sistema deve restringir anúncios a produtos e serviços relacionados ao jogo Magic: The Gathering, especificamente [cartas](../../05_modelagem/02_lexicos/lexicos.md#l08-carta) | Sim | - | - | [Épico 2.3](../../05_modelagem/05_Agil/02_backlogs.md#bus15) | - | [US15](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us15) |
| **RF05** | **Verificar veracidade de dados cadastrados**<br>O sistema deve implementar mecanismos de validação de informações fornecidas pelos usuários durante o [ cadastro](../../05_modelagem/02_lexicos/lexicos.md#l03-cadastrar) de usuario ([membro](../../05_modelagem/02_lexicos/lexicos.md#l01-membro)) | Sim | - | - | [Épico 5.2](../../05_modelagem/05_Agil/02_backlogs.md#bus37) | - | [US37](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us37) |
| **RF06** | **Incluir textos, descrição e fotos nos anúncios**<br>O sistema deve permitir que usuários insiram descrições detalhadas e imagens em seus anúncios | Sim | - | - | [Épico 10.1](../../05_modelagem/05_Agil/02_backlogs.md#bus34) | - | [US34](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us34) |
| **RF07** | **Facilitar contato direto com usuário**<br>O sistema deve disponibilizar meios de contato direto (chat ou mensagens) entre usuários | Sim | - | - | - | - | - |
| **RF08** | **Implementar cobrança de anúncios e venda**<br>O sistema deve permitir a cobrança de taxas sobre anúncios ou vendas realizadas pela plataforma | Sim | - | - | - | - | - |
| **RF09** | **Permitir troca de mensagens privadas**<br>O sistema deve permitir que usuários troquem mensagens privadas de forma segura | Sim | - | - | [Épico 7.1](../../05_modelagem/05_Agil/02_backlogs.md#bus38) | - | [US38](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us38) |
| **RF10** | **Permitir criação de páginas pessoais**<br>O sistema deve permitir que cada usuário personalize e mantenha sua página pessoal/profissional | Não | [CE06](../../05_modelagem/01_cenarios/cenarios.md#ce06) | [UC05](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc05) | [Épico 3.1](../../05_modelagem/05_Agil/02_backlogs.md#bus13), [Épico 3.1](../../05_modelagem/05_Agil/02_backlogs.md#bus22) | - | [US13](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us13), [US22](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us22) |
| **RF11** | **Enviar e responder mensagens no fórum**<br>O sistema deve possibilitar a participação dos usuários em [ fórum](../../05_modelagem/02_lexicos/lexicos.md#l13-forum) de discussão (postagem e resposta) | Não | [CE11](../../05_modelagem/01_cenarios/cenarios.md#ce11) | [UC09](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc09) | [Épico 1.1](../../05_modelagem/05_Agil/02_backlogs.md#bus01) | - | [US01](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us01) |
| **RF12** | **Registrar dados pessoais do usuário**<br>O sistema deve permitir o registro de dados como Nome, RG, CPF, Telefone, E-mail, Data de Nascimento e Endereço para usuario ([membro](../../05_modelagem/02_lexicos/lexicos.md#l01-membro)) | Sim | - | - | [Épico 3.1](../../05_modelagem/05_Agil/02_backlogs.md#bus21) | - | [US21](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us21) |
| **RF13** | **Utilizar dados para finalidades específicas**<br>O sistema deve usar os dados pessoais para identificação, contato, gestão contratual, melhoria de serviços e envio de comunicações | Sim | - | - | [Épico 5.3](../../05_modelagem/05_Agil/02_backlogs.md#bus41) | - | [US41](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us41) |
| **RF14** | **Compartilhar dados com parceiros**<br>O sistema deve possibilitar o compartilhamento de dados pessoais com parceiros, respeitando finalidades declaradas | Sim | - | - | - | - | - |
| **RF15** | **Garantir direitos de titulares**<br>O sistema deve permitir que o usuário solicite acesso, correção, exclusão ou anonimização de seus dados pessoais | Sim | - | - | [Épico 5.1](../../05_modelagem/05_Agil/02_backlogs.md#bus39) | - | [US39](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us39) |
| **RF16** | **Oferecer canal de contato para solicitações**<br>O sistema deve disponibilizar canal (e-mail ou link) para o exercício dos direitos do titular | Sim | - | - | [Épico 5.1](../../05_modelagem/05_Agil/02_backlogs.md#bus16), [Épico 5.1](../../05_modelagem/05_Agil/02_backlogs.md#bus24) | - | [US16](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us16), [US24](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us24) |
| **RF17** | **Utilizar cookies para personalização**<br>O sistema deve utilizar cookies para facilitar login e personalizar a experiência de navegação | Sim | - | - | [Épico 9.1](../../05_modelagem/05_Agil/02_backlogs.md#bus40) | - | [US40](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us40) |
| **RF18** | **Permitir controle de cookies**<br>O sistema deve permitir que o usuário configure seu navegador para aceitar ou bloquear cookies | Sim | - | - | [Épico 9.1](../../05_modelagem/05_Agil/02_backlogs.md#bus25) | - | [US25](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us25) |
| **RF19** | **Solicitar atualização de dados pessoais**<br>O sistema deve permitir que o usuario ([membro](../../05_modelagem/02_lexicos/lexicos.md#l01-membro)) atualize seus dados pessoais e comunique alterações | Sim | - | - | [Épico 3.2](../../05_modelagem/05_Agil/02_backlogs.md#bus11) | - | [US11](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us11) |
| **RF20** | **Pesquisar cartas pelo nome**<br>Permitir que o usuário realize [ pesquisa de carta](../../05_modelagem/02_lexicos/lexicos.md#l05-pesquisar-carta) pelo nome da [carta](../../05_modelagem/02_lexicos/lexicos.md#l08-carta) | Não | [CE03](../../05_modelagem/01_cenarios/cenarios.md#ce03) | [UC02](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc02) | [Épico 4.1](../../05_modelagem/05_Agil/02_backlogs.md#bus04), [Épico 4.1](../../05_modelagem/05_Agil/02_backlogs.md#bus08) | - | [US04](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us04), [US08](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us08) |
| **RF21.1** | **Filtrar cartas por preço**<br>Permitir que o usuário filtre [cartas](../../05_modelagem/02_lexicos/lexicos.md#l08-carta) por preço | Sim | - | - | [Épico 4.1](../../05_modelagem/05_Agil/02_backlogs.md#bus05) | - | [US05](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us05) |
| **RF21.2** | **Filtrar cartas por condição**<br>Permitir que o usuário filtre cartas por condição | Não | [CE07](../../05_modelagem/01_cenarios/cenarios.md#ce07) | [UC06](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc06) | [Épico 2.2](../../05_modelagem/05_Agil/02_backlogs.md#bus14) | - | [US14](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us14) |
| **RF21.3** | **Filtrar cartas por idioma**<br>Permitir que o usuário filtre cartas por idioma | Não | - | - | - | - | - |
| **RF22** | **Exibir resultados da pesquisa**<br>Mostrar preço, condição, idioma e reputação do vendedor ao [ pesquisar](../../05_modelagem/02_lexicos/lexicos.md#l05-pesquisar-carta) uma [carta](../../05_modelagem/02_lexicos/lexicos.md#l08-carta) | Sim | - | - | [Épico 4.1](../../05_modelagem/05_Agil/02_backlogs.md#bus06) | - | [US06](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us06) |
| **RF23** | **Realizar compra**<br>Permitir que o usuario ([membro](../../05_modelagem/02_lexicos/lexicos.md#l01-membro)) realize [comprar de carta](../../05_modelagem/02_lexicos/lexicos.md#l06-comprar-carta) cadastradas, incluindo dados pessoais e endereço de entrega no [carrinho ativo](../../05_modelagem/02_lexicos/lexicos.md#l21-carrinho-ativo) | Sim | - | - | [Épico 12.1](../../05_modelagem/05_Agil/02_backlogs.md#bus31) | - | [US31](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us31) |
| **RF24** | **Histórico de compras**<br>Permitir que o usuario ([membro](../../05_modelagem/02_lexicos/lexicos.md#l01-membro)) acesse seu histórico de [comprar de carta](../../05_modelagem/02_lexicos/lexicos.md#l06-comprar-carta) com informações detalhadas | Sim | - | - | [Épico 3.2](../../05_modelagem/05_Agil/02_backlogs.md#bus12) | - | [US12](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us12) |
| **RF25** | **Visualizar decks**<br>Permitir que o usuário visualize [decks](../../05_modelagem/02_lexicos/lexicos.md#l09-deck) publicados, com lista de cartas | Sim | - | - | [Épico 6.1](../../05_modelagem/05_Agil/02_backlogs.md#bus26) | - | [US26](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us26) |
| **RF26** | **Fórum**<br>Permitir que o usuário busque tópicos, leia, responda e crie postagens no [fórum](../../05_modelagem/02_lexicos/lexicos.md#l13-forum) | Sim | - | - | [Épico 7.1](../../05_modelagem/05_Agil/02_backlogs.md#bus27) | - | [US27](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us27) |
| **RF27** | **Detalhar carta**<br>Permitir que o usuário visualize detalhes de uma [carta](../../05_modelagem/02_lexicos/lexicos.md#l08-carta) ao clicar no resultado da pesquisa, incluindo [edição](../../05_modelagem/02_lexicos/lexicos.md#l11-edicao), [formato](../../05_modelagem/02_lexicos/lexicos.md#l12-formato) e [mana](../../05_modelagem/02_lexicos/lexicos.md#l14-mana) | Sim | - | - | - | - | - |
| **RF28** | **Adicionar a listas**<br>Permitir que o usuário adicione cartas à [coleção de cartas](../../05_modelagem/02_lexicos/lexicos.md#l10-colecao-de-cartas), [deck](../../05_modelagem/02_lexicos/lexicos.md#l09-deck) ou lista de desejos | Não | [CE01](../../05_modelagem/01_cenarios/cenarios.md#ce01), [CE02](../../05_modelagem/01_cenarios/cenarios.md#ce02) | [UC01](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc01) | [Épico 4.2](../../05_modelagem/05_Agil/02_backlogs.md#bus07) | - | [US07](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us07) |
| **RF29** | **Avaliar ou dar feedback**<br>Permitir que o usuário avalie ou dê feedback sobre vendedores ou decks | Não | [CE13](../../05_modelagem/01_cenarios/cenarios.md#ce13) | [UC11](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc11) | [Épico 1.2](../../05_modelagem/05_Agil/02_backlogs.md#bus19) | - | [US19](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us19) |
| **RF30** | **Mostrar informações detalhadas da carta**<br>Mostrar [edição](../../05_modelagem/02_lexicos/lexicos.md#l11-edicao), idioma, condição e preço médio de cada [carta](../../05_modelagem/02_lexicos/lexicos.md#l08-carta), incluindo informações de [mana](../../05_modelagem/02_lexicos/lexicos.md#l14-mana) | Sim | - | - | [Épico 2.1](../../05_modelagem/05_Agil/02_backlogs.md#bus17) | - | [US17](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us17) |
| **RF31** | **Definir alerta de preço**<br>Permitir que o usuário defina um alerta de preço para a [carta](../../05_modelagem/02_lexicos/lexicos.md#l08-carta) selecionada por [edição](../../05_modelagem/02_lexicos/lexicos.md#l11-edicao) | Não | [CE04](../../05_modelagem/01_cenarios/cenarios.md#ce04) | [UC03](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc03) | [Épico 12.2](../../05_modelagem/05_Agil/02_backlogs.md#bus36) | - | [US36](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us36) |
| **RF32** | **Buscar decks relacionados**<br>Permitir que o usuário busque [decks](../../05_modelagem/02_lexicos/lexicos.md#l09-deck) que utilizam a carta selecionada por [formato](../../05_modelagem/02_lexicos/lexicos.md#l12-formato) | Sim | - | - | [Épico 2.1](../../05_modelagem/05_Agil/02_backlogs.md#bus18) | - | [US18](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us18) |
| **RF33** | **Visualizar preço médio por edição**<br>Permitir que o usuário visualize o preço médio da [carta](../../05_modelagem/02_lexicos/lexicos.md#l08-carta) em diferentes [edição](../../05_modelagem/02_lexicos/lexicos.md#l11-edicao) e condições | Sim | - | - | [Épico 13.2](../../05_modelagem/05_Agil/02_backlogs.md#bus33) | - | [US33](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us33) |
| **RF34** | **Acessar histórico de preços**<br>Permitir que o usuário acesse o histórico de preços da [carta](../../05_modelagem/02_lexicos/lexicos.md#l08-carta) em formato gráfico | Sim | - | - | [Épico 13.1](../../05_modelagem/05_Agil/02_backlogs.md#bus32) | - | [US32](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us32) |
| **RF35** | **Adicionar a diferentes listas**<br>Permitir que o usuário adicione a carta a diferentes listas ([coleção de cartas](../../05_modelagem/02_lexicos/lexicos.md#l10-colecao-de-cartas), [deck](../../05_modelagem/02_lexicos/lexicos.md#l09-deck), lista de desejos, carrinho) | Sim | - | - | [Épico 2.3](../../05_modelagem/05_Agil/02_backlogs.md#bus23) | - | [US23](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us23) |
| **RF36** | **Compartilhar carta**<br>Permitir que o usuário compartilhe informações da [carta](../../05_modelagem/02_lexicos/lexicos.md#l08-carta) em redes sociais ou por link direto | Não | [CE12](../../05_modelagem/01_cenarios/cenarios.md#ce12) | [UC10](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc10) | [Épico 2.1](../../05_modelagem/05_Agil/02_backlogs.md#bus02) | - | [US02](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us02) |
| **RF37** | **Reportar problemas**<br>Permitir que o usuário reporte problemas relacionados à carta (erros de informação, anúncios suspeitos, etc.) | Não | [CE05](../../05_modelagem/01_cenarios/cenarios.md#ce05) | [UC04](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc04) | [Épico 7.2](../../05_modelagem/05_Agil/02_backlogs.md#bus28), [Épico 11.1](../../05_modelagem/05_Agil/02_backlogs.md#bus35) | - | [US28](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us28), [US35](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us35) |
| **RF38** | **Gerenciar e Catalogar cartas**<br>Os usuários devem ser capazes de catalogar e gerenciar sua [coleção de cartas](../../05_modelagem/02_lexicos/lexicos.md#l10-colecao-de-cartas) pessoal de [cartas](../../05_modelagem/02_lexicos/lexicos.md#l08-carta) | Não | [CE14](../../05_modelagem/01_cenarios/cenarios.md#ce14) | [UC12](../../05_modelagem/03_casos_de_uso/casos_de_uso.md#uc12) | [Épico 2.2](../../05_modelagem/05_Agil/02_backlogs.md#bus20) | - | [US20](../../05_modelagem/05_Agil/01_historias_de_usuario.md#us20) |


### Requisitos Não Funcionais

|  ID   | Requisito                                          | Implementado | Elos | Especificação Suplementar | NFR Framework |
| :---: | :------------------------------------------------- | :----------: | :--: | :-----------------------: | :-----------: |
| RNF01 | Cumprir legislações aplicáveis                     |     Sim      |
| RNF02 | Adotar medidas de segurança                        |     Sim      |
| RNF03 | Definir procedimentos para incidentes de segurança |     Sim      |
| RNF04 | Notificar alterações de política                   |     Sim      |
| RNF05 | Exigir consentimento e concordância explícita      |     Sim      |
| RNF06 | Atualização do Sistema                             |     Sim      |
| RNF07 | Informações Legais e Tributárias                   |     Sim      |
| RNF08 | Responsividade                                     |     Sim      |
| RNF09 | Organização visual                                 |     Sim      |
| RNF10 | Tempo de resposta para busca                       |     Sim      |
| RNF11 | Disponibilidade                                    |     Sim      |
| RNF12 | Compatibilidade com navegadores                    |     Sim      |
| RNF13 | Segurança de dados                                 |     Sim      |
| RNF14 | Padronização de mensagens                          |     Sim      |
| RNF15 | Backup de dados                                    |     Sim      |
| RNF16 | Escalabilidade                                     |     Sim      |
| RNF17 | Armazenamento e Retenção                           |     Não      |
| RNF18 | Procedimento para Incidentes                       |     Não      |
| RNF19 | Base Legal Específica                              |     Não      |

## Referências

<a id="PRESSMAN"></a>

> 1. SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. _Rastreabilidade de Requisitos_. Monografias em Ciência da Computação, n° 20/05. 2005.

## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição |
| :----- | :---------------: |
| Samuel |                   |
| Thiago |                   |
| Angélica |                   |

## Histórico de versão

| Versão |    Data    | Descrição                                                                         | Autor(es) | Revisor |
| :----: | :--------: | :-------------------------------------------------------------------------------- | :-------: | :-----: |
|  1.0   | 23/10/2025 | Criação inicial do documento                                                      |  Samuel   |    -    |
|  1.1   | 24/10/2025 | Edição inicial do documento                                                       |  Thiago   | Samuel  |
|  1.2   | 26/10/2025 | Adição dos Léxico e Épico                                                         |  Samuel   | Thiago  |
|  1.3   | 26/10/2025 | Adição dos hyperlinks (Cenário, Léxico, Caso de Uso, Épico e História de Usuário) |  Samuel   | Thiago  |
|  1.4   | 28/10/2025 | Adição dos hyperlinks e descrição na tabela de Requisitos Funcionais |  Angélica   | Thiago  |