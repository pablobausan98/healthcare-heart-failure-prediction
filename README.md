# 🫀 Predicción de Insuficiencia Cardíaca  

## 📌 Descripción
Proyecto para **predecir la probabilidad de insuficiencia cardíaca** en pacientes utilizando **Machine Learning**.  
Se basa en el *Heart Failure Prediction Dataset* con 918 registros y 11 características de salud de los pacientes.  

El objetivo es convertir datos médicos en información útil para apoyar decisiones clínicas.  

---

## 🎯 Objetivos
- Explorar y limpiar el dataset.  
- Analizar las características más importantes para la predicción.  
- Entrenar y comparar modelos de Machine Learning.  
- Evaluar el desempeño con métricas precisas.  

---

## 🛠️ Tecnologías utilizadas
- **Lenguajes:** Python, SQL  
- **Machine Learning:** Scikit-Learn (regresión logística, árboles de decisión, random forest)  
- **Visualización:** Matplotlib, Seaborn  
- **Entorno:** Jupyter Notebook  
- **Gestión de versiones:** GitHub  

---

## 🧪 Metodología
1. **Exploración y Limpieza de Datos (Python)**
   - Tratamiento de valores faltantes (imputación de colesterol).
   - Codificación de variables categóricas.
   - Escalado de variables numéricas.
2. **Modelado Predictivo (Python / Scikit-Learn)**
   - Regresión Logística (baseline) – Accuracy: 86%
   - Árbol de Decisión – Accuracy: 81%
   - Random Forest – Accuracy: 88%, Recall: 90%
3. **Consultas SQL (ejemplos)**
   - Distribución de pacientes con factores de riesgo (edad, colesterol, angina).
   - Segmentación por sexo y tipo de dolor torácico.
   - Pacientes en alto riesgo (predicciones positivas).
4. **Dashboard en Power BI:**
   - KPIs principales: % pacientes en riesgo, edad media, colesterol medio.
   - Distribución por sexo y tipo de dolor.
   - Comparativa de modelos predictivos.
---

## 📊 Resultados Clave
- El modelo Random Forest fue el más preciso (88%) y con mejor recall (90%).
- Variables más influyentes: ST_Slope, ExerciseAngina, MaxHR, Oldpeak y Age.
- El dashboard en Power BI facilita la visualización de riesgos cardiovasculares y la comparación de métricas entre pacientes y grupos demográficos.

---
