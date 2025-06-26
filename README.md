# Clasificación de Lesiones Dermatoscópicas con Arquitecturas de Deep Learning
Desarrollo y evaluación de modelos de deep learning para la clasificación de imágenes dermatoscópicas, enfocándose en melanoma y carcinomas, usando arquitecturas como CNN, ViT y ConvNeXt, con técnicas de aprendizaje por transferencia y análisis comparativo de rendimiento.

## 📌 Objetivo

Desarrollar, entrenar y comparar arquitecturas de aprendizaje profundo para la detección de lesiones dermatoscópicas, evaluando su desempeño mediante métricas como precisión, recall, F1-score y matriz de confusión. También se aplica aprendizaje por transferencia para mejorar el rendimiento con datos limitados.

## 🧠 Modelos Implementados

- ✅ CNN (EfficientNetB0 desde cero)
- ✅ Vision Transformer (ViT sin fine tuning)
- ✅ ConvNeXt (feature extraction)
- ✅ Aprendizaje por transferencia para ViT y ConvNeXt

## 🧪 Dataset

Se utilizó el conjunto **HAM10000** (Harvard & ViDIR, ISIC Challenge), aplicado un proceso de **undersampling** para equilibrar clases como *melanoma*, *carcinomas* y *nevos*.

> ⚠️ Las imágenes originales no están incluidas por temas de tamaño y licencia, pero se puede obtener desde: [https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

## 📊 Métricas de Evaluación

- Accuracy
- Recall
- F1-score
- Matriz de confusión
- Gráficos de pérdida y precisión por época

# CNN
![imagen](https://github.com/user-attachments/assets/dd291980-171b-4ff5-b521-f2b5002cecbb)


# Vision Transformer
![imagen](https://github.com/user-attachments/assets/9f261286-893c-425a-bc45-c11eb8c91670)




# ConvNext
![imagen](https://github.com/user-attachments/assets/ee9124b3-16a9-4cb5-8989-8af9227441ea)




## ⚙️ Requisitos

- Python 3.10+
- PyTorch
- torchvision
- scikit-learn
- matplotlib
- pandas

## 📄 Licencia

Este proyecto es de uso académico. Si deseas usarlo o citarlo, por favor contacta previamente.

## 🙋 Autor

Rodrigo Gomez Rosado . Código PUCP : 20201676
