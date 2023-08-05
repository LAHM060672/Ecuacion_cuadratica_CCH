# Ecuación Cuadrática para estudiantes del CCH
Nombre del proyecto: Metodología de solución de problemas e introducción al lenguaje de programación para la solución de ecuaciones cuadráticas.

## Objetivos:

El objetivo de este programa es que los estudiantes de bachillerato aprendan a resolver ecuaciones cuadráticas utilizando la fórmula general y comprendan la importancia de los coeficientes en la solución de estas ecuaciones. 
Al finalizar el programa, los estudiantes serán capaces de: 
- Identificar los coeficientes de una ecuación cuadrática y aplicar la fórmula general para obtener sus soluciones. 
- Distinguir entre los diferentes tipos de soluciones que puede tener una ecuación cuadrática y comprender en qué depende de ello. 
- Interpretar gráficamente las soluciones de una ecuación cuadrática y entender cómo se relacionan con la función cuadrática correspondiente. 
- Reconocer qué sucede si el coeficiente "a" es igual a 0 en una ecuación cuadrática y cómo afecta esto a las soluciones.
## Problema que resuelvo

Dada una ecuación cuadrática ax2 + bx + c = 0, desarrolla lo siguiente:

• Indique como podemos obtener sus soluciones.
• ¿Cuántos tipos de soluciones podemos tener y de que depende?
• ¿Qué representa gráficamente las soluciones de una ecuación cuadrática?
• ¿Qué sucede si el coeficiente "a" es igual a 0 en una ecuación cuadrática?
• ¿Qué información nos brinda la gráfica de una función cuadrática y cómo se relaciona con las soluciones de su ecuación?
Con lo anterior indique las etapas de la metodología de solución de problemas:

• Planteamiento del problema. 
• Análisis del problema. 
• Diseño de la solución del problema: 
- Elaboración de algoritmos. 
- Codificación en Python.
- Prueba de escritorio.
  
## Argumentación sobre el (los) lenguaje(s) utilizado(s) y el porqué de la elección de este lenguaje
El uso del programa Python en el aprendizaje de la solución de ecuaciones cuadráticas puede ser una herramienta muy útil para los estudiantes del Colegio de Ciencias y Humanidades por varias razones.
En primer lugar, el programa Python permite al estudiante visualizar de manera gráfica las soluciones de las ecuaciones cuadráticas, esto significa que los estudiantes pueden ver de manera clara y concreta cómo se relacionan los diferentes valores de la ecuación y cómo se representan en un gráfico, esta visualización puede ayudar a los estudiantes a comprender mejor los conceptos matemáticos y a tener una idea clara de cómo se resuelven las ecuaciones cuadráticas.
Además, el uso de Python también facilita la realización de pruebas de escritorio, la estructura de indentación del lenguaje Python fomenta la legibilidad del código, lo que significa que los estudiantes pueden leer y comprender fácilmente las líneas de código que utilizan para resolver las ecuaciones cuadráticas, esto les permite realizar pruebas de escritorio y verificar paso a paso el proceso de resolución de la ecuación, lo que contribuye a un mejor entendimiento y a la detección de posibles errores.
Otra ventaja del uso de Python es la posibilidad de automatizar la verificación de las soluciones obtenidas, el programa puede realizar cálculos y comparar los resultados obtenidos por el estudiante con los resultados esperados, esto ayuda a los estudiantes a identificar rápidamente si han cometido algún error en sus cálculos y les permite corregirlo de manera inmediata, además, la automatización también ahorra tiempo y esfuerzo al realizar las verificaciones manualmente.
Por lo tanto,  el uso del programa Python como herramienta complementaria en el aprendizaje de la solución de ecuaciones cuadráticas brinda al perfil del egresado una forma visual y práctica de comprender y resolver estas ecuaciones, proporciona una representación gráfica de las soluciones, mejora la legibilidad del código y permite la automatización de la verificación de las soluciones obtenidas, en conjunto, estas ventajas contribuyen a facilitar la comprensión y el aprendizaje de las ecuaciones cuadráticas.

