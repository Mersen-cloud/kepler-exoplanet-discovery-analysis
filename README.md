# 🪐 Kepler Exoplanet Discovery Analysis

> Análisis exploratorio y modelado predictivo sobre datos de la misión Kepler de la NASA, con el objetivo de identificar candidatos a exoplanetas y analizar las características que los distinguen.

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📋 Tabla de Contenidos

- [Descripción del Proyecto](#-descripción-del-proyecto)
- [Objetivos](#-objetivos)
- [Datos](#-datos)
- [Stack Tecnológico](#-stack-tecnológico)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Instalación y Uso](#-instalación-y-uso)
- [Roadmap](#-roadmap)
- [Resultados](#-resultados)
- [Autor](#-autor)
- [Licencia](#-licencia)

---

## 🌌 Descripción del Proyecto

Este proyecto explora el catálogo de objetos de interés del telescopio espacial **Kepler** (NASA), una de las misiones más importantes en la búsqueda de exoplanetas. A través de técnicas de análisis exploratorio de datos (EDA), visualización y machine learning, busco responder preguntas como:

- ¿Qué características distinguen a un exoplaneta confirmado de un falso positivo?
- ¿Existen patrones en los exoplanetas según su tamaño, periodo orbital o temperatura?
- ¿Es posible construir un modelo de clasificación que prediga si un objeto observado es un candidato real a exoplaneta?

Este es un proyecto de portafolio orientado a demostrar habilidades de **análisis de datos, ingeniería de features, visualización y modelado predictivo** aplicadas a un dominio científico real.

---

## 🎯 Objetivos

- **Objetivo principal:** desarrollar un pipeline completo de análisis de datos sobre el catálogo Kepler, desde la extracción hasta el modelado.
- **Objetivos específicos:**
  - Realizar un EDA riguroso del Kepler Objects of Interest (KOI) catalog.
  - Identificar variables relevantes para distinguir exoplanetas confirmados de falsos positivos.
  - Construir visualizaciones que comuniquen hallazgos de forma clara.
  - Entrenar y evaluar modelos de clasificación (Logistic Regression, Random Forest, Gradient Boosting).
  - Documentar el proceso de forma reproducible.

---

## 📊 Datos

Los datos provienen del **NASA Exoplanet Archive**, específicamente del **Kepler Objects of Interest (KOI) cumulative table**.

- **Fuente:** [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)
- **Método de acceso:** API de `astroquery` y descarga directa.
- **Tamaño aproximado:** ~9.500 objetos clasificados.
- **Variables principales:** periodo orbital, radio planetario, temperatura de equilibrio, características de la estrella anfitriona, entre otras.

> ⚠️ Los datos crudos no están versionados en este repositorio (ver `.gitignore`). Para reproducir el proyecto, los scripts en `src/data/` permiten descargarlos automáticamente.

---

## 🛠️ Stack Tecnológico

| Categoría | Herramientas |
|-----------|--------------|
| **Lenguaje** | Python 3.12 |
| **Análisis de datos** | pandas, numpy |
| **Visualización** | matplotlib, seaborn, plotly |
| **Machine Learning** | scikit-learn |
| **Astronomía** | astropy, astroquery |
| **Entorno** | Jupyter Notebook, VS Code |
| **Control de versiones** | Git, GitHub |

---

## 📁 Estructura del Proyecto

---

## ⚙️ Instalación y Uso

### Requisitos previos

- Python 3.10 o superior
- Git
- (Opcional) VS Code con extensiones Python y Jupyter

### Pasos

1. **Clonar el repositorio:**

```bash
git clone https://github.com/Mersen-cloud/kepler-exoplanet-discovery-analysis.git
cd kepler-exoplanet-discovery-analysis
```

2. **Crear y activar un entorno virtual:**

```bash
python -m venv venv
venv\Scripts\activate          # Windows
source venv/bin/activate       # Linux / macOS
```

3. **Instalar las dependencias:**

```bash
pip install -r requirements.txt
```

4. **Lanzar Jupyter:**

```bash
jupyter notebook
```

---

## 🗺️ Roadmap

- [x] Configuración del repositorio y entorno
- [ ] Descarga inicial de datos desde NASA Exoplanet Archive
- [ ] Análisis exploratorio de datos (EDA)
- [ ] Limpieza y preparación de datos
- [ ] Ingeniería de features
- [ ] Entrenamiento de modelos baseline
- [ ] Optimización y evaluación de modelos
- [ ] Visualizaciones finales y dashboard
- [ ] Documentación final y artículo de resultados

---

## 📈 Resultados

> 🚧 *Sección en construcción.* Los resultados se publicarán a medida que avance el proyecto.

---

## 👨‍💻 Autor

**Diego León**
Analista Programador Computacional | Aspirante a Data Analyst / Data Scientist
📍 Santiago, Chile

[![GitHub](https://img.shields.io/badge/GitHub-Mersen--cloud-181717?logo=github)](https://github.com/Mersen-cloud)

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.