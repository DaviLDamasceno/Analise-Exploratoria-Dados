## Analise Exploratória de Dados

Este repositório contém um código em Python que realiza análises estatísticas e gera visualizações gráficas a partir de um conjunto de dados de preços de placas de vídeo. O objetivo é explorar as distribuições dos preços à vista e a prazo e verificar se os dados seguem uma distribuição normal.

## Requisitos

- Python 3
- Bibliotecas: pandas, re, matplotlib, seaborn, numpy, statistics, math e scipy

## Como utilizar

1. Certifique-se de ter Python 3 instalado em seu ambiente.
2. Instale as bibliotecas necessárias, caso ainda não tenha feito, utilizando o comando: `pip install pandas matplotlib seaborn numpy scipy`.
3. Faça o download do arquivo CSV contendo os dados das placas de vídeo e salve-o no caminho: `'C:\\Users\\ddavi\\Downloads\\arquivocsv\\placadeVideo.csv'`.
4. Execute o código no seu ambiente Python.

## Descrição do código

O código realiza  as seguintes tarefas:

1. Importa as bibliotecas necessárias para a análise.
2. Carrega os dados do arquivo CSV em um DataFrame usando a biblioteca pandas.
3. Realiza pré-processamento nos dados para remover caracteres inválidos e converter as colunas de preço para números de ponto flutuante.
4. Calcula estatísticas descritivas, como média, mediana, moda, variância e desvio padrão, para os preços à vista e a prazo.
5. Gera histogramas e boxplots para visualizar a distribuição dos preços.
6. Realiza um teste de normalidade (teste de D'Agostino e Pearson) para verificar se os preços seguem uma distribuição normal.
7. Identifica a melhor distribuição (entre normal, exponencial, lognormal e Weibull) que se ajusta aos dados de cada coluna de preço.

## Resultados

O código apresentará as seguintes informações na saída:

- Estatísticas descritivas dos preços à vista e a prazo (média, mediana, moda, variância e desvio padrão).
- Resultado do teste de normalidade para os preços à vista.
- Melhor distribuição encontrada para cada coluna de preço e seus respectivos parâmetros.

## Visualizações gráficas

O código gerará os seguintes gráficos:

1. Histograma dos preços à vista.
2. Histograma dos preços a prazo.
3. Boxplot com os preços à vista e a prazo.
4. Q-Q plot dos preços à vista em relação à distribuição exponencial.
5. Gráfico de dispersão mostrando a correlação entre os preços à vista e a prazo.

## Observações

- Caso ocorra algum erro relacionado à leitura do arquivo CSV, verifique o caminho fornecido no código e certifique-se de que o arquivo existe no local indicado.
- Para utilizar esse código com outros conjuntos de dados, certifique-se de que o arquivo CSV contenha colunas com os nomes `'preÃ§o pix'` e `'preco a prazo'` para os preços à vista e a prazo, respectivamente.

Lembre-se de adaptar o código conforme necessário para atender às suas necessidades específicas.
