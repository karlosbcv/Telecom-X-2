# Telecom-X-2
Challenge Telecom X2
# 📉 Análisis de Cancelación de Servicios (Customer Churn)

Este proyecto tiene como objetivo **identificar los factores más influyentes en la cancelación de servicios por parte de los clientes (Churn)** y construir modelos predictivos que permitan anticipar el riesgo de pérdida de clientes.

---

## 🎯 Objetivos

- Analizar los datos de clientes para identificar patrones de cancelación.
- Visualizar y entender el impacto de las variables clave en el comportamiento de churn.
- Aplicar modelos explicativos (regresión) y predictivos (árboles, random forest).
- Apoyar la toma de decisiones estratégicas para reducir la fuga de clientes.

---

## 📊 Principales Factores que Influyen en el Churn

Mediante regresión logística, árboles de decisión y visualizaciones, se identificaron las siguientes variables como **las más asociadas con la cancelación de clientes**:

| Variable              | Impacto en el Churn | Descripción                                                             |
|-----------------------|---------------------|-------------------------------------------------------------------------|
| `Contract`            | Muy alto            | Los clientes con contratos mensuales tienen mayor probabilidad de cancelar. |
| `tenure`              | Alto                | Clientes con menor antigüedad (<12 meses) cancelan más.                  |
| `Charges Monthly`     | Moderado            | Cuotas mensuales más altas tienden a asociarse con mayor churn.         |
| `TechSupport`         | Moderado            | La falta de soporte técnico se asocia con más cancelaciones.            |
| `OnlineSecurity`      | Moderado            | La ausencia de seguridad en línea aumenta el riesgo de churn.           |
| `InternetService`     | Variable            | El tipo de servicio (Fibra óptica vs DSL) influye en la retención.      |
| `PaperlessBilling`    | Leve                | Los clientes con facturación electrónica tienden a cancelar más.        |
| `PaymentMethod`       | Leve                | Métodos como "Electronic Check" están más asociados al churn.           |

---

## 📈 Enfoque de Modelo

Se aplicaron diferentes modelos:

- **Regresión Logística**: para interpretar coeficientes e identificar variables con mayor impacto.
- **Árbol de Decisión**: para visualizar reglas de decisión claras que llevan a churn.
- **Random Forest**: para mejorar la capacidad predictiva y evaluar importancia de características.

---

## 📌 Decisiones Estratégicas Recomendadas

- **Incentivar contratos de mayor duración**, ofreciendo beneficios a largo plazo.
- **Reducir cargos mensuales innecesarios** o mejorar la percepción de valor.
- **Monitorear clientes nuevos (tenure < 12 meses)** con programas de fidelización temprana.
- **Revisar la experiencia con facturación electrónica** y ofrecer alternativas más personalizadas.

---



