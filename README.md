## English description

This is the repo of my solution to the *Page View Times Series Visualizer* project from the **Data Analysis with Python** course from freeCodeCamp. Portuguese description is down below.

### Assignment

For this project you will visualize time series data using a line chart, bar chart, and box plots. You will use Pandas, Matplotlib, and Seaborn to visualize a dataset containing the number of page views each day on the freeCodeCamp.org forum from 2016-05-09 to 2019-12-03. The data visualizations will help you understand the patterns in visits and identify yearly and monthly growth.

Use the data to complete the following tasks:

* Use Pandas to import the data from "fcc-forum-pageviews.csv". Set the index to the "date" column.
* Clean the data by filtering out days when the page views were in the top 2.5% of the dataset or bottom 2.5% of the dataset.
* Create a `draw_line_plot` function that uses Matplotlib to draw a line chart similar to "examples/Figure_1.png". The title should be "Daily freeCodeCamp Forum Page Views 5/2016-12/2019". The label on the x axis should be "Date" and the label on the y axis should be "Page Views".
* Create a `draw_bar_plot` function that draws a bar chart similar to "examples/Figure_2.png". It should show average daily page views for each month grouped by year. The legend should show month labels and have a title of "Months". On the chart, the label on the x axis should be "Years" and the label on the y axis should be "Average Page Views".
* Create a `draw_box_plot` function that uses Searborn to draw two adjacent box plots similar to "examples/Figure_3.png". These box plots should show how the values are distributed within a given year or month and how it compares over time. The title of the first chart should be "Year-wise Box Plot (Trend)" and the title of the second chart should be "Month-wise Box Plot (Seasonality)". Make sure the month labels on bottom start at "Jan" and the x and y axis are labeled correctly.

For each chart, make sure to use a copy of the data frame. Unit tests are written for you under `test_module.py`.

### Development

For development, you can use `main.py` to test your functions. Click the "run" button and `main.py` will run.

### Testing 

We imported the tests from `test_module.py` to `main.py` for your convenience. The tests will run automatically whenever you hit the "run" button.

### Submitting

Copy your project's URL and submit it to freeCodeCamp.

----------------------------------------------------------------------------------------------------

## Descrição em português

Esse é o repositório com a minha solução para o projeto *Page View Times Series Visualizer* do curso **Data Analysis with Python** do freeCodeCamp. A tradução é livre e feita por mim.

### Tarefa

Para esse projeto você irá visualizar dados de série temporal usando gráficos de linhas, barras e caixas. Você usará Pandas, matplotlib e Seaborn para visualizar o dataset contendo o número de visualizações diárias na página do freeCodeCamp.org fórum entre 2016-05-09 e 2019-12-03. As visualizações ajudarão a entender os padrões nas visitas e identificar crescimento anual e mensal.

Use os dados para completar as seguintes tarefas:

* Use Pandas para importar os dados de "fcc-forum-pageviews.csv". Coloque o index como a coluna "date".
* Limpe os dados filtrando os dias em que as visualizações estavam no top 2.5% do dataset ou no últimos 2.5% do dataset.
* Crie uma função `draw_line_plot` que usa matplotlib para traçar um gráfico de linhas similar a "examples/Figure_1.png". O título deve ser "Daily freeCodeCamp Forum Page Views 5/2016-12/2019". O label do eixo x deve ser "Date" e o do eixo y deve ser "Page Views".
* Crie uma funcão `draw_bar_plot` que faça um gráfico de barras similar a "examples/Figure_2.png". Ele deve mostrar a média de visitas diárias para cada mês, agrupados por ano. A legenda deve mostrar os labels dos meses e ter o título "Months". No gráfico, o label do eixo x deve ser "Years" e o do eixo y deve ser "Average Page Views".
* Crie uma função `draw_box_plot` que usa Seaborn para desenhar dois gráficos de caixa adjacentes, similar a "examples/Figure_3.png". Esses gráficos devem mostrar como os valores estão distribuídos em um dado ano ou mês e como eles se comparam ao longo do tempo. O título do primeiro deve ser "Year-wise Box Plot (Trend)" e o do segundo deve ser "Month-wise Box Plot (Seasonality)". Garanta que os labels dos meses embaixo começam em "Jan" e os eixos x e y têm os labels corretos.

Para cada gráfico, se assegure de usar uma cópia do dataframe. Testes unitários foram escritor para você em `test_module.py`.

### Desenvolvimento

Escreve seu código em `prob_calculator.py`. Para desenvolvimento, use `main.py` para testar o código. Clique em "run" `main.py` rodará.

### Testando 

Os testes unitários para este projeto estão em `test_module.py`. Importamos os testes de `test_module.py` para `main.py` por conveniência. Os teste vão rodar automaticamente quando clicar em "run".

### Submissão

Copie a URL do projeto e submeta-a ao freeCodeCamp.
