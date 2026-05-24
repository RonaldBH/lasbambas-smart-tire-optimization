# AI-Driven Tire Optimization for CAT 797F Mining Fleet

## Reducción de Variabilidad en Neumáticos Mineros mediante Asignación Dinámica Inteligente

Proyecto desarrollado para el programa **Innovadores en Acción – MMG Las Bambas**, enfocado en la optimización técnica y financiera del consumo de neumáticos en una flota de camiones CAT 797F mediante análisis estadístico, simulación operacional e Inteligencia Artificial.

---

# Objetivo del Proyecto

Diseñar un modelo inteligente de gestión de neumáticos que permita:

* Reducir la variabilidad del desgaste.
* Disminuir el OPEX asociado a neumáticos mineros.
* Optimizar la asignación de flota.
* Mejorar la estabilidad operacional.
* Validar técnicamente escenarios de despacho inteligente.

---

# Contexto Operacional

La operación minera cuenta con:

* 60 camiones CAT 797F.
* Dos zonas operacionales:

  * **Tajo Norte**
  * **Tajo Sur**

Cada zona presenta condiciones geomecánicas distintas que afectan directamente:

* desgaste de neumáticos,
* temperatura,
* TKPH,
* vida útil,
* y costo operacional por hora.

El Tajo Sur presenta:

* mayor dureza de roca,
* pendientes negativas,
* mayor estrés térmico,
* mayor degradación acelerada.

---

# Tecnologías Utilizadas

## Data Science & Machine Learning

* Python 3.10
* Pandas
* NumPy
* Scikit-Learn
* SciPy

## Visualización

* Plotly
* Matplotlib
* Power BI

## Documentación Técnica

* LaTeX

---

# Metodología Aplicada

## 1. Análisis Exploratorio de Datos (EDA)

Se analizaron:

* tasas de desgaste,
* comportamiento por tajo,
* temperatura,
* TKPH,
* costos operacionales.

---

## 2. Inferencia Estadística

Se aplicó:

* Prueba T de Student (Welch)

para validar diferencias significativas entre:

* Tajo Norte
* Tajo Sur

---

## 3. Validación Operacional

Se saneó el modelo operacional considerando:

* disponibilidad mecánica real = 83%

Validando:

* capacidad de producción,
* flota activa,
* cumplimiento de metas operacionales.

---

## 4. Simulación Inteligente

Se desarrolló un modelo híbrido utilizando:

* datos sintéticos,
* Random Forest Regressor,
* reglas dinámicas de optimización.

---

# Arquitectura del Modelo IA

La lógica inteligente evalúa:

* desgaste actual,
* temperatura,
* TKPH,
* vida útil remanente,
* zona operacional.

## Regla principal

Si un camión presenta:

* desgaste > 50%,
* TKPH elevado,
* temperatura crítica,

entonces:

* el sistema reasigna automáticamente el equipo al Tajo Norte para reducir severidad operacional.

---

# Resultados Principales

| Indicador               | Resultado          |
| ----------------------- | ------------------ |
| Diferencia de desgaste  | +29.3% en Tajo Sur |
| Disponibilidad validada | 83%                |
| Flota activa            | 49.8 camiones      |
| Reducción OPEX          | 10.76%             |
| Ahorro proyectado       | USD 1.29M          |
| Horizonte simulado      | 6 meses            |
| Camiones rotados        | 23                 |

---

# Machine Learning

## Modelo utilizado

```python id="stf4v9"
RandomForestRegressor
```

## Variables consideradas

* Horas de uso
* TKPH
* Temperatura
* Tajo asignado
* Desgaste acumulado

## Desempeño

```text id="8a44m5"
R² Score ≈ 0.95
```

---

# Dashboards y Visualizaciones

El proyecto incluye:

* dashboards Power BI,
* gráficos comparativos,
* simulaciones financieras,
* tablas operacionales,
* análisis de desgaste,
* arquitectura IA.

---

# Estructura del Proyecto

```text id="i4ksna"
Proyecto_LasBambas/

├── data/
├── notebooks/
├── outputs/
├── report/
├── dashboards/
├── images/
├── src/
└── README.md
```

---

# Resultados Financieros

| Escenario              | OPEX            |
| ---------------------- | --------------- |
| Asignación Fija        | $12,029,633 USD |
| Asignación Inteligente | $10,734,970 USD |

## Ahorro estimado

```text id="f7d44n"
USD 1,294,662.87
```

---

# Aplicación Industrial

Este proyecto demuestra la viabilidad de implementar:

* IA aplicada a minería,
* Dispatch inteligente,
* optimización operacional,
* mantenimiento predictivo,
* control de neumáticos mediante analítica avanzada.

---

# Futuras Mejoras

* Integración con sistemas DISPATCH reales.
* Uso de telemetría IoT.
* Entrenamiento con históricos reales.
* Integración con APIs de Fleet Management.
* Modelos predictivos en tiempo real.

---

# Autor

## Ruben Ronald Bautista Huillca

* Bachiller en Ingeniería Informática y de Sistemas
* Data Science & AI Applied to Mining
* Perú

---

# Programa

**Innovadores en Acción – MMG Las Bambas**

---

# Licencia

Proyecto académico y de investigación desarrollado con fines de innovación tecnológica aplicada a minería.
