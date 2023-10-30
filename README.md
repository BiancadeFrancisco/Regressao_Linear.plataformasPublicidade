# Regressao_Linear.plataformasPublicidade

## Descrição Projeto


**Conjunto de dados:** Base de dados de uma empresa, com resultados de leads a partir de investimentos em marketing.


**Arquivo:** .csv


**Objetivo:** Analisar uma base de dados com retornos de marketing digital, aplicar machine learning com o modelo Linear Regression, a fim de acompanhar o desempenho de investimentos em campanhas publicitárias. 
Regressão Linear: técnica estatística que permite modelar a relação entre variáveis independentes e uma variável dependente. 


**IDE:** Colab


**Linguagem:** Python


**Principais bibliotecas utilizadas:**

• Pandas, para manipulação e tratamento dos dados; 

• Numpy, para realizar cálculos numéricos; 

• Seaborn, para criação e visualização de gráficos interativos; 

• Plotly, para criação e visualização de gráficos interativos;


• Sklearn, para aprendizado de machine learning;

• Matplotlib, para criação e visualização de gráficos.


**Modelo Utilizado:**

• Linear Regression, algoritmo de aprendizado de máquina com métodos destinados a regressão, nos quais se espera que o valor alvo seja uma combinação linear dos recursos. 

**Métricas Aplicadas:**

• Coeficiente de Determinação - R²:  métrica estatística que varia de 0 a 1 e é usada para avaliar a qualidade do ajuste de um modelo de regressão linear 1. Mede a proporção da variância na variável dependente que é explicada pela variável independente. Quanto mais próximo de 1, melhor será o ajuste do modelo aos dados .


**Sequência de processos:**

1° Instalação bibliotecas;

2° Pré-processamento de conjuntos de dados;

3° Utilizar Boxplot para verificar a distribuição dos dados relacionados a cada variável independente e da variável dependente.
•	BoxPlot, é uma maneira gráfica de representar a alteração dos dados de uma variável por meio de quartis. Ele exibe o resumo de cinco números de um conjunto de dados, que é composto pelo mínimo, primeiro quartil, mediana, terceiro quartil e máximo. 

4° Verificar correlação entre as variáveis utilizando Pairplot e Heatmap;
•	Pairplot, ferramenta de visualização de dados que permite comparar as relações entre pares de variáveis em um conjunto de dados. Ele exibe gráficos de dispersão para cada par de variáveis e histogramas para cada variável individual . Ele é útil para identificar padrões e correlações entre variáveis em um conjunto de dados .
•	Heatmap, ferramenta usada para identificar padrões em grandes conjuntos de dados e para visualizar a correlação entre diferentes variáveis em um conjunto de dados .   

5° Verificar distribuição dos dados da variável dependente;

6° Distribuir os dados em X (variáveis independentes) e y (variável dependente);

7° Separar base de dados para treino e teste;

8° Aplicar o método .fit do modelo de machine learning na base de treino;

9° Aplicar o método .predict do modelo de machine learning na base de teste, para previsão;

10° Aplicado métrica para verificar Coeficiente de Determinação para verificar a linearidade nos meus dados;

11° Plotar gráfico de linhas para verificar os valores originais da variável dependente e os valores preditos pelo modelo de machine learning

**Resultado:** O resultado da métrica aplicada no algoritmo foi de r² = 0,88. Esse resultado indica que quando minhas variáveis explicativas (independentes) mudarem, terei 88% de chance da minha variável target (dependente) mudar também. Posso dizer então que, aplicando esse modelo à essa base de dados tenho uma boa linearidade nos meus dados, conseguindo predizer bem meus resultados.

