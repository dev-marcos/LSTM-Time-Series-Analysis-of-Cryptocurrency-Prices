# Previsão do valor futuro do BTC usando LSTM
Este projeto é um modelo de previsão de valor futuro do Bitcoin usando a técnica de Long Short-Term Memory (LSTM) em Python. O objetivo é utilizar dados históricos para prever o valor futuro do BTC.

## Pré-requisitos
Antes de executar o código, você precisará instalar as seguintes bibliotecas:

* numpy
* pandas
* matplotlib
* sklearn
* keras

Você pode instalar essas bibliotecas usando o pip, rodando o seguinte comando em seu terminal:

```
pip install numpy pandas matplotlib sklearn keras
```

## Como utilizar
O arquivo principal deste projeto é `Previsao_preco_BITCOIN.ipynb`. Ele contém a implementação do modelo LSTM que usa os dados históricos para prever o valor futuro do BTC.

Para utilizar o modelo, basta abri-lo em um Jupyter Notebook.

O modelo é treinado com o dataset BTC-USD.csv, que contém os valores diários do BTC. O modelo então é testado com um conjunto de dados de teste para avaliar a precisão do modelo.

Após a conclusão da execução do modelo, será gerado um gráfico que mostra a previsão do valor futuro do BTC com base no conjunto de teste.

## Como funciona
O modelo de previsão usa a técnica de LSTM, que é uma rede neural recorrente que pode aprender a lembrar informações de longo prazo. A implementação do modelo é realizada em três passos principais:

Carregar o conjunto de dados históricos
Preparar os dados para treinamento e teste
Treinar o modelo e gerar a previsão do valor futuro
O modelo usa os dados históricos para treinamento e, em seguida, é testado com um conjunto de dados de teste. O conjunto de teste é separado do conjunto de dados de treinamento usando a técnica de divisão de dados (80/20). Isso garante que o modelo possa ser avaliado com dados que ele nunca viu antes.

## Conclusão
Este projeto apresenta um exemplo básico de como usar a técnica de LSTM para prever o valor futuro do BTC. No entanto, ele pode ser aprimorado usando outras técnicas e com ajustes de parâmetros para melhorar a precisão da previsão.

## Referências
https://keras.io/examples/timeseries/timeseries_prediction/
https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/
