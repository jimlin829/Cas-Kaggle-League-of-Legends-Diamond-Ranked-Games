# Caso Kaggle: *League of Legends Diamond Ranked Games (10 min)*

---

## **Introducción**
Este proyecto tiene como objetivo predecir el resultado de partidas clasificatorias de *League of Legends* (Diamond Tier) en los primeros 10 minutos de juego, utilizando técnicas de aprendizaje automático. Los datos fueron obtenidos del conjunto de datos de Kaggle: [League of Legends Diamond Ranked Games (10 min)](https://www.kaggle.com/datasets/bobbyscience/league-of-legends-diamond-ranked-games-10-min).

El análisis incluye la preparación de datos, exploración de características, comparación de modelos de clasificación, análisis del modelo final, etc. Además, se destacan las variables clave que influyen en las partidas de *League of Legends*.

---

## **Elementos del Git**
- **`Dataset/`**: Contiene los datos utilizados en el proyecto.
- **`kaggle.ipynb`**: Notebook de Jupyter con el análisis completo del caso Kaggle.
- **`README.md`**: Este archivo.

---

## **Estructura del Proyecto**

1. **Introducción del Proyecto:**
   - Contextualización del caso de estudio y planteamiento del objetivo principal.

2. **Importación de Librerías:**
   - Uso de librerías clave como `pandas`, `scikit-learn`, `matplotlib` y `seaborn` para análisis y visualización.

3. **Exploración de Datos:**
   - Importación de los datos utilizados para el análisis.
   - Análisis inicial para entender las variables.
   - División del dataset en conjuntos de entrenamiento y prueba.

4. **Análisis y Preprocesamiento de Datos:**
   - Gráficas y correlaciones para identificar características relevantes.
   - Limpieza de datos:
     - Eliminación de características irrelevantes.
     - Manejo de valores faltantes.

5. **Preparación de Datos:**
   - División de los datos en variables X (atributos) e Y (target) para ambos conjuntos de entrenamiento y de prueba.

6. **Selección del Modelo:**
   - Evaluación de múltiples algoritmos de clasificación:
     - Regresión Logística
     - SVM
     - Decision Tree
     - K-Nearest Neighbors (KNN)
     - Random Forest
   - Comparación de modelos mediante validación cruzada usando la métrica de precisión (*accuracy*).

7. **Creación del Modelo:**
   - Optimización del mejor modelo identificado (Regresión Logística) mediante `GridSearchCV` para encontrar los hiperparámetros óptimos.

8. **Análisis Final:**
   - Entrenamiento del modelo final utilizando el conjunto completo de datos de entrenamiento.
   - Evaluación del modelo utilizando diferentes métricas y una matriz de confusión.
   - Interpretación de las características más relevantes para las predicciones:
     - **blueTotalGold**
     - **blueTotalExperience**
     - **redTotalGold**
     - **redTotalExperience**
   - Representación de los resultados del model mediante gráficas y curvas.

9. **Conclusiones:**
   - Resumen de los hallazgos clave y rendimiento del modelo.
   - Reflexión sobre el impacto de las características principales en el resultado del juego.
   - Propuestas para trabajos futuros, como incorporar datos en tiempo real o probar modelos avanzados.

---

**Autor:** *Yanhao Lin NIU: 1670136, David Zheng NIU: 1666559*  
**Contacto:** *Yanhao.Lin@autonoma.cat, David.Zheng@autonoma.cat*
