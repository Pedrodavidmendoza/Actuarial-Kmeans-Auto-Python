# Segmentación Actuarial con KMeans en Python

Este repositorio contiene un análisis de segmentación aplicado a datos simulados del sector asegurador, específicamente para pólizas de autos. El objetivo es mostrar cómo las técnicas de **machine learning** pueden apoyar el trabajo actuarial para identificar grupos homogéneos y tomar decisiones técnicas mejor fundamentadas.

---

## 📊 Objetivo

Aplicar segmentación con **KMeans** sobre una base de datos ficticia que contiene:

- Edad del conductor
- Valor del vehículo
- Historial de siniestros
- Prima anual estimada

---

## 💡 Justificación Actuarial

La segmentación permite:

- Identificar grupos de riesgo diferenciados
- Establecer tarifas más precisas
- Optimizar reservas (ej. IBNR)
- Mejorar la selección de riesgos

---

## 📂 Datos

Se generan aleatoriamente 300 registros con las siguientes columnas:

- `edad_conductor`
- `valor_vehiculo_usd`
- `historial_siniestros`
- `prima_anual_usd`

---

## ⚖️ Tecnologías utilizadas

- Python 3.x
- Pandas
- NumPy
- Scikit-learn (KMeans)
- Seaborn y Matplotlib para visualización

---

## 📊 Resultados

Se obtienen 3 segmentos diferenciados visualmente según:

- Edad del conductor
- Valor del vehículo

Gráfico generado: `grafico_segmentacion_actuarial.png`

---

## 📅 Ejecución

1. Clona este repositorio
2. Abre el archivo `.ipynb` en Jupyter o ejecuta el script `.py`
3. Instala los paquetes si es necesario:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

4. Ejecuta el código y revisa el gráfico y el archivo CSV exportado

---

## 🔗 Autor

**Pedro Mendoza**  
Actuario | MBA Candidate | Especialista en BI y Análisis de Datos  
[LinkedIn](https://www.linkedin.com/in/pedrodavidmendoza/)

---

## 🌟 Licencia

Este proyecto está disponible para fines educativos y de demostración.
