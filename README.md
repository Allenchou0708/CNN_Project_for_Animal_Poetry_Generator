<div align="center">

# Animal Poetry Generator

<font size="4">
YEN-LUN CHOU&emsp;
MAN-YI CHANG&emsp;
YU-PING KUO&emsp;
KAI-ROU FANG&emsp;
MAO-YUAN MA&emsp;
</font>
<br>

<font size="4">
National Chung Chi University
</font>

| <a href="https://github.com/Allenchou0708/CNN_Project_for_Animal_Poetry_Generator/blob/main/Animal%20Poetry%20PPT.pdf">Project Description Slide</a> |


![Animal Poetry Generator](https://github.com/user-attachments/assets/148a7756-e6b8-41f3-821a-bb234e6c5b84)

</div>

<br>
<br>


## Abstract

This was the final project of the Convolutional Neural Networks and Visual Recognition course taught by Professor Tsai Rua-Huan. Our system takes an image containing an animal as input and generates a poem based on the identified species. For example, when an image of a goose is provided, the model composes a poem inspired by the goose. We compare the performance of the models VGG16, MobileNet, and ResNet-44-CIFAR which was transfered learning on Animal Dataset. During training, VGG16 encountered overfitting; therefore, we introduced dropout layers and reduced the number of trainable layers to improve generalization. Experimental results show that MobileNet achieved the best performance, reaching a testing accuracy of 93.39%.

<br>
<br>

## Installation
1. Download the notebook<br>
   Download the ipynb notebook from this repository and upload it to your Colab workspace.

2. Prepare the dataset<br>
   Import the [dataset](#datasets) into your Colab notebook environment.

3. Run the experiments<br>
   You can now directly execute the notebook cells to reproduce the experiments.

<br>
<br>


## Datasets

We use the [Animal Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/animal-image-dataset-90-different-animals) in our experiments

<br>
<br>

## Performance 

| Model | VGG16 | MobileNET | ResNet-44-CIFAR | 
| :-- | :-: | :-: | :-: |
| **Accuracy** | **85.07** | **93.39** | **81.25** |
| **Accuracy (Initialize)** | **83.41** | **93.44** | **83.50** |

<br>
<br>
