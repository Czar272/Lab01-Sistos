# Lab01-Sistos

# Ejecución de Programas en C

Este repositorio contiene dos programas escritos en C que trabajan con llamadas al sistema (`open()`, `read()`, `write()`, `close()`) y utilizan la herramienta `strace` para analizar el comportamiento del sistema operativo.

## Requisitos previos
1. **Instalar herramientas necesarias:**
   - Asegúrate de tener `gcc` (compilador de C) instalado en tu entorno WSL o Linux:
     ```bash
     sudo apt-get update
     sudo apt-get install build-essential
     ```
   - Instala `strace`:
     ```bash
     sudo apt-get install strace
     ```

2. **Clonar este repositorio o crear los archivos:**
   - Asegúrate de tener los archivos `file_copy.c` y `hello_world_pid.c` en el mismo directorio.

---

## Ejercicio 1: `hello_world_pid.c`
Este programa imprime "Hello World!" y el ID del proceso (PID) que lo ejecuta.

### Pasos para ejecutar:
1. **Compilar el programa:**
   ```bash
   gcc -o hello_world_pid hello_world_pid.c
   ```
2. **Ejecutar el programa:**
   ```bash
   ./hello_world_pid
   ```

---
   
## Ejercicio 2: `file_copy.c`
Este ejercicio consiste en crear un programa en C que copie el contenido de un archivo fuente a un archivo destino utilizando las llamadas al sistema `open()`, `read()`, `write()` y `close()`.

## Pasos para ejecutar

1. **Compilar el programa:**
   ```bash
   gcc -o file_copy file_copy.c
   ```

2. **Crear un archivo de prueba:**
   ```bash
   echo "Contenido de prueba para copiar" > archivo_origen.txt
   ```

3. **Ejecutar el programa:**
   ```bash
   ./file_copy archivo_origen.txt archivo_destino.txt
   ```

4. **Verificar nuevo archivo:**
   ```bash
   cat archivo_destino.txt
   ```

---

## Ejercicio 3

- Solo logre llegar a esta parte por el tiempo y por lo que dice en el pdf de la entrega.
![image](https://github.com/user-attachments/assets/c5890f52-5b8e-40ab-a5ef-3f0e8ea740ae)

