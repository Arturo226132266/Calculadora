Para usar esta calculadora es necesario seguir estos pasos.
1. Entrada de datos (Pedir los números)
"Primero, el programa le pide al usuario que ingrese dos números por teclado usando la instrucción input(). Como Python recibe todo como texto, usamos float() para convertir ese texto en números con decimales, lo que permite sumar tanto enteros como decimales."

2. Menú de opciones
"Después, el programa despliega un menú visual en la consola con print(), mostrando las cuatro operaciones disponibles (Suma, Resta, Multiplicación y División). El usuario elige una opción escribiendo el número correspondiente (1, 2, 3 o 4)."

3. Toma de decisiones (Estructura if-elif-else)
"Finalmente, usamos condiciones para saber qué operación ejecutar:

Si elige 1, se suman los números.

Si elige 2, se restan.

Si elige 3, se multiplican.

Si elige 4, se dividen; pero aquí agregamos una validación importante: un if que revisa que el segundo número no sea cero, evitando así que el programa truene por un error matemático.

Si escribe cualquier otra cosa, el else final avisa que la opción no es válida."
