# Big Data - Actividad 2

**Análisis de Grandes Volúmenes de Datos**
*Instituto Tecnológico y de Estudios Superiores de Monterrey*

## Descripción

Proyecto de particionamiento y muestreo sobre el dataset **Steam Games Metadata and Player Reviews (2020–2024)** utilizando PySpark.

## Dataset

- **Fuente**: [Steam Games Metadata and Player Reviews](https://data.mendeley.com/datasets/jxy85cr3th/2)
- **Período**: 2020-2024
- **Tamaño**: ~15GB descomprimido

## Objetivo

Construir una estrategia de particionamiento y muestreo representativo utilizando PySpark para procesar grandes volúmenes de datos y facilitar futuros análisis sobre comportamiento y engagement de usuarios.

## Notebooks

- `Evidencia1_Particionamiento_Muestreo.ipynb` - Implementación de particionamiento estratificado y muestreo

## Tecnologías

- Python 3.x
- PySpark 4.1.1
- Jupyter Notebook

## Instalación

```bash
# Crear entorno virtual
python3 -m venv venv
source venv/bin/activate  # En macOS/Linux

# Instalar dependencias
pip install pyspark jupyter
```

## Ejecución

```bash
# Activar entorno virtual
source venv/bin/activate

# Iniciar Jupyter
jupyter notebook
```

---

**Equipo 29**
Edmundo Carmona Galindo | A01796647
Oliver Viveros Juarez | A01796912
