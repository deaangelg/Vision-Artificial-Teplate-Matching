# Vision-Artificial-Teplate-Matching
Este script procesa una imagen para identificar objetos en una imagen. 
Template Matching
Este script realiza el reconocimiento de plantillas en una imagen utilizando la técnica de coincidencia de plantillas. La coincidencia de plantillas es un método de visión por computadora que busca y encuentra una plantilla en una imagen más grande.

Descripción
El script escanea una imagen de entrada buscando una plantilla específica y dibuja rectángulos alrededor de las coincidencias encontradas. En este caso, se busca un objeto (plantilla) dentro de una imagen más grande y se resalta visualmente con rectángulos rojos.

Requisitos
Python 3.x
OpenCV (cv2)
NumPy
Matplotlib
Uso
Asegúrate de tener Python instalado en tu sistema.
Instala las dependencias necesarias ejecutando pip install opencv-python numpy matplotlib.
Coloca la imagen de entrada (Mario.jpg) y la plantilla (Moneda.jpg) en el mismo directorio que el script.
Ejecuta el script template_matching.py.
La imagen resultante con los rectángulos resaltados se guardará como Template matching.png en el mismo directorio.
Ejemplo de Resultado
