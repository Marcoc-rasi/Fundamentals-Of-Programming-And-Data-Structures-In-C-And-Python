# Fundamentals-Of-Programming-And-Data-Structures-In-C

Este repositorio contiene muchos ejercicios que te ayudarán a entender la complejidad de programar con C.
Mis proyectos más completos y que recomiendo revisar son "Banco con tarjetas de depósito y más" y "Aerolínea" estos dos corresponden a mis proyectos finales, el primero solo sobre fundamentos de C y el segundo sobre estructura de datos, donde utilicé punteros triples.
También tengo varios proyectos desarrollados con Python en Jupyter Notebook donde realizo estructuras de datos y gráficas.

| Nombre del proyecto | Descripción de la función |
|---|---|
| Aerolínea | El objetivo del proyecto es simular el funcionamiento de una aerolínea que ofrece vuelos entre diferentes ciudades, utilizando triple pointers para almacenar y manipular la información de pasajeros, vuelos y reservas. |
| Área triángulo, círculo, rectángulo | En este enlace está la carpeta Área triángulo, círculo, rectángulo, que contiene programas para calcular el área de estas figuras geométricas. Los programas piden al usuario que introduzca los datos necesarios para aplicar las fórmulas del área de cada figura, como la base y la altura del triángulo, el radio del círculo o los lados del rectángulo. Luego, los programas muestran el resultado del cálculo en la pantalla. Estos programas son útiles para practicar conceptos básicos de programación y geometría. |
| Banco con tarjetas de depósito y más | Uno de los proyectos más completos y recomendados es Banco con tarjetas de depósito y más, que corresponde a su proyecto final sobre los fundamentos de C. En este proyecto se implementa un sistema bancario que permite crear cuentas, tarjetas, depósitos, retiros, transferencias y consultas, utilizando estructuras de datos y funciones. El código está bien documentado y explicado con comentarios sobre cada parte importante. Este proyecto es un buen ejemplo de cómo aplicar conceptos básicos de programación en C a un problema realista y práctico. |
| Codificador de mensajes | - Estos archivos son programas que implementan el sistema de cifrado conocido como cuadrado de Polibio, que fue inventado por el historiador griego Polibio en el siglo II a.C. . - El cuadrado de Polibio es un método de sustitución monoalfabético que consiste en sustituir cada letra del alfabeto por las coordenadas de su posición en un cuadrado de 5x5. . - Por ejemplo, si el cuadrado es el siguiente: ![alt text](https://miro.medium.com/max/518/1*PyDyJFBNXOeSvfpUbs7GUA.png) - Entonces la palabra HOLA estaría codificada como 23 34 31 11 , ya que H está en la fila 2 y la columna 3, O está en la fila 3 y la columna 4, y así sucesivamente.|
| Estructuras de datos básicas | La carpeta "Estructuras de datos básicas" contiene los siguientes archivos: - cola: programa que implementa una cola usando punteros y estructuras en C. El programa permite encolar, desencolar y mostrar los elementos de la cola, así como verificar si está vacío o lleno. - lista: Programa que implementa una lista enlazada simple usando punteros y estructuras en C. El programa permite insertar, borrar y mostrar los elementos de la lista, así como ordenar la lista en orden ascendente o descendente. - stack: Programa que implementa una pila usando punteros y estructuras en C. El programa permite apilar, desapilar y mostrar los elementos de la pila, así como verificar si está vacía o llena. Estos programas son ejemplos de cómo usar estructuras de datos básicas de C para almacenar y manipular información de manera eficiente. |
| Gráfico lineal y gráfico cuadrático | Contiene programas de Python que le permiten graficar funciones lineales y cuadráticas respectivamente. Una función lineal es una función de la forma f(x) = mx + b, donde m es la pendiente y b es la intersección con el eje y. Una función cuadrática es una función de la forma f(x) = ax^2 + bx + c, donde a, b y c son constantes. La gráfica de una función lineal es una línea recta, mientras que la gráfica de una función cuadrática es una parábola. El programa C utiliza la biblioteca graphics.h para crear una ventana gráfica y dibujar los ejes de coordenadas y los puntos de la función. El programa le pide al usuario que ingrese los valores de m, b, a, b y c manualmente antes de compilar las funciones lineales y cuadráticas, y luego calcula los valores de y para cada valor de x en un intervalo dado. El programa Python utiliza la biblioteca matplotlib.pyplot para crear una figura gráfica y dibujar los ejes de coordenadas y las curvas de las funciones. El programa usa el método plot para trazar las curvas con diferentes colores y el método show para mostrar la figura. |
| Caja y candidatos | Palco: En un palco de lujo en un estadio hay cuatro filas con cuatro asientos por fila. se ofrecerá un asiento para cada asistente, los que están disponibles se indican con D, los que están ocupados con x mayúscula. Si la persona elige un lugar disponible, se le asigna y se cambia a ocupado; si está ocupado, les ofrecemos otro. repita el procedimiento hasta llenar la caja. Candidatos: En un municipio del Estado de México se quiere elegir un nuevo representante vecinal. Son cuatro los contendientes, que registrarán sus votos obtenidos en cuatro colegios principales, se elaboró un programa que indique el nombre del candidato ganador y el total de votos |
| Top Down y fuerza bruta | La programación dinámica es una técnica que consiste en dividir un problema complejo en subproblemas más simples y almacenar las soluciones de estos subproblemas para evitar cálculos repetidos innecesarios. . El enfoque Top Down parte de la solución general y la descompone en subproblemas más pequeños, utilizando la recursividad para resolverlos. El enfoque de fuerza bruta, por el contrario, prueba todas las posibles combinaciones de soluciones hasta encontrar la óptima, lo que puede ser muy lento e ineficiente. Un ejemplo clásico de problema que se puede resolver con programación dinámica es el problema de la mochila, que consiste en elegir los objetos más valiosos que se pueden poner en una mochila con capacidad limitada. Los programas en la carpeta "Top Down and Brute Force" implementan algoritmos para resolver un problema similar utilizando los dos enfoques mencionados. Estos programas pueden servir como ejemplos prácticos para aprender los conceptos básicos de la programación dinámica y comparar las ventajas y desventajas de cada método. |
| cajero automatico muy sencillo | Sin(x): escriba un programa que calcule y muestre los valores obtenidos al realizar sin(x) en un intervalo de valores para x. El usuario debe ingresar seleccionar el valor inicial, el valor final, así como el incremento de la x. log(x): escriba un programa que calcule y muestre los valores obtenidos al realizar log(x) en un rango de valores para x. El usuario debe ingresar seleccionar el valor inicial, el valor final, así como el incremento de la x. banco: construya un programa que simule un cajero automático muy simple. Este programa debería permitir realizar múltiples operaciones mientras se ejecuta, todas en la misma cuenta corriente. Las operaciones pueden ser depósitos, consultas de saldo, retiros (siempre que haya suficiente dinero en la cuenta) y salida. No se permite el sobregiro. Para determinar el saldo inicial de la cuenta corriente, el programa, al inicio, debe permitir por una sola vez definir el saldo. Fiesta: es la entrada a una fiesta en el hotel Zen City, el código después de un par de preguntas te dice el porcentaje de mujeres y hombres así como los que tienen menos de 25 años |
| funciones factoriales exponenciales | El código define cuatro funciones: exponencial, factorial, probabilidad y principal. La función exponencial toma dos parámetros: num y exp. La función calcula el valor de num elevado a la potencia de exp y lo almacena en la variable num. La función factorial recibe un parámetro: num. La función calcula el valor del factorial de num y lo almacena en la variable fac. La función de probabilidad recibe dos parámetros: n y p. La función calcula el valor de la combinación de n elementos tomados de p en p y lo almacena en la variable v. La función principal es la función principal del programa. La función muestra un menú con tres opciones: a) exponencial, b) factorial yc) probabilidad. La función lee la opción elegida por el usuario y llama a la función correspondiente con los valores introducidos por el usuario. |
| supermercado con realloc | “supermarket with realloc” contiene un programa en C que utiliza la función realloc para asignar memoria dinámica a una matriz de estructuras que representan productos en un supermercado. El programa permite agregar, eliminar y modificar productos, así como mostrar inventario y ventas totales |
| tiempo | Este programa imprime "hola" 100 veces y mide el tiempo que tarda en hacerlo |