# Análisis de Discursos Mediatizados sobre Narcoterrorismo en Rosario

## Descripción
Repositorio con código, datos e informe de la pasantía en la **Tecnicatura Universitaria en Inteligencia Artificial (TUIA)** de la **Facultad de Ciencias Exactas, Ingeniería y Agrimensura (FCEIA)** de la **Universidad Nacional de Rosario (UNR)**. Este trabajo se desarrolló en el marco del Programa en Investigación y Desarrollo (PID) *"Discursos sobre lo público-común plataformizados: caracterización interdisciplinaria de las estrategias enunciativas empleadas en plataformas mediáticas contemporáneas y sus flujos de sentido"*, radicado en el **Centro de Investigaciones en Mediatizaciones (CIM)** de la **Facultad de Ciencia Política y Relaciones Internacionales (FCPOLIT)** de la **UNR**. El PID está dirigido por la Dra. Natalia Raimondo Anselmino y codirigido por la Dra. Irene Gindin.

El proyecto analiza el discurso mediático y su repercusión en Facebook sobre eventos de narcoterrorismo ocurridos en Rosario, Argentina, entre marzo y mayo de 2024.

## Objetivos
- Extraer artículos de medios locales y nacionales.
- Recopilar comentarios de Facebook asociados.
- Transformar textos en embeddings.
- Aplicar UMAP y clustering con k-means.

## Contenido del Repositorio
```
/
├── data/                        # Datos del proyecto
├── notebooks/                    # Notebooks de procesamiento
├── scripts/                      # Códigos de scraping y preprocesamiento
├── informes/                     # Informe de la pasantía
├── README.md                     # Este archivo
```

## Ejecución
1. Ejecutar `generacion_dataset.ipynb` para construir el dataset.
2. Ejecutar `transformacion_embeddings_dataset.ipynb` para vectorizar.
3. Ejecutar `umap_kmeans_narcoterrorismo_rosario.ipynb` para clustering.

## Contacto
📧 Francisco J. Alomar - franciscojalomar@gmail.com

