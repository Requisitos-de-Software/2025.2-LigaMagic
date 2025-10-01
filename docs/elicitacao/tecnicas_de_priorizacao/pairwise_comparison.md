# Comparação em Pares - (Pairwise comparison and rank ordering)

## Introdução 
Para priorização dos requisitos neste projeto foi aplicada a técnica Pairwise Comparison, que consiste na comparação sistemática de todos os requisitos dois a dois, de forma a estabelecer sua relevância relativa dentro do sistema. Os requisitos comparados foram tirados da [análise de documentos](../tecnicas_de_elicitacao/analise_documentos.md)

## Metodologia 
A técnica foi aplicada seguindo os seguintes passos:

1. Comparação dos requisitos dentro de cada categoria
2. Definição de prioridades entre categorias
3. Cálculo do ranking final baseado no número de vitórias


## Requisitos Funcionais Analisados

| Categoria | ID | Requisito | Descrição |
|-----------|----|-----------|-----------|
| **Gestão de Produtos/Serviços** | RF4 | Deve permitir apenas produtos relacionados a Magic | O sistema deve restringir anúncios a produtos e serviços relacionados ao jogo Magic: The Gathering |
| **Comunicação Comunitária**     | RF11| Deve permitir envio e respostas a mensagens no fórum | O sistema deve possibilitar a participação dos usuários em fóruns de discussão (postagem e resposta) |
| **Comunicação**                 | RF9 | Deve permitir troca de mensagens privadas | O sistema deve permitir que usuários troquem mensagens privadas de forma segura |
| **Comunicação**                 | RF7 | Deve facilitar contato direto com usuário | O sistema deve disponibilizar meios de contato direto (chat ou mensagens) entre usuários |
| **Gestão de Anúncios**          | RF6 | Deve permitir inclusão de textos, descrição e fotos nos anúncios | O sistema deve permitir que usuários insiram descrições detalhadas e imagens em seus anúncios |
| **Gestão Financeira**           | RF8 | Deve implementar cobrança de anúncios e venda | O sistema deve permitir a cobrança de taxas sobre anúncios ou vendas realizadas pela plataforma |
| **Autenticação e Segurança**    | RF3 | Deve permitir acesso via login e senha | O sistema deve permitir que o usuário acesse sua conta utilizando login e senha cadastrados |
| **Autenticação e Segurança**    | RF5 | Deve verificar veracidade de dados cadastrados | O sistema deve implementar mecanismos de validação de informações fornecidas pelos usuários |
| **Gerenciamento de Usuários**   | RF1 | Permitir Cadastro de usuário | O sistema deve permitir que um novo usuário crie uma nova conta |
| **Gerenciamento de Usuários**   | RF2 | Deve verificar duplicação de cadastros | O sistema deve verificar se já existe um cadastro para o usuário que está tentando fazer cadastro |
| **Gerenciamento de Usuários**   | RF10| Deve permitir criação de páginas pessoais | O sistema deve permitir que cada usuário personalize e mantenha sua página pessoal/profissional |
| **Gerenciamento de Usuários**   | RF12| Registrar dados pessoais do usuário | O sistema deve permitir o registro de dados como Nome, RG, CPF, Telefone, E-mail, Data de Nascimento e Endereço |

## Resultados da Priorização
## Comparações por categoria
### Matriz de Comparação dentro da categoria: Gerenciamento de Usuários (implementar juntos obrigatoriamente)
|ID  | RF1 | RF2|RF12|Vitórias|
| ---|-----|----|----|-----------|
|**RF1** |-----|🔵  |🔴 | 1 |
|**RF2** |🔴   |----|🔴 | 0 |
|**RF12**|🔵   |🔵 |---| 2 |

### Matriz de Comparação dentro da categoria: Autenticação e Segurança (implementar juntos obrigatoriamente)
|ID  | RF3| RF5|Vitórias|
| ---|----|----|--------|
|**RF3** |----|🔵 |1|
|**RF5** |🔴 |----|0|

