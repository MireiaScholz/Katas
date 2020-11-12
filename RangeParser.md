# Range Parser

Fuente: https://www.codewars.com/kata/57d307fb9d84633c5100007a

Implementar un método que convierta una cadena de texto compuesta por _tokens_ que representan el rango entre dos enteros (por ejemplo el token `n1-n2` representa el rango de enteros entre n1 y n2) en una lista con todos los enteros comprendidos en ese rango.

Los tokens pueden estar separados por `,` o `, `.

## Ejemplo
- "2" 🠊 [2]
- "5-10" 🠊 [5, 6, 7, 8, 9, 10]
- "2,5-10" 🠊 [2,5, 6, 7, 8, 9, 10]
- "1-10,14,20-25" 🠊 [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 14, 20, 21, 22, 23, 24, 25]


