# using-llama2-locally
usando llama2 localmente y la nueva tecnologia langchain y Ollama

Utilizo la informacion de la LEY 2354 DE 2024 COLOMBIA TABACO. Se instalan estan dependencias: pip install unstructured[docx] langchain langchainhub langchain_community langchain-chroma
- se carga el documento .docx
- Creación de cadenas Langchain para el sistema de recuperación de preguntas y respuestas
Para construir un sistema adecuado de recuperación de preguntas y respuestas, utilizaremos cadenas Langchain y comenzaremos a agregar los módulos.

En nuestra cadena de preguntas y respuestas, vamos a:

Utilice vector store como recuperador y formatee los resultados.
Después de eso, le proporcionaremos el mensaje RAG. Puede obtenerlo fácilmente desde Langchain Hub.
Luego, proporcionaremos la función de inferencia de Ollama Llama 2.
Al final, analizaremos los resultados solo para mostrar la respuesta
- question = "que es la ley 2354?"
qa_chain.invoke(question)
