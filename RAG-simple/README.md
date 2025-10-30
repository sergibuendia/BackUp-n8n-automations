# Agente conectado a una base de datos vectorial (RAG)

Este workflow implementa un sistema RAG (Retrieval-Augmented Generation) conectado a un Agente de IA que responde preguntas a partir de los documentos que tu le subas:

- Busca y descarga automáticamente un documento desde una carpeta de Google Drive.
- Divide el contenido en fragmentos y genera embeddings con OpenAI, que se almacenan en una base de datos vectorial.
- Cuando el usuario envía una pregunta por chat, el sistema consulta primero esa base vectorial para encontrar los fragmentos más relevantes.
- El agente de IA (OpenAI Chat Model) utiliza esos fragmentos para generar una respuesta precisa y contextual.
- Gracias a la memoria integrada, puede mantener el contexto de la conversación y responder consultas complejas sobre los documentos cargados.
