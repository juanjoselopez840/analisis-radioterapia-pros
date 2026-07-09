# Análisis de síntomas reportados por pacientes (PROs) durante tratamientos de radioterapia

Este repositorio contiene el código desarrollado en el marco del **Taller de Tesis** de la **Maestría en Ciencia de Datos** de la **Universidad de Buenos Aires (UBA)**.

El trabajo presenta un análisis de los **Patient Reported Outcomes (PROs)** registrados por pacientes durante tratamientos de radioterapia en un **centro de salud privado de Argentina**. A partir de estos reportes, se caracterizan los patrones de síntomas, su evolución a lo largo del tratamiento y los factores asociados con una mayor probabilidad de presentar síntomas moderados o severos.

---

## Objetivo

Caracterizar los síntomas reportados por pacientes durante tratamientos de radioterapia a partir de cuestionarios **Patient Reported Outcomes (PROs)**, identificando patrones según la región anatómica irradiada, la evolución temporal del tratamiento y los factores asociados con una mayor probabilidad de presentar síntomas moderados o severos mediante técnicas de ciencia de datos.

---

## Metodología del estudio

El análisis se desarrolló a partir de registros clínicos y cuestionarios **Patient Reported Outcomes (PROs)** obtenidos durante la práctica asistencial. La metodología combinó técnicas de preparación de datos, análisis exploratorio, análisis estadístico y aprendizaje automático para caracterizar la evolución de los síntomas e identificar los factores asociados con una mayor probabilidad de presentar síntomas moderados o severos.

El siguiente esquema resume las principales etapas desarrolladas durante el estudio.

<p align="center">
  <img src="figures/metodologia.png" alt="Metodología del estudio" width="900">
</p>

---

## Principales resultados

El análisis exploratorio permitió caracterizar la población de estudio y describir las principales variables demográficas y clínicas. La cohorte final estuvo compuesta por **438 pacientes** y **24.799 respuestas**, correspondientes a **28 síntomas unificados**, registradas durante el seguimiento de los tratamientos de radioterapia.

La siguiente figura resume las principales características de la cohorte analizada, incluyendo la distribución por rango etario, sexo, región anatómica irradiada y técnica de tratamiento.

<p align="center">
  <img src="figures/resumen.png" alt="Caracterización de la cohorte" width="900">
</p>

Posteriormente, se analizaron las asociaciones entre la severidad de los síntomas, la región anatómica irradiada y el tiempo transcurrido desde el inicio del tratamiento. Los resultados evidenciaron patrones diferenciales de severidad entre regiones, observándose una mayor concentración de síntomas moderados o severos entre los **30 y 60 días** desde el inicio del tratamiento, especialmente en pacientes tratados en **Cabeza y Cuello** y **Pelvis**.

<p align="center">
  <img src="figures/Heatmap.png" alt="Asociación entre región anatómica y severidad de los síntomas" width="900">
</p>

---

## Estructura del repositorio

```text
analisis-radioterapia-pros/
│
├── README.md
├── Analisis de Radioterapia.ipynb
└── figures/
    ├── metodologia.png
    ├── resumen.png
    └── heatmap.png
```

---

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Disponibilidad de los datos

Los datos utilizados en este proyecto corresponden a registros clínicos provenientes del sistema **MOSAIQ (Elekta)** de un centro de salud privado de Argentina. Debido a que contienen información sensible de pacientes, no pueden ser compartidos públicamente. Este repositorio incluye el código desarrollado y las principales visualizaciones obtenidas durante el estudio.

---

## Autor

**Juan José López**

Taller de Tesis – Maestría en Ciencia de Datos  
Universidad de Buenos Aires (UBA)

---

## Citación

Si este repositorio resulta de utilidad para trabajos académicos o de investigación, se agradece citar este proyecto y su correspondiente trabajo de tesis.
