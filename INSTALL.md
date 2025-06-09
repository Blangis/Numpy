## Requisitos previos

Para ejecutar el notebook de este repositorio necesitas clonar usando **HTTPS o SSH** y tener instalado:

- Python 3.x
- NumPy
- Jupyter Notebook (o Jupyter Lab)

### Instalación de dependencias (usando pip):

```bash
pip install numpy notebook
```

Desde la terminal, navega hasta el directorio del repositorio y ejecuta:

```bash
jupyter notebook
```
Luego selecciona el archivo .ipynb que quieras abrir desde la interfaz web que se abrirá en tu navegador.

### Alternativa (usando Anaconda):

Si tienes Anaconda, puedes abrir los notebooks directamente desde el navegador ejecutando:

```bash
jupyter notebook
```

### Posibles problemas
---
```bash
jupyter: command not found
```
```bash
ModuleNotFoundError: No module named 'numpy'
```
- Causas: Jupyter Notebook no está instalado globalmente o no está en tu PATH. 
NumPy no está instalado en el entorno desde donde ejecutas el notebook.
- Solución: Asegúrate de haber ejecutado:
```bash
pip install numpy notebook
```
```bash
pip install numpy
```
---

El navegador no se abre automáticamente.
- Causa: En algunos sistemas, Jupyter no abre el navegador por defecto.
- Solución: Copia la URL que aparece en la terminal (algo como http://localhost:8888/...) y pégala en tu navegador.
