Este repositorio contiene tres proyectos que implementan sistemas RAG (Retrieve and Generate) utilizando modelos de lenguaje y almacenamiento de vectores en diferentes formatos.

## 1. RAG en inglés que crea un Vector Store a partir de los datos de una página web

### Descripción

Este proyecto muestra cómo crear un sistema RAG en Python que extrae texto de una página web y lo convierte en un vector store utilizando un modelo de embeddings. El sistema permite realizar consultas sobre el contenido de la página web.

### Requisitos

- Python 3.7 o superior
- Bibliotecas necesarias:
  - `requests`
  - `beautifulsoup4`
  - `langchain`
  - `langchain_ollama`
  - `langchain_core`

### Instalación
Puedes instalar estas dependencias utilizando `pip`:
```bash
pip install requests beautifulsoup4 langchain langchain-ollama langchain-core`
```
# 2.RAG en castelán que crea vector store a partir de un ou varios ficheiros pdf

Este proyecto utiliza el enfoque de **RAG** (Retrieval-Augmented Generation) para crear un **Vector Store** a partir de uno o varios archivos PDF. Utilizando diversas bibliotecas de `langchain`, este sistema es capaz de procesar y almacenar los contenidos de los archivos PDF en un formato de vectores, que luego se pueden utilizar para realizar consultas inteligentes y generar respuestas contextuales.

## Requisitos

-   Python 3.7+
-   Librerías de Python:
    -   `langchain_huggingface`
    -   `langchain_chroma`
    -   `langchain_core`
    -   `langchain_ollama`
    
### Instalación
Puedes instalar estas dependencias utilizando `pip`:

 ```bash
pip install langchain_huggingface langchain_chroma langchain_core langchain_ollama`
```