# tarea-1-Python-
TAREA DE LA PRIMERA SEMANA DE PYTHON

Introducción a Python: Generación de Números Aleatorios y Uso de Loops
En este cuaderno trabajaremos con la generación de números aleatorios y su manipulación usando estructuras como loops.
Estas herramientas son fundamentales en el desarrollo de simulaciones, análisis estadísticos y resolución de problemas computacionales.
Objetivos
Comprender el uso de la librería random para generar números aleatorios.
Implementar ciclos for y while para iterar sobre datos generados.
Aprender a realizar operaciones y condiciones basadas en datos aleatorios.
# Proyecto: Generación de Números Aleatorios y Uso de Loops

## Descripción
Este proyecto tiene como objetivo enseñar el uso de Python para la generación de números aleatorios y la implementación de loops `for` y `while`. Además, se incluyen ejemplos prácticos y ejercicios propuestos para reforzar el aprendizaje. 

El cuaderno de Google Colab asociado contiene los pasos para la configuración, el código de ejemplo, y las instrucciones para realizar las actividades.

## Estructura del Proyecto
1. **Introducción a Python**: Conceptos básicos de generación de números aleatorios y su manipulación.
2. **Ejemplo de Código**: Demostración del uso de ciclos para procesar números.
3. **Ejercicios Propuestos**: Problemas para que el usuario practique y mejore su comprensión.
4. **Imágenes Relacionadas**: Capturas de pantalla que documentan el proceso en terminal y Google Colab.

## Imágenes Relacionadas
### Captura de la Terminal
![Captura de terminal](https://raw.githubusercontent.com/tu_usuario/tu_repositorio/main/imagen1.png)

### Captura de Google Colab
![Captura de Google Colab](https://raw.githubusercontent.com/tu_usuario/tu_repositorio/main/imagen2.png)

> **Nota**: Reemplaza `tu_usuario` y `tu_repositorio` con tu nombre de usuario y el nombre de tu repositorio en GitHub.

## Uso del Cuaderno en Google Colab
1. Clona este repositorio en tu máquina local o accede directamente al cuaderno en Google Colab.
2. Asegúrate de que las dependencias estén instaladas (no se requieren librerías adicionales más allá de Python estándar).
3. Sigue las instrucciones en el cuaderno para ejecutar el código de ejemplo y resolver los ejercicios propuestos.

## Código de Ejemplo
```python
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
