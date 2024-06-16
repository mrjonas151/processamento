# Processamento de imagens prática

## Equipe
- Jonas Tomaz de Aquinos
- Pedro Henrique Tonon Ferreira
- Vinícius Gomes Ribeiro

## Descrição do Descritor Implementado
O projeto tem como objetivo desenvolver um classificador para diferenciar entre imagens de raio-X de pulmões com e sem Covid-19. Utilizamos um descritor de textura baseado no padrão binário local (LBP) para extrair características das imagens e treinamos um classificador SVM (Support Vector Machine) para realizar a classificação.

## Repositório do Projeto
https://github.com/mrjonas151/processamento

## Classificador e Acurácia
O modelo utiliza um classificador Support Vector Machine (SVM) treinado com características extraídas usando Local Binary Pattern (LBP).
A acurácia é uma métrica que indica a proporção de previsões corretas feitas pelo modelo.

## Instruções de Uso
- Requisitos:
Python 3.x

- Bibliotecas: OpenCV, scikit-image, scikit-learn, numpy
- Como Usar:
Certifique-se de ter imagens de raio-X em duas pastas dentro de "dataset": "covid" e "normal";

Execute o script python .\covid_detection.py;

Analise os resultados exibidos após a conclusão do script;

- Resultados
O programa exibirá a matriz de confusão e a acurácia do modelo.
