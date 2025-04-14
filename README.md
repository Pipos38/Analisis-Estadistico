# Análisis de comportamiento de usuarios y comparación de tarifas – Megaline

Este proyecto simula un análisis realizado para la empresa de telecomunicaciones Megaline, que busca identificar cuál de sus dos planes de prepago (Surf vs Ultimate) genera más ingresos y cuál es más popular entre los usuarios.

## 🎯 Objetivo

Analizar los patrones de uso (llamadas, mensajes, datos) de los clientes y comparar los ingresos mensuales promedio por plan y por región, utilizando herramientas estadísticas y visualización de datos.

## 📂 Datos utilizados

El proyecto se basa en 5 conjuntos de datos:

- `megaline_users.csv`: información general de los usuarios (edad, ciudad, plan, fechas de alta y baja).
- `megaline_calls.csv`: duración de llamadas por usuario y fecha.
- `megaline_messages.csv`: cantidad de mensajes enviados por usuario y fecha.
- `megaline_internet.csv`: volumen de datos usados por usuario y fecha.
- `megaline_plans.csv`: detalles de cada plan prepago ofrecido por la empresa.

## 📊 Análisis realizado

- Limpieza de datos y conversión de tipos de columnas.
- Cálculo de ingresos mensuales por usuario considerando los excedentes sobre el plan contratado.
- Agrupación de uso mensual (llamadas, SMS, datos) por usuario.
- Análisis estadístico descriptivo por tipo de plan.
- Visualización de distribuciones con histogramas y estadísticas agrupadas.
- Pruebas de hipótesis:
  - Diferencia en ingresos promedio entre usuarios de Surf y Ultimate.
  - Diferencia en ingresos promedio entre regiones (NY/NJ vs otras).

## 🛠️ Herramientas utilizadas

- `Python`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy.stats`
- `Jupyter Notebook`

## ✅ Conclusión

*El plan Ultimate genera mayores ingresos por usuario, pero el plan Surf es más popular. Se recomienda enfocar el marketing en usuarios con alto uso de datos y llamadas para migrarlos al plan Ultimate.*

## 📁 Este repositorio contiene:

├── megaline_users.csv              # Datos de clientes  
├── megaline_calls.csv              # Datos de llamadas  
├── megaline_messages.csv           # Datos de SMS  
├── megaline_internet.csv           # Datos de navegación  
├── megaline_plans.csv              # Información de los planes  
├── megaline_analysis.ipynb         # Notebook principal con el análisis  
├── requirements.txt                # Librerías necesarias para reproducir el proyecto  
└── README.md                       # Descripción del proyecto  
