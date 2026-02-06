# Generación de Datos Textuales Sintéticos con LLMs Cuantizados

Este repositorio contiene el código y los experimentos desarrollados para un Trabajo de Fin de Grado (TFG) centrado en la generación de datos textuales sintéticos mediante modelos de lenguaje de gran tamaño (LLMs) cuantizados. El repositorio sirve como apoyo a la metodología y los resultados presentados en la memoria del TFG.

## Objetivo
El objetivo principal de este proyecto es evaluar si los LLMs cuantizados son capaces de generar texto sintético de alta calidad en entornos con recursos computacionales limitados.

## Alcance
- Comparación de distintas técnicas de prompting (zero-shot, few-shot, etc.)
- Evaluación de la calidad del texto, alineación semántica y diversidad
- Análisis de restricciones de memoria y computación

## Estructura del repositorio
- `notebooks/`: Notebooks de Jupyter correspondientes a cada fase de la metodología:
  - Fase 1: Selección de LLM cuantizado
  - Fase 2: Generación del dataset sintético
  - Fase 3: Evaluación del dataset
- `data/`: Datasets sintéticos generados durante los experimentos
- `results/`: Resultados y métricas derivados de la evaluación

### Descripción de los notebooks
- `01_model_selection.ipynb`: Selección y análisis de modelos LLM cuantizados bajo restricciones de hardware.
- `02_dataset_generation.ipynb`: Generación del dataset de texto sintético utilizando el modelo seleccionado.
- `03_dataset_evaluation.ipynb`: Evaluación del dataset generado mediante métricas cualitativas y cuantitativas.

### Descripción del dataset
El dataset sintético generado se proporciona en formato Excel y contiene los textos producidos durante la Fase 2 del proyecto. Cada fila corresponde a una instancia de texto generado junto con los atributos asociados utilizados en la evaluación.

### Resultados
Esta carpeta contiene los resultados obtenidos durante la Fase 3 del proyecto.

La evaluación se centra en la calidad del dataset sintético generado, incluyendo análisis cualitativos y métricas cuantitativas derivadas del diseño experimental.

## Tecnologías
- Python
- LLMs cuantizados
- Prompt Engineering
- Métricas de evaluación en PLN

## Autora
Laura Santamaría Báez


