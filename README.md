# 📊 Challenge de Evasión de Clientes — TelecomX

Este Challenge se enfocó en realizar una extracción, limpieza y analisis de datos con python, ultizando pandas, matplotlib y seaborn, con el fin de entender por qué los clientes abandonan la empresa TelecomX, mediante un analisis exploratorio basado en un dataset estructurado con información sobre contratos, servicios y comportamiento de los usuarios,etc. A partir de este análisis, se proponen acciones que permitan mejorar la fidelización de clientes y que la empresa telecomX sea rentable en el tiempo.

---

## 🔍 Principales Hallazgos y Explicaciones

### 1. **Tasa de evasión: 26% de los clientes se van de la compañia de telecomunicaciones**

Esto significa que aproximadamente **1 de cada 4 clientes** deja el servicio propuesto por la empresa. Esta tasa es crítica, ya que representa una pérdida directa de ingresos , lo cual supera los margenes aceptables del rubro de telecomunicaciones. Este margen esta en el nivel superior segun punto de vista economico, ya que el rango maximo de evasión ronda para que sea rentable entre un 10 a 25% (Esta empresa tiene un 26%). Y puede estar relacionada con insatisfacción, falta de lealtad o debilidad en la propuesta de valor percibida.

Esto se ve de mejor manera si lo traemos a numeros tangibles en un ejemplo.

Si suponemos que tenemos 100 clientes que captas como muestra y se van 26. Y este costo de adquisición (CAC) es alto, y el valor de vida del cliente es bajo, es probable que no sea rentable y no se pueda recuperar la inversión inicial de adquisición. 

Esto se explicara con mas detalle en el punto siguente con la tasa de retención(antiguedad)

---

### 2. **Antigüedad: los clientes nuevos (0–12 meses) se evaden más**

Se agruparon los clientes por rangos de antigüedad (en meses). El análisis muestra que la **mayor tasa de evasión ocurre en los primeros 6 a 12 meses**. Esto indica que los clientes que recién ingresan:

- Aún no han construido una relación sólida con la empresa.
- Pueden experimentar dificultades en la implementación o servicios defectuosos iniciales.
- Tienen menor compromiso emocional o contractual.

🔎 **Interpretación**: Los primeros meses son críticos. Si no se establece confianza y valor desde el principio, el riesgo de abandono es mucho mayor.

Por lo que, retomando el punto anterior con este y dejando el siguente ejemplo podemos ver de mejor manera que esto puede ser peligroso y dejar a la empresa fuera del rubro por no ser rentable. Si nos suponemos como en el punto anterior el CAC es alto y el retorno mensual por cliente es bajo, tenemos :

Costo de Adquisición (CAC) = $150
Ingreso mensual por cliente = $20
Margen neto mensual = $10

Si el cliente con estos datos se va entre en el limite superior de 12 meses te deja una ganancia neta de $120 por lo que estas perdiendo $30 por cada cliente.

---

### 3. **Tipo de contrato: mensual = mayor evasión**

Al analizar el tipo de contrato (mensual, anual o bianual), se encontró que los clientes con **contratos mensuales presentan la mayor tasa de evasión**. En cambio, los contratos de mayor duración retienen más clientes.

📌 **Explicación**:
- Los contratos mensuales permiten salir fácilmente, lo que reduce el compromiso.
- En cambio, los contratos anuales o bianuales implican planificación y generalmente ofrecen mejores precios.

---

### 4. **Cargo mensual: alto valor asociado a mayor evasión**

Se identificó que los clientes que pagan más al mes son más propensos a evadirse. Sin embargo, este grupo también suele tener servicios como **fibra óptica**, lo que sugiere que son clientes premium.

⚠️ **Riesgo**:
- Si un cliente paga más pero no percibe una mejora clara en el servicio, es más probable que se frustre y se vaya.
- Perder clientes premium implica perder más valor por cliente.

---

### 5. **Distribución: mayoría son clientes nuevos**

La mayoría de los clientes actuales tienen menos de 12 meses de antigüedad. Por lo tanto, la empresa debe concentrar esfuerzos de retención en este grupo, ya que cualquier mejora tendrá un impacto directo sobre el total de clientes.

---

## 📈 Visualizaciones Relevantes

Se incluyeron:
- **Tasa de evasión por grupo de antigüedad** (gráfico de línea).
- **Cantidad de clientes por grupo + tasa de evasión** (doble eje con línea y barra).
- Comparaciones por tipo de contrato, cargo mensual y servicios.

Estos gráficos permitieron evidenciar las relaciones antes descritas.

---

## ✅ Recomendaciones Estratégicas

1. **Campañas de contacto en los primeros 6 meses**
   - Automatizar mensajes, llamadas o encuestas para asegurarse de que el cliente esté satisfecho en los primeros meses.
   - Ofrecer soporte preferente para nuevos clientes.

2. **Incentivar contratos anuales o bianuales**
   - Ofrecer descuentos o beneficios exclusivos por cambiar de contrato mensual a uno de mayor duración.
   - Comunicar con claridad los beneficios del largo plazo.

3. **Atención personalizada a clientes premium**
   - Detectar clientes con cargos mensuales altos.
   - Ofrecerles soporte especializado, upgrades o bonos si cumplen un año.

4. **Programas de lealtad escalonados**
   - Crear un sistema de fidelización por tiempo: más meses con la empresa = más beneficios.
   - Esto puede incluir descuentos, regalos o acceso anticipado a nuevos servicios.

5. **Monitorear percepción de valor**
   - Aplicar encuestas o análisis de quejas en clientes con alta facturación.
   - Investigar causas de salida específicas mediante entrevistas o feedback automatizado.

---

## 📌 Próximos pasos

- Integrar estos hallazgos en un **dashboard interactivo** para monitoreo continuo.
- Desarrollar un **modelo predictivo de churn** (con Machine Learning).
- Conectar con fuentes externas (como encuestas o redes sociales) para enriquecer el perfil de riesgo de evasión.

---

🔧 **Creado por**: Pablo Santander  
📁 **Repositorio**: `Challenge_datos_2`  
📅 **Fecha**: Julio 2025
