# MoSCoW

## **1. Introdução**

O objetivo deste documento é definir e priorizar os requisitos funcionais para o desenvolvimento do site LigaMagic, uma plataforma online para a comunidade de jogadores de Magic: The Gathering. A técnica de priorização utilizada é a MoSCoW, que classifica os requisitos em quatro categorias para garantir que os esforços de desenvolvimento se concentrem nos recursos de maior valor e impacto para o sucesso do projeto. A elaboração deste documento seguiu os princípios e boas práticas delineados na lista de verificação sobre a técnica MoSCoW.

## **2. Metodologia de Priorização**

Para garantir um entendimento comum entre todas as partes interessadas, as definições de cada categoria MoSCoW são estabelecidas da seguinte forma:

- **Must (Deve Ter):** O requisito deve ser satisfeito para que a solução seja considerada um sucesso. Sem ele, o sistema não pode ser lançado.
- **Should (Deveria Ter):** O requisito é importante e deve ser incluído na solução, se possível, mas não é obrigatório para o sucesso da versão atual.
- **Could (Poderia Ter):** É uma capacidade desejável, mas que pode ser adiada ou eliminada. Será implementada apenas se o tempo e os recursos permitirem.
- **Won't (Não Terá):** Indica um requisito que não será implementado desta vez, mas pode ser incluído em uma versão futura. Para este projeto, a classificação "Won't" significa explicitamente "não será implementado na próxima versão", e não "não será implementado nunca", esclarecendo a ambiguidade potencial da categoria.

## **3. Requisitos Priorizados**

A seguir, os requisitos são apresentados agrupados por sua prioridade.

### **3.1. Requisitos _Must Have_ (Essenciais)**

Esses requisitos são fundamentais para a funcionalidade básica do site. O lançamento do produto não é viável sem a implementação completa destes itens.

|    ID    | Requisito                                   | Descrição                                                                                          |
| :------: | :------------------------------------------ | :------------------------------------------------------------------------------------------------- |
| **RF1**  | Permitir Cadastro de usuário                | O sistema deve permitir que um novo usuário crie uma nova conta.                                   |
| **RF2**  | Deve verificar duplicação de cadastros      | O sistema deve verificar se já existe um cadastro para o usuário que está tentando fazer cadastro. |
| **RF3**  | Deve permitir acesso via login e senha      | O sistema deve permitir que o usuário acesse sua conta utilizando login e senha cadastrados.       |
| **RF16** | Oferecer canal de contato para solicitações | O sistema deve disponibilizar canal (e-mail ou link) para o exercício dos direitos do titular.     |
| **RF18** | Permitir controle de cookies                | O sistema deve permitir que o usuário configure seu navegador para aceitar ou bloquear cookies.    |
| **RF19** | Solicitar atualização de dados pessoais     | O sistema deve permitir que o usuário atualize seus dados pessoais e comunicar alterações.         |

### **3.2. Requisitos _Should Have_ (Importantes)**

Estes requisitos são importantes e agregam valor significativo ao usuário, mas o site pode ser lançado sem eles em uma primeira versão.

|    ID    | Requisito                                            | Descrição                                                                                                         |
| :------: | :--------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------- |
| **RF4**  | Deve permitir apenas produtos relacionados a Magic   | O sistema deve restringir anúncios a produtos e serviços relacionados ao jogo Magic: The Gathering.               |
| **RF5**  | Deve verificar veracidade de dados cadastrados       | O sistema deve implementar mecanismos de validação de informações fornecidas pelos usuários.                      |
| **RF11** | Deve permitir envio e respostas a mensagens no fórum | O sistema deve possibilitar a participação dos usuários em fóruns de discussão (postagem e resposta).             |
| **RF15** | Garantir direitos de titulares                       | O sistema deve permitir que o usuário solicite acesso, correção, exclusão ou anonimização de seus dados pessoais. |

### **3.3. Requisitos _Could Have_ (Desejáveis)**

Estes requisitos são considerados melhorias ou funcionalidades adicionais que serão implementadas se houver tempo e recursos disponíveis após a conclusão dos requisitos _Must_ e _Should_.

