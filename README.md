# Projeto: Análise Automatizada de Dados - Dataset Titanic

## Integrantes

* Márcio Gastaldi - RM98811
* Arthur Bessa Pian - RM99215
* Davi Desenzi - RM550849

## Descrição do Projeto
Este projeto tem como objetivo realizar uma análise exploratória automatizada de dados utilizando o conjunto de dados Titanic. Para isso, usamos diversas bibliotecas populares de análise de dados e visualização para explorar o dataset e extrair insights, incluindo regressão linear para análise preditiva e gráficos interativos para visualização de padrões. No final, geramos um relatório automatizado em formato HTML que resume toda a análise de maneira eficiente.

## Ferramentas Utilizadas
As principais bibliotecas utilizadas no projeto são:

- **pandas**: Manipulação e análise de dados, especialmente na criação e gerenciamento de DataFrames.
- **hvplot.pandas**: Criação de gráficos interativos diretamente a partir de DataFrames do pandas.
- **seaborn**: Geração de gráficos estatísticos para explorar padrões nos dados.
- **matplotlib.pyplot**: Criação de gráficos estáticos simples.
- **vega_datasets**: Fornecimento de datasets prontos para análise e visualização.
- **ydata_profiling**: Geração de relatórios automáticos de análise exploratória de dados, semelhante ao Pandas Profiling.
- **sklearn.linear_model**: Regressão linear para análise de relações entre variáveis.
- **numpy**: Computação numérica e operações com arrays e matrizes.

## Funcionalidades do Código
### 1. Importação de Bibliotecas
O projeto inicia com a importação de todas as bibliotecas necessárias para análise de dados e visualizações gráficas.

### 2. Carregamento e Visualização do Dataset
Utilizamos o dataset Titanic, que já vem disponível na biblioteca Seaborn. Este conjunto de dados contém informações dos passageiros do Titanic, como idade, tarifa, classe e sobrevivência.

### 3. Geração de Gráficos Interativos
Criamos um **heatmap** interativo para mostrar a relação entre idade, tarifa e sobrevivência dos passageiros. Este gráfico ajuda a identificar padrões no comportamento dos dados, como a chance de sobrevivência com base na idade e no valor pago.

### 4. Aplicação de Regressão Linear
Implementamos uma **regressão linear** para explorar se existe uma relação entre a idade dos passageiros e a tarifa que eles pagaram. Embora o modelo mostre que a correlação entre essas variáveis é fraca, o gráfico ajuda a visualizar possíveis outliers.

### 5. Visualizações Adicionais
Geramos gráficos de regressão e **pairplots** utilizando Seaborn, o que nos ajuda a entender melhor as interações entre múltiplas variáveis no dataset, especialmente a variável de sobrevivência.

### 6. Geração Automática de Relatórios
Definimos uma função chamada `gerar_relatorio_html`, que gera automaticamente um relatório de análise exploratória de dados em formato HTML. Este relatório inclui:

- Estatísticas descritivas;
- Correlações;
- Análises de distribuição de variáveis;
- Detecção de valores ausentes e outliers.

O relatório é gerado de forma automatizada, tornando o processo de análise mais rápido e eficiente.

## Execução do Projeto
Para executar este projeto, siga os seguintes passos:

1. Clone o repositório em seu ambiente local.
2. Certifique-se de que todas as bibliotecas necessárias estão instaladas. Você pode instalar as dependências usando o seguinte comando:

```bash
pip install -r requirements.txt
```

3. Execute o script em um Jupyter Notebook ou diretamente em Python.
4. O relatório de análise será gerado e salvo como `titanic_analysis_report.html`. Você pode abri-lo em qualquer navegador para explorar a análise completa.

## Conclusão
Este projeto automatiza o processo de análise de dados, utilizando tanto visualizações interativas quanto técnicas de machine learning para extrair insights sobre o conjunto de dados Titanic. O uso de ferramentas como ydata_profiling agiliza a análise exploratória, enquanto as bibliotecas de visualização proporcionam uma compreensão clara dos dados.

