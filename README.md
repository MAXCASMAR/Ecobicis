# Ecobicis
Objetivo: Trabajar con datos de movilidad autónoma, explorar las diferencias antes, durante y después del covid sobre el uso de estaciones de ecobici, propuestas, presupuesto, impacto… Distancias, trayectos, eficiencia.


## Datasets y artículos
**TODOS DEBEN DE LEER ESTOS**
**Artículos:**

- “Ranking Cyclability in Europe with OpenStreetMap”
https://towardsdatascience.com/ranking-cyclability-in-europe-with-openstreetmap-198d3b17463c
- Visualizing Bike Mobility in London using Interactive Maps and Animations
https://towardsdatascience.com/visualizing-bike-mobility-in-london-using-interactive-maps-for-absolute-beginners-3b9f55ccb59#9f3c
- Boris Bike usage in London during the coronavirus lockdown
https://towardsdatascience.com/boris-bike-usage-in-london-during-the-coronavirus-lockdown-9680a5e52e11


**Datos:**

- The public TfL data (or 'open data')
https://cycling.data.tfl.gov.uk/
- Ubicación de estaciones ECOBICI, Biciestacionamientos, Ciclovías y puntos de arribo de monopatines eléctricos y bicicletas
https://datos.cdmx.gob.mx/dataset/infraestructura-vial-ciclista
- Alcaldías
https://datos.cdmx.gob.mx/dataset/alcaldias/resource/e4a9b05f-c480-45fb-a62c-6d4e39c5180e 
- OpenStreetMap
https://www.openstreetmap.org/export#map=13/19.4124/-99.1571&layers=Y 
- Datos de eobici
https://www.ecobici.cdmx.gob.mx/es/informacion-del-servicio/open-data

## Tasks 
1. Replicar el análisis del primer link para los estados de México y para las **alcaldías de la Ciudad de México**
- Inicialmente, hacer los análisis en pandas y luego al final en Spark o Apache Hadoop
- Google Colab con el entregable de la tabla del ranking
Subtasks:
  - Descargar la data
  - Obtener polygons
2. Mapas de rutas, infraestructure y otros insights
3. Leyes y políticas públicas en relación con movilidad en bici


## Tasks generales

#### 1. Encuesta de Google Forms

*Objetivos*:
- Conocer la población de estudiantes que usan como transporte al ITAM una bicicleta.
  - Bajo qué escenarios la gente prefiere utilizar bicicletas.
  - Conocer las rutas que utilizan. 
  - Población foránea vs. población local.
  - Género.
  - Gasto en gasolina, y estacionamientos en promedio semanal
  - Cuantos saben andar en bici y si andan en la ciudad

- Razones por las que no utilizan bicicletas.
  - Clima (Contingencia).
  - Por seguridad.
  - Falta de conocimiento de la infraestructura.
  - Falta de infraestructura.

- Disposición a usar más la bici
  - En caso de hacer rodadas con otras personas del ITAM hacia la H.
  - Qué medidas de seguridad incentivarían su uso
  - Mayor conocimiento de formas de utilizar las bicis

#### 2. Manual de uso de bicicletas para estudiantes del ITAM

  *Objetivos*
    Dar a conocer la infraestructura existente de bicicletas en la ciudad a los alumnos del ITAM y que al final con actualizaciones compartamos los resultados de       nuestro análisis. 

  - Etapas:

  a. Primera versión que vamos a compartir al mandar la encuesta.
    - Dar a conocer los objetivos de nuestra investigación.
    - Rutas definidas para estudiantes y para zonas más populares
    - De haber brigadas, exponer horarios, ubicaciones, etc. 
    - Medidas de seguridad que se podrían implementar
    - Básicos de “mecánica” de las bicicletas en caso de tener que arreglar un inconveniente
    - Números de asistencia vial
    - ¿Qué son las ecobicis? Forma de registrarse Podríamos explorar facilitar el proceso con el itam

  b. Segunda versión con los resultados de la encuesta y de la comparación entre la CDMX y otras ciudades.
    - Compartir las estadísticas que obtuvimos de la encuesta.
    - Después de las respuestas, ¿cuáles son las medidas que podríamos buscar implementar?
    - Razones por las cuales (según el análisis) el ITAM debería de preocuparse más por la cultura ciclista.
    - Medidas a largo plazo que ayudarían a los estudiantes.


#### 3. Análisis de infraestructura de la CDMX y luego comparar entre ciudades

  - Cómo es la infraestructura 
  - Identificar estrategia geográfica
  - Gasto público destinado a: infraestructura, mantenimiento, análisis.
  - Ventajas y desventajas que han tenido los programas ciclistas en otras ciudades.
  - Comparación de los estudiantes en otras ciudades y la CDMX.
  - El principal objetivo de este análisis es responder ¿por qué el ITAM se debe de preocupar por promover una cultura ciclista?
  - Como segundo objetivo, ¿cómo se podría promover una cultura ciclista en la CDMX? ¿Qué ventajas traería a la ciudad?


## Otros links importantes

**Links**
https://towardsdatascience.com/ecoviz-39a8e50c6c1

https://medium.com/@jeroaranda/mo-r-vilidad-3f25206cdb13

http://ciclociudades.mx/

Strava y wikiloc te permiten visualizar tus recorridos personales: https://www.strava.com/activities/3599258536

**Code or papers**
Google Maps es la fuente de la información espacial de este artículo, esta interfaz te permite obtener las coordenadas de cualquier dirección, obtener rutas operativas entre otras posibilidades. Notebook en Python con conexión a API, análisis y gráficos.

https://colab.research.google.com/drive/1FmQHSXKHKgGrph_evAFAxU8TMMl_pCTW?usp=sharing

https://github.com/ecastillomon/ecoVIZ


https://urbantransitions.global/wp-content/uploads/2021/02/Sustainable-Mobility-for-Sustainable-Cities_Lessons-from-cycling-schemes-in-Mexico-City-and-Guadalajara-Mexico.pdf

https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0213106


https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8719369/






