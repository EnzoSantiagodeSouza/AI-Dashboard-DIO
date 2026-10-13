# Projeto de Organizador de Imposto de Renda - Bootcamp Santander & DIO
Este repositório contém o projeto desenvolvido como parte do Lab do Bootcamp Santander - Excel com IA e Claude, uma iniciativa promovida pela DIO (Digital Innovation One) em parceria com o Santander. O objetivo deste laboratório é explorar os recursos do ChatGPT para a criação de dashboards interativos em sites a partir de uma base de dados.

## Sobre o Projeto
O projeto consiste em um projeto de dashboard criado com IA sobre uma base de dados fictícia de vendas de carros da Porsche. Através da aplicação de recursos do ChatGPT, o projeto buscou desenvolver habilidades de engenharia de prompts e exploração das tecnologias da IA para a análise de dados.

## Recursos do ChatGPT Utilizados
Para a construção e o funcionamento eficiente do dashboard, foram utilizados recursos do ChatGPT, tais como:

- **Linguagem Natural**: Meio de se comunicar com a Inteligência Artifical.

- **Canvas**: Criação de dashboards interativos em HTML, com estilização em CSS e programação em Javascript.

## Estrutura do Repositório
```assets```: Pasta para conter recursos essenciais do projeto.

```└── database_porsche_sales.xlsx```: Arquivo com a base de dados fictícias.

```index.html```: Arquivo principal com as funcionalidades criadas com a IA.

```README.md```: Documentação descritiva do projeto.

## Perguntas de Negócio Fictícias
1. Qual modelo mais vendido em cada ano da análise - O que o público gosta nesse para replicarmos em próximos modelos
2. Qual estado com maior quantidade de vendas e o com menor - Para saber onde vende-se menos para melhorar o que for necessário baseado onde vende-se mais
3. Quantos carros já foram entregues e quantos estão pendentes - Não podemos deixar nossos clientes esperarem demais

## Prompts utilizados
```
Crie para mim um dashboard interativo com o recurso Canvas, baseado na planilha anexada. O design deve ser baseado em um estilo moderno, com cores preto, e tons de vermelho, semelhante ao site da Porsche: https://www.porsche.com/international/models/mission-s-preview/

PERGUNTAS DE NEGÓCIO QUE DEVEM SER RESPONDIDAS

1. Qual modelo mais vendido em cada ano da análise - O que o público gosta nesse para replicarmos em próximos modelos
2. Qual estado com maior quantidade de vendas e o com menor - Para saber onde vende-se menos para melhorar o que for necessário baseado onde vende-se mais
3. Quantos carros já foram entregues e quantos estão pendentes - Não podemos deixar nossos clientes esperarem demais

Filtros:
- Por estado
- Por ano

Deixe em big numbers, no início da página, KPIs necessárias, como o total das vendas, quantidade de vendas, e o que mais for interessante e relacionado às perguntas de negócio.
```


