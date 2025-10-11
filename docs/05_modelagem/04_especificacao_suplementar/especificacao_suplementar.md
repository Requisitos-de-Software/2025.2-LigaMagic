# Especificação Suplementar

## Descrição

Este documento apresenta a Especificação Suplementar do sistema LigaMagic, utilizando o modelo FURPS+ para garantir que o software atenda não apenas aos requisitos funcionais, mas também aos aspectos de qualidade, como segurança, desempenho, usabilidade e suportabilidade.

## Objetivo

O objetivo deste documento é detalhar os requisitos não funcionais do sistema, garantindo que todas as necessidades de desempenho, segurança, compatibilidade e qualidade sejam atendidas durante o desenvolvimento e manutenção da plataforma.

## Metodologia

A elaboração desta Especificação Suplementar organizar e detalhar os requisitos do sistema LigaMagic de forma estruturada. A especificação segue o modelo FURPS+, que organiza os requisitos nas seguintes categorias:

- Funcionalidade: regras de negócio, validações e exigências legais específicas do sistema LigaMagic.
- Usabilidade: interface intuitiva, acessibilidade e experiência do consumidor.
- Confiabilidade: segurança dos dados, disponibilidade e tolerância a falhas.
- Desempenho: tempos de resposta, capacidade de atendimento em horários de pico e escalabilidade da aplicação.
- Suporte: manutenção, documentação e compatibilidade com múltiplas plataformas (Web, Android e iOS).
- Outros (“+”): restrições legais, padrões de identidade digital e integração com sistemas externos ou governamentais.

## Distribuição de especificaçoes por integrante

| Integrante | Especificação   |
| :--------- | :-------------- |
| Angélica   | Usabilidade     |
| Vera       | Usabilidade     |
| Thiago     | Usabilidade     |
| Samuel     | Compatibilidade |
| Raissa     | Suportabilidade |
|Marcelo |   Confiabilidade |

## Definições, Acrônimos e Abreviações

- RNF - Requisito não funcional
- US - Usabilidade
- COM - Compatibilidade
- CON - Confiabilidade
- SUP - Suportabilidade

## Funcionalidades

As funcionalidades deste projeto foram listados a partir das técnicas de elicicação:

- Analise de Dcumentos
- Observação
- Glossário

Os requisitos que foram elicitados com essas técnicas estão no artefato [Requisitos Elicitados](../../03_elicitacao/artefatos/requisitos_elicitados.md)

## Usabilidade (Usability)

A usabilidade do sistema deve garantir uma experiência de uso fluida, intuitiva e consistente para o consumidor deve seguir padrões visuais e de navegação conhecidos.

|  ID  | Descrição                                                                                                                                                 | Rastreabilidade                                                 | Autor   |
| :--: | :-------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------- | :-----  |
| US01 | As informações sobre cartas, anúncios e decks devem ser organizadas de forma clara, com boa legibilidade e espaçamento adequado, facilitando a navegação. | [RNF09](../../03_elicitacao/artefatos/requisitos_elicitados.md) | Vera    |
| US02 | As mensagens de alerta, erro e confirmação devem aparecer de forma padronizada e visível, para evitar confusões.                                          | [RNF14](../../03_elicitacao/artefatos/requisitos_elicitados.md) | Angélica|
| US03 | O site deve ser totalmente responsivo, garantindo boa visualização e funcionalidade em computador, tablet e smartphone.                                   | [RNF08](../../03_elicitacao/artefatos/requisitos_elicitados.md) | Thiago  |

Fonte: [Vera Lucia](https://github.com/verabelucia), [Angélica](https://github.com/angelicaccampos) e [Thiago](https://github.com/Acciolyy), 2025


## Desempenho (Performance)

Esta seção avalia os requisitos de desempenho do software, podendo usar como medida diversos aspectos, entre eles o tempo de resposta às solicitações, o consumo de memória, a utilização da CPU e a capacidade de carga do sistema.

## Confiabilidade

A confiabilidade do software está relacionado à sua integridade e conformidade, analisando a capacidade do sistema de funcionar corretamente mesmo diante de falhas.

|  ID   | Descrição                                                  | Rastreabilidade                                                 |
| :---: | :--------------------------------------------------------- | :-------------------------------------------------------------- |
| CON01 | Garantir que anúncios incluam informações fiscais corretas | [RNF07](../../03_elicitacao/artefatos/requisitos_elicitados.md) |
|CON02  | O site deve ser compatível com as versões mais recentes dos principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge e Safari)|[RNF12](../../03_elicitacao/artefatos/requisitos_elicitados.md) |

**Fonte:** Marcelo e Samuel,2025

## Suportabilidade

Os requisitos de suportabilidade se referem às características que tornam o software mais fácil de usar, manter e adaptar. Entre essas características estão a testabilidade, adaptabilidade, manutenibilidade, compatibilidade, configurabilidade, instalabilidade, escalabilidade, localizabilidade, entre outras.

