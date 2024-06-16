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
Certifique-se de ter o Python instalado em sua máquina antes de prosseguir com essas etapas.

Este tutorial foi desenvolvido para usuários do Windows com um terminal PowerShell. Siga as etapas abaixo para executar o projeto localmente em sua máquina:

*Crie um ambiente virtual executando o seguinte comando no terminal:
```
python -m venv env
```

* Em seguida, ative o ambiente virtual. Você verá que o prompt do terminal mostrará '(env)':
```
.\env\Scripts\activate
```

* Agora, instale todas as dependências listadas no arquivo 'requirements.txt', executando o seguinte comando:
```
pip install -r requirements.txt
```

* Certifique-se de ter imagens de raio-X em duas pastas dentro de `dataset`: `covid` e `normal`;

* Com as dependências instaladas (opencv-python, scikit-image, scikit-learn, numpy), execute o arquivo 'covid_detection.py':
```
python -u covid_detection.py
```

* Se desejar parar a execução da aplicação, pressione Ctrl + C no terminal. Em seguida, você pode desativar o ambiente virtual executando o seguinte comando:
```
deactivate
```

Após desativar o ambiente virtual, a execução do projeto será encerrada.

Lembre-se de que, sempre que desejar executar novamente o projeto localmente, você precisará ativar o ambiente virtual antes de iniciar a aplicação.

## Resultados
O programa exibirá a matriz de confusão e a acurácia do modelo.
