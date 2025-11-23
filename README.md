# mi-primera-pagina
un lenguaje de programacion es un lenguaje formal o artificial especificas que le ayudan al programador a dar instrucciones en forma de algoritmos a una maquina.
hay lenguaje interpretado las iunstrucciones son traducidas por un lenguaje interprete( python,perl,bash)
lenguaje compilados las instrucciones son traducidas en un grupo por una aplicacion compilador (FORTRAM, C/C++)
lenguaje intermedio por parte compilados y  parte interpretados (java,scala)
los entornos de desarrollo integrado (IDE) permiten a los programadores puedan escribir el codigo les ayuda a escribirlo,corregirlo y  probarlo  la IA a ayudado bastante en la actualidad en la escritura de codigo.( Google Colaboratory),esta herramienta se integra con drive su nube de almacenamiento.
los algoritmos cuenta con entradas, procesos y salidas, Por ejemplo: puede considerarse como algoritmo una serie de instrucciones para obtener el resultado de la suma de dos números
un programa es un conjunto de instrucciones que recvibe una maquina para realizar diversas tareas, busquedas, operaciones.
las variables son espacios en la memoria donde se guarda informacion tales como numeros,textos,resultados.
ejemplo nombre="ana" edad "20" se usa la palabra porque nombre y edad son variables luego se usa print para mostrar un mensaje 
tipos de datos Los datos son uno de los insumos más relevantes en la existencia del algoritmo, pues gracias a ellos es posible ejecutar las acciones en el procesamiento del mismo,numerico entero, numerico decimal,cadena de texto,booleano,fecha,binario.
tipo de datos en pytohm numeros complejos,tupla,lista,diccionario,Los tipos de datos varían levemente de un lenguaje de programación a otro. En algunos lenguajes, por ejemplo, los datos numéricos pueden ser enteros, decimales y decimales de coma flotante. Python tiene solo el tipo numérico, aunque se puede adaptar a alguno de los anteriores, dependiendo del contenido del dato que se le asigna. 
Instrucciones lógicas: Se utilizan únicamente para operar datos de tipo lógico o booleano (verdadero o falso). Las expresiones lógicas dan como resultado otro dato de tipo lógico.
Instrucciones matemáticas: Se aplican sobre datos de tipo numérico y permiten realizar las operaciones aritméticas o matemáticas.
operadores aritmeticos Son utilizados para realizar las operaciones matemáticas básicas sumar,restar, multiplicar y dividir.
operadores relacionales Usados para evaluar expresiones condicionales a partir de la comparación de dos variables y/o valores. Al ser condicionales, el resultado de un operador relacional será verdadero o falso. igual,diferente,mayor que,mayor igual ,menor que,menor igual.
operadores logicos Al igual que los relacionales, los operadores lógicos se usan para evaluar expresiones condicionales a partir de la unión de varios valores y/o variables. Los operadores lógicos devuelven un resultado que puede ser verdadero o falso. Y conjuncion,O disyuncion,NO negacion.
ejemplo de python # Listas
frutas = ["manzana", "plátano", "naranja"]
print(frutas)

# Acceder a un elemento de la lista
print(frutas[0])

# Agregar un elemento a la lista
frutas.append("pera")
print(frutas)

# Longitud de la lista
print(len(frutas))
referencias
https://codigital.ec/introduccion-a-python-10-ejemplos-de-codigo-para-principiantes/
https://iudigital.instructure.com/courses/23661/pages/formas-de-representacion?module_item_id=1594910

# Reto 1: Simula el comportamiento de la tortuga con print() y input()  
# Simulación de avance con print e input
pasos = int(input("¿Cuántos pasos deseas que avance la tortuga? "))
for i in range(pasos):
    print("→", end="")
print()  # Salto de línea al final
