# PIIA_AgenteConversacional
El repositorio contiene los archivos necesarios para ejecutar un agente conversacional basado en un pipeline funcional VAD -> ASR -> LLM -> TTS con gestión de los turnos e interrupciones.

Para ejecutar el proyecto basta con hacer un docker compose up desde la carpeta _TresPi_ y despues entrar al localhost:8770 para acceder a la interfaz gráfica 

Es recomendable disponer de una gráfica Nvidia compatible con la versión de CUDA 12.1 para tener un mínimo de fluidez en la conversación, de otra forma la velocidad de procesamiento será muy lenta.
