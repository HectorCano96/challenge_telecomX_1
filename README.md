# 📊 Telecom X - Análisis de Evasión de Clientes

## 🗂 Descripción del Proyecto
Este repositorio contiene el análisis realizado para el desafío **"Churn de Clientes"** de **Telecom X**.  
El objetivo principal es **comprender los factores que explican la pérdida de clientes** y ofrecer un **informe exploratorio con insights relevantes** que sirvan de base para modelos predictivos y estrategias de retención.

---

## 🚀 Objetivos del desafío

✔️ Recopilar y procesar datos de clientes de Telecom X.  
✔️ Aplicar procesos **ETL** (Extracción, Transformación y Carga) en Python.  
✔️ Realizar un **Análisis Exploratorio de Datos (EDA)** para detectar patrones y correlaciones.  
✔️ Generar **visualizaciones estratégicas** que faciliten la interpretación de resultados.  
✔️ Proveer **insights clave** para la toma de decisiones del área de negocio y Data Science.

---

## 📂 Estructura del repositorio

📦 challenge_telecomX_1
┣ 📜 README.md
┣ 📜 TelecomX_LATAM.ipynb

---

## ⚙️ Cómo usar este repositorio

1. **Clonar el repositorio**  

   ```bash
   git clone https://github.com/HectorCano96/challenge_telecomX_1.git
   cd TelecomX-Churn
   
3. **Crear y activar un entorno virtual (opcional, recomendado)**
    
  python -m venv venv
  source venv/bin/activate   # En Linux/Mac
  venv\Scripts\activate      # En Windows
  
4. **Instalar dependencias**

pip install -r requirements.txt

5. **Abrir el Notebook**

jupyter notebook TelecomX_LATAM.ipynb


##📊 **Resumen de Resultados**

Tras el análisis exploratorio, los hallazgos más relevantes fueron:

###📌 Factores principales de cancelación:

Los clientes con contratos mensuales presentan una tasa de churn más alta en comparación con contratos a largo plazo.

El uso de servicios adicionales (Internet, teléfono, TV) influye directamente en la permanencia: a mayor número de servicios contratados, menor probabilidad de churn.

El monto de facturación mensual resultó un predictor clave: clientes con cargos elevados tienen mayor propensión a cancelar.

###📌 Segmentos de riesgo:

Clientes con pocos meses de antigüedad son más propensos a cancelar.

El churn se concentra más en clientes que pagan mes a mes frente a quienes usan tarjetas o débitos automáticos.

###📌 Visualizaciones estratégicas:
Se desarrollaron gráficos que muestran la distribución del churn, comparaciones entre clientes que cancelaron y los que permanecieron, y relaciones entre variables clave.


###📌 Conclusión
El análisis permitió identificar variables críticas en la evasión de clientes, destacando el tipo de contrato, el método de pago y los montos facturados.
Estos resultados servirán como base para el desarrollo de modelos predictivos de churn y el diseño de estrategias de retención personalizadas.

Héctor Cano - Economista | Analista y científico de datos.
