# tesis-portafolio

# Optimización de Carteras con Deep Learning

**Autor:** Lucas Mauricio Velázquez  
**Tesis de Maestría en Ciencia de Datos**, Julio 2025  
Directora: Dra. Leticia I. Gómez

---

## 📖 Resumen

Este proyecto acompaña la tesis “Optimización de Carteras con Deep Learning”.  
Compara métodos clásicos de Markowitz con dos paradigmas de Deep Learning:
- **End-to-End** (LSTM y DMLP optimizando directamente el Sharpe Ratio).  
- **Dos pasos** (predicción de retornos + optimización con MSAD).  

Se evalúan sobre:
- Años 2020–2023 (mercado normal).  
- Periodos de estrés: Crisis COVID-19 (feb–abr 2020) y Suba de tasas FED (jun–ago 2022).

---

## 📂 Estructura del repositorio

- **data/**  
  - `datos.xlsx`  
    - Hoja **VTI**: precios y log-retornos  
    - Hoja **AGG**: precios y log-retornos  
    - Hoja **DBC**: precios y log-retornos  
    - Hoja **^VIX**: precios y log-retornos  

- **notebooks/**  
  - `Portfolio_Optimizacion.ipynb`  
    Notebook completo (Colab/Jupyter) con todo el flujo de:  
    1. Carga y preprocesamiento  
    2. Definición de modelos (LSTM, DMLP, MSAD…)  
    3. Entrenamiento, validación y test  
    4. Cálculo de métricas y gráficos

- **slides/**  
  - `Defensa_Tesis.pptx`  
    Presentación para la defensa de la tesis

- `requirements.txt`  
  Lista de dependencias Python (`pandas`, `numpy`, `tensorflow`, `cvxpy`, `keras-tuner`, `openpyxl`, etc.)

- `.gitignore`  
  Ignora archivos temporales de Python y Jupyter:


