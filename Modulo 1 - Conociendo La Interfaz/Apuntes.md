# Curso de Sonic Pi

# Módulo 1 - Conociendo la interfaz de Sonic Pi

## Objetivo

Al finalizar este módulo podrás:

-   Abrir Sonic Pi.
-   Identificar cada parte de la interfaz.
-   Ejecutar código.
-   Detener código.
-   Entender qué es un buffer.

> **Todavía no aprenderemos instrucciones como `play` o `sleep`.**
> Primero debemos conocer la herramienta.

------------------------------------------------------------------------

## ¿Qué es la interfaz?

La **interfaz** es todo lo que ves cuando abres un programa.

-   En Visual Studio Code, la interfaz son el explorador de archivos, el
    editor y la terminal.
-   En Word, la interfaz son la hoja y la barra de herramientas.
-   En Sonic Pi ocurre exactamente lo mismo.

------------------------------------------------------------------------

## Partes principales de Sonic Pi

``` text
+--------------------------------------------------------+
| Run | Stop | Save | Record | Help | Prefs | Info |
+--------------------------------------------------------+

+------------------------+
| Buffer 0               |
|                        |
|      Editor            |
|                        |
+------------------------+

+------------------------+
| Log                    |
+------------------------+

+------------------------+
| Cue Log                |
+------------------------+
```

## La barra superior

### ▶ Run

Ejecuta el código que escribiste.

### ■ Stop

Detiene todo lo que está sonando.

### 💾 Save

Guarda el contenido del buffer.

### 🎙 Record

Graba el audio producido por Sonic Pi.

### ❓ Help

Abre la documentación integrada.

### ⚙ Prefs

Permite cambiar la configuración del programa.

------------------------------------------------------------------------

## El Editor

Es la zona donde escribirás tu código.

Ejemplo:

``` ruby
play 60
```

------------------------------------------------------------------------

## ¿Qué es un Buffer?

Un **buffer** es un espacio temporal donde escribes código.

Es como una hoja de un cuaderno.

Ejemplos:

``` text
Buffer 0 -> Canción A
Buffer 1 -> Canción B
Buffer 2 -> Experimentos
```

------------------------------------------------------------------------

## El Log

Muestra:

-   Código ejecutado.
-   Errores.
-   Mensajes del sistema.

Es similar a la terminal de Visual Studio Code.

------------------------------------------------------------------------

## El Cue Log

Muestra mensajes de sincronización entre procesos y se utilizará más
adelante.

------------------------------------------------------------------------

## Comparación con Visual Studio Code

  Visual Studio Code   Sonic Pi
  -------------------- ----------
  Editor               Editor
  Terminal             Log
  Archivo              Buffer
  Ejecutar programa    Run
  Detener programa     Stop

------------------------------------------------------------------------

# Resumen

-   **Run** ejecuta el código.
-   **Stop** detiene la ejecución.
-   El **Editor** es donde escribes el código.
-   El **Log** muestra errores y mensajes.
-   Un **Buffer** es una hoja de trabajo independiente.

------------------------------------------------------------------------

# Ejercicio

1.  Abre Sonic Pi.
2.  Localiza **Run** y **Stop**.
3.  Encuentra el **Editor**.
4.  Observa el **Log**.
5.  Cambia entre distintos **Buffers**.

------------------------------------------------------------------------

## Nota

En este módulo aprendimos la interfaz. En el siguiente comenzaremos a
escribir nuestro primer programa.
