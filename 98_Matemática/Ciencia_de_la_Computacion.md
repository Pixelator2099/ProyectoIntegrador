# Bienvenidos

Estos son los apuntes acerca de ciencias de la computación (computer science). Ciencias de la computación es el estudio de las teorías de la información y de la computación, abarca el estudio de algortimos y su aplicación práctica en aplicaciones o sistemas.

## Autor

Profesional de las ciencias de la computación con 20 años de experiencia en desarrollo de sistemas.

Me pueden escribir en [Observatorio de Cursos](https://www.facebook.com/ObservatorioEducacionVirtual)

## Introducción

Las ciencias de la computación tambien llamada ciencias de la informática tienen una variedad de aplicaciones en diversas ramas, pero se enfrentan a una problemática inherente a la tecnología que es la curva de aprendizaje.

Al respecto de la curva de aprendizaje, las preguntas que complican la decisión del profesional de la computación son ¿Qué lenguaje de programación debo aprender? ¿Cuánto tiempo me tomará? ¿Aprender HTML, programación WINDOWS/LiNUX/ANDROID?.

Por tal motivo, es importante que el profesional desarrolle sus habilidades de análisis independiente a las técnologias por lo que se recomienda aprender por medio de diagramas, flujogramas así como del uso de pseudocódigo el diseño, análisis las formas de optimizar un algoritmo.

## Lenguajes de programación y el pseucódigo

Un algoritmo es un conjunto de pasos para solucionar un problema, realizar un cálculo asi como automatizar actividades. Su objetivo es este punto es aportar al aprendizaje del diseño algoritmos con una estructura simple para entender de forma general los pasos que se van a tomar para lograr una solución óptima.

Por tal motivo, cuando se enseñe y aprenda pseucódigo se debe considerar que la estructura es simple, y que si bien puede tener parecido con algún lenguaje el objetivo es el aprendizaje del diseño de algoritmos en lugar de enseñar un lenguaje en si mismo.

### Sintaxis de programación en pseucódigo

Si bien el pseucódigo no tiene una sintaxis específica, se recomienda establecer ciertas reglas para su desarrollo y aprendiza común con cierto parecido a un lenguaje real.

#### Pseucódigo PSC-1

PSC-1 es una propuesta del diseño de actividades con Pseucódigo que puede ser adaptado a diversos lenguajes. Es un lenguaje no formal para aprender a diseñar estructuras.

El PSC-1 permite aprender a usar variables y comandos genéricos como se describe a continuación.

```
  // Ejemplo 1
  VARIABLE nombre (cadena) // Crea una variable como cadena
  VARIABLE edad (número) // Crea una variable como número
  LEER nombre
  LEER edad
  IMPRIMIR "mi nombre es " + nombre
  IMPRIMIR "mi edad es " + edad
```

El bloque de PSC-1 anterior crea variables y las muestra en pantalla. Tiene un parecido con el lenguaje BASIC.

```
  // Ejemplo 2
  VARIABLE edad (número) // Crea una variable como número
  LEER edad
  
  SI (EDAD >=18) ENTONCES
  IMPRIMIR "ERES MAYOR DE EDAD"
  SI NO ENTONCES
  IMPRIMIR "ERES MENOR DE EDAD"
```
El bloque de PSC-1 anterior crea una variable y un condicional para definirsi eres mayor o menor de edad. Tiene un parecido con el lenguaje BASIC.

```
  // Ejemplo 3
  VARIABLE cantidad (número) // Crea una variable como número
  
  PARA cantidad DE 1 hasta 10
  IMPRIMIR "LA CANTIDAD ACTUAL ES " + cantidad
  FIN REPETIR
  
  IMPRIMIR "FIN DEL ALGORITMO"
```

El bloque de PSC-1 anterior crea una variable y una estructura de iteracción que va de 1 hasta 10 e imprimir el valor actual de la variable cantidad.

#### Pseucódigo PSC-2

PSC-2 es un bloque de comando que incluyen interaciones

```
  // PSC-2
  
  REPETIR
  //
  // COMANDO SE REPITE HASTA CUMPLIR CONDICION
  //
  HASTA condicion
  
  MIENTRAS condicion
  //
  // COMANDO SE REPITE MIENTRAS SE CUMPLA LA CONDICION
  //
  FIN MIENTRAS
  
  PARA cantidad DE 1 HASTA 10 PASO 2
  //
  // SE REPITE DE 1 HASTA 10 AVANZANDO DE 2 EN 2
  //
  FIN PARA
  
  
  // OPERACIONES CON NUMEROS
  VARIABLE peso (número)
  
  // ASIGNACION DE VALORES Y OPERACIONES MATEMATICAS
  peso = 10
  peso = peso * 2
  peso = peso + 2
  
  // OPERACIONES CON CADENA
  VARIABLE parrafo (cadena de texto)
  
  // ASIGNACION Y CONCATENAR VALORES
  parrafo = "Bienvenidos"
  parrafo = parrafo + " al mundo del algoritmo" 
  
```

#### Pseucódigo PSC-3

PSC-3 es un bloque de comando que incluyen funciones y procedimientos. Las funciones son bloques de código que se utilizan para ejecutar código y retornar el resultado, el procedimiento en cambio ejecuta el código pero no retorna un valor.

```
  // PSC-3
  
  // Función que  suma A + B
  FUNCION SUMAR(A,B)
    RETORNAR A + B
  FIN FUNCION
  
  // Procedimiento que imprime un texto
  PROCEDIMIENDO HOLA()
    IMPRIMIR "PROCEDIMIENTO 1"
  FIN PROCEDIMIENO
  
```


Con estos simples comandos se pueden construir los diversos programas y algoritmos.


### Actividad

Para complementar el estudio recomendamos la siguiente actividad: Buscar definiciones académicas de pseucódigo y la historia de los lenguajes de programación.

Para motivar la curiosidad y el aprendizaje empírico, se recomienda buscar métodos de análisis de algoritmos que son fórmulas y métricas para calcular la complejidad de una solución.

## Recursos

Aprendamos desde el punto de vista téorico científico con 
[Revistas de computación](https://www.redalyc.org/area.oa?id=33&tipo=coleccion)
