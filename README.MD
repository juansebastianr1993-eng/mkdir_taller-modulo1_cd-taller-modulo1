# 🌍 Análisis de Salud Mundial

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Estado-Completo-2ea44f?style=for-the-badge)

**Taller Integrador — Módulo 1**  
Máster en IA & Data Science · DevSeniorCode

**Autor:** Juan Sebastián Restrepo Díaz  
**Entrega:** 24 de marzo de 2026

</div>

---

## 📌 Descripción del proyecto

Este proyecto analiza indicadores de salud pública de **159 países** usando Python y Pandas. A partir del dataset `salud_mundial.csv`, se exploran variables como esperanza de vida, gasto en salud, mortalidad infantil y cobertura de vacunación para identificar patrones por región y nivel de ingresos.

El trabajo cubre todo el stack del Módulo 1:

| Área | Contenido |
|------|-----------|
| 🐍 Python | Listas, diccionarios, funciones, bucles |
| 🐼 Pandas | Carga, limpieza, filtrado, agrupaciones, columnas calculadas |
| 🔧 Git & GitHub | Flujo de trabajo, commits, buenas prácticas |
| 📝 Documentación | README, comentarios en código, celdas de texto |

---

## 📁 Estructura del repositorio

```
mkdir_taller-modulo1_cd-taller-modulo1/
│
├── taller_modulo1.ipynb   # Notebook principal con todo el análisis
├── salud_mundial.csv      # Dataset con indicadores de 159 países
└── README.md              # Este archivo
```

---

## 📊 Dataset

El archivo `salud_mundial.csv` contiene **159 filas × 13 columnas** con datos de salud pública a nivel mundial.

| Columna | Tipo | Descripción |
|--------|------|-------------|
| `pais` | str | Nombre del país |
| `region` | str | Continente o región geográfica |
| `nivel_ingresos` | str | Low / Medium / High / Very High |
| `esperanza_vida` | float | Esperanza de vida al nacer (años) |
| `gasto_salud_usd` | float | Gasto per cápita en salud (USD/año) |
| `mortalidad_infantil` | float | Muertes por cada 1,000 nacidos vivos |
| `medicos_por_1000` | float | Médicos por cada 1,000 habitantes |
| `poblacion_urbana_pct` | float | % de población urbana |
| `obesidad_pct` | float | % de población con obesidad |
| `diabetes_pct` | float | % de población con diabetes |
| `tabaquismo_pct` | float | % de fumadores |
| `camas_hospital_por_1000` | float | Camas hospitalarias por 1,000 hab. |
| `vacunacion_pct` | float | % de cobertura de vacunación |

> ⚠️ El dataset contiene valores nulos en varias columnas numéricas, tratados mediante imputación con la media de cada columna.

---

## 🚀 Cómo ejecutar

### Requisitos previos

- Python 3.10+
- pip

### Instalación

```bash
# 1. Clona el repositorio
git clone https://github.com/juansebastianr1993-eng/mkdir_taller-modulo1_cd-taller-modulo1.git
cd mkdir_taller-modulo1_cd-taller-modulo1

# 2. Instala las dependencias
pip install pandas jupyter

# 3. Abre el notebook
jupyter notebook taller_modulo1.ipynb
```

Luego ve a **Kernel → Restart & Run All** para ejecutar todas las celdas.

---

## 🔍 Hallazgos principales

### 1. Ingresos y longevidad van de la mano
Los países con nivel de ingresos **Very High** tienen un gasto promedio en salud de **$6,553 USD/año** y una esperanza de vida superior a **80 años**. Los países **Low income** gastan apenas **$127 USD/año** y no superan los 65 años en promedio.

### 2. Vacunación y mortalidad infantil están fuertemente relacionadas
Los países con cobertura de vacunación **> 80%** presentan una mortalidad infantil promedio de **11.52** por cada 1,000 nacidos vivos, frente a **46.11** en los países con menor cobertura — una diferencia de **34.59 puntos**.

### 3. Europa lidera, África rezagada
Europa tiene la mayor esperanza de vida promedio (**77.65 años**) y el mayor gasto en salud por región. África registra la menor esperanza de vida (**63.51 años**) y la mayor mortalidad infantil promedio.

### 4. Distribución global de categorías de vida
Del total de 159 países analizados:
- **39.6%** tienen esperanza de vida **Alta** (≥ 75 años)
- **49.7%** tienen esperanza de vida **Media** (60–74.9 años)
- **10.7%** tienen esperanza de vida **Baja** (< 60 años)

---

## 🛠️ Tecnologías utilizadas

- **Python 3.10+** — Lógica, funciones y estructuras de datos
- **Pandas** — Manipulación y análisis de datos tabulares
- **Jupyter Notebook** — Entorno de desarrollo interactivo
- **Git & GitHub** — Control de versiones y repositorio remoto

---
