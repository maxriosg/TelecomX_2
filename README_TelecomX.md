
# 📉 Telecom X – Predicción de Cancelación de Clientes (Churn)

Este proyecto utiliza técnicas de Machine Learning para predecir la cancelación de clientes en Telecom X, permitiendo a la empresa tomar decisiones estratégicas basadas en datos.

## 🎯 Objetivo

Desarrollar modelos predictivos capaces de identificar clientes con alta probabilidad de cancelar sus servicios, utilizando datos históricos tratados y variables relevantes del negocio.

## 🧰 Herramientas y Tecnologías

- Python 3 (Google Colab)
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (SMOTE)
- Seaborn, Matplotlib
- GitHub

## 📂 Estructura del Proyecto

- `datos_tratados.csv`: Datos preprocesados
- `TelecomX_2.ipynb`: Notebook principal
- `README.md`: Este archivo
- `resultados/`: Reportes y métricas de los modelos

## 🔎 Análisis Exploratorio

- Se identificó desbalance en la clase objetivo (`Evasion`).
- Variables como tipo de contrato, método de pago, y tenencia del cliente mostraron fuerte relación con la cancelación.

## ⚙️ Modelos Desarrollados

| Modelo               | Accuracy | Precision | Recall | F1-score |
|----------------------|----------|-----------|--------|----------|
| Regresión Logística  | 0.500    | 0.500     | 0.484  | 0.492    |
| Random Forest        | 0.678    | 0.734     | 0.560  | 0.635    |

**Conclusión:** Random Forest fue el modelo con mejor desempeño general.

## 💡 Principales Hallazgos

- Contratos mensuales y clientes nuevos tienen mayor probabilidad de cancelar.
- La combinación de alto pago mensual y baja percepción de valor aumenta el churn.
- El modelo ayuda a priorizar acciones comerciales sobre segmentos críticos.

## 🛡️ Estrategias Recomendadas

- Incentivar contratos de mayor duración.
- Mejorar beneficios para clientes nuevos.
- Enfocar esfuerzos en clientes con bajo engagement y alta probabilidad de cancelar.

## 📝 Instrucciones de uso

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tu_usuario/TelecomX_2.git
   ```

2. Abre el archivo `TelecomX_2.ipynb` en Google Colab.
3. Sube `datos_tratados.csv` si no está cargado automáticamente.
4. Ejecuta el notebook paso a paso para replicar el análisis y entrenar los modelos.

## 📌 Créditos

Desarrollado por: **Tu Nombre o Equipo**  
Rol: Analista Junior de Machine Learning  
Desafío: Parte 2 – Predicción de Cancelación – Telecom X  
Plataforma: [Google Colab](https://colab.research.google.com/)
