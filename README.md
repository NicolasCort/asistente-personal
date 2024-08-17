# Asistente Personal de IA Rápido

> Crea tu asistente personal de IA usando OpenAI, Groq e ElevenLabs.

![tu-ia](./img/thumbnail.png)

## Configuración

- Clona el repositorio:
  ```bash
  git clone https://github.com/NicolasCort/asistente-personal.git  # Necesitas tener instalado Git`
  ```

- Crea y activa un entorno virtual:
  ```bash
  python -m venv venv
  venv\Scripts\activate  # En Mac, usa `source venv/bin/activate`
  ```

- Instala las dependencias:
  ```bash
  pip install -r requirements.txt
  ```

- Configura las variables de entorno:
  ```bash
  # Edita el archivo .env y añade tus claves API
  ```
  `Recomiendo comenzar con el asistente de OpenAI ya que solo necesitas configurar la clave API de OpenAI.`

- Ejecuta el script principal:
  ```bash
  python main.py
  ```

- Presiona `Enter` para comenzar a grabar y `Enter` nuevamente para detener la grabación.

- Ajusta la duración máxima de la grabación en `constants.py: DURATION`

- Actualiza las variables de configuración en `constants.py`
  - Modifica los nombres.
  - Actualiza el prompt según tus preferencias.
  - Cambia el tipo de asistente al que prefieras usar.

## Mira el video de demostración
[Crea Tu Propio Asistente Personal con IA  [GPt-4o-mini + ElevenLabs]](https://youtu.be/14g67rKExEo)

## Recursos
 
- https://console.groq.com/docs/speech-text
- https://console.groq.com/docs/libraries
- https://platform.openai.com/docs/guides/speech-to-text
- https://platform.openai.com/docs/guides/text-to-speech
- https://platform.openai.com/docs/api-reference/audio#audio/createTranscription-prompt
- https://openai.com/api/pricing/
- https://elevenlabs.io/app
