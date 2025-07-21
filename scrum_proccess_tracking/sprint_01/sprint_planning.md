# 🗓️ Sprint 01 - 21/07/2025 al 22/07/2025

## 🎯 Objetivo del Sprint
Inicializar correctamente el entorno de desarrollo del proyecto PodcastTraductorAI, preparando su estructura de carpetas, el entorno virtual Python, la instalación de dependencias clave, y la base documental del proceso Scrum.

## 📋 Tareas seleccionadas del Product Backlog

- [*] Crear estructura base del proyecto (carpetas y archivos)
- [*] Crear carpeta `/scrum_process_tracking/sprint_01/`
- [*] Escribir planificación del sprint (`sprint_planning.md`)
- [*] Inicializar entorno virtual Python (.venv)
- [ ] Instalar dependencias básicas (whisper, gTTS, googletrans)
- [ ] Generar `requirements.txt`
- [ ] Inicializar repositorio Git
- [ ] Crear `.gitignore` para entorno virtual y carpetas temporales
- [ ] Primer commit con estructura y dependencias

- [ ] Crear archivo `transcriber.py` en `/app`
- [ ] Implementar función `transcribe_audio(path)` usando Whisper
- [ ] Añadir manejo de errores básicos (archivo no válido, no existe...)
- [ ] Integrar modelo Whisper (whisper.load_model)
- [ ] Ejecutar transcripción y devolver texto en inglés
- [ ] Guardar resultado en /data/transcriptions/ con mismo nombre base
- [ ] Probar con audio .mp3 de ejemplo
- [ ] Documentar uso básico en comentarios y/o README interno
- [ ] Crear archivo test_transcriber.py con prueba manual

## 🧪 Criterio de finalización del Sprint

El sprint se considerará completado cuando:

- Todas las tareas anteriores estén terminadas y versionadas en Git.
- El entorno esté listo para ejecutar código en Python con las dependencias instaladas.
- La documentación de planificación esté completa.

## 📎 Notas adicionales

Este es el primer sprint del proyecto. Se documentará en paralelo en Trello y en esta carpeta.