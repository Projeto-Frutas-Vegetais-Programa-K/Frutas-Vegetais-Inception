# Frutas-Vegetais-Inception

Notebook colab, utilizando rede inception, resultado do instruction 1 - pesquisa de modelos.

Grupo: Auxílio na tomada de decisão no processo de compra de frutas e vegetais.

## Introdução

Para alcançar o nosso objetivo, precisamos obter o conhecimento necessário para a classificação com redes neurais. Como primeiro passo na nossa jornada, decidimos criar um tutorial de como usar 2 redes neurais famosas:
+ Resnet 50
+ Inception v3

Este repositório contém o conteúdo e o notebook da rede Inception v3, assim como um guia para auxiliar aqueles que estão dando os seus primeiros passos.


### O que é a Inception

A Inception é uma rede neural convolucional criada pelo Google (veja o artigo "Going Deeper with Convolutions", na seção de [Links úteis](https://github.com/Projeto-Frutas-Vegetais-Programa-K/Frutas-Vegetais-Inception/blob/main/README.md#outros-links-úteis)), também conhecida como GoogLeNet. Essa é uma arquitetura muito famosa, foi a vencedora do torneio “ImageNet Large Scale Visual Recognition Challenge” (ILSVRC) de 2014, e ela se encontra no top 3 menores erros dessa competição:

![top7_torneio_ILSVRC](https://user-images.githubusercontent.com/119753668/233491811-85bbdcd0-230b-4173-8be5-ba773889d1fa.png)

Neste tutorial, utilizamos a versão 3 dessa arquitetura, proposta em 2015 e conhecida como "Inception v3" (veja o artigo "Rethinking the Inception Architecture for Computer Vision", na seção de [Links úteis](https://github.com/Projeto-Frutas-Vegetais-Programa-K/Frutas-Vegetais-Inception/blob/main/README.md#outros-links-úteis)).


## Entendendo conceitos fundamentais da Inception:

O principal diferencial dessa rede é o "módulo Inception", que é formado pelo paralelismo e a concatenação de várias convoluções pequenas para reduzir o número de parâmetros. Abaixo uma ilustração desse módulo:
![modulo_inception](https://user-images.githubusercontent.com/119753668/233491397-5b2e67fd-8643-43f9-87d6-aa3081e9d0b8.png)

Além disso, a Inception é uma rede única porque tem duas camadas de saída durante o treinamento. A segunda saída é conhecida como uma saída auxiliar e está contida na parte AuxLogits da rede. Já a saída principal é uma camada linear no final do rede. 


### Outros links úteis:

+ [CS231n Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/transfer-learning/) - Texto sobre Aprendizado por Transferência
+ [Transfer Learning - Machine Learning's Next Frontier](https://ruder.io/transfer-learning/) - Texto sobre Aprendizado por Transferência
+ [Going Deeper with Convolutions](https://arxiv.org/abs/1409.4842) - Artigo da Inception v1
+ [Review: GoogLeNet (Inception v1)— Winner of ILSVRC 2014 (Image Classification)](https://medium.com/coinmonks/paper-review-of-googlenet-inception-v1-winner-of-ilsvlc-2014-image-classification-c2b3565a64e7) - Texto sobre a Rede Inception v1
+ [Rethinking the Inception Architecture for Computer Vision](https://arxiv.org/abs/1512.00567) - Artigo da Inception v3
+ [Torchvision Models and pre-trained weights](https://pytorch.org/vision/stable/models.html) - Documentação de modelos do Pytorch
+ [Inception_v3](https://pytorch.org/vision/stable/models/generated/torchvision.models.inception_v3.html#torchvision.models.inception_v3) - Documentação do modelo Inception v3 do Pytorch


## Nosso Tutorial

[Inception_v3_Tutorial_+_Case_com_Dataset_Personalizado](https://github.com/Projeto-Frutas-Vegetais-Programa-K/Frutas-Vegetais-Inception/blob/main/Inception_v3_Tutorial_%2B_Case_com_Dataset_Personalizado.ipynb)

## Contato

Se após essas leituras ainda tiver alguma dúvida ou curiosidade sobre o tutorial, não hesite em entrar em contato no seguinte email: <larissarosa@discente.ufg.br>
