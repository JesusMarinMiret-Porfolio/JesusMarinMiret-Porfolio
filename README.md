# Jesús Marín Miret – Data Analyst Portfolio

👋 ¡Hola! Soy Jesús, doctor en Biología Evolutiva con sólida experiencia en análisis de datos, visualización y automatización de procesos. He trabajado en investigación científica durante más de 6 años y ahora aplico mis habilidades para resolver problemas complejos usando R, Python, SQL y Power BI.

🔍 Me apasiona transformar datos en decisiones. En este repositorio encontrarás proyectos que demuestran mis habilidades como Data Analyst en distintos contextos.

---

## 📂 Proyectos destacados

### 1. **Campañas Online**
**Herramientas**: Power BI, Excel  
**Descripción**: Dashboard interactivo información detallada sobre ventas minoristas simuladas. Se analiza evolución de ventas, ranking de productos, comparativa entre regiones, etc.  
**Lo que aprendí**: Limpieza avanzada con Power Query, Creación de medidas con DAX, diseño de visualizaciones efectivas y narrativa con datos. 


![image](https://github.com/user-attachments/assets/67b45176-6290-4352-9f2e-909a1bd20ea5)

---

## 2. Retail Sales Analysis

**🔧 Herramientas:** Python, pandas, seaborn, matplotlib, Jupyter Notebook  
**📂 Dataset:** Datos simulados de ventas minoristas con más de 9,000 registros.

**🧾 Descripción:**  
Este proyecto consiste en un análisis exploratorio (EDA) de un dataset de ventas con el objetivo de identificar patrones de consumo, productos más rentables, tendencias temporales y oportunidades comerciales. Se analizaron variables como fecha, región, categoría de producto, cantidad vendida, descuentos, beneficios y más.

**📊 Análisis realizados:**
- Evolución mensual de ventas y beneficios.
- Ranking de productos por volumen de ventas.
- Análisis por región.
- Evaluación del impacto de los descuentos en el margen de beneficio.
 
![image](https://github.com/user-attachments/assets/6a40bee9-0b69-465e-836d-685d7554038d)

**📈 Lo que aprendí:**
- Aplicación completa del proceso EDA en un entorno de negocio simulado.
- Visualización efectiva de KPIs mediante gráficos claros y comparativos.
- Identificación de insights accionables útiles para marketing o estrategia comercial.

📁 *[Ver notebook aquí](https://github.com/JesusMarinMiret-Porfolio/JesusMarinMiret-Porfolio/blob/main/retail-sales-analysis/notebooks/retail_sales_analysis.ipynb)*

---

## 3. Microbiome Data Automation
**Herramientas**: R, Bash, ggplot2, DADA2, phyloseq, vegan

**Descripción:**
Desarrollé un pipeline automatizado y reproducible para el análisis de datos metagenómicos 16S rRNA, aplicado al estudio de la microbiota intestinal de la cucaracha Blattella germanica sometida a tres pulsos periódicos del antibiótico kanamicina. Este trabajo formó parte de mi tesis doctoral y culminó en la publicación del artículo:
📄 Adaptability of the gut microbiota of the German cockroach Blattella germanica to a periodic antibiotic treatment
🔗 DOI: 10.1016/j.micres.2024.127863

**Contribuciones clave:**

- Automatización del análisis bioinformático: Implementé scripts en R y Bash para procesar más de 500 muestras, incluyendo control de calidad, ensamblado, asignación taxonómica y análisis estadístico, garantizando reproducibilidad y eficiencia.

- Visualización de datos complejos: Utilicé ggplot2 para crear gráficos de diversidad alfa y beta, análisis de componentes principales (PCA) y representaciones de abundancia relativa, facilitando la interpretación de los cambios en la microbiota.

- Análisis de resiliencia microbiana: Evalué la capacidad de recuperación de la microbiota tras cada tratamiento antibiótico, identificando taxones bacterianos clave que mostraron patrones de resistencia y resiliencia.

- Predicción funcional: Apliqué herramientas de inferencia funcional para anticipar cambios en las rutas metabólicas bacterianas asociadas a los tratamientos, proporcionando una visión más profunda del impacto funcional de los antibióticos.

**📈 Lo que aprendí:**

- Estandarización de flujos de trabajo: Desarrollé un pipeline robusto que puede adaptarse a diferentes estudios metagenómicos, mejorando la eficiencia y la reproducibilidad.

- Automatización en bioinformática: Integré herramientas de línea de comandos y scripts en R para automatizar procesos complejos, reduciendo errores manuales y acelerando el análisis.

- Visualización profesional de datos: Perfeccioné mis habilidades en ggplot2 para generar visualizaciones claras y efectivas, esenciales para comunicar hallazgos científicos.

- Colaboración interdisciplinaria: Trabajé en un equipo multidisciplinario, coordinando con microbiólogos, bioinformáticos y estadísticos, lo que enriqueció mi perspectiva y habilidades de comunicación científica.

---

![image](https://github.com/user-attachments/assets/d2e0ac86-56e5-4593-8f4b-4e4f84534f14)

## 🛠️ Habilidades técnicas

- Lenguajes: **R, Python, SQL, Bash, DAX**
- Visualización: **Power BI, ggplot2, Matplotlib, Seaborn**
- Herramientas: **Git, Docker, Linux, Jupyter, Power Query**
- Análisis: **EDA, KPIs, Automatización, Estadística**

---

## 4. Traveler Insights with SQL  
**Herramientas**: SQL Server, Microsoft SSMS, modelo estrella, limpieza de datos, funciones de agregación  

**Descripción:**  
Diseñé y ejecuté un análisis completo sobre datos de hábitos de viaje a partir de un conjunto de datos realista descargado desde Kaggle. El proyecto abarcó la limpieza avanzada de los datos originales, la transformación de columnas problemáticas (como fechas y costes en diferentes formatos) y el diseño de un modelo dimensional (estrella) para facilitar el análisis de KPIs relevantes en el sector turístico.  

**Contribuciones clave:**  

- **Limpieza y normalización de datos**: Traté inconsistencias en campos numéricos como `Accomodation_cost` (mezcla de símbolos `$`, "USD") y homogeneicé formatos de fecha. Separé correctamente campos combinados como `Destination` en `City` y `Country`, incluso cuando los datos eran incompletos o ambiguos.

- **Modelo estrella**: Construí una base de datos con una tabla de hechos (`Trips`) y varias dimensiones (`Traveler`, `Date`, `Destination`, `Spending`) que permitiera análisis estructurado y reproducible a través de consultas OLAP.

- **Análisis exploratorio mediante SQL**: Calculé KPIs clave como el gasto medio por edad, duración media del viaje y destinos más populares, utilizando funciones como `AVG()`, `DATEDIFF()`, `GROUP BY`, y CTEs para consultas más complejas.

- **Visualización e interpretación**: Extraje conclusiones claras del comportamiento del viajero por grupos de edad, tipo de destino y estacionalidad, y preparé capturas visuales para representar los resultados, pensadas para un público técnico o de negocio.

**📈 Lo que aprendí:**  

- **Modelado de datos relacional**: Profundicé en el diseño de esquemas de bases de datos adaptados a casos reales, entendiendo la importancia de la separación entre hechos y dimensiones.

- **Transformación de datos complejos**: Desarrollé lógica SQL para normalizar y transformar columnas inconsistentes, y apliqué buenas prácticas de limpieza reproducible.

- **Consultas analíticas en SQL**: Mejoré mis habilidades para construir consultas complejas orientadas a negocio, interpretando resultados y vinculándolos con contextos reales del sector travel.

- **Documentación y presentación de proyectos**: Elaboré un README técnico para explicar el flujo de trabajo del proyecto, buenas prácticas aplicadas y resultados obtenidos, facilitando su evaluación como parte de mi portfolio profesional.

---

![image]<img width="959" height="710" alt="Modelo_Estrella" src="https://github.com/user-attachments/assets/45e02133-d5fc-440c-8c0e-23354764e8c5" />



## 📫 Contacto

- 💼 [LinkedIn](https://www.linkedin.com/in/jesus-marin-miret/)
- ✉️ jesusmiret@hotmail.com
