# Detector de Incêndio com Deep Learning

Este projeto aplica técnicas de **visão computacional** com redes neurais convolucionais (CNNs) para detectar incêndios em imagens, usando o Keras e TensorFlow.

## Objetivo

Desenvolver e treinar um modelo de deep learning capaz de identificar imagens com ocorrência de fogo, com base em um conjunto de dados rotulado.

## Modelo

- Arquitetura baseada em CNN com camadas `Conv2D`, `MaxPooling2D`, `Dense` e `Dropout`.
- Função de perda: `categorical_crossentropy`
- Otimizador: `Adam`
- Métricas: `accuracy`

> O modelo final foi salvo como `fire_detector_model.h5` (tamanho: 376 MB)

---

---

## Dados

Os dados de treino e validação estão disponíveis na pasta `Data/`, contendo imagens em duas classes: `Fire` e `NoFire`.

> Por limite de tamanho do GitHub, os dados não estão incluídos no repositório.

📥 Baixe o conjunto de dados e o modelo através dos links:

- 🔗 [Data (Google Drive)](https://drive.google.com/drive/folders/1X04kMcWOrjQMe6DJhaS1VVr14qVmHaIx?usp=sharing)
- 🔗 [Modelo Treinado (fire_detector_model.h5)](https://drive.google.com/file/d/1Fl1p5790Y0MwqZ8Cf8wQOB2obWGGuZs0/view?usp=sharing)

> Após o download, coloque os arquivos nas pastas correspondentes.

## Métricas de Avaliação
- Acurácia de validação acima de 90%
-  Matriz de confusão e curva ROC disponíveis no notebook
