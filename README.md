<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# IFR2 Strategy: Relative Strength Index (RSI) and Moving Average

## Description

The IFR2 strategy is based on the Relative Strength Index (RSI) calculated over a 2-day period, combined with a 5-day Simple Moving Average (SMA). The RSI is a momentum indicator that measures the fluctuations between buying and selling pressures on a scale from 0 to 100. Extreme RSI values often indicate overbought or oversold conditions, signaling potential weakening of a trend.

This strategy uses RSI for entry signals and SMA for exit signals, focusing on price volatility without considering the current market trend.

## Project Features

- **Data Collection**: Import historical price data for financial assets using the MetaTrader5 library.

- **Indicator Calculation**: Add the Relative Strength Index (RSI) and Simple Moving Average (SMA) to the price data DataFrame.

- **Entry and Exit Signals**:
  - **Buy Signal**: Generated when the RSI is below a critical level (5).
  - **Sell Signal**: Generated when the closing price is above the SMA.

- **Strategy Returns Calculation**: Calculate the returns of the strategy based on entry and exit signals and compare with a buy-and-hold strategy.

- **Performance Evaluation**: Analyze metrics such as total return, number of trades, winning and losing trades, percentage of winning trades, average gain and loss per trade, and average return per trade.

- **Results Export**: Save the performance metrics in a DataFrame and export it to an Excel file.

## Technologies Used

- **Language**: Python

- **Libraries**:
  - `pandas` for data manipulation
  - `ta` for technical indicators calculations
  - `MetaTrader5` for financial data collection

- **Development Environment**: Jupyter Notebook or your preferred IDE

## Project Structure

1. **Library Import**: Import necessary libraries for data manipulation, calculations, and data collection.

2. **Data Collection**: Download historical price data for the selected asset using the MetaTrader5 library.

3. **Indicator Calculation**: Add RSI and SMA to the historical price data DataFrame.

4. **Entry and Exit Signal Definition**: Identify buy and sell signals based on indicator values.

5. **Strategy Returns Calculation**: Evaluate the strategy's performance by calculating returns and comparing them with a buy-and-hold strategy.

6. **Performance Evaluation and Export**: Analyze performance metrics and export results to an Excel file.

## Results

The project provides a detailed analysis of the IFR2 strategy, including total strategy return, number of trades, winning and losing trades, percentage of winning trades, average gain and loss per trade, and comparison with the buy-and-hold strategy. Performance metrics are exported to an Excel file for further analysis.

__________________________________________________________________________________________________________________

# Estratégia IFR2: Indicador de Força Relativa (RSI) e Média Móvel

## Descrição

A estratégia IFR2 baseia-se no Indicador de Força Relativa (RSI) calculado para um período de 2 dias, combinando-o com a média móvel simples (SMA) de 5 dias. O RSI é um indicador de momentum que reflete as oscilações das forças compradoras e vendedoras de um ativo em uma escala de 0 a 100. Valores extremos de RSI geralmente indicam zonas de sobrecompra ou sobrevenda, o que pode sinalizar o enfraquecimento de uma tendência.

Esta estratégia utiliza o RSI para identificar pontos de entrada e a SMA para pontos de saída, sendo uma abordagem focada na volatilidade dos preços, sem considerar a tendência atual do mercado.

## Funcionalidades do Projeto

- **Coleta de Dados**: Importar dados históricos de preços de ativos financeiros usando a biblioteca MetaTrader5.
  
- **Cálculo dos Indicadores**: Adicionar o Indicador de Força Relativa (RSI) e a Média Móvel Simples (SMA) ao DataFrame dos preços históricos.
  
- **Definição de Sinais de Compra e Venda**:
  - **Sinal de Compra**: Gerado quando o RSI está abaixo de um valor crítico (5).
  - **Sinal de Venda**: Gerado quando o preço de fechamento está acima da SMA.

- **Cálculo dos Retornos da Estratégia**: Calcular os retornos da estratégia com base nos sinais de compra e venda e comparar com o retorno de uma estratégia de buy and hold.

- **Avaliação de Desempenho**: Analisar métricas como retorno total, número de operações, operações vencedoras e perdedoras, percentual de operações vencedoras, média de ganho e perda por operação, e retorno médio por operação.

- **Exportação dos Resultados**: Salvar as métricas de desempenho em um DataFrame e exportá-lo para um arquivo Excel.

## Tecnologias Utilizadas

- **Linguagem**: Python

- **Bibliotecas**:
  - `pandas` para manipulação de dados
  - `ta` para cálculos de indicadores técnicos
  - `MetaTrader5` para coleta de dados financeiros

- **Ambiente de Desenvolvimento**: Jupyter Notebook ou IDE de sua escolha

## Estrutura do Projeto

1. **Importação de Bibliotecas**: Importar as bibliotecas necessárias para manipulação de dados, cálculos e coleta de dados.

2. **Coleta de Dados**: Baixar dados históricos de preços para o ativo selecionado usando a biblioteca MetaTrader5.

3. **Cálculo dos Indicadores**: Adicionar o RSI e a SMA ao DataFrame dos preços históricos.

4. **Definição dos Sinais de Compra e Venda**: Identificar sinais de compra e venda com base nos valores dos indicadores.

5. **Cálculo dos Retornos da Estratégia**: Avaliar o desempenho da estratégia calculando os retornos e comparando com uma estratégia de buy and hold.

6. **Avaliação e Exportação dos Resultados**: Analisar as métricas de desempenho e exportar os resultados para um arquivo Excel.

## Resultados

O projeto fornece uma análise detalhada da estratégia IFR2, incluindo o retorno total da estratégia, número de operações, operações vencedoras e perdedoras, percentual de operações vencedoras, média de ganho e perda por operação, e comparação com o retorno da estratégia de buy and hold. As métricas de desempenho são exportadas para um arquivo Excel para uma análise adicional.