|    ID    | Requisito                                                        | Descrição                                                                                                                           |
| :------: | :--------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------- |
| **RF6**  | Deve permitir inclusão de textos, descrição e fotos nos anúncios | O sistema deve permitir que usuários insiram descrições detalhadas e imagens em seus anúncios.                                      |
| **RF7**  | Deve facilitar contato direto com usuário                        | O sistema deve disponibilizar meios de contato direto (chat ou mensagens) entre usuários.                                           |
| **RF9**  | Deve permitir troca de mensagens privadas                        | O sistema deve permitir que usuários troquem mensagens privadas de forma segura.                                                    |
| **RF10** | Deve permitir criação de páginas pessoais                        | O sistema deve permitir que cada usuário personalize e mantenha sua página pessoal/profissional.                                    |
| **RF12** | Registrar dados pessoais do usuário                              | O sistema deve permitir o registro de dados como Nome, RG, CPF, Telefone, E-mail, Data de Nascimento e Endereço.                    |
| **RF13** | Utilizar dados para finalidades específicas                      | O sistema deve usar os dados pessoais para identificação, contato, gestão contratual, melhoria de serviços e envio de comunicações. |
| **RF17** | Utilizar cookies para personalização                             | O sistema deve utilizar cookies para facilitar login e personalizar a experiência de navegação.                                     |

### **3.4. Requisitos _Won't Have_ (Não Incluídos Nesta Versão)**

Os requisitos a seguir foram explicitamente deixados de fora do escopo desta versão do projeto para garantir a entrega dos itens de maior prioridade. Eles poderão ser reavaliados e priorizados em futuras versões.

|    ID    | Requisito                                     | Descrição                                                                                                           |
| :------: | :-------------------------------------------- | :------------------------------------------------------------------------------------------------------------------ |
| **RF8**  | Deve implementar cobrança de anúncios e venda | O sistema deve permitir a cobrança de taxas sobre anúncios ou vendas realizadas pela plataforma.                    |
| **RF14** | Compartilhar dados com parceiros              | O sistema deve possibilitar o compartilhamento de dados pessoais com parceiros, respeitando finalidades declaradas. |

## **4. Análise e Justificativa da Priorização**

Esta seção aborda como os princípios da lista de verificação foram aplicados para garantir uma priorização eficaz.

- **Distribuição das Prioridades:** Evitou-se uma concentração excessiva de requisitos na categoria "Must". A distribuição atual (_Must_, _Should_, _Could_ e _Won't_) é considerada razoável e realista para um ciclo de desenvolvimento, prevenindo o cenário onde todos os requisitos são tratados como críticos, o que na prática invalida a priorização.
- **Racionalidade e Conexão com os Objetivos de Negócio:** A classificação não foi apenas um exercício de rotulagem. Cada requisito "Must" está diretamente ligado à viabilidade do negócio: sem cadastro (RF1) e login (RF3), a plataforma não pode operar. Requisitos como a criação de fóruns (RF11) foram classificados como "Should", pois, embora importantes para a comunidade, o site pode ser lançado inicialmente sem essa funcionalidade, que pode ser adicionada posteriormente. Essa análise fundamenta a diferença entre o que é essencial e o que é importante.
- **Consciência sobre as Limitações da Técnica:** A equipe está ciente de que a MoSCoW não oferece, por si só, uma razão para a priorização, mas sim um esquema de classificação. Por isso, a justificativa para cada prioridade foi baseada na análise de importância e urgência, conectada aos objetivos de negócio do projeto.
- **Priorização como Processo Contínuo:** Esta priorização representa o estado atual do projeto. Conforme o desenvolvimento avança e novas informações surgem (feedback de usuários, mudanças no mercado, etc.), a lista de requisitos e suas prioridades serão revisitadas periodicamente. Isso garante que a equipe continue a alocar tempo e recursos nas atividades de maior valor ao longo do ciclo de vida do projeto.

## Video de Validação

[Link do Vídeo de Validação com Usuário:](https://youtu.be/lmzToU_Psmc)

## Histórico de versão

| Versão |    Data    | Descrição                             | Autor(es) | Revisor(es) |
| :----: | :--------: | :------------------------------------ | :-------: | :---------: |
|  1.0   | 30/09/2025 | Criação da página de documentação     |  Samuel   |   Thiago    |
|  1.1   | 02/09/2025 | Formatação e organização do documento |  Samuel   |      -      |
|  1.2   | 24/10/2025 | Adicionando o Vídeo de Validação |  Thiago   |      -      |
