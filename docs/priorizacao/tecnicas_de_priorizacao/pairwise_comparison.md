# Comparação em Pares - (Pairwise comparison and rank ordering)

## Introdução 
Para priorização dos requisitos neste projeto foi aplicada a técnica Pairwise Comparison, que consiste na comparação sistemática de todos os requisitos dois a dois, de forma a estabelecer sua relevância relativa dentro do sistema. Os requisitos comparados foram tirados da [análise de documentos](../../elicitacao/tecnicas_de_elicitacao/analise_documentos.md)

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
|RF1 |-----|RF1 |RF1 |-----------|
|RF2 |RF2  |----|RF2 |-----------|
|RF12|RF12 |RF12|----|-----------|

Os RF1, RF2 e RF12 só fazem sentido juntos (cadastro de usuário + duplicação + dados pessoais), então foram avaliados juntos e o RF10 foi avaliado entre os resultados das comparações por categorias.


### Matriz de Comparação dentro da categoria: Autenticação e Segurança (implementar juntos obrigatoriamente)
|ID  | RF3| RF5|Vitórias|
| ---|----|----|-----------|
|RF3 |----|RF3 |-----------|
|RF5 |RF5 |----|-----------|

### Matriz de Comparação dentro da categoria: Comunicação
|ID  | RF9 |RF7 |RF11|Vitórias|
| ---|-----|----|----|-----------|
|RF9 |-----|RF9 |RF9 |-----------|
|RF7 |RF7  |----|RF7 |-----------|
|RF11|RF11 |RF11|----|-----------|

#### Legenda:  
 🔵 Requisito da LINHA vence					
 🔴 Requisito da COLUNA vence					

## Comparações entre os resultados das comparações por categorias
|Categorias                    |ID  | RF0|RF0 |RF0 |RF6 |RF8 |RF4 |RF10|Vitórias   |
| -----                        |--- |----|-   |----|----|----|----|----|-------    |
|Gerenciamento de Usuários     |RF0 |----|RF0 |RF0 |RF0 |RF0 |RF0 |----|-------    |
|Autenticação e Segurançagorias|RF0 |RF0 |----|RF0 |RF0 |RF0 |RF0 |RF0 |-------    |
|Comunicação                   |RF0 |RF0 |RF0 |----|RF0 |RF0 |RF0 |RF0 |-------    |
|Gestão de Anúncios            |RF6 |RF6 |RF6 |RF6 |----|RF6 |RF6 |RF6 |-----------|
|Gestão Financeira             |RF8 |RF8 |RF8 |RF8 |RF8 |----|RF8 |RF8 |-----------|
|Gestão de Produtos/Serviços   |RF4 |RF4 |RF4 |RF4 |RF4 |RF4 |----|RF4 |-----------|
|Gerenciamento de Usuários     |RF10|RF10|RF10|RF10|RF10|RF10|RF10|----|-------    |

## Posição		
|Posição|ID  |Vitórias   |
|------ |----|-----------|
|----  -|RF1 |----|
|----  -|RF2 |----|
|----  -|RF3 |----|
|----  -|RF4 |----|
|----  -|RF5 |----|
|----  -|RF6 |----|
|----  -|RF7 |----|
|----  -|RF8 |----|
|----  -|RF9 |----|
|----  -|RF10|----|
|----  -|RF11|----|
|----  -|RF12|----|


##  Ranking	Final dos Requisitos	
|Categoria         | Posição | Requisitos Incluídos|
|----              |-------  |-----------          |
| Alta prioridade  | 1 - 5   |                     |
| Média prioridade | 6 - 9   |                     |
| Baixa prioridade | 10 - 12 |                     |

## Histórico de versão

| Versão |    Data     |                        Descrição                        |                     Autor                     |                     Revisor                     |
|:------:|:-----------:|:-------------------------------------------------------:|:---------------------------------------------:|:-----------------------------------------------:|
|  1.0   | 28/9/2025  | Criação da estrutura da página| Angélica|Marcelo|