# PIIA_AgenteConversacional
El repositorio contiene los archivos necesarios para ejecutar un agente conversacional basado en un pipeline funcional **VAD -> ASR -> LLM -> TTS** con gestión de los **turnos** e **interrupciones**.

Para ejecutar el proyecto basta con:
1. Hacer un `docker compose up --build` desde la carpeta _TresPi_
2. Ejecutar en otra terminal el comando `python -m http.server 3000` desde la carpeta _client_
3. Y por último entrar al _localhost:3000/index2.html_ en tu navegador para acceder a la interfaz gráfica.

Es recomendable disponer de una gráfica Nvidia compatible con la versión de CUDA 12.1 para tener un mínimo de fluidez en la conversación, de otra forma la velocidad de procesamiento será muy lenta. Además de una buena conexión WiFi.
