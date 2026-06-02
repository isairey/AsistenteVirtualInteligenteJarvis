<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/4712/4712109.png" />

# 🤖 JARVIS on Messenger

### Asistente virtual inteligente para Facebook Messenger 🚀

<p align="center">
  <b>JARVIS on Messenger</b> es un chatbot modular desarrollado en Python que integra procesamiento de lenguaje natural, múltiples APIs y servicios externos para ofrecer respuestas inteligentes directamente desde Facebook Messenger.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JARVIS-MessengerBot-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-2.7-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/NLP-Chatbot-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Facebook-Messenger-1877F2?style=for-the-badge&logo=facebook&logoColor=white">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-funcionalidades">Funciones</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-estructura-del-proyecto">Estructura</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**JARVIS on Messenger** es un asistente virtual diseñado para ejecutarse dentro de Facebook Messenger, permitiendo a los usuarios acceder a información, entretenimiento y herramientas útiles mediante lenguaje natural.

El proyecto fue creado con dos objetivos principales:

- 🤖 Construir un chatbot con múltiples funcionalidades.
- 🌍 Facilitar la participación de nuevos desarrolladores en proyectos open source.

Gracias a su arquitectura modular, cualquier desarrollador puede crear nuevas capacidades para el bot de manera sencilla.

---

# ✨ Funcionalidades

## 📚 Información y conocimiento

- 📖 Definiciones de diccionario
- 🌐 Consultas Wikipedia
- 📰 Noticias recientes
- 📚 Información de libros
- 🎬 Información de películas
- 🎵 Búsqueda musical

---

## 🌦️ Utilidades

- 🌤️ Pronóstico del clima
- 💱 Conversión de monedas
- 🕒 Consulta de horarios mundiales
- 🔗 Acortamiento de URLs
- 📡 Comprobación de servicios online

---

## 🎲 Entretenimiento

- 😂 Chistes aleatorios
- 📜 Frases célebres
- 🎲 Lanzamiento de dados
- 🪙 Lanzamiento de monedas
- 🎭 Datos curiosos

---

## 🎥 Multimedia

- 🎬 Videos de YouTube
- 🎵 Letras de canciones
- 🎶 Información musical
- 📺 Recomendaciones multimedia

---

## 🧠 Inteligencia Conversacional

- Procesamiento de lenguaje natural
- Clasificación automática de consultas
- Sistema modular extensible
- Integración con APIs externas

---

# 🤖 Módulos disponibles

## 📚 Conocimiento

- Wikipedia
- Diccionario
- Libros
- Noticias

---

## 🎵 Multimedia

- Música
- Letras
- Videos
- Películas

---

## 🌍 Utilidades

- Conversión de moneda
- Clima
- Horarios
- URLs

---

## 🎲 Diversión

- Chistes
- Frases
- Datos curiosos
- Juegos rápidos

---

# 🛠️ Tecnologías utilizadas

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=python" />
</p>

- Python 2.7
- NLP Processing
- REST APIs
- Messenger Bot Framework

---

## 🤖 Inteligencia y NLP

<p>
  <img src="https://skillicons.dev/icons?i=python" />
</p>

- Natural Language Processing
- Intent Recognition
- Query Classification
- Modular Commands

---

## 🌐 APIs Externas

- Goodreads API
- Spotify API
- YouTube API
- OpenWeatherMap API
- NewsAPI
- MediaWiki API
- TimeZoneDB
- MusixMatch

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- VS Code
- Travis CI

---

# 📂 Estructura del proyecto

```bash
JARVIS-on-Messenger/
│
├── modules/               # Funcionalidades del bot
├── modules/src/           # Código principal
├── modules/tests/         # Pruebas unitarias
├── data/                  # Datos compartidos
├── templates/             # Mensajes estructurados
├── images/                # Recursos visuales
├── config.py              # Configuración general
├── jarvis.py              # Bot principal
├── requirements.txt
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- Python 2.7
- Pip
- Git
- Facebook Messenger API

---

# 🚀 Configuración

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/swapagarwal/JARVIS-on-Messenger.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd JARVIS-on-Messenger
```

---

## 3️⃣ Instalar dependencias

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Configurar APIs

Editar:

```bash
config.py
```

Agregar las claves correspondientes para los módulos que se deseen utilizar.

Ejemplo:

```python
OPENWEATHER_API_KEY="your_key"
SPOTIFY_API_KEY="your_key"
NEWS_API_KEY="your_key"
```

---

## 5️⃣ Ejecutar aplicación

```bash
python jarvis.py
```

---

# 🌐 Endpoints locales

## Procesamiento de intención

```bash
http://localhost:5000/process/?q=hello
```

Permite determinar qué módulo responderá la consulta.

---

## Consulta completa

```bash
http://localhost:5000/search/?q=weather in london
```

Devuelve la respuesta final generada por el sistema.

---

# 📊 Capacidades principales

## 🧠 Procesamiento de lenguaje

- Clasificación de intenciones
- Interpretación de consultas
- NLP modular

---

## 🔌 Integraciones

- Facebook Messenger
- Servicios REST
- APIs públicas
- Plataformas multimedia

---

## ⚡ Arquitectura modular

Cada funcionalidad está implementada como módulo independiente.

Ejemplos:

- weather.py
- joke.py
- dictionary.py
- music.py
- news.py
- wiki.py

---

# 🚧 Roadmap

## 🔮 Futuras mejoras

- 🤖 IA conversacional avanzada
- 🧠 Modelos LLM
- 🎙️ Reconocimiento de voz
- 🌍 Soporte multilenguaje
- 📱 Aplicación móvil
- ☁️ Despliegue cloud automático
- 🔔 Notificaciones inteligentes

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/new-module
```

2. Commit

```bash
git commit -m "✨ Nuevo módulo"
```

3. Push

```bash
git push origin feature/new-module
```

4. Crear Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Swap Agarwal

Creador de JARVIS on Messenger y promotor del aprendizaje open source mediante proyectos colaborativos de inteligencia conversacional.

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella

🍴 Haz fork

📢 Comparte el proyecto

🤝 Contribuye con nuevos módulos

---

# 📜 Licencia

Proyecto distribuido bajo licencia MIT para fines educativos, investigación y desarrollo de asistentes virtuales.

---

<div align="center">

### 🤖 JARVIS on Messenger — Inteligencia conversacional modular para Facebook Messenger 🚀

</div>
