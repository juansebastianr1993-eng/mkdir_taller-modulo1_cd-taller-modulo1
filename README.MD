# Taller Módulo 1 — Salud Mundial

**Autor:** Juan Sebastián Restrepo Diaz
**Máster:** IA & Data Science — DevSeniorCode

## Descripción
Este proyecto analiza indicadores de salud a nivel mundial usando Python y Pandas.
Se exploran variables como esperanza de vida, gasto en salud, mortalidad infantil
y tasas de vacunación para identificar patrones entre regiones y niveles de ingresos.

## Dataset
El dataset `salud_mundial.csv` contiene información de 159 países con 13 columnas
que incluyen: nombre del país, región geográfica, nivel de ingresos, esperanza de
vida, gasto en salud en dólares, mortalidad infantil, número de médicos por cada
1000 habitantes, porcentaje de población urbana, tasas de obesidad, diabetes,
tabaquismo, camas hospitalarias disponibles y porcentaje de vacunación.

## Cómo ejecutar
1. Clona el repositorio:
   git clone [url]
2. Instala dependencias:
   pip install pandas jupyter
3. Ejecuta:
   jupyter notebook taller_modulo1.ipynb

## Hallazgos principales
- Hallazgo 1: Los países con nivel de ingresos "Very High" tienen una esperanza
  de vida promedio superior a 80 años, mientras que los de nivel "Low" no superan
  los 65 años en promedio.
- Hallazgo 2: Los países con tasas de vacunación por encima del 80% presentan
  una mortalidad infantil significativamente menor que el resto.
- Hallazgo 3: Europa concentra el mayor gasto en salud per cápita por región,
  mientras que África registra los valores más bajos junto con la menor
  esperanza de vida promedio.

## Tecnologías
Python · Pandas · Jupyter Notebook · Git · GitHub