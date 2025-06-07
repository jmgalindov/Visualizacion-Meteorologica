
# 📊 Visualización Interactiva de Datos Meteorológicos

## 🌦️ Descripción

Este proyecto consiste en un programa interactivo de visualización de datos meteorológicos históricos del año 2003. El usuario puede seleccionar una ciudad y un mes, y el programa generará gráficos que muestran las temperaturas **máximas y mínimas** registradas durante ese período.

Fue desarrollado como parte de un curso de Python con enfoque en análisis y visualización de datos, aplicando conceptos como:

- Manipulación de datos con `pandas`
- Visualización con `matplotlib`
- Interacción con el usuario desde consola
- Filtrado y agrupación de datos

---

## 🎯 Objetivo del proyecto

> Crear un programa interactivo que permita al usuario visualizar registros climáticos por ciudad y mes, combinando la creación de gráficos con el desarrollo de funciones en Python.

---

## 🧩 Funcionalidades

- Carga y limpieza de datos meteorológicos
- Conversión de fechas al formato correcto
- Selección de ciudad y mes por parte del usuario
- Gráficas de temperatura máxima y mínima por día
- Destacado automático de los valores extremos (máximo y mínimo)
- Consulta interactiva continua hasta que el usuario decida finalizar

---

## 🛠️ Requisitos

- Python 3.x
- pandas
- matplotlib
- numpy

Puedes instalar los paquetes necesarios con:

```bash
pip install pandas matplotlib numpy
```

---

## ▶️ Cómo usar

1. Asegúrate de tener el archivo CSV con los datos meteorológicos en la misma carpeta.
2. Ejecuta el script Python.
3. Elige una ciudad y un número de mes cuando se te solicite.
4. Observa las gráficas generadas.
5. Decide si deseas realizar otra consulta.

---

## 📌 Notas

- Los datos fueron agrupados por mes a partir de registros diarios.
- Las fechas nulas o incompletas fueron limpiadas o reemplazadas mediante métodos de imputación promedio.
- El eje Y de las gráficas se ha estandarizado para permitir una mejor comparación visual.

---

## 👨‍💻 Autor

Este proyecto fue desarrollado como parte de un curso de Python y forma parte de mi portafolio en análisis y visualización de datos.
