# Reconstrucción de Trazas con Aprendizaje Automático en el Experimento CMS del LHC
Este repositorio contiene la muestra de datos y los códigos en formato Notebook de Python utilizados para la eleboración del TFG. Concretamente el proyecto se centra en una etapa determinada del proceso de reconstrucción de trayectorias: la **clasificación de dobletes**. Se considerará que un doblete está formado por dos hits o impactos en distintos puntos del detector de píxeles de silicio, que podrían haber sido producidos por una misma partícula cargada en su trayectoria. 
Para ello se propone la implementación de técnicas de **aprendizaje automático supervisado** usando para ello una muestra de datos simulada que cataloga a cada doblete como verdadero (`True`) o (`False`).

## Contenido del Repositorio
* **2 Notebooks**: Ejecutados en la plataforma en línea Kaggle que se dividen en:
   * **Visualizacion-Dobletes**: Dedicado a la exploración y visualización de la muestra de dobletes
   * **ML-Dobletes**: Dedicado a la implementación, entrenamiento y evaluación de los modelos de aprendizaje automático. Concretamente se hace una comparación entre un Boosted Decision Tree (BDT) y una Red Neuronal Profunda (DNN)
* **Muestra de datos** usada durante la ejecución de ambos Notebooks. Contiene aproximadamente 1 millón de dobletes y ha sido balanceada para no provocar sesgos entre clases.

## Contacto
Autor: Celia González Fernández - [celiaglzf21@gmail.com](mailto:celiaglzf21@gmail.com)
Trabajo tutorizado por : Javier Fernández Menéndez
