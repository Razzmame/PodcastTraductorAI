# 🎙️ PodcastTraductorAI

**PodcastTraductorAI** es una aplicación modular en Python que traduce archivos de audio (podcasts) del inglés al español. El sistema realiza:

1. Transcripción automática del audio.
2. Traducción del texto generado.
3. Generación de voz en español (TTS).

---

## 🚀 Objetivo actual

En **fase Alpha**, centrado en el backend:

- Transcripción con **Whisper**
- Traducción básica con **googletrans**
- Generación de voz con **gTTS**
- Sin interfaz gráfica por ahora

---

## 📦 Tecnologías (Alpha)

- Python 3.9+  
- `whisper` (OpenAI) – Transcripción  
- `googletrans` – Traducción  
- `gTTS` – Text-to-speech  
- `torch` – Dependencia de Whisper  
- Git + GitHub – Control de versiones  
- Trello – Gestión Scrum  
- Metodología **Scrum** documentada

---

## 📚 Seguimiento Scrum
Se aplica Scrum adaptado a proyecto personal:

    - Product Backlog con tareas del módulo actual y siguiente
    - Sprints de 2 días documentados en /scrum_process_tracking/sprint_XX/
    - Daily Scrum breve registro diario
    - Sprint Review y Retrospective en cada sprint

---

## Instalación 
git clone https://github.com/tuusuario/PodcastTraductorAI.git
cd PodcastTraductorAI
python -m venv .venv
# Linux/macOS
source .venv/bin/activate
# Windows
.venv\Scripts\activate
pip install -r requirements.txt

## 🧱 Estructura del proyecto

```text
PodcastTraductorAI/
│
├── .venv/                         
├── app/                           
│   ├── __init__.py                
│   ├── transcriber.py             
│   ├── translator.py              
│   ├── tts_generator.py           
│   └── main.py                    
│
├── data/                          
│   ├── input/                     
│   ├── transcriptions/            
│   ├── translations/              
│   └── output_audio/              
│
├── scrum_process_tracking/        
│   ├── product_backlog.md         
│   ├── README.md                  
│   └── sprint_01/                 
│       ├── sprint_planning.md     
│       ├── daily_notes.md         
│       ├── sprint_review.md       
│       └── retrospective.md       
│
├── requirements.txt               
├── README.md                      
└── .gitignore                     

---