### Matriz de Comparação dentro da categoria: Comunicação
|ID  | RF9 |RF7 |RF11|Vitórias|
| ---|-----|----|----|-----------|
|**RF9** |-----|🔴 |🔵 | 1 |
|**RF7** |🔵  |----|🔵 | 2 |
|**RF11**|🔴  |🔴  |----| 0 |				

## Comparações entre os resultados das comparações por categorias
|Categorias                    |ID  |RF12|RF3 |RF7 |RF6 |RF8 |RF4 |RF10|Vitórias   |
| -----                        |--- |----|-   |----|----|----|----|----|-------    |
|Gerenciamento de Usuários     |**RF12** |----|🔵 |🔴 |🔴 |🔵 |🔴 |🔵|3  |
|Autenticação e Segurança      |**RF3**|🔴 |----|🔴 |🔴 |🔴 |🔴 |🔴 |0  |
|Comunicação                   |**RF7** |🔴 |🔵 |----|🔵 |🔵 |🔵 |🔵 |5    |
|Gestão de Anúncios            |**RF6**|🔵 |🔵 |🔴 |----|🔵 |🔴 |🔵 |4|
|Gestão Financeira             |**RF8**|🔴 |🔵 |🔴 |🔴 |----|🔴 |🔵 |2|
|Gestão de Produtos/Serviços   |**RF4** |🔵 |🔵 |🔴 |🔵 |🔵 |----|🔵 |5|
|Gerenciamento de Usuários     |**RF10**|🔴|🔵|🔴|🔴|🔴|🔴|----|1   |

#### Legenda:  
 🔵 Requisito da LINHA vence					
 🔴 Requisito da COLUNA vence	

## Posição		
|Posição|ID  |Vitórias   |
|------ |----|-----------|
|1|**RF7** |5|
|1|**RF4** |5|
|2|**RF6** |4|
|3|**RF12***|3|
|4|**RF8** |2|
|5|**RF10**|1|
|5|**RF9** |1|
|6|**RF3*** |0|
|6|**RF11**|0|

* O RF12 por estar em uma categoria que deve ser implementados junto com outros requisitos obrigatoriamente representa o bloco e Gerenciamento de Usuários (RF1, RF2, RF12), com 3 vitorias e na posição 3 (Média prioridade).
* O RF3 por estar em uma categoria que deve ser implementados junto com outros requisitos obrigatoriamente representa o bloco de Autenticação e Segurança (RF5), com 0 vitorias e na posição 6 (Baixa prioridade).

##  Ranking	Final dos Requisitos	
|Categoria         | Posição | Requisitos Incluídos|
|----              |-------  |-----------          |
| Alta prioridade  | 1 - 2   | RF7, RF4, RF6       |
| Média prioridade | 3 - 4   | RF12 (Bloco de Gerenciamento de Usuários (RF1, RF2, RF12)), RF8  |
| Baixa prioridade | 5 - 5   | RF9, RF3(Bloco de Autenticação e Segurança (RF5)), RF11           |
 
O RF7 e o RF4 se mostraram as funcionalidades mais prioritárias para o sistema, seguidas pelo RF6. Já o Gerenciamento de Usuários, embora essencial, ficou em prioridade média por comparação, e os requisitos RF9, RF3, RF5, RF11 empataram com vitórias mínimas, por isso foram classificados na mesma faixa de prioridade, baixa.

## Vídeo da priorização feita com um usuario 
Para realizar a priorização dos requisitos fizemos uma consulta com um usuario do app, disponivel aqui:

[Assista ao vídeo no YouTube](https://youtu.be/NiyykwAPFow). Este video foi produzido pela aluna Angélica Campos e Guilherme Oliveira.

[Tabelas usadas com o usuario](pairwisecomparetion.pdf)

## Histórico de versão

| Versão |    Data     |        Descrição               | Autor     |    Revisor |
|:------:|:-----------:|:------------------------------:|:---------:|:----------:|
|  1.0   | 28/09/2025  | Criação da estrutura da página | Angélica  |  Marcelo   |
|  1.1   | 30/09/2025  |       Adição do ranking        | Angélica  |  Marcelo   |
|  1.2   | 30/09/2025  |        Adição do video         | Angélica  |  Marcelo   |