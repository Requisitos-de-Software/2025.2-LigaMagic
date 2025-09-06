## Introdução

Este documento tem o objetivo de consolidar padrões de uso do Git no desenvolvimento doa projeto. Neste projeto usaremos uma adaptação do padrão git flow. Este conceito tem seu fundamento na organização de repositórios, atribuindo políticas de uso e restrições de segurança, sempre com o objetivo de cumprir com as práticas mais adequadas, observadas e aperfeiçoadas ao longo do tempo. Nota-se que o idioma que se seguirá na política de constribuição é o português.

## Fluxo de Branches

Para garantir um fluxo de trabalho contínuo e de forma padronizada, possibilitando o rastreamento das funcionalidades desenvolvidas e facilitando o desenvolvimento contínuo. Os conceitos-chave para implementação da estratégia serão:

- ```Main```: Branch de produção, responsável por abrigar o código da última release.
- ```Feature```: Branch de desenvolvimento de funcionalidade, representa a branch de trabalho sob uma determinada funcionalidade, tarefa, correção de bugs e afins.

É importante que a branch de funcionalidade seja criada seguindo o padrão:

- <b>feat#(número-da-issue)/(US)-(nome-da-issue)</b>
- Exemplo: feat#74/US05-Login

Ela deve ser criada a partir da branch de produção ```Main```.

A branch de correção deve ser criada no padrão:

- <b>fix#(número-da-issue)/(nome-da-issue)</b>
- Exemplo: fix#74/US05-Login

Ela deve originar-se da branch que apresentou o erro.

## Commits

As informações abaixo referem-se aos padrões de escrita de commits do nosso repositório:

1. Sempre dividir o trabalho em pequenos e significativos commits, de maneira que cada commit implemente apenas uma funcionalidade.
2. A anatomia do commit deve seguir o formato determinado abaixo:

```
[tipo](#número da issue): assunto 
```
> As opções permitidas para o campo ```tipo``` são:

- ```feat```: nova funcionalidade
- ```docs```: relacionado à documentação
- ```refact```: refatoração de código
- ```fix```: correções

> As opções permitidas para o campo ```tipo``` são:

- Mensagem curta e sucinta
- Todo texto deve estar sempre em letras minúsculas
- Deve conter ```o que```

Exemplo de commit: 
```
[refact](#25): ajustando página de login  
```

## Pull Request

Por meio do processo de pull request, realizado no GitHub, toda nova funcionalidade deve ser integrada à branch ```Main```. Mas isso semente será feito após todos os critérios de sucesso para a feature estarem atendidos.

## Histórico de versão
| Versão | Data | Descrição | Autor(es)	 | Revisor(es)	 |
|:--:|:------------:|:-----------:|:----:| :----:|
|  1.0  |       06/09/2025       |       Versão inicial da pagina	      |   Angélica   |      |