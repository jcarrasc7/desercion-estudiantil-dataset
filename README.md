 # Dataset sintético de deserción estudiantil
 
Juan David Carrascal Berdugo 

Este repositorio contiene un conjunto de datos sintético generado en Google Colab para simular información de estudiantes universitarios y analizar la deserción académica en el primer año.

## Archivos
- synthetic_dropout_dataset.csv (o .xlsx): dataset generado
- notebook.ipynb: código en Colab usado para crear el dataset
- README.md: explicación del dataset

## Variables incluidas
- age: edad del estudiante (16–30)
- gender: género (Male, Female, Other)
- origin: lugar de origen (Urban, Rural)
- highschool_avg: promedio de secundaria (0.0–5.0)
- admission_test: puntaje de examen de admisión (0–100)
- first_semester_gpa: promedio del primer semestre (0.0–5.0)
- socioeconomic_level: nivel socioeconómico (1–6)
- scholarship: si tiene beca (Yes/No)
- loan: si tiene préstamo (Yes/No)
- dropout: variable objetivo (Yes/No)

## Características del dataset
- Se generaron 500 registros.
- Se añadieron valores nulos de forma aleatoria en algunas variables.
- Se incluyeron outliers como edades atípicas o notas fuera de rango.
- La variable objetivo (dropout) está balanceada (Yes/No).
- Contiene variables numéricas y categóricas.

## Uso
El dataset puede usarse para probar modelos de machine learning supervisados de clasificación (ejemplo: logistic regression, decision trees).