## Descripción de lo que está simulando, analizando o demostrando:
La fórmula general x = (-b ± √(b^2 - 4ac)) / (2a) es utilizada para obtener las soluciones de una ecuación cuadrática ax2 + bx + c = 0, dependiendo del valor del discriminante (b^2 - 4ac), se pueden obtener dos soluciones reales diferentes si es mayor que cero, una solución real doble si es igual a cero o dos soluciones complejas conjugadas si es menor que cero. 
Las soluciones de una ecuación cuadrática representan los puntos donde la función cuadrática intersecta el eje x en su gráfica, si el coeficiente "a" es igual a cero, la ecuación cuadrática se convierte en una ecuación lineal con una única solución. 
La gráfica de una función cuadrática proporciona información sobre su concavidad, vértice, eje de simetría y puntos de intersección con los ejes x e y, el vértice de la parábola corresponde al punto medio entre las dos soluciones, el eje de simetría pasa por el vértice y los puntos de intersección con el eje x son las soluciones de la ecuación. 
Para resolver problemas que involucran ecuaciones cuadráticas, se sigue una metodología de tres etapas: planteamiento del problema, análisis del problema y diseño de la solución, en la tercera etapa, se desarrollan algoritmos utilizando la fórmula general, se codifican en Python y se realizan pruebas de escritorio para verificar su correcto funcionamiento.

## Ejemplo básico de funcionamiento general, instrucciones de ejecución y uso

El primer programa
vamos a calcular la ecuación cuadrática con la fórmula general, sin condicionantes.
En este programa se utiliza el lenguaje de programación Python para resolver un problema matemático, en este caso, la ecuación cuadrática, a
través de funciones de entrada y salida de datos, el programa solicita al usuario los coeficientes a, b y c, y luego realiza los cálculos necesarios para obtener los valores de x1 y x2.
# Solicitar coeficientes al usuario
a = float(input("Ingrese el coeficiente a: "))

b = float(input("Ingrese el coeficiente b: "))

c = float(input("Ingrese el coeficiente c: "))

# se calcula el descriminante
D=pow(b,2)-4*a*c

# se calcula el valor de x1 y el valor de x2
x1=(-b+pow(D,1/2))/(2*a)

x2=(-b-pow(D,1/2))/(2*a)


print("El resultado de x1 es",x1)

print("El resultado de x2 es",x2)

Ahora vamos a calcular la ecuación cuadrática con la fórmula general, con estructuras de control if-elif-else.
Es importante manejar estructuras de control condiciones if-elif-else en este ejercicio porque se debe tener en cuenta que la ecuación cuadrática puede tener diferentes soluciones dependiendo del valor del discriminante D:
*si D es mayor que cero, la ecuación tiene dos soluciones reales diferentes.
*Si D es igual a cero, la ecuación tiene una única solución real.
*Y si D es menor que cero, la ecuación no tiene soluciones reales, sino soluciones complejas.
Por lo tanto, se utiliza la estructura de control if-elif-else para determinar qué solución se debe mostrar al usuario según el valor del discriminante D.¶
Aquí está el código:
# Solicitar coeficientes al usuario
a = float(input("Ingrese el coeficiente a: "))

b = float(input("Ingrese el coeficiente b: "))

c = float(input("Ingrese el coeficiente c: "))


# se calcula el descriminante

D=pow(b,2)-4*a*c

if D<0:

	print("X1 y x2 sus soluciones son complejas")
 
	x1=(-b+pow(D,1/2))/(2*a)
 
	x2=(-b-pow(D,1/2))/(2*a)
 
	print("El resultado de x1 es",x1)
 
	print("El resultado de x2 es",x2)  
 
elif D>0:

	print("X1 y x2 sus soluciones son reales y distintas")
 
	x1=(-b+pow(D,1/2))/(2*a)
 
	x2=(-b-pow(D,1/2))/(2*a)
 
	print("El resultado de x1 es",x1)
 
	print("El resultado de x2 es",x2)
 
else:

		print("X1 y x2 sus soluciones son iguales")
  
		x1=(-b+pow(D,1/2))/(2*a)
  
		x2=(-b-pow(D,1/2))/(2*a)
  
		print("El resultado de x1 es",x1)
  
		print("El resultado de x2 es",x2)  
  

## Tema que ayuda a comprender: Ecuación cuadrática.

## Justificación de cómo ayuda al alumno a comprender el tema

La fórmula general para encontrar las soluciones de una ecuación cuadrática es una herramienta matemática fundamental que ayuda a los estudiantes de bachillerato en el Colegio de Ciencias y Humanidades a comprender y resolver problemas en áreas como la física, la ingeniería, la economía y la informática, al entender cómo funciona esta fórmula y cómo se aplica en diferentes contextos, los estudiantes pueden desarrollar habilidades de resolución de problemas y razonamiento matemático que les serán útiles en su vida académica y profesional, además, la comprensión de la gráfica de una función cuadrática les permite visualizar y analizar patrones y tendencias en datos numéricos, lo que puede ser útil en áreas como la estadística y la investigación científica. 
Por lo tanto, la comprensión de las ecuaciones cuadráticas y su fórmula general es una herramienta valiosa para cualquier estudiante que busque tener éxito en cualquier área del conocimiento que requiera habilidades matemáticas.
