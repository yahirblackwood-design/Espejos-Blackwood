# Espejos-Blackwood
Sistema que integra 5 IAs para responder 1 pregunta desde 5 ángulos. Creado por Yahir Joel Blackwood Adles el 19 oct 2025.
Objetivo*: Permitir que un usuario haga una sola pregunta y reciba 5 respuestas simultáneas generadas por 5 modelos de IA distintos, presentadas en paralelo para comparar estilo, enfoque, profundidad y razonamiento.

*Funcionamiento básico*:
1. *Input único*: El usuario escribe una pregunta/prompt en un solo campo de texto.
2. *Distribución*: El sistema envía ese mismo prompt vía API a 5 modelos de lenguaje distintos. Ej: GPT, Claude, Gemini, Llama, Mistral.
3. *Ejecución paralela*: Las 5 llamadas se hacen al mismo tiempo para reducir latencia total.
4. *Presentación en espejo*: Las 5 respuestas se muestran en pantalla dividida en 5 paneles, cada uno etiquetado con el nombre del modelo/estilo.
5. *Metadatos*: Cada panel muestra tiempo de respuesta, tokens usados y temperatura, para análisis comparativo.
6. *Iteración*: El usuario puede repreguntar, editar el prompt o pedir que solo X modelos respondan.

*Valor diferencial*: No es un simple chatbot. Es una herramienta de análisis comparativo que revela sesgos, fortalezas y diferencias de razonamiento entre modelos usando la misma entrada. Útil para investigación, redacción, debate y testing de IAs.

*Estado al 19 oct 2025*: Concepto, nombre “Espejo Blackwood”, flujo de usuario y arquitectura base definidos.
