# Carreras de Caballos con Concurrencia

## Matricula y Nombre

- 173258 - Dorian Alberto Ibáñez Nangüelú

- 191219 - Pablo Daniel Pérez López

## Introducción

[PyQt5](https://pypi.org/project/PyQt5/) es un binding de la biblioteca gráfica Qt para el lenguaje de programación Python. Dicha librería es usada para crear proyectos visuales usando a Python como base, funcionando similarmente a [tkinter](https://docs.python.org/es/3/library/tkinter.html) de manera nativa con Python en cuanto a interfaz visual.

Paralelamente, se usó [QT Designer](https://doc.qt.io/qt-5/qtdesigner-manual.html) el cual es la herramienta de Qt para diseñar y construir interfaces gráficas de usuario (GUI) con Qt Widgets de una manera sencilla.

Este programa genera un archivo *.ui al guardar el proyecto, por lo que se recomienda instalar [Anaconda](https://www.anaconda.com/products/individual) o librerias adicionales de PyQt5 para convertir dicho archivo *.ui a un archivo legible *.py.

## Instalación

Usar [pip](https://pip.pypa.io/en/stable/) para instalar [PyQt5](https://pypi.org/project/PyQt5/)  y PyQt5-tools

```bash
pip3 install pyqt5 pyqt5-tools
```


## Como convertir el proyecto de QT Designer a Python

Usar pyuic5 despues de instalar Anaconda, nombrar el archivo *.ui y guardarlo como .py en la computadora

```bash
pyuic5 -x archivo.ui -o archivo_python.py
```


## Inicializar el proyecto

Para correr el programa de Carreras de Caballos, usar dentro de la carpeta:

```bash
python3 main_proyecto.py
```

El archivo meramente visual es vista_caballo.py el cual solo arrancará la vista sin ninguna funcionalidad, y la clase_caballo.py es de manera redundante, la clase hilos para mover a los caballos dentro del main.

## Licencia
[MIT](https://choosealicense.com/licenses/mit/)
