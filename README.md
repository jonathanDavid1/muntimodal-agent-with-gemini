# 🧬 Multimodal Video Intelligence Agent

Este proyecto es un **Agente de Inteligencia Artificial Multimodal** diseñado para analizar, razonar y extraer información crítica de archivos de video. Utiliza el modelo **Gemini 1.5 Flash** para procesar datos visuales y auditivos simultáneamente, permitiendo una comprensión profunda del contenido temporal y espacial.

## 🚀 Capacidades Principales

* **Análisis Visual Profundo:** Capacidad para entender contextos, objetos y secuencias de eventos dentro de clips de video.
* **Razonamiento Contextual (VQA):** Responde preguntas complejas basadas en la lógica de lo observado en el contenido multimodal.
* **Interfaz Streamlit:** Interfaz web lista para producción que permite la carga de archivos y visualización de resultados en tiempo real.
* **Gestión de Archivos Temporales:** Implementación de seguridad que elimina automáticamente los archivos procesados tanto del sistema local como de la API de Google tras cada análisis.

## 🛠️ Stack Tecnológico

* **Core AI:** Google Gemini 1.5 Flash API.
* **Frontend/UI:** Streamlit.
* **Lenguaje:** Python 3.10+.
* **Gestión de Archivos:** Google Generative AI File API.

---

## 📋 Configuración e Instalación

### 1. Preparar el entorno e instalar dependencias
Asegúrese de tener instaladas las dependencias especificadas en el archivo `requirements.txt`:

```bash
pip install -r requirements.txt

streamlit run "multimodal_agent.py"
