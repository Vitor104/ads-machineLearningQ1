

# Previsão de Doenças Cardíacas com Modelos de Classificação
Este projeto utiliza técnicas de Machine Learning para prever a presença de doenças cardíacas em pacientes com base em um conjunto de dados médicos. Foram implementados, avaliados e comparados dois modelos de classificação: Random Forest e SVM.

## Estrutura do Projeto

O primeiro passo foi estruturar o projeto. Para isso, criei um dataset sintético usando **make_classification** com 1000 amostras e 4 features (idade, pressão arterial, colesterol e frequência cardíaca).

## Pré-Processamento

Fiz o tratamento de valores ausentes e, em seguida, ajuste e normalização dos valores para garantir que todos estivessem em uma escala comparável, usendo o **StandardScaler**.

## Divisão do dataset

Dividi o dados da seguinte forma: 80% para treinamento e 20% para teste.

## Treinamento dos modelos

Foi utilizado o **RandomForest** e o **SVM** com kernel "rbf".

# Como executar o projeto

### Clone o repositório:

git clone https://github.com/Vitor104/ads-machinelearningQ1.git

### Instale as dependências:

pip install pandas numpy scikit-learn

### Execute o notebook:

Abra o arquivo Q5.ipynb em um ambiente Jupyter.

# Resultados e conclusão

Após o treinamento e a avaliação do modelo, o que teve o melhor desempenho foi o Random Forest, obtendo um valor superior em todas métricas avaliadas, com uma acurácia de 94% e uma pontuação ROC-AUC de 0.940.
E as variáveis que tiveram maior influência no resultado foram a pressão arterial (0.366) e a idade (0.309).
