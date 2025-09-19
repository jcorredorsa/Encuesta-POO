# Encuesta de Ideas de Proyecto en Python
Este programa recopila información básica de estudiantes interesados en desarrollar proyectos con Python. A través de una encuesta interactiva en consola, se registran sus datos personales, nivel de experiencia y propuesta de proyecto. Al finalizar, se muestra una lista de todos los participantes.
# Estructura del proyecto
El código se organiza en cuatro componentes principales:
1. Estudiante
Clase que representa a cada participante.
- Atributos: nombre, edad, respuesta_proyecto
- Método estático: crear_estudiante_input()
Solicita nombre y edad por consola, validando los datos. Agrega el nombre a lista_estudiantes.
<img width="663" height="456" alt="image" src="https://github.com/user-attachments/assets/872c24af-0948-43cf-9133-c2f9ea693d96" />

2. Encuesta
Clase que gestiona las preguntas y respuestas del formulario.
<img width="822" height="489" alt="image" src="https://github.com/user-attachments/assets/37a87c41-00fe-4a90-a807-e5bce5a69d13" />
<img width="738" height="478" alt="image" src="https://github.com/user-attachments/assets/240d61b1-69e3-44f4-92b5-665ea5647af9" />
<img width="807" height="449" alt="image" src="https://github.com/user-attachments/assets/90c8c60e-e177-488e-aa1b-064c62b7c33f" />

3. mostrar_todos_los_resultados(lista1, lista2)
Función que imprime todos los nombres y sus respuestas organizadas.
<img width="515" height="108" alt="image" src="https://github.com/user-attachments/assets/f485331b-1095-4c7f-be61-b1bccb66bbb7" />

4. main()
Ejecuta el flujo completo para 10 estudiantes:
- Crea instancias de Estudiante y Encuesta
- Muestra el resumen individual
- Al final, imprime todos los resultado
<img width="584" height="193" alt="image" src="https://github.com/user-attachments/assets/61ecf3b5-0e57-434a-8151-286d6fa18dc0" />









