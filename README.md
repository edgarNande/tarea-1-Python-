# tarea-1-Python-
TAREA DE LA PRIMERA SEMANA DE PYTHON

Introducción a Python: Generación de Números Aleatorios y Uso de Loops
En este cuaderno trabajaremos con la generación de números aleatorios y su manipulación usando estructuras como loops.
Estas herramientas son fundamentales en el desarrollo de simulaciones, análisis estadísticos y resolución de problemas computacionales.
Objetivos
Comprender el uso de la librería random para generar números aleatorios.
Implementar ciclos for y while para iterar sobre datos generados.
Aprender a realizar operaciones y condiciones basadas en datos aleatorios.
# Importamos la librería random
import random

# Generamos una lista de 10 números aleatorios entre 1 y 100
numeros_aleatorios = [random.randint(1, 100) for _ in range(10)]

# Mostramos los números generados
print("Números aleatorios generados:", numeros_aleatorios)

# Procesamos la lista usando un loop para identificar pares e impares
for numero in numeros_aleatorios:
    if numero % 2 == 0:
        print(f"El número {numero} es par.")
    else:
        print(f"El número {numero} es impar.")
Ejercicio Propuesto
Modifica el código anterior para:
Generar 20 números aleatorios en lugar de 10.
Calcular la suma y el promedio de los números generados.
Usa un loop while para encontrar el primer número mayor a 50 en la lista generada.
Conclusión
La combinación de números aleatorios y estructuras iterativas amplía las posibilidades para resolver problemas de forma eficiente y creativa. 
Explora cómo ajustar los parámetros de random y cómo usar condiciones para obtener resultados específicos.
