# Ejercicio 1: Conversión de Números y Organización de Datos​

## Objetivo

Se busca convertir el número decimal 45 a su representación en:​
* Binario​
* Octal​
* Hexadecimal​

Explica brevemente cómo se agrupan los bits para formar un byte y cómo se utilizan estos en la construcción de palabras (16, 32 o 64 bits) en la memoria del computador.

## Código Fuente:
```python
decimal = 45

binario = bin(decimal)[2:]  
octal = oct(decimal)[2:]    
hexadecimal = hex(decimal)[2:] 

print("El número decimal", decimal, "en binario es:", binario)
print("El número decimal", decimal, "en octal es:", octal)
print("El número decimal", decimal, "en hexadecimal es:", hexadecimal)

```

### Explicación del algorítmo:

El objetivo de este algoritmo es convertir un número decimal en sus respectivas representaciones en los sistemas de numeración binario, octal y hexadecimal. El algoritmo toma un número decimal de entrada, realiza las conversiones a cada uno de estos sistemas y luego muestra los resultados.


# Respuesta a la Pregunta:

Los bits son las unidades más pequeñas de información, representadas por 0 o 1. Un byte se forma agrupando 8 bits. Los bytes se combinan en palabras de mayor tamaño, como 16, 32 o 64 bits, dependiendo de la arquitectura del computador. Estas palabras se usan para almacenar datos más grandes o instrucciones de la CPU, siendo los sistemas modernos generalmente de 32 o 64 bits para aprovechar más capacidad y velocidad de procesamiento.


***¿Cómo se utilizan estos en la construcción de palabras (16, 32 o 64 bits) en la memoria del computador?***

Los bytes se agrupan en palabras, las cuales son secuencias de varios bytes, y la longitud de estas palabras varía según la arquitectua de la computadora, tal como se explicó previamente. En este caso, este agrupamiento se utiliza para representar valores numéricos más grandes, direcciones de memoria o instrucciones de la CPU.

Es así como:

Una palabra de 16 bits, puede contener valores desde 0 hasta 65,535
Una palabra de 32 bits puede contener valores de 0 a 4,294,967,295
Una palabra de 64 bits, puede contener valores de 0 a 18,446,744,073,709,551,615



