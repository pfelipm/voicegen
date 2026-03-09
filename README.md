# VoiceGen Pro - Centralita multilingüe 🎙️✨

**VoiceGen Pro** es un generador de locuciones profesionales multilingües diseñado para crear mensajes de audio con acentos nativos de forma rápida y sencilla. 

Originalmente creado para automatizar los mensajes del contestador de un centro educativo durante periodos de vacaciones, su versatilidad lo hace ideal para centralitas, vídeos corporativos, material educativo y cualquier proyecto que requiera una voz profesional en múltiples idiomas.

![VoiceGen Pro Screenshot](https://raw.githubusercontent.com/pfelipm/voicegen/main/assets/captura-iu-voicegenpro.png)

## 🚀 Características principales

- **Multilingüe y Acentuado:** Traduce y locuta simultáneamente a múltiples idiomas (Español de España, México, Argentina; Inglés de Reino Unido, EE. UU., Australia; Francés, Alemán e Italiano).
- **Control de Voz:** Selección de sexo del hablante (Femenino/Masculino) y tono (Profesional, Cálido, Neutro, Serio).
- **Procesamiento de Audio:** Genera un único archivo `.wav` combinando todas las locuciones con pausas personalizables entre idiomas.
- **Historial Local:** Almacena los últimos 3 audios generados para su rápida reproducción o descarga.
- **Modo Claro/Oscuro:** Sincronización automática con el sistema operativo y cambio manual.
- **Resiliencia:** Diseñado con la estrategia "Trae tu propia clave de API" para ser totalmente funcional en hospedajes estáticos como GitHub Pages o Google Sites.

## 🛠️ Requisitos técnicos

Para utilizar VoiceGen Pro necesitas:
1. Una **clave de API de Google Gemini**.
2. Un proyecto en **Google Cloud** asociado (puedes gestionarlo fácilmente desde [Google AI Studio](https://ai.dev)).

> **Importante:** Ten en cuenta que el nivel gratuito de la API de Google Gemini tiene límites de uso diarios para el servicio de texto a voz (TTS).

## 🌍 Estrategia "Trae tu propia clave de API"

Este proyecto demuestra cómo crear herramientas funcionales que requieren servicios de IA en entornos sin backend (como GitHub Pages). Al no disponer de persistencia real en estos hospedajes, la app utiliza el almacenamiento local del navegador (`localStorage`) para recordar tus ajustes de forma segura durante la sesión.

## 🤝 Créditos y autoría

Este proyecto ha sido creado y es mantenido por **Pablo Felip** ([LinkedIn](https://www.linkedin.com/in/pfelipm/) | [GitHub](https://github.com/pfelipm)).

## 📄 Licencia

Este proyecto se distribuye bajo **licencia libre**.
