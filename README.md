# 📊 Optimización de Telemarketing Financiero mediante Modelado Predictivo

> **Trabajo Final de Máster (TFM)** enfocada en la aplicación de análisis de datos y machine learning para optimizar el marketing directo en el sector de la Banca y Servicios Financieros (Fintech).

---

## 🛠️ Tech Stack & Librerías

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-v1.5-150458.svg?style=flat&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-🚀-blue)

---

## 💼 Problema de Negocio

La entidad financiera enfrenta el desafío de maximizar la conversión de depósitos a plazo fijo mediante campañas de telemarketing. El modelo actual adolece de tres ineficiencias críticas:

*   **Baja eficiencia operativa:** Impactos repetidos al mismo cliente sin una garantía predictiva de éxito.
*   **Volatilidad estacional:** Concentración ineficiente de actividades en meses específicos (ej. sobrecarga en mayo vs. inactividad en noviembre).
*   **Costes elevados:** Recursos humanos y técnicos no optimizados según la propensión de compra real del cliente.

**🎯 Objetivo del Proyecto:** Analizar los datos de campañas históricas para identificar, ponderar (mediante técnicas como valores SHAP) y predecir los factores determinantes que impulsan a un cliente a contratar un depósito.

---

## 📊 Dataset

*   **Origen:** Dataset privado proporcionado por el programa de Máster (no disponible públicamente por restricciones de confidencialidad).
*   **Contenido:** Datos crudos y procesados que integran variables demográficas, del histórico de relación con el cliente y variables macroeconómicas.

---

## ⚙️ Metodología Aplicada

El proyecto sigue un pipeline riguroso de Ciencia de Datos dividido en las siguientes fases:

1.  **Definición Estratégica:** Establecimiento de objetivos generales, tácticas de negocio y diseño del árbol de indicadores clave de rendimiento (KPIs).
2.  **Configuración y Carga:** Preparación del entorno de producción en Python y orquestación de librerías (`Pandas`, `Seaborn`, `Plotly`, `FuzzyWuzzy`).
3.  **Exploración de Datos (EDA):** Análisis profundo de perfiles demográficos, impacto de variables macroeconómicas (Euríbor, inflación) y determinantes operativos de las campañas.
4.  **Limpieza e Ingeniería de Datos:** Tratamiento automatizado de valores nulos, eliminación de duplicados, gestión de *outliers* y normalización/codificación de variables categóricas.
5.  **Análisis Avanzado de KPIs:**
    *   *Penetración en Contexto de Tasas:* Impacto del Euríbor en la propensión de contratación.
    *   *Elasticidad de Conversión:* Relación matemática entre las variaciones de mercado y las ventas finales.
    *   *Tasa de Recurrencia:* Comportamiento analítico de clientes con historial de éxito previo.

---

## 💡 Principales Hallazgos (Insights)

*   **📈 Ventana de Oportunidad Macro:** Se detectó un repunte crítico de conversión en periodos con un Euríbor superior al **4.8%**, donde el producto se vuelve altamente competitivo.
*   **👤 Perfil de Alta Conversión:** Los perfiles administrativos con educación universitaria muestran una estabilidad financiera que correlaciona positivamente con la suscripción de depósitos a largo plazo.
*   **🛑 Fatiga del Cliente (Over-contacting):** El análisis de frecuencia de contacto identificó el límite óptimo de llamadas por campaña. Superado este umbral, la probabilidad de éxito decae drásticamente, disparando el coste operativo de forma innecesaria.

---

## 📦 Entregables del Repositorio

*   📁 `notebooks/` - Jupyter Notebook con todo el código estructurado de EDA, limpieza y modelado.
*   📁 `docs/` - Documento técnico detallado con la metodología y justificación estadística.
*   📄 `presentacion_ejecutiva.pdf` - Presentación final orientada a la Junta Directiva de la Fintech.

---

## 🚀 Cómo Ejecutar el Proyecto

1. Clona este repositorio en tu máquina local:
```bash
   git clone [https://github.com/tu-usuario/tu-repo.git](https://github.com/tu-usuario/tu-repo.git)
