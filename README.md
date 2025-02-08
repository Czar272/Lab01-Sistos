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
