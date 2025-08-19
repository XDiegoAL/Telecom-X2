Challenge3-TelecomX2
Este proyecto tiene como objetivo identificar los factores que influyen en la cancelación de clientes (churn) utilizando modelos de aprendizaje automático. A partir de los datos analizados, se desarrollaron modelos predictivos para anticipar la probabilidad de cancelación y se propusieron estrategias de retención basadas en los hallazgos.

📊 Análisis Predictivo de Cancelación de Clientes (Churn)
📌 Descripción
Este proyecto tiene como objetivo identificar los factores que influyen en la cancelación de clientes (churn) utilizando modelos de aprendizaje automático. A partir de los datos analizados, se desarrollaron modelos predictivos para anticipar la probabilidad de cancelación y se propusieron estrategias de retención basadas en los hallazgos.

🤖 Modelos Utilizados
🌳 Árbol de Decisión: Obtuvo un accuracy de 80.05%, mostrando un buen balance entre clases sin necesidad de normalización.
👥 K-Nearest Neighbors (KNN): Logró un accuracy de 78.31%, pero requiere normalización y es sensible a la distribución de las variables.
✅ El Árbol de Decisión fue seleccionado como el modelo más robusto para la implementación debido a su mejor desempeño general.

🔍 Variables Relevantes
Las variables que más impactan la predicción de cancelación incluyen:

📄 Tipo de contrato (Contract)
⏳ Antigüedad del cliente (tenure)
💳 Método de pago (PaymentMethod)
🧾 Facturación electrónica (PaperlessBilling)
🌐 Servicio de internet (InternetService)
🛠️ Técnicas Aplicadas
⚖️ Manejo de desbalance de clases mediante SMOTE
📈 Evaluación de modelos con métricas de precisión, recall y accuracy
💡 Estrategias de Retención Propuestas
🔒 Fomentar contratos a largo plazo con incentivos.
👋 Atención personalizada a nuevos clientes.
💰 Incentivar métodos de pago automáticos.
🧑‍💻 Mejorar soporte técnico y calidad del servicio.
🧠 Implementar monitoreo predictivo continuo.
🧰 Requisitos
🐍 Python 3.x
📦 Librerías: pandas, scikit-learn, imblearn, matplotlib, seaborn, etc.
▶️ Cómo Ejecutar
Clonar el repositorio
Instalar las dependencias:
pip install -r requirements.txt
👤 Autor
Diego Aylas - Alura Latam
