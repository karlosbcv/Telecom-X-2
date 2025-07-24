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

## Graficas

<img width="913" height="561" alt="imagen" src="https://github.com/user-attachments/assets/a1be7fcc-beb3-4df1-b896-396b6845ec94" />

<img width="923" height="563" alt="imagen" src="https://github.com/user-attachments/assets/0a1277f6-c8d4-435f-97b0-88bd24a0778e" />

<img width="1007" height="597" alt="imagen" src="https://github.com/user-attachments/assets/68303968-1a27-4516-adf0-8439122d8a0e" />

<img width="1044" height="613" alt="imagen" src="https://github.com/user-attachments/assets/7a6433bf-c540-4fbb-9a80-748b5edd87eb" />



<img width="947" height="665" alt="imagen" src="https://github.com/user-attachments/assets/b7b672a0-b951-4cfe-9342-295238af35e5" />



- <img width="1495" height="468" alt="imagen" src="https://github.com/user-attachments/assets/743a8952-d7dc-4dad-af97-c5fadf9e481e" />


---

## 📌 Decisiones Estratégicas Recomendadas

- **Incentivar contratos de mayor duración**, ofreciendo beneficios a largo plazo.
- **Reducir cargos mensuales innecesarios** o mejorar la percepción de valor.
- **Monitorear clientes nuevos (tenure < 12 meses)** con programas de fidelización temprana.
- **Revisar la experiencia con facturación electrónica** y ofrecer alternativas más personalizadas.

---



