# regression_course

Este repositório vai ser nosso guia no aprendizado de técnicas de regressão.

## Para usar esse repositório:

Em seu terminal:

```bash
git clone git@github.com:Carne-de-Pescoco/regression_course.git
cd regression_course
pip install -r requirements.txt
```

ou se você usa o **pipenv**:

```bash
pipenv sync --dev
```

## Diário de bordo

### 29/08/2021

> - Puxamos dados da Secretaria de Segurança Pública do Governo de São Paulo, especificamente dados da capital referentes aos anos de 2019, 2020 e 2021, sendo este último até Julho).
> - Realizamos um pequeno preprocessamento e disponibilizamos os dados na forma de um dataframe com os ano-mês em cada linha e contagem de crimes ou ações policiais como colunas.
> - Fizemos a visualização de algumas ocorrências em relação a outras, com o intuito de:
>    - Verificar se houve evolução de cada modalidade em cada ano; e
>    - Verificar se havia correlação entre as classes de crimes.
> [Notebook](./notebooks/01-data_understanding-crimes.ipynb)
> [Gráfico](./reports/crimes_scatter.html)