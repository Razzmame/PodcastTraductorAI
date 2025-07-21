# 📋 Product Backlog – PodcastTraductorAI

Este backlog contiene únicamente las tareas correspondientes al módulo actual en curso (Módulo 1) y al siguiente módulo desbloqueado (Módulo 2).  
Nuevas tareas se añadirán conforme se inicie un nuevo módulo.

---

## 🟢 Módulo 1: Inicialización del proyecto

- [ ] Crear estructura base del proyecto (carpetas y archivos)
- [ ] Inicializar entorno virtual Python (.venv)
- [ ] Instalar dependencias básicas (whisper, gTTS, googletrans)
- [ ] Generar `requirements.txt`
- [ ] Inicializar repositorio Git
- [ ] Crear `.gitignore` para entorno virtual y carpetas temporales
- [ ] Primer commit con estructura y dependencias
- [ ] Crear carpeta `/scrum_process_tracking/sprint_01/`
- [ ] Escribir planificación del sprint 1 (`sprint_planning.md`)

---

## 🟡 Módulo 2: Transcripción (audio → texto)

- [ ] Crear archivo `transcriber.py` en `/app`
- [ ] Implementar función `transcribe_audio(path)` usando Whisper
- [ ] Añadir manejo de errores básicos (archivo no válido, no existe...)
- [ ] Integrar modelo Whisper (whisper.load_model)
- [ ] Ejecutar transcripción y devolver texto en inglés
- [ ] Guardar resultado en /data/transcriptions/ con mismo nombre base
- [ ] Probar con audio .mp3 de ejemplo
- [ ] Documentar uso básico en comentarios y/o README interno
- [ ] Crear archivo test_transcriber.py con prueba manual

---