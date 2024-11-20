# 🛒 Test A/B para una Tienda Online

## 📖 Descripción del Proyecto

Este proyecto se centra en la **priorización de hipótesis** y el **análisis de un test A/B** para tomar decisiones basadas en datos en una tienda online. Se utilizan los frameworks **ICE** y **RICE** para priorizar hipótesis de forma estructurada y metódica. Además, se realiza un análisis detallado de los resultados del test A/B para evaluar su impacto en métricas clave como la tasa de conversión y el tamaño promedio de pedido.

## 💻 Demostración de Funciones y Aplicaciones

### **Parte 1: Priorización de Hipótesis**

#### Carga de Datos y Preprocesamiento
- Importación del archivo `hypotheses_us.csv` con hipótesis y métricas clave como **Reach**, **Impact**, **Confidence** y **Effort**.
- Verificación y limpieza de datos para garantizar precisión y consistencia.

#### Aplicación del Framework ICE
- Cálculo de la puntuación **ICE** para cada hipótesis.
- Ordenamiento de hipótesis en orden descendente basado en sus puntuaciones.

#### Aplicación del Framework RICE
- Cálculo de la puntuación **RICE** para cada hipótesis, integrando el parámetro **Reach**.
- Ordenamiento de hipótesis en orden descendente según su puntuación RICE.

#### Comparación entre ICE y RICE
- Análisis de las diferencias en la priorización al incluir el parámetro **Reach**.
- Identificación de hipótesis que ganan o pierden prioridad al cambiar de ICE a RICE.

### **Parte 2: Análisis de Test A/B**

#### Metodología
- Evaluación de la **tasa de conversión** y el **tamaño promedio de pedido** para los grupos A y B.
- Análisis de datos originales y datos filtrados tras eliminar anomalías.

#### Resultados Clave
- No se encontraron diferencias significativas en la **tasa de conversión** entre los grupos A y B en datos originales o filtrados.
- No se observaron diferencias significativas en el **tamaño promedio de pedido** entre los grupos A y B en datos originales o filtrados.
- Se detectó una tendencia a un menor tamaño promedio de pedido en el grupo B, pero esta diferencia no fue estadísticamente significativa.

#### Decisión Final
- Con base en los resultados, no se recomienda realizar cambios, ya que no se encontraron evidencias de diferencias significativas entre los grupos.

### **Conclusión**
Las pruebas de significancia estadística no muestran evidencia suficiente para rechazar la hipótesis nula. Aunque se observan tendencias en los datos filtrados, no son concluyentes para justificar modificaciones.

## 🛠 Tecnologías Utilizadas
- **Python**
- **Pandas**
- **Matplotlib**
- **NumPy**
- **SciPy**
- **Datetime**

## 📊 Resultados Clave
1. **Priorización de Hipótesis**:
   - El framework RICE demostró ser más completo al incluir el parámetro **Reach**, resultando en una priorización más ajustada a las necesidades del negocio.

2. **Análisis del Test A/B**:
   - No se encontraron diferencias significativas entre los grupos en las métricas evaluadas.
   - Se recomienda no realizar cambios basados en los resultados actuales.

## 🤝 Contribuciones
¡Sugerencias y mejoras son bienvenidas!  
Si deseas contribuir a este proyecto, por favor:  
- Crea un *issue* para reportar problemas o sugerir mejoras.  
- Abre un *pull request* con los cambios que quieras proponer.  

¡Gracias por tu interés en mejorar este proyecto! 😊
