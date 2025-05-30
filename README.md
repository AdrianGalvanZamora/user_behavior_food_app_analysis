# Análisis del Comportamiento del Usuario para Aplicación de Alimentos

Proyecto realizado en abril de 2025 como parte del bootcamp de TripleTen. Analicé el embudo de ventas y los resultados de un test A/A/B para evaluar el impacto de un cambio de fuentes en la aplicación de una empresa emergente de alimentos.

## Tecnologías
- Python (pandas, matplotlib, seaborn, scipy)
- Jupyter Notebook

## Estructura del Proyecto
- **Paso 1:** Estudio de datos generales (`logs_exp_us.csv`).
- **Paso 2:** Preparación de datos (renombrar columnas, manejar valores ausentes, agregar columnas de fecha).
- **Paso 3:** Análisis exploratorio:
  - Número de eventos y usuarios.
  - Período de datos y completitud.
- **Paso 4:** Embudo de eventos:
  - Frecuencia de eventos y proporción de usuarios.
  - Pérdida de usuarios por etapa.
- **Paso 5:** Resultados del test A/A/B:
  - Comparación de grupos de control (246 vs. 247).
  - Comparación del grupo de prueba (248) con controles.
  - Pruebas de hipótesis y nivel de significancia.
- **Paso 6:** Conclusiones generales.

## Archivos
- `notebooks/comportamiento_usuario_alimentos.ipynb`: Jupyter Notebook con el análisis completo.
- `data/logs_exp_us.csv`: Dataset original (no incluido por restricciones).
- `output/`: Capturas de gráficos.

## Instrucciones
1. Clona el repositorio: `git clone https://github.com/adriangalvanzamora/comportamiento-usuario-alimentos.git`
2. Instala dependencias: `pip install -r requirements.txt`
3. Abre el notebook: `jupyter notebook notebooks/comportamiento_usuario_alimentos.ipynb`
