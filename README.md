# COVID19Brasil
## Dados do Coronavirus (COVID-19): Brasil x Outros Países

**Acesse a dashboard [clicando aqui](http://coronavirus.leonardofullana.com/Dashboard_COVID19_Brasil.html)**

A Dashboard comparativa do Coronavírus (COVID-19) no Brasil x Outros Países dá uma visão geral do cenário da pandemia em 2020 para o Brasil. Essa dashboard foi construída na linguagem R usando o framework R Markdown e foi adaptada dessa [dashboard](https://ramikrispin.github.io/coronavirus_dashboard/) por Rami Krispin.

## Código

O código por trás dessa dashboard está disponível no [GitHub](https://github.com/leonardofullana/CoronavirusBrasil).

## Dados

Os dados utilizados nessa dashboard vêm do dataset disponível do pacote R [`{coronavirus}`](https://github.com/RamiKrispin/coronavirus). Para ter os últimos dados, tenha certeza de estar baixando a versão de desenvolvimento do pacote:

```
install.packages("devtools")
devtools::install_github("RamiKrispin/coronavirus")
```

Os dados e a dashboard são atualizados diariamente.

Os dados brutos são adquiridos do [repositório](https://github.com/RamiKrispin/coronavirus-csv) sobre o Coronavírus do Johns Hopkins University Center for Systems Science and Engineering (JHU CCSE).

**Metodologia de Projeção**
A estimativa é do Centro para Modelagem Matemática de Doenças Infecciosas da London School of Tropical Medicine, do Reino Unido, que fez uma estimativa da subnotificação da covid-19 em vários países. O levantamento mostra que no Brasil apenas 11% do total de casos foram diagnosticados. Link para a [notícia](https://www.correiobraziliense.com.br/app/noticia/brasil/2020/03/23/interna-brasil,836169/estudo-brasil-teria-11-vezes-mais-casos-de-coronavirus-do-que-o-regis.shtml)

## Contato

Para qualquer pergunta ou feedback, você pode me mandar um [tweet](https://twitter.com/leonardofullana) ou mensagem no [LinkedIn](https://www.linkedin.com/in/leonardofullana/).
