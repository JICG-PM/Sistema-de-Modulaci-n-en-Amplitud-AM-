# Actividad Formativa 4: Sistema de Modulación en Amplitud (AM)

## Descripción
Este repositorio contiene un cuaderno de Python (Google Colab) desarrollado para implementar y analizar un sistema de Modulación en Amplitud (AM). El código simula una señal de mensaje, una portadora, y evalúa el efecto del ruido y la atenuación en la señal modulada.

## Contenido del Código
1. *Generación de Señales:* Creación de una señal de información (50 Hz) y una portadora (1000 Hz).
2. *Modulación AM:* Aplicación de la ecuación matemática de AM con un índice de modulación de 0.8.
3. *Análisis de Escenarios:*
   - Inyección de ruido blanco gaussiano.
   - Atenuación de la señal (reducción de amplitud).
4. *Visualización:* Gráficas en el dominio del tiempo y análisis espectral (FFT) para observar la portadora y las bandas laterales.

## Herramientas Utilizadas
- Python 3 (Google Colab)
- NumPy
- Matplotlib

## Cómo ejecutarlo
Abre el archivo .ipynb en Google Colab y ejecuta las celdas en orden. Las gráficas se generarán automáticamente mostrando los resultados de la simulación.
