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

## Ejecución desde cero 
1. Ejecutar `generacion_dataset.ipynb` para construir el dataset.
2. Ejecutar `transformacion_embeddings_dataset.ipynb` para vectorizar.
3. Ejecutar `umap_kmeans_narcoterrorismo_rosario.ipynb` para clustering.

## Ejecución para ver resultados e interfaz exploratoria de datos 

Se puede ejecutar directamente `umap_kmeans_narcoterrorismo_rosario.ipynb` y como resultado se obtendrán métricas y gráficos para el análisis. Además, los gráficos resultan interactivos con metadados de los puntos que representan artículos o comentarios de facebook. De los metadatos es de particular importancia el "índice", mediante el cual, en la última porción de código se accede a la información de ese un artículo en particular. Por ejemplo:

Ingrese un índice entre 0 y 594: 400

-- INFORMACIÓN DEL ÍNDICE SELECCIONADO

Índice: 400
Fecha: 2024-04-07
Medio: lacapital
URL: https://www.lacapital.com.ar/edicion-impresa/cada-agente-las-fuerzas-federales-rosario-le-cuesta-la-provincia-11600-dia-n10126983.html
Tipo Medio: local
Número de Cluster: 1

--       INFORMACIÓN DEL ARTÍCULO

Título:
Cada agente de las fuerzas federales en Rosario le cuesta a la provincia $11.600
por día

Bajada:
Por un acuerdo con Nación, el gobierno de Santa Fe cubre los gastos de techo y
comida. Qué comen y dónde duermen los 1.200 efectivos que llegaron a Rosario

Cuerpo del texto:
El Hotel República, en San Lorenzo y San Martín, es uno de los alojamientos
donde los efectivos residen en la ciudad.  El lado B de la saturación de
seguridad en Rosario indica que cada uno de los agentes de las fuerzas federales
que vinieron a la ciudad cuestan $11.600 por día, en alimentación y alojamiento
. El acuerdo indica que Nación envía los 1.200 efectivos de Gendarmería Nacional...

## Contacto
📧 Francisco J. Alomar - franciscojalomar@gmail.com

