# Projeto de Transfer Learning em Python: 
## Classificação de Cães e Gatos🐶😸
## 🎯Objetivo:
Construir um modelo de aprendizado de máquina capaz de classificar imagens como sendo de cães ou gatos, utilizando a técnica de Transfer Learning para acelerar o processo de treinamento e melhorar a performance.
## Abordagem:

**1️⃣ Transfer Learning:** Foi utilizada a arquitetura MobileNetV2, pré-treinada com o dataset ImageNet, como base para o modelo. Isso permitiu aproveitar o conhecimento já adquirido pela rede em um conjunto de dados massivo e diverso.

**2️⃣. Dataset:** O dataset "cats_vs_dogs" do TensorFlow Datasets foi utilizado para treinar e avaliar o modelo. As imagens foram pré-processadas, incluindo redimensionamento, normalização e técnicas de aumento de dados como rotações, flips e ajustes de brilho e contraste.

**3️⃣. Arquitetura do Modelo:** Uma nova camada de classificação foi adicionada à MobileNetV2, composta por camadas densas, funções de ativação e dropout para regularização.

**4️⃣. Treinamento:** O modelo foi treinado utilizando o otimizador Adam e a função de perda binary cross-entropy. O desempenho foi monitorado através das métricas de acurácia e perda durante o processo de treinamento.

**5️⃣. Avaliação:** Após o treinamento, o modelo foi avaliado com imagens de teste para verificar sua capacidade de generalização e precisão na classificação de novas imagens.

## 📈Resultados:

O modelo alcançou uma alta acurácia na classificação de cães e gatos, demonstrando a eficácia da técnica de Transfer Learning para este tipo de problema. O uso da MobileNetV2 como base permitiu um treinamento mais rápido e eficiente, com resultados satisfatórios em termos de precisão.

## 🛠Código:

O código do projeto foi implementado em Python utilizando as bibliotecas TensorFlow e Keras, e está disponível no Google Colab. O código inclui as etapas de carregamento do dataset, pré-processamento das imagens, construção do modelo, treinamento, avaliação e salvamento do modelo treinado.

## 🔎Conclusões:

O projeto demonstra a viabilidade e eficiência da técnica de Transfer Learning para a classificação de imagens, possibilitando a criação de modelos robustos e precisos com menor esforço de treinamento. O código desenvolvido oferece uma base sólida para a construção de outros projetos de classificação de imagens utilizando diferentes datasets e arquiteturas de redes neurais.