|  ID   | Descrição                                                                                                          | Rastreabilidade                                                 |
| :---: | :----------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------- |
| SUP01 | Permite que o sistema seja alterado ou atuaizado sem interromper o uso, ligado a manutenibilidade e adaptabilidade | [RNF06](../../03_elicitacao/artefatos/requisitos_elicitados.md) |
| SUP02 | O sistema funcione em diferentes navegadores                                                                       | [RNF12](../../03_elicitacao/artefatos/requisitos_elicitados.md) |

Fonte: [Raissa](https://github.com/RaissaAndradeS), 2025

## Requisitos de Design

Os requisitos de design, também conhecidos como restrições de projeto, definem limitações ou diretrizes que devem ser seguidas durante o desenvolvimento do sistema. Esses requisitos estabelecem parâmetros que influenciam a estrutura e o comportamento do software, como a linguagem de programação utilizada, o processo de desenvolvimento adotado, as ferramentas de apoio empregadas e o uso de bibliotecas ou frameworks específicos.



## Requisitos de Implementação

Os requisitos de implementação determinam condições técnicas ou restrições relacionadas ao desenvolvimento do código e à construção do sistema. Eles orientam como o software deve ser implementado, especificando aspectos como padrões obrigatórios de programação, linguagens de desenvolvimento permitidas, políticas de integridade e segurança do banco de dados, além de limitações de recursos e ambientes operacionais compatíveis.



## Requisitos de Interface

Os requisitos de interface definem ou limitam as funcionalidades e interações entre o sistema e o jogador. Eles estabelecem como os elementos da interface devem se comportar e se apresentar, garantindo consistência visual, clareza nas informações exibidas e facilidade de uso durante a navegação no sistema.



## Video de validação feita com um jogador
Para a validação da Especificação Suplementar, cada integrante do grupo ficou responsável por validar a especificação suplementar de sua autoria. A seguir, são apresentados os vídeos referentes às validações realizadas:

- [Assista ao vídeo no YouTube](https://youtu.be/LLM2-XJXOMU). Este video foi produzido pela aluna Angélica Campos.
- [Assista ao vídeo no YouTube](https://youtu.be/OHdbeTbz57o).  Este video é referente à validação especificação suplementar de usabelidade e foi produzido pela aluna Vera.
- [Assista ao vídeo no YouTube](https://youtu.be/1lxHnaYfWR4).  Este video é referente à validação especificação suplementar de Confiabilidade e foi produzido pelo aluna Marcelo (Os minutos estão na descrição).
- [Assista ao vídeo no YouTube](https://www.youtube.com/watch?v=YXONTjL32WU) Este vídeo foi produzido pelo aluno Samuel, sendo referente à validação da especificação suplementar de Compatibilidade (Os minutos estão na descrição).
- [Assista ao vídeo no YouTube](https://www.youtube.com/watch?v=YXONTjL32WU) Este vídeo foi produzido pelo aluno Thiago, sendo referente à validação da especificação suplementar de Usabilidade (Os minutos estão na descrição).
- [Assista ao vídeo no YouTube](https://www.youtube.com/watch?v=ZlX_tKeczd8) Este vídeo foi produzido pela aluna Raissa, sendo referente à validação da especificação suplementar de Suportabilidade (Os minutos estão na descrição).

## Bibliografia

> 1.FURPS+. QualidadeBR, 10 jul. 2008. Disponível em: https://qualidadebr.wordpress.com/2008/07/10/furps/
> . Acesso em: 9 out. 2025.

## Nível de Contribuição dos Integrantes

| Nome   | % de Contribuição        |
| :----- | :---------------:         |
|Angélica| 16,67%                   |
|Raissa |   16,67%             |
|Vera|      16,67%             |
| Samuel |     16,67%             |
| Thiago |    16,67%            |
|Marcelo |      16,67%           |

## Histórico de versão

| Versão |    Data    | Descrição                                            |                  Autor(es)                   |                   Revisor                   |
| :----: | :--------: | :--------------------------------------------------- | :------------------------------------------: | :-----------------------------------------: |
|  1.0   | 08/10/2025 | Adicionando conteudo                                 | [Vera Lucia](https://github.com/verabelucia) | [Raissa](https://github.com/RaissaAndradeS) |
|  1.1   | 09/10/2025 | Adicionado conteúdo em confiabilidade                |                   Marcelo                    |                   Thiago                    |
|  1.2   | 10/10/2025 | Adicionado conteúdo em compatibilidade e usabilidade |                Samuel, Thiago                |                    Vera                     |
|  1.3   | 10/10/2025 | Corrigindo "usuários" do projeto" e pequenas coisas |             Thiago                |                    Samuel                     |
|1.4| 11/10/2025| Adição do vídeo de validação | Vera | Angélica |
|1.5| 11/10/2025| Adição do vídeo de validação | Marcelo | Thiago|
|1.5.1| 11/10/2025| Adição do vídeo de validação dos integrantes | Thiago | Marcelo |
