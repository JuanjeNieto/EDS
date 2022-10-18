## Ejercicio 1: Ejecuta un hola mundo en distintos lenguajes

### Bash:

![Comandos bash](/home/usuariodaw/Escritorio/Entornos/Tema 2 - Entornos integrados de Desarrollo/capturas ejercicio01/Captura desde 2022-10-04 09-52-41.png)

<pre><code>echo "Hola, Juan";</code></pre>

### Python: 

![Comandos python](/home/usuariodaw/Escritorio/Entornos/Tema 2 - Entornos integrados de Desarrollo/capturas ejercicio01/Captura desde 2022-10-06 08-49-57.png)



<pre><code>print ("Hola, Juan")</code></pre>



### Javascript

![código Js](/home/usuariodaw/Escritorio/Entornos/Tema 2 - Entornos integrados de Desarrollo/capturas ejercicio01/Captura desde 2022-10-06 08-58-51.png)

<pre><code>console.log("Hola, Juan");</code></pre>



### C

![Comandos C](/home/usuariodaw/Escritorio/Entornos/Tema 2 - Entornos integrados de Desarrollo/capturas ejercicio01/Captura desde 2022-10-11 08-10-07.png)

<pre><code>
int main()
{
    printf("¡Hola, Juan!");
    return 0;
}</code></pre>

### Java

![Comandos Java](/home/usuariodaw/Escritorio/Entornos/Tema 2 - Entornos integrados de Desarrollo/capturas ejercicio01/Captura desde 2022-10-11 08-14-23.png)

<pre><code>class Hola
{
    public static void main(String[] args)
    {
        System.out.println("Hola Juan");
    }
}</code></pre>	



## Ejercicio 2: Para cada uno de los lenguajes anteriores, indica el proceso realizado  para conseguir ejecutar el código: ¿compilación o interpretación?

(he dejado algunas capturas de pantalla donde se ve el proceso de complilación y ejecución)

- Bash --> utilizamos el interprete de la consola de linux, por tanto es un lenguaje interpretado
- Python --> descargando la extensión de phython, lo hice por Visual studio Code. También fue un lenguaje interpretado.
- JavaScript --> LO hicimos en un intérprete de JS online, por tanto otro interpretado.
- C --> Con C tuvimos que compilar y ejecutar en la consola de Linux
- Java --> ionterpretación, compilación y ejecución en la consola de Linux.



## Ejercicio3: Para cada uno de los lenguajes anteriores, indica el nombre del compilador o interprete utilizado en GNU/Linux.

Bash - Terminal, Python - VS Code, Javascript - RunJS, C - terminal, Java - Terminal.



## Ejercicio 04: 

bash --> .sh

python --> .py

php --> .php

javascript --> .js

c --> .c

c++ --> .cpp

java --> .java

ensamblador --> .asm

ruby --> .rb

go --> .go

rust --> .rs

lisp --> .lisp



## Ejercicio 06

Los archivos de código objeto tienen la extensión .obj o la extensión .o

## Ejercicio 07-08

![Comandos codigoobjeto](/home/usuariodaw/Escritorio/Entornos/Tema 2 - Entornos integrados de Desarrollo/capturas ejercicio01/Captura desde 2022-10-11 08-54-37.png)



## Ejercicio 11

Las bibliotecas se puedend definir como un conjunto de archivos objeto que extienden la funcionalidad del lenguaje, es decir, nos permiten poder hacer más cosas y programas más complejos en cada lenguaje de programación.

## Ejercicio 12

Es más común el uso de bibiliotecas dinámicas para la funcionalidad básica, y el uso de plugins se deja para la funcionalidad opcional.

## Ejercicio 13

<pre><code> 
gcc  -c  -fPIC  aritmetica.c

gcc  -shared  -fPIC  -o  libaritmetica.so  aritmetica.o

cp  libaritmetica.so  /lib
</code></pre>

## Ejercicio 14


