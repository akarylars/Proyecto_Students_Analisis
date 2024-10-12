# Student Performance Factors

## Selección y Justificación de la Base de Datos

**Base de datos elegida:**
“ student performance factors” / factores de rendimiento estudiantil
https://www.kaggle.com/datasets/lainguyn123/student-performance-factors
Este conjunto de datos nos ofrece una comprensiva revisión de varios factores sociales y educativos que influyen en los resultados de los alumnos durante la presentación de exámenes;a la vez nos habla de hábitos, asistencia, el nivel de compromiso de los padres y otros aspectos que pueden ayudar a determinar razones para un éxito académico dentro de un plantel o sistema educativo. 

**Justificación**
Dentro de la discusión y búsqueda por un tema de interés común para el equipo, decidimos optar por algo relacionado con la educación. Los sistemas educativos tanto públicos como privados a menudo se modifican con el propósito de una optimización de resultados en las pruebas de aprovechamiento escolar; esto para poder solicitar mejoras en escuelas así como recursos; y aunque este por sí mismo es un derecho, es cierto que también existe una contienda interminable por mejorar los promedios del alumnado para representar la calidad de las instituciones, por lo que sí es de suma importancia saber cómo y porqué se obtienen buenos, malos o regulares resultados. 
El equipo concuerda con que no solo es de interés para las escuelas en particular, sino también para el diseño más asertivo de políticas públicas enfocadas al sector, para resolver inconformidades sociales, y mejorar el ambiente para un fundamental futuro pilar de nuestra sociedad; los jóvenes. 

Mediante las facilidades gratuitas que se ofrecen en _“Kaggle”_, se logró encontrar una base de datos limpia y con elementos que ayudan a nuestro análisis a modo de práctica y de utilidad para el proyecto. La data disponible es un recurso abierto y de simulación que nos ofrece un preámbulo adecuado para obtener los objetivos deseados del proyecto.

¿Qué preguntas quiero responder con este análisis?
¿Qué factores influyen en las mejores calificaciones de los alumnos?
¿Qué factores influyen en una baja calificación?
¿Qué nivel de aprovechamiento es más común?
¿Cómo podemos mejorar el panorama actual de resultados en estudiantes con calificaciones más bajas?

**Factores de rendimiento de los estudiantes**
El rendimiento académico es un gran tema de interés y preocupación a nivel mundial ya que en esta etapa llega tener un impacto significativo en el desarrollo personal de cada individuo de una sociedad.
La educación es un derecho fundamental de todas las personas y es la clave para la construcción de sociedades más justas y equitativas, ya que se considera el mejor factor de producción esta nos permite acabar de raíz con muchos de los problemas económicos de una nación y funge como instrumento regulador de las desigualdades sociales, **_“saber más para servir mejor”_**.

Partiendo de esto al elegir este conjunto de datos, el cual nos proporciona una descripción general de varios factores que afectan el rendimiento de los estudiantes en los exámenes, incluyendo información sobre los hábitos de estudio, la asistencia, la participación de los padres y otros aspectos que influyen en el éxito académico, buscamos dar a conocer los principales factores que necesitamos mitigar tanto en el personal docente como familiar, también cuantificar las necesidades para el solicitar recursos gubernamentales.

## Preparación y Limpieza de los Datos

**Descripción de la Base de Datos:**
La base de datos cuenta con 6607 registros y 20 campos los cuales se describen a continuación:
![image](https://github.com/user-attachments/assets/eac81be4-f471-4177-a240-e65528f191c1)

**Limpieza de Datos:**

• Identificación y manejo de valores faltantes
• Corrección de errores en los datos 
• Transformaciones necesarias

Descripción: 
Haciendo uso de la función de Excel CONTAR.BLANCO, nos percatamos que el 3.47% de los registros contaban con al menos un campo en blanco (null), ya que no se nos hizo relevante decidimos eliminar los registros.
Al final de cada fila colocamos la función antes mencionada, con el rango de todos los campos, corrimos la fórmula para duplicar en cada uno de los registros, con el uso de un filtro seleccionamos los registros mayores a cero y procedimos a eliminar las filas.

## Análisis Exploratorio de Datos (EDA)

**Análisis Descriptivo:**
• Estadísticas descriptivas (media, mediana, moda, desviación estándar) 
• Distribuciones de variables/campos.

![image](https://github.com/user-attachments/assets/5e76a63b-582a-48b0-b2e6-fdeb42bc15df)
![image](https://github.com/user-attachments/assets/ceb254bc-e0ea-4163-90c3-2d53eda6ae03)
![image](https://github.com/user-attachments/assets/a77bd170-940d-4161-b95a-d9d9fcb1760e)
![image](https://github.com/user-attachments/assets/923e6577-526a-4b3e-880c-ae008865bcb1)

## Visualización de Datos

 • Herramienta de Visualización: Uso de Tableau para crear visualizaciones interactivas
 • Software de análisis de datos: Excel
 • Principales Visualizaciones: https://public.tableau.com/app/profile/luis.cardenas4701/viz/ProyectoFinal_Tableau_17283596205450/Historia

## Interpretación y Conclusiones

**Resultados del Análisis:**
 • El promedio de calificación por género no muestra gran diferencia 67.27 para mujeres y 67.23 para hombres 
 • El factor escuela privada o pública no es de gran relevancia para una calificación alta o baja
 • El acceso a internet es un factor de gran impacto para obtener buena calificación
 • El apoyo de los padres de medio a alto contribuye positivamente a una mejor calificación
 • El acceso a recursos estudiantiles de medio a alto contribuye positivamente a una mejor calificación
 • Los estudiantes que dedicaron más de 15 horas de estudio muestran calificaciones más altas

**Conclusiones:**

 • El promedio general de examen para los estudiantes de la base de datos analizada fue de 67.35
 • Los factores de mayor relevancia observados  para este análisis fueron acceso a internet, acceso a recursos estudiantiles, apoyo de los padres y horas de estudio. La presencia de los recursos mencionados en un nivel alto o medio favorece una mayor calificación y viceversa.
 • No existe una fórmula mágica o verdad absoluta ya que también se observó una minoría estudiantes con limitaciones o carencias de estos recursos obteniendo buena calificación, claro que la probabilidad de que esto suceda es menor.


**Recomendaciones basadas en los resultados obtenidos**
 • Hacer lo posible para tener acceso a internet así como otros recursos estudiantiles
 • Llevar una buena relación con la familia y apoyarse en ella
 • Estudiar al menos 15 horas

**Posibles limitaciones del análisis y sugerencias para trabajos futuros**
 • La base  de datos elegida muestra un porcentaje muy pequeño de estudiantes con calificaciones altas lo cual dificulta el análisis y recomendaciones ya que observamos estudiantes en igualdad de recursos y calificaciones menores
 • A futuro se podría buscar una base de datos que incluya escuela de procedencia así como estado/país para obtener un mejor análisis
