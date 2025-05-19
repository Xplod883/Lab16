# Lab16

Carlos Eduardo García Cortez
5090-24-14824
19/05/2025

INFORME DE FUNCIONAMIENTO DEL CHATBOT CON BASE DE CONOCIMIENTO DINÁMICO

Este proyecto consiste en un programa tipo chatbot desarrollado en C++, cuyo objetivo es responder preguntas del usuario en base a una base de conocimiento cargada desde un archivo de texto llamado 'conocimiento.txt'.

- El chatbot lee el archivo 'conocimiento.txt', el cual debe contener pares de pregunta y respuesta en el formato:
  ¿Pregunta?|Respuesta

- Cada línea representa un conocimiento del bot. Por ejemplo:
  ¿Qué es C++?|Un lenguaje de programación.

- Las preguntas y respuestas se almacenan dinámicamente en una lista enlazada.

- Cuando el usuario escribe una pregunta, el chatbot busca una coincidencia exacta en la base cargada y devuelve la respuesta correspondiente.

- Si no encuentra coincidencias, responde con un mensaje genérico: "No tengo una respuesta para eso."

Se utilizaron las siguientes librerías para este laboratorio:
- <iostream> y <fstream> para el manejo de entrada/salida estándar y archivos.
- <string> para la manipulación de texto.
- <limits> permite consultar los límites de variables numéricas.

- El usuario puede escribir preguntas directamente en la consola.
- Para salir del chatbot, se debe escribir el comando: salir

- conocimiento.txt: Base de conocimiento con preguntas y respuestas.
- main.cpp: Código fuente principal del chatbot.
- Lab16.exe: Ejecutable final generado.

Este chatbot está diseñado para pruebas locales, es liviano y puede compilarse fácilmente con cualquier compilador de C++ moderno.
