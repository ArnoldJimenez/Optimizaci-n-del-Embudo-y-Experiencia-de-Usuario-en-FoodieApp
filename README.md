# 📱 Prueba A/A/B – Análisis de Eventos en App Móvil

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![ABTest](https://img.shields.io/badge/A%2FB-Testing-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

Este proyecto analiza una **prueba A/A/B** realizada en una aplicación móvil, con el objetivo de evaluar si un **cambio en la tipografía** afecta la conversión de los usuarios en las distintas etapas del embudo de navegación.  

---

## 🚀 Conclusiones principales

### 📊 Eventos analizados
Se compararon las proporciones de usuarios que completaron los siguientes eventos:
- `Tutorial`  
- `MainScreenAppear`  
- `OffersScreenAppear`  
- `CartScreenAppear`  
- `PaymentScreenSuccessful`  

---

### 🧪 Resultados estadísticos
- Se realizaron **15 pruebas de hipótesis** en total:  
  - 5 comparaciones entre **grupo 246 vs 247** (A/A).  
  - 5 comparaciones entre **grupo 248 vs 246** (A/B).  
  - 5 comparaciones entre **grupo 248 vs 247** (A/B).  
- En todos los casos, los **p-valores fueron mayores al nivel de significancia**.  

---

### 🎯 Nivel de significancia
- Por convención en pruebas A/B se suele usar **α = 0.05 (5%)**.  
- En este análisis, aunque no se especificó inicialmente, **ningún resultado fue significativo ni con α = 0.05 ni con α = 0.1**.  

---

### 🧐 Interpretación
- **No se detectaron diferencias estadísticamente significativas** entre los grupos en ninguna etapa del embudo.  
- Los grupos A (246 y 247) se comportaron de manera similar, confirmando que el experimento estuvo bien balanceado.  
- El grupo B (248, con nueva tipografía) tampoco mostró un impacto significativo frente a los grupos de control.  

---

## 🛠️ Conclusiones finales
- El cambio en la **tipografía** de la aplicación **no afecta la conversión** de los usuarios.  
- El embudo se mantiene estable en todas las comparaciones.  
- Se valida que la aplicación puede mantener la modificación sin riesgo de empeorar la experiencia de usuario.  

---

## 📂 Contenido del repositorio
- 📁 `notebooks/` → Jupyter Notebooks con el análisis de los eventos.  
- 📁 `data/` → Dataset anonimizado de usuarios y eventos.  
- 📁 `reports/` → Tablas y visualizaciones de resultados.  

---

## ✨ Tecnologías utilizadas
- **Python** 🐍 (pandas, numpy, scipy, statsmodels)  
- **Jupyter Notebook** 📓  
- **Visualización**: matplotlib, seaborn  
- **Pruebas estadísticas**: Z-test para comparación de proporciones  

---

## 📌 Autor
**Arnold Joel Jimenez**  
📍 Analista de Datos | Bogotá, Colombia  


