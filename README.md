# Predicción temprana del riesgo de preeclampsia · Streamlit

Metamodelo Ensemble Stacking (Random Forest, CatBoost, XGBoost, LightGBM y Regresión Logística + metamodelo de
Regresión Logística, SMOTE) con explicaciones SHAP. Umbral de decisión: 0.38.

Resultados en Test (n = 687): sensibilidad 0.9529 (81/85), especificidad 0.9219, ROC-AUC 0.9861, AP 0.9598.

## Despliegue en Streamlit Community Cloud

1. Subir todos los archivos de esta carpeta a la raíz del repositorio de GitHub.
2. En share.streamlit.io: *Create app* → repositorio → `app.py` → *Advanced settings* →
   la misma versión de Python que usó Colab al exportar el modelo → *Deploy*.

Prueba local: `pip install -r requirements.txt` y luego `streamlit run app.py`.

> Herramienta académica de apoyo. No constituye un diagnóstico médico.
