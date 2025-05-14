# analisis-fp-renovables

# ⚡ Optimización del Factor de Potencia y Proyección de Ahorro con Paneles Solares  

Este proyecto calcula la **potencia reactiva a compensar** para mejorar el **Factor de Potencia (F.P.)** y estima la **capacidad fotovoltaica** necesaria para cubrir un porcentaje del consumo eléctrico.  

---

## 🚀 **Características**  

✅ **Optimización del Factor de Potencia**:  
   - Calcula los **kVAr de compensación** necesarios para mejorar el F.P. a **0.95**.  
   - Ayuda a reducir **costos por energía reactiva**.  

✅ **Proyección de Ahorro con Paneles Solares**:  
   - Estima la **capacidad de paneles solares** (en kW) para cubrir el **30% del consumo**.  
   - Considera el **rendimiento solar de la región**.  

✅ **Visualización**:  
   - Gráfica de **capacitores requeridos (kVAr)** vs **potencia fotovoltaica (kW)** recomendada.  

---

## 📂 **Requisitos**  

📌 **Librerías necesarias**

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```bash
pip install numpy pandas matplotlib
