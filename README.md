# Binary Digit

Esta asignación tiene un valor de 15 puntos. La fecha de entrega está en moodle. Entregas tardías perderán 1 punto por cada día o fracción de día tarde. 

## Antes de comenzar

Cada dígito de un número binario se le llama un dígito binario o bit y puede tener un valor de 0 o 1. Un número binario de 4 bits se puede representar como `b3b2b1b0` (`b#` representa cada bit) y puede ser convertido a su número correspondiente `d` en base 10 (el sistema numérico que utilizamos regularmente) utilizando la siguiente fórmula:

`d = b3 * 8 + b2 * 4 + b1 * 2 + b0`

## Instrucciones 

Escriba un programa que le pida al usuario un número binario de 4 bits. El programa debe convertir el número a su equivalente en base 10.  

**HINT:** Para convertir un caracter numérico (de tipo char) a su número entero equivalente puede hacer lo siguiente:  

```c++
// Ejemplo:
char caracter = '9';
int numero = static_cast<int>(caracter) - '0';
// La variable numero ahora contiene el valor 9 de tipo int
```



**Ejemplo de output:**

```
Estre programa convierte un número binario de 4 bits a su número correspondiente en base 10.

Entre un número binario de 4 bits: 1010
Su equivalente en base 10 es: 10
```

## Rúbrica

Su programa debe:

- Seguir las instrucciones detalladas arribla (9 pts):

  - Pedir un número binario de 4 bits (2 pts)
  - Convertir correctamente el número binario a base 10 (5 pts)
  - Desplegar el resultado (2 pts)

- Desplegar el propósito del mismo, no tiene que ser igual el del ejemplo pero debe estar claro para el usuario el propósito (2 pts)

- Tener nombres apropiados para las variables (1 pt)

- Debe estar debidamente comentado e indentado de manera que su código sea legible y contener su información en la parte superior del código (ver ejemplo abajo) (2 pts)

  ```c++
  /*
  Asignación 1: Binary Digit
  Nombre: Juan del Pueblo
  Núm. Est: 801-XX-XXXX
  Colaboraciones: 
  - tutor X,
  - página web: [link]
  */
  ```

- Asegurar que los literales que se asignan a variables sean del mismo tipo de dato (1 pt)

- Solamente utilice conceptos discutidos en clase o en esta rúbrica, de otro modo perderá 1/3 de los puntos

- Si su programa no corre o se interrumpe, perderá la mitad de los puntos
