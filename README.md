# Análisis del Comportamiento del Usuario en Aplicación de Alimentos 🍔📊

**Nota:** La versión en inglés se encuentra al final de este documento.  

---

## 📖 Descripción General

Este proyecto, desarrollado en abril de 2025 como parte del bootcamp de **TripleTen**, analiza el **embudo de ventas** y los resultados de un experimento **A/A/B test** en una aplicación de una startup del sector alimentario.  
El objetivo fue determinar si un cambio en las fuentes de la interfaz afectaba el comportamiento de los usuarios y las conversiones dentro de la app.

---

## 🧰 Tecnologías Utilizadas

- **Python:** pandas, matplotlib, seaborn, scipy  
- **Entorno:** Jupyter Notebook  

---

## 🧩 Estructura del Proyecto

1. **Estudio de datos generales:** Análisis inicial del dataset `logs_exp_us.csv`.  
2. **Preparación de datos:** Renombrado de columnas, manejo de valores ausentes y creación de columnas de fecha.  
3. **Análisis exploratorio:**  
   - Conteo de eventos y usuarios únicos.  
   - Identificación del período cubierto por los datos.  
4. **Embudo de eventos:**  
   - Cálculo de la frecuencia de eventos y proporción de usuarios por etapa.  
   - Análisis de pérdida de usuarios entre pasos del embudo.  
5. **Resultados del test A/A/B:**  
   - Comparación entre los grupos de control (246 y 247).  
   - Evaluación del grupo experimental (248).  
   - Pruebas de hipótesis para diferencias significativas.  
6. **Conclusiones:** Impacto del cambio visual y recomendaciones basadas en los datos.

---

## 🗂️ Archivos del Proyecto

- `notebooks/comportamiento_usuario_alimentos.ipynb`: Notebook con el análisis completo.  
- `data/logs_exp_us.csv`: Dataset original (no incluido por políticas de privacidad).  
- `output/`: Carpeta con capturas de gráficos y resultados.  

---

## 🚀 Instrucciones de Ejecución

Para reproducir el análisis localmente, ejecuta los siguientes comandos:

\`\`\`bash
# Clonar el repositorio
git clone https://github.com/adriangalvanzamora/comportamiento-usuario-alimentos.git

# Acceder al directorio
cd comportamiento-usuario-alimentos

# Instalar dependencias
pip install -r requirements.txt

# Abrir el notebook
jupyter notebook notebooks/comportamiento_usuario_alimentos.ipynb
\`\`\`

---

## 📈 Resultados Clave

- Los grupos de control (246 y 247) no mostraron diferencias estadísticamente significativas.  
- El grupo experimental (248) mantuvo tasas de conversión similares, indicando que el cambio de fuente **no afectó la experiencia del usuario**.  
- Se observó que la mayoría de los usuarios abandonan en las etapas intermedias del embudo, lo que sugiere oportunidades de optimización UX.  

---

## 💡 Mejoras Futuras

- Ampliar el análisis con pruebas A/B adicionales en variables visuales.  
- Implementar un seguimiento de cohortes para evaluar retención a largo plazo.  
- Automatizar reportes de embudo con paneles interactivos (Streamlit o Power BI).  

---

## 🧑‍💻 Autor

**Adrián Galván Zamora**  
📂 [Repositorio en GitHub](https://github.com/adriangalvanzamora/comportamiento-usuario-alimentos.git)


---

# 🇺🇸 User Behavior Analysis for Food Delivery App 🍕📉

## 📖 Overview

This project, completed in **April 2025** as part of the **TripleTen Bootcamp**, focuses on analyzing user behavior within a food delivery application.  
The study examines the **sales funnel** and evaluates an **A/A/B experiment** to determine whether changing font styles in the interface influenced user engagement and conversion rates.

---

## 🧰 Technologies

- **Python:** pandas, matplotlib, seaborn, scipy  
- **Environment:** Jupyter Notebook  

---

## 🧩 Project Structure

1. **General Data Review:** Exploration of the `logs_exp_us.csv` dataset.  
2. **Data Preparation:** Column renaming, handling missing values, and date processing.  
3. **Exploratory Analysis:**  
   - Number of unique users and events.  
   - Period coverage and completeness.  
4. **Funnel Analysis:**  
   - Frequency of events and user proportions at each step.  
   - Drop-off rates between funnel stages.  
5. **A/A/B Test Results:**  
   - Comparison of control groups (246 vs. 247).  
   - Evaluation of the experimental group (248).  
   - Hypothesis testing for statistical significance.  
6. **Conclusions:** Summary of experiment impact and actionable insights.

---

## 🗂️ Project Files

- `notebooks/comportamiento_usuario_alimentos.ipynb`: Full Jupyter Notebook with the analysis.  
- `data/logs_exp_us.csv`: Original dataset (excluded for confidentiality).  
- `output/`: Folder with plots and output images.  

---

## 🚀 How to Run

To reproduce the analysis locally, run the following commands:

\`\`\`bash
# Clone the repository
git clone https://github.com/adriangalvanzamora/comportamiento-usuario-alimentos.git

# Navigate to project directory
cd comportamiento-usuario-alimentos

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook notebooks/comportamiento_usuario_alimentos.ipynb
\`\`\`

---

## 📈 Key Findings

- Control groups (246 and 247) showed no statistically significant difference.  
- Experimental group (248) exhibited similar conversion rates, indicating that the font change **did not impact user behavior**.  
- Major user drop-offs occurred mid-funnel, highlighting UX optimization opportunities.  

---

## 💡 Future Improvements

- Extend A/B tests to other visual or interaction changes.  
- Perform cohort retention analysis over time.  
- Develop interactive dashboards for automated funnel reporting.  

---

## 🧑‍💻 Author

**Adrián Galván Zamora**  
📂 [GitHub Repository](https://github.com/adriangalvanzamora/comportamiento-usuario-alimentos.git)

---
