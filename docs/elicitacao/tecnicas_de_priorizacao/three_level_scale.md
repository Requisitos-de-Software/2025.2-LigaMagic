#  Three Level Scale

## Introdução  
Priorização é fundamental para organizar projetos e facilitar decisões em desenvolvimento de software. No processo de elicitação de requisitos, a técnica **Tree Level** permite organizar os requisitos em níveis de importância. 

## Metodologia

Para realizar a priorização dos requisitos, utilizou-se como base os requisitos funcionais e não funcionais previamente elicitados.  A classificação foi feita utilizando a técnica Three-Level Scale, que permite categorizar cada requisito em três níveis de prioridade:

1. Alta: requisitos essenciais que devem ser implementados obrigatoriamente no produto final
2. Média: requisitos importantes, mas cuja implementação pode ser adiada sem comprometer a funcionalidade principal
3. Baixa: requisitos desejáveis, que agregam valor ao produto, mas não são críticos para o seu funcionamento inicial

A decisão sobre o nível de prioridade de cada requisito considerou o contexto as necessidades identificadas durante a observação de usuários. Essa abordagem possibilitou uma priorização consistente.

## Requisitos Funcionais  

| ID   | Requisito                                                                                                          | Prioridade  | Descrição                                                                                    |
|------|--------------------------------------------------------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------|
| RF01 | Permitir que o usuário pesquise cartas pelo nome                                                                   | Alta        | Permitir que o usuário encontre cartas específicas utilizando o nome como critério de busca. |
| RF02 | Permitir que o usuário filtre cartas por preço, condição e idioma                                                  | Alta        | Facilitar a seleção de cartas com base em preço, estado e idioma.                            |
| RF03 | Exibir resultados da pesquisa com preço, condição, idioma e reputação do vendedor                                  | Alta        | Informação mínima para o usuário tomar decisão de compra.                                    |
| RF04 | Permitir que o usuário realize a compra de cartas cadastradas                                                      | Alta        | Permitir a aquisição de cartas, incluindo informações pessoais e endereço de entrega.        |
| RF05 | Permitir que o usuário acesse seu histórico de compras                                                             | Alta        | Fundamental para que o usuário acompanhe suas transações.                                    |
| RF06 | Permitir que o usuário visualize decks publicados                                                                  | Média       | Informação útil, mas não impede operação principal.                                          |
| RF07 | Permitir que o usuário busque tópicos, leia, responda e crie postagens no fórum                                    | Média       | Facilitar interação do usuário com a comunidade e discussões sobre cartas.                   |
| RF08 | Permitir que o usuário visualize detalhes de uma carta                                                             | Alta        | Essencial para avaliar a carta antes de comprar.                                             |
| RF09 | Permitir que o usuário adicione cartas a listas (desejo/carrinho/coleção)                                          | Média       | Facilita organização do usuário, mas não bloqueia compra.                                    |
| RF10 | Permitir que o usuário avalie ou dê feedback sobre vendedores ou decks                                             | Baixa       | Suporte à confiança do usuário, mas não crítico.                                             |
| RF11 | Permitir que o usuário visualize informações detalhadas da carta, incluindo edição, idioma, condição e preço médio | Alta        | Informações completas para melhor decisão de compra.                                         |
| RF12 | Permitir que o usuário defina um alerta de preço para a carta selecionada                                          | Média       | Notificar o usuário sobre alterações de preço em cartas de interesse.                        |
| RF13 | Permitir que o usuário busque decks que utilizam a carta selecionada                                               | Média       | Ajudar o usuário a conhecer estratégias relacionadas à carta.                                |
| RF14 | Permitir que o usuário visualize o preço médio da carta em diferentes edições e condições                          | Média       | Facilitar análise comparativa de preços por edição e estado.                                 |
| RF15 | Permitir que o usuário acesse o histórico de preços da carta em formato gráfico                                    | Média       | Auxiliar no acompanhamento de tendências de preço da carta.                                  |
| RF16 | Permitir que o usuário adicione a carta a diferentes listas (coleção, deck, lista de desejos, carrinho)            | Média       | Organizar cartas de acordo com finalidade desejada.                                          |
| RF17 | Permitir que o usuário compartilhe informações da carta em redes sociais ou por link direto                        | Baixa       | Conveniência extra, não essencial.                                                           |
| RF18 | Permitir que o usuário reporte problemas relacionados à carta                                                      | Baixa       | Informar erros ou anúncios suspeitos para manutenção do sistema.                             |

<sub>Fonte: [Vera Lucia](https://github.com/verabelucia) e [Guilherme]( https://github.com/GuilhermeOliveira1327), 2025</sub>



## Requisitos Não Funcionais  

| ID    | Requisito                                                                                    | Prioridade   | Descrição                                                         |
|-------|----------------------------------------------------------------------------------------------|--------------|-------------------------------------------------------------------|
| RNF01 | O site deve apresentar informações de cartas, anúncios e decks de forma organizada e legível | Alta         | Facilitar leitura e compreensão das informações pelo usuário.     |
| RNF02 | O sistema deve garantir a transmissão segura de dados pessoais e informações de pagamento    | Alta         | Proteção de dados sensíveis durante transações e armazenamento.   |
| RNF03 | O sistema deve fornecer mensagens claras de sucesso ou erro                                  | Alta         | Informar corretamente o usuário sobre o resultado de suas ações.  |
| RNF04 | O sistema deve ser compatível com os principais navegadores                                  | Alta         | Permitir acesso consistente em Chrome, Firefox, Edge e Safari.    |
| RNF05 | O sistema deve garantir backup automático dos dados de usuários e transações                 | Média        | Evitar perda de informações em caso de falha do sistema.          |
| RNF06 | Mensagens de alerta, erro ou confirmação devem ser exibidas de forma clara e consistente     | Alta         | Facilitar compreensão e consistência na interação do usuário.     |
| RNF07 | O site deve criptografar dados sensíveis do usuário                                          | Alta         | Proteger senhas e informações de pagamento.                       |
| RNF08 | O site deve carregar corretamente em dispositivos móveis com telas menores que 6 polegadas   | Alta         | Garantir que o site funcione em smartphones pequenos.             |

<sub>Fonte: [Vera Lucia](https://github.com/verabelucia) e [Guilherme]( https://github.com/GuilhermeOliveira1327), 2025</sub>


## Validação com Usuário
No video abaixo é feito a validação com o integrante [Guilherme]( https://github.com/GuilhermeOliveira1327), com a usuária....

## Bibliografia

> 1. VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de requisitos: software orientado ao negócio. Disponível em: [Aprender3](https://aprender3.unb.br/pluginfile.php/3210603/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf)


## Histórico de versão

| Versão |    Data    |                  Descrição                   |                          Autor                          |                        Revisor                         |
|:------:|:----------:|:--------------------------------------------:|:-------------------------------------------------------:|:------------------------------------------------------:|
|  1.0   | 24/09/2025 |        Criação da estrutura da página        |      [Vera Lucia](https://github.com/verabelucia)       | [Guilherme]( https://github.com/GuilhermeOliveira1327) |
|  1.1   | 28/09/2025 | Colocado nivél de priorização nos requisitos |      [Vera Lucia](https://github.com/verabelucia)       | [Guilherme]( https://github.com/GuilhermeOliveira1327) |
|  1.2   | 29/09/2025 |           Adicionando Bibliografia           | [Guilherme]( https://github.com/GuilhermeOliveira1327)  |   [Vera Lucia](https://github.com/verabelucia)         |