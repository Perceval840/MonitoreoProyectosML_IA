# MonitoreoProyectosML_IA

Repositorio creado para el desarrollo de la guía de monitoreo en proyectos de Machine Learning e Inteligencia Artificial.

---

## 🌲 Forest Cover Type Classification

Este proyecto entrena tres modelos de clasificación para predecir el tipo de cobertura forestal a partir de características geoespaciales y ambientales.

📌 **Modelos utilizados:**
1. **Decision Tree**
2. **Random Forest**
3. **XGBoost**

Los modelos son monitoreados y versionados con **MLflow**, lo que permite registrar hiperparámetros, métricas y almacenar los modelos entrenados para su reutilización.

---

## 📂 Contenido del Repositorio

📁 `forest_cover_classification.ipynb` → Notebook con el análisis de datos, preprocesamiento y entrenamiento de los modelos.  
📁 `dataset/train.csv` → Dataset utilizado en el análisis.  
📁 `MLflow_Evidencia.pdf` → Documento con capturas de pantalla de MLflow.  
📁 `README.md` → Explicación del proyecto y guía de ejecución.

---

## 🛠 Requisitos e Instalación

Para ejecutar este proyecto, necesitas instalar las siguientes librerías:

```bash
pip install pandas numpy scikit-learn xgboost mlflow matplotlib seaborn
```

Además, para monitorear los modelos, asegúrate de tener MLflow instalado y ejecutándose en local:

```bash
mlflow ui
```

Esto abrirá MLflow en http://127.0.0.1:5000/.

---

## 🚀 Ejecución del Proyecto

Para entrenar los modelos y visualizar las métricas:

1. Abre el notebook `forest_cover_classification.ipynb` en Jupyter Notebook o VSCode.
2. Ejecuta todas las celdas en orden, desde la carga de datos hasta la evaluación de modelos.
3. Abre MLflow con `mlflow ui` para visualizar los experimentos guardados.

---

## 📊 Resultados

Después de entrenar los modelos, las métricas obtenidas para XGBoost fueron:

- **Accuracy:** 0.874
- **Precision:** 0.872
- **Recall:** 0.874
- **F1-Score:** 0.872

El modelo XGBoost fue registrado en MLflow para su uso posterior.

---

## 📌 Contribución

Este proyecto fue desarrollado por:

- Jose Pérez
- Leidy Correa
- Diego Juvinao

Si deseas mejorar el proyecto o realizar experimentos adicionales, siéntete libre de hacer un fork y enviar un pull request.