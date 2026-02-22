# 🛡️ Monitor de Anomalías y Análisis de Riesgo

Este proyecto implementa un motor de detección de comportamientos anómalos (Churn) para el sector financiero, enfocado en la integridad y retención de cuentas.

## 🚀 Características Técnicas
- **Algoritmo:** Random Forest Classifier optimizado.
- **Manejo de Datos:** Balanceo de clases mediante Upsampling (Sobremuestreo) para mejorar la detección de eventos raros.
- **Métricas:** Enfoque en F1-Score y AUC-ROC para minimizar falsos positivos en entornos de seguridad.

## 📊 Hallazgos Clave
- El modelo alcanzó un **F1-Score de 0.62** en validación.
- La **Edad** y el **Estatus de Membresía Activa** resultaron ser los predictores más críticos para el perfilamiento de riesgo.
