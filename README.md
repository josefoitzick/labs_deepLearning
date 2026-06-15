# 🧠 Deep Learning — Labs & Proyectos

> Colección de laboratorios y experimentos de aprendizaje profundo: redes neuronales, visión por computador y datos tabulares.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

---

## 📂 Proyectos

| # | Proyecto | Descripción | Stack |
|---|----------|-------------|-------|
| 1 | [Detección de Fraude](DL1.ipynb) | Red neuronal para clasificar transacciones fraudulentas con tarjeta de crédito. Manejo de **datos desbalanceados**, modelo *baseline* y experimentos de regularización (*dropout*). | `PyTorch` · `scikit-learn` · `pandas` |
| 2 | [Clasificación de Flores (CNN)](LAB2_DL_CNN.ipynb) | Clasificación de imágenes en 5 clases (*TensorFlow Flowers*) mediante **Transfer Learning** con la arquitectura preentrenada **MobileNetV2**. | `TensorFlow` · `Keras` |

---

## 🔍 Detalle

### 1. Detección de Fraude — `DL1.ipynb`
- **Dataset:** `creditcard.csv` (versión real, fuertemente desbalanceada hacia `isFraud = False`).
- **Enfoque:** análisis exploratorio del desbalance, escalado de features y entrenamiento de una red en PyTorch.
- **Experimentación:** línea base + variantes con *dropout* y evaluación con matriz de confusión.

### 2. Clasificación de Flores — `LAB2_DL_CNN.ipynb`
- **Dataset:** *TensorFlow Flowers* — 3.670 imágenes, 5 clases (*daisy, dandelion, roses, sunflowers, tulips*).
- **Enfoque:** *Transfer Learning* con **MobileNetV2**, redimensionado a 160×160 y normalización.
- **Motivación:** red ligera y eficiente, ideal para entrenamiento rápido sin sacrificar precisión.

---

## 🚀 Cómo ejecutar

```bash
# Clonar el repositorio
git clone https://github.com/<tu-usuario>/labs_deepLearning.git
cd labs_deepLearning

# Abrir los notebooks
jupyter notebook
```

> 💡 También puedes abrirlos directamente en [Google Colab](https://colab.research.google.com/).

---

## 🛠️ Tecnologías

`Python` · `PyTorch` · `TensorFlow / Keras` · `scikit-learn` · `pandas` · `NumPy` · `Matplotlib` · `Seaborn`
