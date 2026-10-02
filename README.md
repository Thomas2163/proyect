# Modelado Predictivo de Salud Mental y Agotamiento Estudiantil (Burnout)

Este proyecto desarrolla un pipeline de Machine Learning para analizar y modelar la interacción entre la presión académica, los hábitos de vida y el bienestar psicológico de los estudiantes. El objetivo central es predecir los niveles de agotamiento (*burnout*).

---

## 👥 Integrantes del Equipo
* Alonso Gustavo Pacherres Rodriguez (20216420)
* Integrante 2 (código / rol)
* Integrante 3 (código / rol)
* Integrante 4 (código / rol)

---

## 📌 Descripción del Proyecto

### Objetivo
Desarrollar y evaluar modelos de Machine Learning supervisados para predecir el índice de agotamiento (`burnout_score`) a partir de indicadores de estilo de vida, factores académicos y bienestar psicológico.

---

## 📊 Descripción del Dataset

El conjunto de datos comprende **1,000,000 de registros** y **17 características (features)** distribuidas en las siguientes dimensiones:

* **Datos Demográficos:** `age` (17–29), `gender`, `academic_year` (1–4).
* **Factores Académicos:** `study_hours_per_day`, `exam_pressure` (1–10), `academic_performance` (0–100).
* **Indicadores de Salud Mental:** `stress_level` (0–10), `anxiety_score` (0–10), `depression_score` (0–10).
* **Estilo de Vida:** `sleep_hours`, `physical_activity` (horas semanales), `social_support` (0–10).
* **Conducta y Entorno:** `screen_time`, `internet_usage`, `financial_stress` (0–10), `family_expectation` (0–10).
* **Variables Derivadas / Objetivos:** `burnout_score` (0–10), `mental_health_index` (0–10), `risk_level` (Low, Medium, High), `dropout_risk` (0–10).

El archivo de datos sin procesar se ubica en `data/raw/`.

---

## 📁 Estructura del Repositorio

```text
proyecto/
├── README.md                      # Descripción del proyecto y ejecución
├── ENTREGABLE_PARCIAL.md          # Checklist de entregas (Semana 8)
├── ENTREGABLE_FINAL.md            # Checklist de entregas (Semana 15)
├── data/
│   ├── raw/                       # Datos originales (1M de registros)
│   └── processed/                 # Datos limpios y preprocesados
├── notebooks/
│   ├── 01_eda.ipynb               # Análisis exploratorio de datos
│   └── 02_modelos.ipynb           # Entrenamiento y evaluación de modelos
├── src/
├── results/
├── papers/                        # Artículos de referencia revisados por el equipo
├── report.pdf                     # Reporte / paper final
├── presentation.pdf               # Diapositivas de la presentación
