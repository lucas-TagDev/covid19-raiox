# covid19-raiox
Detectar Covid-19 por Raio-X

Este projeto consiste em realizar um diagnóstico experimental na detecção da Covid-19 através de imagens de Raio-x. Usando tecnologias como TensorFlow, OpenCV e Keras.

# Estrutura de Diretórios
notebooks
10_dataset — 
<br>       |_ covid  [aqui irão ficar imagens para treinamento do modelo 1]
<br>       |_ normal [aqui irão ficar imagens para treinamento do modelo 1]
<br>
20_dataset — 
<br>       |_ covid  [aqui irão ficar imagens para treinamento do modelo 2]
<br>       |_ pneumo [aqui irão ficar imagens para treinamento do modelo 2]
<br>
input - 
<br>      |_ 10_Covid_Imagens _ 
<br>      |
               <br> |_ [metadata.csv]
               <br> |_ images [imagens de Covid-19 aqui]
      <br>
               <br> |_ 20_Chest_Xray -
                      <br>|_ test _
                               <br>|_ NORMAL    [Imagens aqui]
                               <br>|_ PNEUMONIA [Imagens aqui]
                       <br>|_ train _
                                <br>|_ NORMAL    [Imagens aqui]
                                <br>|_ PNEUMONIA [Imagens aqui]
<br>model
<br>dataset_validation _
                   <br>|_ covid_validation          [Imagens aqui]
                   <br>|_ non_covidcovid_validation [Imagens aqui]
                   <br>|_ normal_validation         [Imagens aqui]
