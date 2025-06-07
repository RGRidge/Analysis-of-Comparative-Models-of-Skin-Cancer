![imagen](https://github.com/user-attachments/assets/b3a94a17-03aa-4249-add7-325e0b0dd674)# Clasificación de Lesiones Dermatoscópicas con Arquitecturas de Deep Learning
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
![imagen](https://github.com/user-attachments/assets/4f64ffca-2707-4fea-bd78-7a6e23a3d877)

# Vision Transformer

![imagen](https://github.com/user-attachments/assets/14035cd6-43ea-46a8-99a2-69add403c33f)


# ConvNext
![imagen](https://github.com/user-attachments/assets/6c366275-b013-4eaa-8226-d39c55afd87a)



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
