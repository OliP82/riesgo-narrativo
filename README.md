# 📊 Riesgo Narrativo en Informes Financieros

Este proyecto tiene como objetivo analizar informes anuales de empresas cotizadas para detectar señales narrativas de riesgo oculto. Utiliza técnicas de PLN, análisis de sentimiento y evolución bursátil para generar un score compuesto que combina tono, opacidad y movimiento posterior del precio.

---

## 🚀 ¿Qué hace este proyecto?

- Extrae texto de informes anuales en PDF.
- Analiza el tono general usando FinBERT.
- Evalúa la opacidad narrativa mediante detección de lenguaje evasivo.
- Compara la narrativa entre años (similitud semántica).
- Descarga precios bursátiles y analiza su evolución tras el informe.
- Genera un score de riesgo por informe y lo visualiza en el tiempo.

---

## 📁 Estructura del proyecto
```
riesgo-narrativo/
├── backend/ # Notebook y lógica de análisis
├── frontend/ # Interfaz (por desarrollar)
├── data/ # PDFs de ejemplo
├── results/ # Archivos generados (JSON, gráficos, etc.)
└── README.md # Descripción general del proyecto
```

---

## 🛠 Cómo empezar

1. Clona este repositorio: `git clone https://github.com/tu_usuario/riesgo-narrativo.git`

2. Abre el archivo `backend/riesgo_narrativo.ipynb` en Google Colab o localmente.

3. Sigue las instrucciones del notebook para subir informes, indicar tickers y obtener análisis.

---

## 🧪 Próximos pasos

- Añadir análisis por secciones específicas (ej. "Risk Factors").
- Implementar fine-tuning de modelo para opacidad narrativa.
- Conectar backend con una interfaz React o Streamlit.

---

## 👤 Autor

Desarrollado como herramienta experimental para evaluar la narrativa financiera en contextos de riesgo potencial.

---

## 📄 Licencia

Este proyecto está bajo licencia MIT o personalizada (puedes ajustar esta sección según necesites).
