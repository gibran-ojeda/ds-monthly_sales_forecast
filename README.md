# 📈 ds-monthly_sales_forecast  
**Predicción de Ventas Mensuales usando Regresión Lineal y Random Forest**  

## 📋 Descripción del Proyecto  
Este proyecto tiene como objetivo construir modelos de **regresión lineal** y **Random Forest** para prever las ventas del próximo mes, utilizando datos históricos.  
Se realiza una comparación entre ambos modelos para evaluar cuál ofrece mejores resultados, validando las predicciones con las ventas reales de diciembre.  

El análisis proporciona:  
- 📊 **Predicción de ventas mensuales** para cada sucursal o almacén.  
- 📈 **Comparación de predicciones (regresión lineal vs Random Forest) vs ventas reales**.  
- 🛠️ **Visualización** de las proyecciones en gráficos claros y detallados.  

---

## 🚀 Beneficios Clave  
- **Anticipación de ventas futuras** con base en patrones históricos.  
- **Evaluación de modelos predictivos** para elegir el más preciso.  
- **Optimización de inventarios y recursos** mediante previsión de demanda.  
- **Automatización** del análisis mensual, reduciendo el tiempo manual de estimación.  

---

## 🛠️ Herramientas Utilizadas  
- **Python** – Desarrollo de los modelos de predicción.  
  - **Scikit-learn** – Implementación de regresión lineal y Random Forest.  
  - **Pandas** – Manipulación y análisis de datos.  
  - **Matplotlib / Seaborn** – Visualización de resultados.  
- **Excel / CSV** – Entrada de datos históricos de ventas.  

---

## 📂 Componentes del Proyecto  
1. **Datos de ventas mensuales** (últimos 12-24 meses).  
2. **Modelos de regresión lineal y Random Forest** entrenados con datos históricos.  
3. **Gráficos comparativos** que muestran:  
   - Predicción de ambos modelos.  
   - Ventas reales para validación.  
4. **Reporte final con proyecciones de ventas** para el próximo mes.  

---

## 🔧 Cómo Ejecutar el Proyecto  
1. **Ubica el archivo CSV con los datos históricos de ventas** en la carpeta `input/`.  
2. **Ejecuta el script principal para entrenar los modelos:**  
   ```bash
   python train_model.py
