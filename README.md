# covid19-raiox
Detectar Covid-19 por Raio-X

Este projeto consiste em realizar um diagnóstico experimental na detecção da Covid-19 através de imagens de Raio-x. Usando tecnologias como TensorFlow, OpenCV e Keras.

# Estrutura de Diretórios
notebooks
10_dataset — 
<br>       ----|_ covid  [aqui irão ficar imagens para treinamento do modelo 1]
<br>       ----|_ normal [aqui irão ficar imagens para treinamento do modelo 1]
<br>
20_dataset — 
<br>       ----|_ covid  [aqui irão ficar imagens para treinamento do modelo 2]
<br>       ----|_ pneumo [aqui irão ficar imagens para treinamento do modelo 2]
<br>
input - 
<br>      |_ 10_Covid_Imagens _ 
<br>      |
               <br>----|_ [metadata.csv]
               <br>----|_ images [imagens de Covid-19 aqui]
      <br>
               <br> |_ 20_Chest_Xray -
                      <br>----|_ test _
                               <br>------|_ NORMAL    [Imagens aqui]
                               <br>------|_ PNEUMONIA [Imagens aqui]
                       <br>----|_ train _
                                <br>------|_ NORMAL    [Imagens aqui]
                                <br>------|_ PNEUMONIA [Imagens aqui]
<br>model
<br>dataset_validation _
                   <br>----|_ covid_validation          [Imagens aqui]
                   <br>----|_ non_covidcovid_validation [Imagens aqui]
                   <br>----|_ normal_validation         [Imagens aqui]

<br>

# Seção de Downloads

<br>
Baixe imagens de pacientes com covid-19(Dr.Joseph Paul Cohen PhD):<br>
Repo Oficial: https://github.com/ieee8023/covid-chestxray-dataset<br>
Ou em meu Driver pra enconomizar seu tempo:<br>
https://drive.google.com/file/d/1H_ECCueOVeJj144_ap9eAANMz5fN2C1G/view?usp=sharing<br>

Baixe as imagens de pacientes com pneumonia:<br>
Repo Oficial:https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia<br>
Ou em meu Driver pra enconomizar seu tempo:<br>
https://drive.google.com/file/d/1HTPkFVZlHqZGFIB4fZfZSoVxwhC642z8/view?usp=sharing<br>
