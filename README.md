# Actividad Python Clase 11

_____________________________________________________________________________________________

En este repositorio encontraremos los pasos para crear y activar un entoro virtual en Python

_____________________________________________________________________________________________

### Pasos

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window
2. Creamos una carpeta o directorio: `mkdir python-final`
3. Entramos en ella: `cd python-final`
4. Iniciamos el repositorio: `git init`
5. Creamos un archivo: `touch finales.py`
6. Abrimos VSC: `code .`
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada: `python -V` o `python3 -V`
8. Creamos el entorno virtual en Python: `python3 -m venv venv #Creamos el entorno virtual`
9. Activamos el entorno virtual: `source venv/bin/activate` (Activamos el entorno virtual en Linux) `venv/scripts/activate` (En Windows)
10. Hacemos actualización del pip de Python `python3 -m pip install --upgrade pip` (Actualizamos el PIP)
11. Investigar ¿Qué es el pip y porque lo actualizamos?

_____________________________________________________________________________________________

PIP (Pip Installs Packages) es el gestor de paquetes oficial para Python. Su propósito principal es facilitar la instalación, 
actualización y desinstalación de paquetes y bibliotecas en Python. 
Es una herramienta fundamental para cualquier desarrollador de Python, ya que permite instalar fácilmente paquetes desde el 
índice de paquetes de Python (PyPI), que es el repositorio oficial de software de terceros para Python.


### Actualizamos PIP para:

* Seguridad: Corregir vulnerabilidades.
* Nuevas Funcionalidades: Acceder a nuevas características.
* Compatibilidad: Mantener compatibilidad con versiones recientes de Python y paquetes.
* Corrección de Errores: Solucionar problemas y mejorar la estabilidad y rendimiento.
