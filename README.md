# 📈 QuantumFinance: Deep Learning para Predição de Ativos

### 📋 Sobre o Desafio

Este projeto foi desenvolvido para a QuantumFinance, que busca construir um fundo de ações baseado em modelos de Deep Learning. O objetivo principal é criar um modelo "perseguidor de tendência" capaz de decidir entre compra ou venda de um ativo, baseando-se na movimentação do mercado dos últimos 15 dias.

Os dados foram previamente rotulados por economistas, utilizando técnicas de suavização de preços para identificar tendências de alta (verde) e baixa (vermelho).

### 🏗️ Ativos Analisados

O modelo foca em quatro das principais ações do mercado brasileiro:

- VALE3 – Vale do Rio Doce

- PETR4 – Petrobras

- BBAS3 – Banco do Brasil

- CSNA3 – Companhia Siderúrgica Nacional

### 🛠️ Tecnologias e Abordagens

Para a resolução do problema, exploramos diferentes arquiteturas de Redes Neurais visando a melhor performance preditiva:

- CNN 1D (Redes Neurais Convolucionais 1D): Para extração de padrões temporais nos dados tabulares (CSV).

- RNN (Redes Neurais Recorrentes): Ideal para o tratamento de séries temporais e dependências sequenciais.

- CNN 2D: Utilizada para o treinamento baseado em representações visuais (imagens) das tendências.

- Tensorflow/Keras: Framework principal para construção e treinamento dos modelos de Deep Learning.

### 📊 Estrutura dos Dados

- Treino: Dados históricos de Janeiro de 2000 até meados de 2019.

- Teste: Dados de meados de 2019 até Dezembro de 2023.

- Input: Janelas deslizantes de 15 dias de comportamento do mercado.

- Output: Classificação binária (Compra ou Venda) para o dia seguinte.

### 🚀 Entregas e Indicadores

A solução está consolidada em Jupyter Notebooks, contendo o ciclo completo de ciência de dados. Para cada ativo, apresentamos:

### ✅ Métricas de Classificação:

- Acurácia no conjunto de teste.

- Matriz de Confusão.

- Precision e Recall.

### ✅ Análise de Viabilidade (Opcional/Diferencial):

- Backtest: Avaliação do desempenho financeiro real para validar se o modelo geraria retorno sobre o capital investido.
