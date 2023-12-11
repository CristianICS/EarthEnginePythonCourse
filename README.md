# Introducción a Google Earth Engine con Python

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

La disponibilidad de datos abiertos procedentes de imágenes de satélite es del orden de Terabytes. Procesarla de forma eficiente requiere de una infraestructura computacional y de personal calificado en ingeniería de datos. La API de Google Earth Engine (GEE) permite el procesado de multitud de colecciones satelitales e información raster y vectorial de forma gratuita y rápida. En este curso, creado por [Cesar Luis Aybar Camacho](https://github.com/csaybar/), se presenta la herramienta de Google Earth Engine con el objetivo de reemplazar los flujos de trabajos tradicionales en procesamiento digital de imágenes. 

## Objetivos

1) Mostrar las ventajas y desventajas entre flujos de trabajo tradicionales (ej: ENVI + ARCGIS) frente a Google Earth Engine ("Lazy evaluation").

2) Mostrar las ventajas y desventajas del uso de GEE mediante las APIs de Python vs JavaScript.

3) Exponer flujos de trabajos eficientes a la hora de trabajar con sistemas cliente-servidor.

4) Introducción a la sintaxis de la API de GEE en Python.  

5) Descargar, manipular y procesar cientos de imágenes satelitales (Sentinel, Landsat, Modis, etc.) de cualquier parte del mundo en cuestión de minutos.

## Programa

- **Módulo 01:** Entendiendo GEE
  - Bienvenidos
  - ¿Qué es Google Earth Engine?
  - Catálogo de datos de GEE
  - ¿Comó funciona la Infraestructura computacional de GEE?
  - API’s: Programación funcional
  - Cuáles son las ventajas y desventajas de usar el API de Python frente al de JavaScript.
  - Colab (jupyter notebbok) como interfaz para usar Python.
  - [Primeros pasos en colab y comandos básicos en Linux](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module01/01_introcolab.ipynb).


- **Módulo 2:** Sintaxis de mínima de Python para GEE
  - [Tipos de datos en Python](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/01_tipodedatos.ipynb).
  - [Estructuras de datos](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/02_estructuradedatos.ipynb).
  - [Operadores de comparación](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/03_Operadoresdecomparación.ipynb).
  - [Declaraciones if, else y elif](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/04_if_else_elif.ipynb)
  - [Ciclos for](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/05_Ciclosfor.ipynb).
  - [Funciones](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/06_Funciones.ipynb).
  - [Expresiones lambda y funciones map y filter](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/07_Lambda.ipynb).
  - [modulos y paquetes en Python](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/08_Modulos_y_Paquetes.ipynb).
  
  
- **Módulo 3:** Datos Espaciales en Python
  - [WKT y GeoJSON e introducción a geopandas](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module03/01_wkt_geojson.ipynb).
  - Subida de datos raster y vector a GEE


- **Módulo 4:** Sintaxis en GEE 
  - [Como inicializar la Earth Engine Python API](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module04/01_EDGEE.ipynb).
  - [ED básicas en Google Earth Engine](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module04/01_EDGEE.ipynb).
  - [ED espaciales en Google Earth Engine I (ee.Image): cálculo de índices: NDVI, NDWI.](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module04/02_EDGEE.ipynb) 
  - [ED espaciales en Google Earth Engine II ( ee.ImageCollection): map y filter](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module04/03_EDGEE.ipynb)
  - [ED espaciales en Google Earth Engine III (ee.Feature y ee.FeatureCollection).](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module04/04_EDGEE.ipynb)


- **Módulo 5:** GEE en acción I
  - [Manipulación de ee.Image y ee.ImageCollection y exploración de metadatos](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module05/01_metadatos_I.ipynb).
  - [Manipulación de ee.Feature y ee.FeatureCollection y exploración de metadatos](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module05/02_metadatos_II.ipynb).
  - [Reducciones espacio temporales en ee.Image y ee.ImageCollection.](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module05/03_reducer.ipynb)
  - [Ejercicio 01:  Generación de una base de datos espacial](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module05/04_Ejercicio_01.ipynb).
  - [Ejercicio 02:  Descarga automática de imágenes Sentinel-2 en cualquier parte del mundo de forma 100% automatica.](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module05/05_Ejercicio_02.ipynb)


- **Módulo 6:** GEE en acción II
  - [Composición y mosaico](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module06/01_composites.ipynb).
  - [Técnicas de visualización en ee.Image.Collection](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module06/02_ICviz.ipynb)
  - [Clasificacion supervisada y no supervisada.](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module06/03_class.ipynb)
  - [Ejercicio: Predicción de la erosión hídrica a nivel mundial](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module06/04_RUSLE.ipynb).
  - [Ejercicio Propuesto:  Estimación de la Precipitación máxima en 24 horas y evapotranspiración para todos las distritos de Loreto - Perú](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module06/prop01_PP_ETP.ipynb).
- **Extras:** Material adicional en español fuera del curso!
  - [Joins en Google Earth Engine](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/EXTRA/extra_joins.ipynb).

## Ejercicios Propuestos

- [Ejercicio N°01](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/tarea/PROP_01_RUSLE.ipynb):  Estimar la erosión multianual para cualquier parte del mundo

- [Ejercicio N°02](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/tarea/Indices.ipynb): Elaborar un Mapa de Índice espectral (e.g. NDVI, NDSI, NDWI, etc.) 

## "Snippets"

Puedes acceder a todos los "snippets" desarrollados en el curso dando clic [aquí](https://colab.research.google.com/drive/1n0CWwURmOmw93GDkiwcT5HWtwv5pbtjl)

## Donde seguir aprendiendo  

Actualmente la API de GEE ofrece más de **1000** formas diferentes de interactuar (entre `clases`, `métodos` y `funciones`) con los servidores de Google Earth Engine. En esta sección se adjuntan algunos de los materiales más importantes que encontrarás en Internet sobre la Earth Engine Python API y donde seguir mejorando tus habilidades con **Python**.

**Material Online en Github**

- [**earthengine-py-notebooks**](https://github.com/giswqs/earthengine-py-notebooks): Una colección de más de 300 Jupyter notebooks para usar Google Earth Engine.
- [**EEwPython**](https://github.com/csaybar/EEwPython): Una serie de Jupyter notebooks para aprender Google Earth Engine con Python
- [**qgis-earthengine-examples**](https://github.com/giswqs/qgis-earthengine-examples): Una colección de más de 290+ Python scripts para usar Google Earth Engine.
- [**earthengine-community**](https://github.com/google/earthengine-community): Repositorio oficial de la comunidad de Google Earth Engine.
- [**gee-community**](https://github.com/gee-community): Esta organización contiene contenido aportado por la comunidad de desarrolladores de Earth Engine. Este no es un producto de Google oficialmente compatible.

**Libros y material online**

- [**Python Data Science Handbook**](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb): Mejora tu nivel de Python en análisis de datos, aprende como implementar un flujo de trabajo usando Machine Learning.

- [**Fluent Python**](https://www.amazon.com/Fluent-Python-Concise-Effective-Programming/dp/1491946008) Excelente libro para perfeccionar tus habilidades en Python sobretodo si ya tienes experiencia en Python u otro lenguaje de programación.

- [**Complete Python Bootcamp: Go from zero to hero in Python 3**](https://www.udemy.com/course/complete-python-bootcamp/)
