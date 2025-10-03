# Observação

## Descrição

A observação consiste em acompanhar como o usuário interage com a aplicação, registrando seu comportamento, as tarefas realizadas, eventuais obstáculos encontrados e oportunidades de melhoria.

## Objetivo

Identificar aspectos relacionados à usabilidade, navegação e funcionalidades do site LigaMagic por meio da técnica de elicitação por observação. Serão analisadas as interações de usuários, destacando dificuldades, comportamentos e oportunidades de melhoria, com o objetivo de propor recomendações que aprimorem a experiência, a eficiência e a satisfação no uso da plataforma.

## Método de Observação

A observação foi conduzida pelo integrante [Guilherme](https://github.com/GuilhermeOliveira1327), utilizando a técnica de observação ativa guiada por tarefas, com um usuário participante. O objetivo foi compreender como o usuário interage com o site LigaMagic, identificar dificuldades na navegação e nas funcionalidades, e coletar informações que ajudem a aprimorar a experiência do usuário. Para conduzir a observação, foi elaborado um roteiro de ações, que foi lido e apresentado ao usuário.

## Ações Observadas

Foram criadas algumas ações para que o usuário pudesse seguir durante a observação.

| N°  | Questões                           | Objetivo da ação                                                                      |
| :-: | :--------------------------------- | :------------------------------------------------------------------------------------ |
|  1  | Navegação inicial                  | Avaliar se o usuário consegue localizar as principais seções do site                  |
|  2  | Busca de cartas no marketplace     | Verificar se o usuário consegue encontrar cartas específicas                          |
|  3  | Filtrar carta por preço e condição | Avaliar se o usuário consegue aplicar filtros para selecionar a carta desejada        |
|  4  | Cadastro para realizar compra      | Observar se o usuário consegue cadastrar-se ou preencher dados para comprar uma carta |
|  5  | Realizar compra da carta           | Verificar se o usuário consegue concluir a compra                                     |
|  6  | Comparação de anúncios             | Analisar critérios que o usuário utiliza para escolher entre diferentes anúncios      |
|  7  | Exploração de decks                | Avaliar se o usuário compreende a composição e estratégia do deck                     |
|  8  | Interação no fórum                 | Verificar como o usuário busca tópicos, lê e responde mensagens                       |
|  9  | Uso em dispositivo móvel           | Observar a responsividade e usabilidade no celular                                    |

<sub>Fonte: [Vera Lucia](https://github.com/verabelucia) e [Guilherme](https://github.com/GuilhermeOliveira1327), 2025</sub>

## Requisitos Funcionais

## Requisitos Funcionais – Usuário Comprador

|  ID  | Requisitos                      |        Categoria         | Descrição                                                                                                     |
| :--: | :------------------------------ | :----------------------: | :------------------------------------------------------------------------------------------------------------ |
| RF01 | Pesquisa de cartas pelo nome    |   Pesquisa e Filtragem   | Permitir que o usuário pesquise cartas pelo                                                                   |
| RF02 | Filtrar cartas                  |   Pesquisa e Filtragem   | Permitir que o usuário filtre cartas por preço, condição e idioma                                             |
| RF03 | Exibir resultados da pesquisa   |   Pesquisa e Filtragem   | Mostrar preço, condição, idioma e reputação do vendedor ao pesquisar uma carta                                |
| RF04 | Realizar compra                 |     Compra de Cartas     | Permitir que o usuário compre cartas cadastradas, incluindo dados pessoais e endereço de entrega              |
| RF05 | Histórico de compras            | Gerenciamento de Usuário | Permitir que o usuário acesse seu histórico de compras com informações detalhadas                             |
| RF06 | Visualizar decks                |   Interação com Cartas   | Permitir que o usuário visualize decks publicados, com lista de cartas                                        |
| RF07 | Fórum                           |  Interação com Usuários  | Permitir que o usuário busque tópicos, leia, responda e crie postagens no fórum                               |
| RF08 | Detalhes da carta               |   Interação com Cartas   | Permitir que o usuário visualize detalhes de uma carta ao clicar no resultado da pesquisa                     |
| RF09 | Adicionar a listas              | Gerenciamento de Usuário | Permitir que o usuário adicione cartas à lista de desejos, carrinho ou coleção                                |
| RF10 | Avaliar ou dar feedback         |  Interação com Usuários  | Permitir que o usuário avalie ou dê feedback sobre vendedores ou decks                                        |
| RF11 | Informações detalhadas da carta |   Interação com Cartas   | Mostrar edição, idioma, condição e preço médio de cada carta                                                  |
| RF12 | Alerta de preço                 |   Relatórios e Alertas   | Permitir que o usuário defina um alerta de preço para a carta selecionada                                     |
| RF13 | Buscar decks relacionados       |   Interação com Cartas   | Permitir que o usuário busque decks que utilizam a carta selecionada                                          |
| RF14 | Preço médio por edição          |   Relatórios e Alertas   | Permitir que o usuário visualize o preço médio da carta em diferentes edições e condições                     |
| RF15 | Histórico de preços             |   Relatórios e Alertas   | Permitir que o usuário acesse o histórico de preços da carta em formato gráfico                               |
| RF16 | Adicionar a diferentes listas   | Gerenciamento de Usuário | Permitir que o usuário adicione a carta a diferentes listas (coleção, deck, lista de desejos, carrinho)       |
| RF17 | Compartilhar carta              |  Interação com Usuários  | Permitir que o usuário compartilhe informações da carta em redes sociais ou por link direto                   |
| RF18 | Reportar problemas              |  Interação com Usuários  | Permitir que o usuário reporte problemas relacionados à carta (erros de informação, anúncios suspeitos, etc.) |

<sub>Fonte: [Vera Lucia](https://github.com/verabelucia) e [Guilherme](https://github.com/GuilhermeOliveira1327), 2025</sub>

---

## Requisitos Não Funcionais (RNF)

## Requisitos Não Funcionais – Usuário Comprador

|  ID   | Requisitos                      |    Categoria    | Descrição                                                                                                        |
| :---: | :------------------------------ | :-------------: | :--------------------------------------------------------------------------------------------------------------- |
| RNF01 | Site responsivo                 |   Usabilidade   | O site deve ser totalmente responsivo, garantindo boa visualização em computador, tablet e smartphone            |
| RNF02 | Organização da informação       |   Usabilidade   | O site deve apresentar informações de cartas, anúncios e decks de forma organizada e legível                     |
| RNF03 | Transmissão segura de dados     |    Segurança    | O sistema deve garantir a transmissão segura de dados pessoais e informações de pagamento                        |
| RNF04 | Mensagens de sucesso/erro       |   Usabilidade   | O sistema deve fornecer mensagens claras de sucesso ou erro ao realizar ações como cadastro, compra ou inscrição |
| RNF05 | Compatibilidade com navegadores | Compatibilidade | O site deve ser compatível com os principais navegadores (Chrome, Firefox, Edge, Safari)                         |
| RNF06 | Backup automático               |     Backup      | O sistema deve garantir backup automático dos dados de usuários e transações                                     |
| RNF07 | Alertas e confirmações          |   Usabilidade   | Mensagens de alerta, erro ou confirmação devem ser exibidas de forma clara e consistente                         |
| RNF08 | Criptografia de dados sensíveis |    Segurança    | O site deve criptografar dados sensíveis do usuário, como senhas e informações de pagamento                      |
| RNF09 | Suporte a telas pequenas        |   Usabilidade   | O site deve carregar corretamente em dispositivos móveis com telas menores que 6 polegadas                       |

<sub>Fonte: [Vera Lucia](https://github.com/verabelucia) e [Guilherme](https://github.com/GuilhermeOliveira1327), 2025</sub>

## Validação com Usuário

Este vídeo apresenta a aplicação da técnica de Observação para elicitação de requisitos, registrando como os usuários interagem com o sistema em situações reais de uso. A atividade foi conduzida por [Guilherme](https://github.com/GuilhermeOliveira1327), que acompanhou as ações dos usuários

<iframe width="560" height="315" 
    src="https://www.youtube.com/embed/YeQpnw3gJto" 
    title="Validação com Usuário - Observação" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
</iframe>

## Bibliografia

> 1. Site LigaMagic. Disponível em: https://www.ligamagic.com.br/ Acesso em: 26/09/2025.
> 2. VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de requisitos: software orientado ao negócio. Disponível em: [Aprender3](https://aprender3.unb.br/pluginfile.php/3210603/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf)

## Histórico de versão

| Versão |    Data    | Descrição                             |                         Autor                         |                        Revisor                        |
| :----: | :--------: | :------------------------------------ | :---------------------------------------------------: | :---------------------------------------------------: |
|  1.0   | 24/09/2025 | Criação da estrutura da página        |     [Vera Lucia](https://github.com/verabelucia)      | [Guilherme](https://github.com/GuilhermeOliveira1327) |
|  1.1   | 28/09/2024 | Criação das ações para o usuário      |     [Vera Lucia](https://github.com/verabelucia)      | [Guilherme](https://github.com/GuilhermeOliveira1327) |
|  1.2   | 29/09/2024 | Adicionando Bibliografia              | [Guilherme](https://github.com/GuilhermeOliveira1327) |     [Vera Lucia](https://github.com/verabelucia)      |
|  1.3   | 02/09/2025 | Formatação e organização do documento |                        Samuel                         |                           -                           |
