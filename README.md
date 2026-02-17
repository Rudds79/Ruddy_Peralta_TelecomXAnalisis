# 📊 Telecom X – Análisis de Evasión de Clientes (Churn)

**Autor:** RUDDY PERALTA RODRIGUEZ  
 

---

## 🧠 Introducción

Este proyecto analiza el fenómeno de **evasión de clientes (churn)** en Telecom X, con el objetivo de identificar patrones y factores asociados a la cancelación del servicio.

El churn representa la pérdida de clientes y constituye un problema crítico, ya que impacta directamente en los ingresos recurrentes y en la sostenibilidad del negocio. Identificar patrones y variables asociadas al abandono permite diseñar estrategias de retención más efectivas.



---

## 🎯 Objetivos del análisis

- Analizar la distribución del churn entre los clientes.
- Identificar variables  y numéricas asociadas a la evasión.
- Explorar relaciones entre variables mediante análisis de correlación.
- Generar insights relevantes para la toma de decisiones.

---

## 🧹 Limpieza y preparación de datos

Actividades a realizar en esta primera etapa:

1. Importar los datos;

2. Comprender qué información contiene el dataset;

3. Verificar las inconsistencias;

4. Corregir las inconsistencias;

5. Traducir las columnas y/o datos;

6. Crear la columna de cuentas diarias.

---

## 📊 Análisis Exploratorio de Datos (EDA)

### 🔹 Distribución de evasión
Se analizó la proporción de clientes que cancelaron el servicio frente a los que permanecieron activos.

### 🔹 Variables
Se estudió la evasión según:
- Género
- Tiempo de contrato
- Valor mensual
- Total Cobrado 
- Tipo de contrato
- Tipo de internet
- Método de pago


Los resultados indican que:
- El análisis muestra una mayor tasa de churn en contratos mensuales y ciertos métodos de pago.
- Los clientes que abandonan el servicio tienden a tener menor antigüedad.
- Los clientes con churn presentan, en promedio, cargos mensuales más elevados.
- El total gastado está fuertemente asociado a la antigüedad del cliente.
- Los métodos de pago automáticos (transferencia y tarjeta) están asociados con mayor retención de clientes, mientras que los cheques electrónicos concentran el mayor riesgo de churn

---

## 🔗 Análisis de correlación

Se realizó una matriz de correlación entre variables numéricas para identificar relaciones relevantes.

El churn está más asociado con clientes nuevos y de bajo total cobrado, mientras que los clientes de mayor antigüedad y con pagos acumulados más altos muestran mayor fidelidad. En cambio, el valor mensual y las cuentas diarias tienen una relación positiva pero débil con el churn, lo que sugiere que pagar más cada mes no garantiza permanencia si la relación con la empresa es corta.

---

## 📌 Conclusiones e insights

- El churn se concentra en clientes recientes.
- Los contratos mensuales presentan mayor tasa de evasión.
- La antigüedad actúa como un factor protector frente al churn.
- El nivel de cargos influye en la decisión de abandono.
- Pagos automáticos reducen significativamente la evasión, mientras que métodos manuales como cheques electrónicos aumentan el riesgo.

---

## 💡 Recomendaciones


- Programas de fidelización por antigüedad: Recompensar a clientes de larga duración con beneficios acumulativos, reforzando la permanencia.- Incentivar la migración hacia contratos de mayor duración.
- Atención proactiva a clientes nuevos: Implementar seguimiento personalizado en los primeros meses para reducir la tasa de abandono inicial.
- Evaluar beneficios para clientes con cargos elevados mensuales.
- La forma de pago no solo es un detalle administrativo, sino un factor clave en la fidelización: quienes usan pagos automáticos tienden a mantener una relación más estable con la empresa.
- Usar modelos predictivos basados en estas correlaciones para identificar clientes en riesgo y actuar antes de que se produzca la evasión.


📌 En resumen, el análisis muestra que la retención depende más de la antigüedad y la experiencia del cliente que del gasto mensual o la cantidad de servicios contratados. Las estrategias deben enfocarse en simplificar la gestión, incentivar pagos automáticos y fortalecer la relación a largo plazo.
---


## 🛠️ Tecnologías utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib 
- Plotly Express 
- Seaborn  
- Google Colab  

---


