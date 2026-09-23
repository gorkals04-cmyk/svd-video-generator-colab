# 🎬 SVD Video Generator WebUI (Google Colab)

Generador de vídeo cinemático **Image-to-Video** basado en **Stable Video Diffusion XT** (`stabilityai/stable-video-diffusion-img2vid-xt`) y Hugging Face `diffusers`, con interfaz web interactiva mediante **Gradio**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gorkals04-cmyk/svd-video-generator-colab/blob/main/svd_video_generator.ipynb)

---

## 🚀 Características
- **Image-to-Video (I2V):** Convierte cualquier imagen estática en un clip animado de 25 fotogramas con coherencia temporal.
- **Control de movimiento dinámico:** Parámetro `Motion Bucket ID` ajustable para calibrar la intensidad del movimiento (desde paneos lentos hasta acción dinámica).
- **Optimización de VRAM:** Integración de `enable_model_cpu_offload` y `decode_chunk_size` para permitir inferencia de vídeo en entornos Colab (GPU T4 / A100).
- **Exportación MP4:** Visualización directa y descarga en contenedor MP4 estándar.

## 🛠️ Tecnologías y Librerías
- **Python 3.10+**
- **PyTorch** & **CUDA**
- **Diffusers** & **Transformers** (Hugging Face)
- **Gradio** (Frontend interactivo)
- **OpenCV** (Procesamiento de vídeo)

## 📖 Cómo ejecutarlo
1. Haz clic en el botón superior **Open in Colab**.
2. Selecciona un entorno con GPU (*Entorno de ejecución > Cambiar tipo de entorno de ejecución > GPU*).
3. Ejecuta las celdas en orden.
4. Abre el enlace local o público generado por Gradio, sube tu imagen y renderiza tu clip.
