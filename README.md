# tesis-portfolio

**Optimización de Carteras con Deep Learning**  
**Autor:** Lucas Mauricio Velázquez  
**Tesis de Maestría en Ciencia de Datos**, ITBA, Julio 2025  
**Directora:** Dra. Leticia I. Gómez  

---

## 📖 Resumen

Este repositorio acompaña la tesis _“Optimización de Carteras con Deep Learning”_.  
Compara el método clásico de Markowitz con dos paradigmas de Deep Learning:
- **End-to-End:** LSTM y DMLP optimizando directamente el Sharpe Ratio (softmax + sharpe_loss).  
- **Dos pasos:** predicción de retornos con redes y optimización con MSAD.

Se evalúa sobre:  
- Años **2020–2023** (mercado normal).  
- Periodos de estrés: **Crisis COVID-19** (feb-abr 2020) y **Suba de tasas FED** (jun-ago 2022).

---

## 📁 Estructura del repositorio

```text

tesis-portfolio/
├── Portfolio_Optimizacion.ipynb  # Notebook principal
├── requirements.txt               # Dependencias
├── .gitignore                     # Ignorados por Git
├── README.md                      # Documentación del proyecto
├── data/                          # Datos
└── slides/                        # Presentación PPTX
```
---

## 🚀 Ejecución

1. **Abrir en Colab**  
   https://colab.research.google.com/github/Lucasmv84/tesis-portfolio/blob/main/Portfolio_Optimizacion.ipynb  


2. **Instalar dependencias** (local):  
   ```bash
   pip install -r requirements.txt
   ```  

3. **Ejecutar todas las celdas** del notebook para reproducir los resultados. 

---

## 📜 Licencia

Este proyecto se distribuye bajo los términos de la **GNU General Public License v3.0**.  
Para más detalles, consulta el fichero [LICENSE](LICENSE).

#### Derechos y obligaciones principales

- **Copyleft fuerte**: cualquier derivado de este trabajo debe publicarse también bajo GPL v3.  
- **Uso libre**: puedes usar, copiar, modificar y distribuir este software.  
- **Transparencia**: debes proporcionar el código fuente completo de las modificaciones.  
- **Sin garantía**: este software se ofrece “tal cual”, sin ninguna garantía.

> _Para ver el texto completo de la licencia, abre el archivo `LICENSE`._
