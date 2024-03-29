# Formação Machine Learning - Alura
Curso de Formação de Machine Learning da Alura
# Curso 1 - Introdução
Este primeiro curso tem como objetivo apresentar a biblioteca Sklearn e seus algoritmos de classificação:
* LinearSVC
* SVC
* DecisionTree </br>

O material produzido no curso encontra-se no notebook [[introducao_machine_learning.ipynb]](https://github.com/conradoov/formacao_machine_learning_alura/blob/bbae4f8d301e5be74b2a5d5cb401ffdebf1c7a84/introducao_machine_learning.ipynb)
# Curso 2 - Entendendo a matemática por trás de alguns modelos de classificação
Este curso utilizou 3 modelos de classificação em um problema de Churn (1 ou 0) para clientes de uma empresa fictícia.
Os modelos estudados foram obtidos da biblioteca Sklearn:
* KNN
* BNB
* DTC </br>
Na última etapa estudamos métricas para avaliar os modelos:
* Matriz de confusão
* Accuracy Score
* Precision Score
* Recall Score </br>
Nesta avaliação concluímos que a melhor métrica para avaliar o melhor modelo seria a Precision Score, pois ela mostra a qualidade dos valores Churn Positivo, métrica que a empresa precisa reduzir. O melhor modelo nesse quesito foi o DTC.
O material produzido no curso encontra-se no notebook [[entendendo_modelos_de_classificacao.ipynb]](https://github.com/conradoov/formacao_machine_learning_alura/blob/4e527ebd1df6f3b391ceabc6e89b2d4764b2ffd8/entendendo_modelos_de_classificacao.ipynb)


# Curso 3 - Modelo multivariado

Este curso teve como objetivo a implementação de um algorimo de Random Forest Classifier para classifiar se o conjunto de diversos exames gerava um resultado de cancêr maligno ou benigno. Buscando melhorar o Score do modelo, foram utilizados diversos algoritimos para selecionar as melhores features.

## Plots para análise descritiva dos dados:

* Violin Plot
* Matriz de Correlação (Mapa de calor)

## Modelos aplicados:
* RandomForestClassifier

## Seleção de Features
* Retirada de um dos pares de features com alta correlação
* SelectKBest
* RFE
* RFECV
* PCA

Ao final, aplicou-se o algoritmo t-SNE para possibilitar que dados multivariados fossem vistos no plano.

O material produzido no curso encontra-se no notebook [[machine_learning_modelo_multivariado.ipynb]](https://github.com/conradoov/formacao_machine_learning_alura/blob/main/machine_learning_modelo_multivariado.ipynb)
