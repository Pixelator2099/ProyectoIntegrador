


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

### Ejercicios

ALGORITMOS RESUELTOS CON DIAGRAMAS DE FLUJO Y PSEUDOCÓDIGO

[ALGORITMOS](pdf/algoritmos.pdf)

Autores

Francisco Javier Pinales Delgado

César Eduardo Velázquez Amador

