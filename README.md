# 📊 Telecom X – Predicción de Cancelación (Churn)

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Análisis%20de%20Datos-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Cómputo%20Numérico-013243?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Tipo de Problema](https://img.shields.io/badge/Problema-Clasificación-blueviolet)
![Mejor Modelo](https://img.shields.io/badge/Mejor%20Modelo-Random%20Forest-success)
![Accuracy](https://img.shields.io/badge/Accuracy%20Test-80%25-brightgreen)
![Estado](https://img.shields.io/badge/Estado-Completado-success)
![Nivel](https://img.shields.io/badge/Nivel-Proyecto%20ML%20Junior-informational)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)

---

## 🚀 Descripción del Proyecto

Proyecto de Machine Learning enfocado en la **predicción de cancelación de clientes (Churn)** para Telecom X.

El objetivo fue construir un pipeline completo de modelado predictivo que permita anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios y así diseñar estrategias de retención basadas en datos.

---

## 🎯 Objetivo de Negocio

Permitir a Telecom X:

- Anticiparse a la cancelación de clientes  
- Reducir pérdidas económicas  
- Optimizar campañas de retención  
- Incrementar el Customer Lifetime Value (CLV)  

---

## 🧠 Modelos Implementados

Se entrenaron y evaluaron tres modelos de clasificación:

- 🌳 Árbol de Decisión  
- 🌲 Random Forest  
- 🤝 K-Nearest Neighbors (KNN)  

🏆 **Modelo más robusto:** Random Forest  
Accuracy en test ≈ 80%

---

## 🛠️ Pipeline del Proyecto

### 1️⃣ Preprocesamiento
- Limpieza y transformación de datos  
- Codificación de variables categóricas (OneHotEncoder)  
- Balanceo de clases  
- División en conjunto de entrenamiento y prueba  

### 2️⃣ Entrenamiento
- Ajuste de modelos  
- Evaluación comparativa  
- Análisis de generalización  

### 3️⃣ Evaluación
Se utilizaron métricas como:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Matriz de confusión  

### 4️⃣ Interpretación
- Importancia de variables (modelos basados en árboles)  
- Análisis de patrones de similitud (KNN)  
- Traducción de resultados en insights estratégicos  

---

## 📊 Principales Hallazgos

Los factores que más influyen en la cancelación son:

- 📌 Contrato mensual (Month-to-month)  
- ⏳ Baja antigüedad del cliente  
- 💰 Bajo gasto mensual o total acumulado  
- 🔐 No contar con Seguridad Online  
- 💳 No utilizar pago automático  

---

## 🎯 Perfil del Cliente con Mayor Riesgo

Cliente que:

- Tiene contrato mensual  
- Posee poca antigüedad  
- Presenta bajo compromiso con servicios adicionales  
- No utiliza pago automático  
- Tiene baja inversión acumulada  

---

## 💡 Estrategias de Retención Propuestas

- Incentivar contratos de largo plazo  
- Promover activación de pago automático  
- Ofrecer paquetes con servicios adicionales  
- Diseñar programas de fidelización temprana  

---

## 📈 Impacto Potencial

El modelo puede integrarse en sistemas CRM para:

- Identificar clientes en riesgo en tiempo real  
- Priorizar campañas de retención  
- Optimizar recursos comerciales  
- Mejorar la rentabilidad a largo plazo  

---

## 🧪 Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Google Colab  

---

## 📌 Conclusión

La cancelación en Telecom X está principalmente asociada a bajo compromiso contractual y baja antigüedad.

El modelo Random Forest mostró mayor estabilidad y capacidad de capturar relaciones complejas entre variables financieras y contractuales, convirtiéndose en la mejor opción para implementación en producción.

Este proyecto demuestra la aplicación práctica de Machine Learning orientado a la toma de decisiones estratégicas.

---

## 👨‍💻 Autor

| [<img src="https://github.com/user-attachments/assets/170d1b9d-3728-4fdd-a7b5-e5dda810171b" width=115><br><sub>Erick Honorio</sub>](https://github.com/lErick3000) |  
| :---: | 

Proyecto desarrollado como parte del **Challenge Data Science LATAM – Alura + Oracle Next Education (ONE)**.
