# Voice-to-text con Whisper

Script sencillo para transcribir un archivo de audio a texto con el modelo Whisper de OpenAI (en local). 

## Requisitos
 - Python 3.7+
 - Whisper (instalable via pip):
   
   ```
   pip install openai-whisper
   ```

 - ffmpeg (https://ffmpeg.org/download.html):

   (Windows)
   ```
   winget install ffmpeg
   ```

   (MacOS)
   ```
   brew install ffmpeg
   ```

   (Linux)
   ```
   sudo apt install ffmpeg
   ```

## Uso

```
python voice-to-text.py <ruta_archivo_audio> [tamaño_modelo]
```

El segundo parámetro es opcional. Por defecto, será `small`. Se pueden obtener mejores resultados con los modelos `large`, `medium` y `turbo`.
