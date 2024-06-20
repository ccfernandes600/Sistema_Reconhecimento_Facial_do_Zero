# Criando um Sistema de Reconhecimento Facial do Zero

Este projeto oferece um código Python para detecção de faces em imagens, utilizando o modelo Haar Cascade. O objetivo é construir um sistema básico de reconhecimento facial do zero, com instruções passo a passo para preparar o ambiente e realizar a detecção.

## Preparação do Ambiente
Para executar o código, você precisa ter um ambiente Python configurado com as bibliotecas necessárias. O Google Colab é recomendado para facilitar a execução interativa do código. As principais bibliotecas utilizadas são:
- TensorFlow
- NumPy
- OpenCV (cv2)
- Matplotlib
- PIL (Python Imaging Library)


# Carregando e Pré-processando os Dados
Para um sistema de reconhecimento facial eficaz, precisamos de um conjunto de dados de faces. Vamos usar um conjunto de dados de exemplo direto do Google Driver. No google Driver criei 04 pastas com foros de 04 pessoas diferentes. O nome de cada pasta é proprio nome da pessoa a ser treinada e reconhecida

# Criando e Treinando o Modelo
Aqui, criaremos uma CNN simples para reconhecimento facia. Porém antes foi codificado os labels, dividido dados em treinamento e teste (80, 20). Tanbém foi realizado um "Data Augmentation". Por ultimo, criei um menu para escolher uma das 05 redes de tranfer que posso trabalhar efinalmente treinar o modelo 

# Avaliação do Modelo
Faço uma avaliação para identificar a acaruracia do modelo

# Detecção de Faces em uma Imagem
Após treinar o modelo, podemos usá-lo para detectar e reconhecer faces em novas imagens.

## Visualização das Faces Detectadas com Seus Respectivos Labels 
Após a detecção, retângulos são desenhados ao redor das faces na imagem original. A imagem é convertida para RGB e exibida usando Matplotlib.




## Informações Adicionais
Projeto criado para fins de estudo junto com a DIO.me e o instrutor Diego Renan

Divirta-se explorando o mundo da visão computacional!
