# covid19-raiox
Detectar Covid-19 por Raio-X

Este projeto consiste em realizar um diagnóstico experimental na detecção da Covid-19 através de imagens de Raio-x. Usando tecnologias como TensorFlow, OpenCV e Keras.

# Estrutura de Diretórios
notebooks
10_dataset — 
           |_ covid  [aqui irão ficar imagens para treinamento do modelo 1]
           |_ normal [aqui irão ficar imagens para treinamento do modelo 1]
20_dataset — 
           |_ covid  [aqui irão ficar imagens para treinamento do modelo 2]
           |_ pneumo [aqui irão ficar imagens para treinamento do modelo 2]
input - 
      |_ 10_Covid_Imagens _ 
      |                   |_ [metadata.csv]
      |                   |_ images [imagens de Covid-19 aqui]
      |_ 20_Chest_Xray -
                       |_ test _
                               |_ NORMAL    [Imagens aqui]
                               |_ PNEUMONIA [Imagens aqui]
                       |_ train _
                                |_ NORMAL    [Imagens aqui]
                                |_ PNEUMONIA [Imagens aqui]
model
dataset_validation _
                   |_ covid_validation          [Imagens aqui]
                   |_ non_covidcovid_validation [Imagens aqui]
                   |_ normal_validation         [Imagens aqui]
