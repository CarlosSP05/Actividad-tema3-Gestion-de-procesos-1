Proyecto: Números Aleatorios y Ordenación

Descripción:
-------------
Este proyecto en Java contiene dos programas separados:

1. Aleatorios.java
   - Genera automáticamente 40 números aleatorios entre 0 y 100.
   - Imprime los números en la salida estándar.

2. OrdenarNumeros.java
   - Recibe números desde la entrada estándar.
   - Ordena los números de menor a mayor.
   - Imprime los números ordenados en la salida estándar.

El proyecto cumple con la práctica evaluable manteniendo las dos clases separadas.

Archivos incluidos:
------------------
- Aleatorios.java
- OrdenarNumeros.java
- README.txt

Instrucciones de ejecución en CMD:
-----------------------------------
1. Abrir CMD y entrar en la carpeta del proyecto:
   cd C:\Users\USERNAME\Desktop\numeros_proyecto

2. Compilar los archivos:
   javac Aleatorios.java
   javac OrdenarNumeros.java

3. Generar números aleatorios y guardarlos en un archivo temporal:
   java Aleatorios > numeros.txt

4. Ver los números generados (opcional):
   type numeros.txt

5. Ordenar los mismos números:
   java OrdenarNumeros < numeros.txt

Uso de tubería (opcional):
----------------------
Se puede pasar directamente la salida de Aleatorios a OrdenarNumeros:
   java Aleatorios | java OrdenarNumeros

Nota: Con la tubería, CMD no mostrará los números generados antes de la ordenación. Para verlos, usar el archivo temporal (numeros.txt).

Ejemplo de ejecución:
---------------------
Números generados:
23 7 88 12 56 34 0 45 78 90 11 67 50 25 84 28 53 22 33 84 9 57 7 70 30 46 18 68 25 83 61 52 66 67 11 98 91 56

Números ordenados:
0 7 7 9 11 11 12 18 18 22 23 25 25 28 30 33 34 45 46 50 52 53 56 56 57 61 66 67 67 68 70 78 78 83 84 84 88 90 91 98

Consideraciones:
----------------
- Mantener las dos clases separadas es obligatorio para cumplir la práctica.
- Usar un archivo temporal permite ver los números generados y luego ordenarlos exactamente.
- La ejecución con tubería demuestra cómo pasar la salida de un programa a otro.
