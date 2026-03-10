# VoiceGen Pro - Centralita multilingüe 🎙️✨

**VoiceGen Pro** es un generador de locuciones profesionales multilingües diseñado para crear mensajes de audio con acentos nativos de forma rápida y sencilla. 

Accede a la aplicación en: 👉 [**voicegen.pablofelip.online**](https://voicegen.pablofelip.online)

Originalmente creado para automatizar los mensajes del contestador de un centro educativo durante periodos de vacaciones, su versatilidad lo hace ideal para centralitas, vídeos corporativos, material educativo y cualquier proyecto que requiera una voz profesional en múltiples idiomas.

![VoiceGen Pro Screenshot](https://raw.githubusercontent.com/pfelipm/voicegen/main/assets/captura-iu.png)

## 🚀 Características principales

- **Multilingüe y acentuado:** Traduce y locuta simultáneamente a múltiples idiomas (español de España, México, Argentina; inglés de Reino Unido, EE. UU., Australia; francés, alemán e italiano).
- **Control de voz:** Selección de sexo del hablante (femenino/masculino) y tono (profesional, cálido, neutro, serio).
- **Procesamiento de audio:** Genera un único archivo `.wav` combinando todas las locuciones con pausas personalizables entre idiomas.
- **Historial local:** Almacena los últimos 3 audios generados para su rápida reproducción o descarga.
- **Modo claro/oscuro:** Sincronización automática con el sistema operativo y cambio manual.
- **Gestión inteligente de configuración:** Sistema de verificación persistente que detecta automáticamente si la clave de API y los modelos son operativos tras cada uso, diferenciando entre errores de configuración y fallos temporales del servicio.
- **Resiliencia:** Diseñado con la estrategia "Trae tu propia clave de API" para ser totalmente funcional en hospedajes estáticos como GitHub Pages o Google Sites.

## 🛠️ Requisitos técnicos

Para utilizar VoiceGen Pro necesitas:
1. Una **clave de API de Google Gemini**.
2. Un proyecto en **Google Cloud** asociado (puedes gestionarlo fácilmente desde [Google AI Studio](https://ai.dev)).

> **Importante:** Ten en cuenta que el nivel gratuito de la API de Google Gemini tiene límites de uso diarios para el servicio de texto a voz (TTS).

## 🌍 Estrategia "Trae tu propia clave de API"

Este proyecto demuestra cómo crear herramientas funcionales que requieren servicios de IA en entornos sin backend. 

A diferencia de otros despliegues similares que suelo realizar en Google Sites, **VoiceGen Pro** se hospeda en **GitHub Pages** para garantizar la persistencia real de los ajustes (clave de API, selección de modelos, etc.) y del historial de audios generados a través de `localStorage`, evitando las restricciones de aislamiento de almacenamiento que imponen los iFrames en Google Sites.

![VoiceGen Pro Settings](https://raw.githubusercontent.com/pfelipm/voicegen/main/assets/captura-ajustes.png)

## 🔒 Privacidad y seguridad

VoiceGen Pro es una aplicación cliente puro (frontend-only). Esto significa que:
- Tu clave de API se almacena únicamente en el navegador de tu dispositivo (`localStorage`).
- Las peticiones para traducir y generar audio se realizan directamente desde tu navegador a los servidores de Google Gemini.
- **Ningún dato, texto o clave es interceptado ni almacenado por servidores de terceros.**

## 🤝 Créditos y autoría

Este proyecto ha sido creado y es mantenido por **Pablo Felip** ([LinkedIn](https://www.linkedin.com/in/pfelipm/) | [GitHub](https://github.com/pfelipm)).

## 📄 Licencia

Este proyecto se distribuye bajo los términos del archivo [LICENSE](LICENSE).
