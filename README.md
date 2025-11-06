📦 Product Portfolio Review — Análisis Estratégico de Productos con Ciencia de Datos

Objetivo: Evaluar el desempeño del portafolio de productos de una compañía a través de técnicas avanzadas de ciencia de datos. Este análisis permite tomar decisiones 
informadas sobre descontinuación, promoción, ajuste de precios, forecast y gestión de clientes clave.
   
📍 Este análisis forma parte de una iniciativa de IBP (Integrated Business Planning) con foco en rentabilidad, precisión de forecast y estrategias comerciales.
________________________________________
🧠 Tecnologías y Librerías
•	Python (pandas, numpy, seaborn, matplotlib)
•	Modelado estadístico: statsmodels, Prophet, XGBoost
•	Clustering: KMeans, Isolation Forest
•	Modelado de series temporales
•	Análisis multivariado y segmentación
________________________________________
📁 Dataset
Contiene más de 200,000 registros de ventas, forecasts, precios, responsables, canales y categorías de productos.
Formato: Excel .xlsx
Variables clave:
•	Producto, Cliente, Responsable, Fecha, Precio, Facturado, Forecast, Ordenes, etc.
________________________________________
🔍 Módulos Analíticos Realizados

✅ 1. Revisión ABC Cruzada (Ingresos vs. Unidades)
•	Clasificación de productos en A/B/C por ingresos y rotación.
•	Priorización del portafolio.
•	👉 Resultado: mayoría de productos se concentran en "C-C" (baja rotación y bajos ingresos).

✅ 2. Elasticidad Precio-Demanda
•	Modelo log-log para calcular sensibilidad al precio.
•	Etiquetado de productos como elásticos/inelásticos.
•	👉 Resultado: más del 30% de productos presentan elasticidad alta (>-1), indicando sensibilidad al precio.

✅ 3. Canibalización entre productos
•	Análisis de correlación negativa entre pares de productos.
•	👉 Resultado: No se detectaron correlaciones canibalizantes fuertes (< -0.5).

✅ 4. Segmentación BCG con Machine Learning
•	Variables: rentabilidad e ingreso.
•	Clustering en 4 grupos: Estrellas, Vacas, Interrogantes, Perros.
•	👉 Resultado: segmentación estratégica para inversión y promoción.

✅ 5. Erosión de Margen
•	Margen calculado con Costo estimado (60% del precio).
•	👉 Resultado: productos de alto volumen presentan márgenes negativos (pérdida).

✅ 6. Forecast Accuracy: MAPE y Bias
•	Evaluación de precisión del forecast consensuado por Categoria y Responsable.
•	👉 Métricas: MAPE promedio, Bias promedio.
•	👉 Resultado: categorías con alto volumen muestran MAPE > 60% y Bias negativos altos → sobreestimación sistemática.

✅ 7. Análisis por Cliente
•	Identificación de clientes críticos: alto volumen y baja precisión de forecast.
•	Clasificación simbólica por prioridad: 🟢 Alta | 🟠 Media | 🔴 Baja.

✅ 8. Ciclo de Vida del Producto
•	Clasificación en Introducción, Crecimiento, Madurez o Declive.
•	Basado en comparación de ventas 2023 vs 2024.
•	👉 Resultado: más del 80% de los productos activos están en fase de Declive.
________________________________________

📦 Product Portfolio Review — Análisis Estratégico de Productos con Ciencia de Datos
Objetivo: Evaluar el desempeño del portafolio de productos de una compañía a través de técnicas avanzadas de ciencia de datos. Este análisis permite tomar decisiones informadas sobre descontinuación, promoción, ajuste de precios, forecast y gestión de clientes clave.
   
📍 Este análisis forma parte de una iniciativa de IBP (Integrated Business Planning) con foco en rentabilidad, precisión de forecast y estrategias comerciales.
________________________________________
🧠 Tecnologías y Librerías
•	Python (pandas, numpy, seaborn, matplotlib)
•	Modelado estadístico: statsmodels, Prophet, XGBoost
•	Clustering: KMeans, Isolation Forest
•	Modelado de series temporales
•	Análisis multivariado y segmentación
________________________________________
📁 Dataset
Contiene más de 200,000 registros de ventas, forecasts, precios, responsables, canales y categorías de productos.
Formato: Excel .xlsx
Variables clave:
•	Producto, Cliente, Responsable, Fecha, Precio, Facturado, Forecast, Ordenes, etc.
________________________________________

📌 Conclusiones Estratégicas
•	🟥 Gran parte del portafolio tiene bajo impacto comercial.
•	📉 Amplia erosión de márgenes en productos de alto volumen.
•	🟡 Forecast inconsistente en varias categorías.
•	🔎 Urgente optimización de clientes y productos clave (prioridad de forecast y abastecimiento).
________________________________________
📎 Recomendaciones
•	Reducir o eliminar productos tipo "C-C" y con margen negativo.
•	Promocionar productos con alta elasticidad positiva (alto potencial de crecimiento).
•	Revisar estrategia de precios.
•	Ajustar forecast por etapa del ciclo de vida.
•	Enfocar esfuerzos comerciales en clientes con 🟢 alta prioridad y MAPE bajo.

<img width="1971" height="1125" alt="image" src="https://github.com/user-attachments/assets/51a18548-70bb-4f7d-914d-78a21289fd85" />
<img width="1971" height="1125" alt="image" src="https://github.com/user-attachments/assets/e9262b40-2516-42cd-bbc9-65c0cd9da534" />
<img width="1971" height="1125" alt="image" src="https://github.com/user-attachments/assets/18fb825f-b72a-4eb7-b74f-9c510efe3715" />
<img width="1971" height="1125" alt="image" src="https://github.com/user-attachments/assets/27ff1d63-80b2-44e5-ae01-2c1c11786ac7" />
<img width="1971" height="1125" alt="image" src="https://github.com/user-attachments/assets/6802bacf-efdb-4f19-ade0-bce92a51845e" />
<img width="1971" height="1125" alt="image" src="https://github.com/user-attachments/assets/17bb0d01-69ab-47b6-945c-e3701c5ae0ac" />
<img width="1971" height="1125" alt="image" src="https://github.com/user-attachments/assets/34952c70-d28a-473c-a80e-d6524705382b" />
<img width="1971" height="1125" alt="image" src="https://github.com/user-attachments/assets/fff1d44f-5c64-435d-92a9-b58bf6cf9809" />
<img width="1971" height="1125" alt="image" src="https://github.com/user-attachments/assets/32ae0f90-ffa1-4b9f-965e-8d3e0849f37c" />







## Autora

**Maribel Casillas** – Experta en planeación de la demanda y ciencia de datos aplicada a la cadena de suministro.


