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
Baixe imagens de pacientes com covid-19(Dr.Joseph Paul Cohen PhD):
Repo Oficial: https://github.com/ieee8023/covid-chestxray-dataset
Ou em meu Driver pra enconomizar seu tempo:
https://drive.google.com/file/d/1H_ECCueOVeJj144_ap9eAANMz5fN2C1G/view?usp=sharing

Baixe as imagens de pacientes com pneumonia:
Repo Oficial:https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
Ou em meu Driver pra enconomizar seu tempo:
https://drive.google.com/file/d/1HTPkFVZlHqZGFIB4fZfZSoVxwhC642z8/view?usp=sharing
