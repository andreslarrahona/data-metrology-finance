

<details>
  <summary style="cursor:pointer"><strong>Versión en español:</strong>
  </summary>
  
  # Auditoría de Estabilidad: USDT, USDC, DAI (2020-2022)

## Descripción
Evaluación técnica de la paridad (peg) de activos digitales mediante criterios de metrología y gestión de calidad. El análisis se centra en cuantificar la estabilidad y el riesgo de desviación operativa durante el trienio 2020-2022.

## Contenido del Repositorio
* **FI_EST_004.ipynb**: Notebook de Python que contiene el protocolo de ensayo FI-MET-004. Incluye la ingesta automatizada de datos, procesamiento de errores y visualización de control estadístico.

## Metodología Aplicada
1. **Captura de Datos**: Muestreo diario de precios de cierre (API Yahoo Finance).
2. **Criterio de Aceptación**: Tolerancia de paridad unitaria de 1.0000 USD ± 1%.
3. **Métricas de Calidad**:
    * Cálculo de Error Medio y Desviación Estándar.
    * Identificación de puntos fuera de tolerancia (Out of Tolerance - OOT).
    * Análisis de recuperación ante eventos de estrés sistémico.

## Requisitos
* Python 3.x
* Pandas
* Matplotlib / Seaborn
* yfinance

---
*Este análisis forma parte de un estudio de factibilidad técnica para operaciones de tesorería.*


</details>
<details open>
<summary style="cursor:pointer"><strong>English version:</strong>
</summary>

# Stability Audit: USD-Pegged Digital Assets (2020-2022)

## Project Overview
This repository contains a technical assessment of price stability for the three major stablecoins (USDT, USDC, and DAI). The study applies industrial metrology standards and quality management principles to evaluate financial data integrity and asset reliability for treasury operations.

## Repository Structure
* **FI_EST_004.ipynb**: A Python-based validation protocol. It handles automated data ingestion, error calculation, and statistical control visualization.

## Technical Methodology
The analysis follows the **FI-EST-004** feasibility study framework, focusing on the following stages:

1. **Data Ingestion**: Automated daily sampling from market APIs (2020-2022 period).
2. **Acceptance Criteria**: Unit parity defined at 1.0000 USD ± 1% tolerance.
3. **Quality Metrics**: 
    * Mean Error and Standard Deviation analysis.
    * Identification of **Out-of-Tolerance (OOT)** events.
    * Recovery rate assessment following systemic market stress (e.g., Q2 2022).

## Key Findings
The protocol identifies **USDC** as the asset with the highest conformity rate and lowest volatility during the audited period, demonstrating superior resilience during high-volatility events.

## Requirements
* Python 3.9+
* Pandas
* Matplotlib / Seaborn
* yfinance

---
*This project was developed as a technical feasibility study for operational risk management.*