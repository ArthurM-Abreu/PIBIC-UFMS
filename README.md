(PT/EN)

# Classificação de Distúrbios de Qualidade de Energia Elétrica 

Este projeto foi desenvolvido no âmbito de um **Programa de Iniciação Científica** da  
**UFMS – Universidade Federal de Mato Grosso do Sul**.

A implementação foi realizada em **Python**, utilizando o ambiente do **Google Colab**.

## Descrição do Projeto
O projeto consiste no desenvolvimento e na avaliação de um **classificador de sinais de distúrbios de qualidade de energia elétrica**.

Ao todo, são consideradas **16 classes distintas de sinais**, representando diferentes tipos de distúrbios elétricos.  
Foram implementados e comparados **diversos classificadores**, abrangendo tanto **modelos de Machine Learning** quanto **modelos de Deep Learning**, com o objetivo de analisar o desempenho de cada abordagem.

Os dados utilizados são **sinais artificiais**, gerados sinteticamente por meio de um **algoritmo de geração de sinais**, permitindo controle total sobre os parâmetros e características dos distúrbios.

## Estrutura e Uso do Projeto
Para a correta execução do projeto, recomenda-se seguir os seguintes passos:

1. Executar o **gerador de sinais**, responsável por criar os dados sintéticos e salvá-los no **Google Drive**.
2. Após a geração dos dados, executar os notebooks relacionados ao **Deep Learning**, que contêm a implementação dos algoritmos classificadores.

## Observações Importantes
- O código faz uso de **aceleração por GPU**, sendo necessário habilitar a GPU no Google Colab antes da execução.
- A aceleração por GPU é especialmente importante para a inicialização e treinamento do classificador **FT-Transformer**.

## Tecnologias Utilizadas
- Python  
- Google Colab  
- Machine Learning  
- Deep Learning  
- Aceleração por GPU (CUDA)

## Contexto Acadêmico
Este projeto possui caráter **acadêmico e científico**, sendo voltado ao estudo e à comparação de técnicas de classificação aplicadas à área de **Qualidade de Energia Elétrica**.

########################################################################################################################################################3

# Classification of Power Quality Disturbances

This project was developed within the scope of an **Undergraduate Research Program** at  
**UFMS – Federal University of Mato Grosso do Sul**.

The implementation was carried out in **Python**, using the **Google Colab** environment.

## Project Description
The project focuses on the development and evaluation of a **power quality disturbance signal classifier**.

A total of **16 distinct signal classes** are considered, representing different types of electrical disturbances.  
Several classifiers were implemented and compared, including both **Machine Learning** and **Deep Learning** models, with the objective of analyzing and comparing their performance.

The dataset is composed of **artificially generated signals**, created through a **signal generation algorithm**, which allows full control over the parameters and characteristics of the disturbances.

## Project Structure and Usage
To correctly run the project, the following steps are recommended:

1. Execute the **signal generator**, which is responsible for creating the synthetic data and saving it to **Google Drive**.
2. After the data generation step, run the **Deep Learning notebooks**, which contain the implementation of the classification algorithms.

## Important Notes
- The code makes use of **GPU acceleration**, and GPU support must be enabled in Google Colab before execution.
- GPU acceleration is especially important for initializing and training the **FT-Transformer** classifier.

## Technologies Used
- Python  
- Google Colab  
- Machine Learning  
- Deep Learning  
- GPU Acceleration (CUDA)

## Academic Context
This is an **academic and scientific project**, aimed at studying and comparing classification techniques applied to **Power Quality** analysis.







