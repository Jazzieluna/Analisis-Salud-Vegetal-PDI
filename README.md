# Analisis-Salud-Vegetal-PDI
Sistema para detección de daño foliar usando segmentación HSV.
# Análisis de Salud Vegetal mediante PDI 🍃

**Materia:** Procesamiento Digital de Imágenes  
**Alumnos:** Jeovani Yael Hernandez Cervantes, Jassiel Luna Cantu, Daniel Alejandro Ramirez Hernandez   
**Fecha:** 05 de Enero 2026

## Descripción
Este proyecto implementa un sistema de visión por computadora capaz de detectar y cuantificar el daño en hojas vegetales. Utiliza técnicas de procesamiento de imágenes como filtros Gaussianos, detección de bordes y segmentación en el espacio de color HSV para mitigar problemas de iluminación y sombras.

## Funcionalidades
- **Preprocesamiento:** Reducción de ruido con filtro Gaussiano.
- **Segmentación Inteligente:** Uso del canal de Saturación (HSV) para eliminar sombras proyectadas.
- **Clasificación:** Distinción entre tejido sano y tejido necrótico/clorótico.
- **Reporte Automático:** Cálculo del porcentaje de daño en la superficie foliar.


##  Tecnologías
- Python 3
- OpenCV (cv2)
- NumPy
- Matplotlib
- SciPy
