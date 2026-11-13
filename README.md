# TFG-Emmanuel-Mora-Quirós
# Simulación Monte Carlo de curvas de isodosis en intervencionismo

Este repositorio contiene los códigos desarrollados para un Trabajo Final de Graduación en Ingeniería Física, orientado a caracterizar la distribución espacial de la radiación dispersa en una sala de cardiología intervencionista mediante simulaciones Monte Carlo.

El modelo fue desarrollado con OpenGATE/Geant4 e incluye la fuente de rayos X, la geometría principal del sistema de angiografía, un maniquí antropomórfico simplificado, puntos de medición ocupacional y una malla espacial para la generación de mapas y curvas de isodosis.

## Contenido del repositorio

El repositorio incluye:

- un notebook con la simulación principal y el postprocesamiento de resultados;
- un notebook para el análisis de sensibilidad asociado con el tamaño de los volúmenes de scoring;
- un notebook para el análisis de sensibilidad de la representación del maniquí;
- un archivo `.txt` con el espectro de rayos X generado mediante SpekPy y utilizado como entrada de la fuente en la simulación.

## Funcionalidades principales

- Simulación del transporte de fotones con OpenGATE/Geant4.
- Cálculo de \(H^*(10)\) en puntos de interés.
- Comparación entre simulación y mediciones experimentales.
- Evaluación de la incertidumbre estadística Monte Carlo.
- Generación de mapas espaciales y curvas de isodosis.
- Análisis de sensibilidad de parámetros relevantes del modelo.

## Requisitos principales

- Python
- OpenGATE
- Geant4
- SpekPy
- NumPy
- Pandas
- Matplotlib
- SciPy
- SimpleITK
- uproot

## Uso

Se recomienda ejecutar primero simulaciones con un número reducido de historias para verificar la geometría, los actores y los archivos de salida antes de realizar las simulaciones finales.

## Autor

Trabajo Final de Graduación de Ingeniería Física, Instituto Tecnológico de Costa Rica.

## Uso académico

Este repositorio se publica con fines académicos y de reproducibilidad.
