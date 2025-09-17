# Práctica de RAG (Retrieval-Augmented Generation)

## Información del Proyecto
- **Estudiante**: Juan Felipe Jojoa Crespo  
- **Código**: A00382042  
- **Materia**: Inteligencia Artificial II 
- **Tema**: RAG (Generación aumentada con recuperación)  

---

## Descripción
Este repositorio contiene la práctica realizada sobre **Retrieval-Augmented Generation (RAG)**.  
El objetivo principal fue experimentar con un enfoque que combina **modelos de lenguaje** con **motores de búsqueda/recuperación de información**, de modo que el modelo pueda dar respuestas más precisas y fundamentadas en documentos externos.  

---

## Pasos Realizados

1. **Preparación de los Documentos**  
   - Se recopilaron y organizaron fuentes de información relevantes.  
   - Los documentos fueron procesados para facilitar su indexación (ej. en embeddings o base vectorial).  

2. **Construcción del Pipeline RAG**  
   - Se configuró un sistema de recuperación de información (retriever).  
   - El retriever se conectó al modelo de lenguaje para complementar sus respuestas con contexto adicional.  

3. **Ejecución de Consultas**  
   - Se hicieron preguntas al modelo con y sin RAG.  
   - Se compararon las diferencias en calidad y precisión de las respuestas.  

---

## Resultados
- Con RAG, las respuestas fueron más completas y alineadas con los documentos de referencia.  
- Se comprobó que el modelo ya no depende únicamente de su conocimiento previo, sino que puede acceder a información actualizada y específica.  

---

## Conclusiones
- **RAG mejora la precisión** en tareas donde se requiere información confiable.  
- La calidad de la base de conocimiento usada en el retriever es tan importante como el modelo en sí.  
- El ejercicio permitió entender cómo integrar **bases vectoriales** con **modelos de lenguaje** de manera práctica. 

---
