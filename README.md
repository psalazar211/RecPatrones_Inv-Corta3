# RecPatrones_Inv-Corta3
Este respositorio corresponde a la investigación corta 3 del curso de reconocimiento de patrones de la maestria en ingeniria electroca del TEC. En esta investigación teorica se abordaron los temass de:
- Cloudy ML
- Hadoop-Sparks

En este readme se explica de forama teorica estos temas. Adicionalmente el repositorio incluye los siguientes ejemplos prácticos desarrollados en Azure:
- Cloudy ML, Azure Machine Learning.ipynb: Este cuaderno explica de forma general como usar Azure Machine Learning.
- Hadoop-Sparks, Apache-spark-azure-machine-learning-tutorial1.ipynb: Este cuaderno explica como crear un cuaderno en Azure para implemntar una solucion que utlice Apache Spark.
- Hadoop-Sparks, Apache-spark-azure-machine-learning-tutorial2.ipynb: Este cuaderno es la cuatinucion del aterior y corresponde a un ejemplo de como entrenar un modelo en azure usando Apache Spark.

## Cloudy ML

El aprendizaje automático se ha vuelto más popular en los últimos años como una rama de estudio que ofrece potentes herramientas para abordar temas difíciles y ofrecer modelos basados ​​en datos previos. Cada vez más empresas están surgiendo y utilizando soluciones de aprendizaje automático para mejorar su negocio y crear mejores productos basados ​​en la demanda del mercado. Tradicionalmente, el uso del aprendizaje automático en la producción ha seguido siendo una dificultad para muchas empresasy no existe un sistema que permita a los científicos de datos y ingenieros de aprendizaje automático para trabajar juntos y compartir información para entregar modelos para la producción.Debido a esto, muchos proyectos de ML no logran entrar en producción. Para resolver todos estos problemas, las organizaciones utilizan la metodología DevOps actual que exige reducir el tiempo de comercialización e implementar aplicaciones en producción. Basado en esta metodología, una tecnología llamada MLOps, o operaciones de aprendizaje automático, se ha utilizado en los últimos años para el aprendizaje automático.Está relacionado con DevOps mediante el uso de
conceptos de integración continua (CI) y continuidad entrega (CD) en proveedores de nube [3]. Estos proveedores de la nube permiten la ejecución de procesos MLOps en su nube, al ofrecer una amplia gama de herramientas y servicios para acelerar el desarrollo, implementación, escalamiento, seguimiento y reentrenamiento de modelos de ML. Los tres principales proveedores de nube, Servicios web de Amazon (AWS), plataforma en la nube de Google (GCP) y Microsoft Azure.[1]

### DevOPs
Un movimiento cultural hacia la colaboración entre desarrollo, control de calidad y operaciones se conoce como "DevOps". Como resultado, las empresas descubren con frecuencia que la transición a la producción es un proceso desafiante que requiere trabajos manuales, propensos a errores e incluso de última hora modificaciones. DevOps sugiere un conjunto complementario de Técnicas ágiles para facilitar la entrega iterativa de software en ciclos breves. DevOps amplía la metodología ágil por ejemplo, en DevOps se enfatiza la interacción y cooperación entre desarrolladores y operadores en lugar de tecnologías y procesos, puede lograr objetivos ágiles para disminuir la latencia del trabajo en equipo y extender conceptos ágiles a todo el proceso de entrega de software.[1]

### Concepto MLOPS

Los sistemas del mundo real requieren modelos de aprendizaje automático (ML) que puedan ajustarse a los datos de entrada cambiantes. Una vez que el modelo se ha puesto en producción, los frecuentes cambios de datos provocan una reducción en su rendimiento. Por lo tanto, el monitoreo de modelos es esencial para controlar correctamente el proceso que puede activar, reentrenar y garantizar que los modelos funcionen según lo previsto. Sin embargo, el seguimiento del rendimiento de un modelo a lo largo del ciclo de vida del aprendizaje automático plantea varios desafíos. Todos estos problemas se pueden resolver utilizando MLOps. El equivalente de aprendizaje automático de DevOps es MLOps. Hace posible que los desarrolladores colaboren y aceleren el desarrollo, la implementación, el escalado y el desarrollo del modelo de IA. [1]

MLOps se refiere al conjunto de métodos, prácticas y herramientas que se utilizan para optimizar y gestionar el ciclo de vida del aprendizaje automático (ML) de un extremo a otro, desde el desarrollo y la capacitación hasta la implementación y el monitoreo. A continuación se ofrece una descripción general de los métodos clave de MLOps [1]:

- Control de versiones: utilice sistemas de control de versiones para gestionar código, datos y artefactos de modelo. Este método ayuda a rastrear cambios, colaborar eficazmente y garantizar la reproducibilidad.
- Integración continua (CI) e implementación continua (CD): implemente canalizaciones de CI/CD para automatizar las pruebas, la creación y la implementación de modelos de aprendizaje automático. Este método acelera la implementación del modelo y garantiza
consistencia.
-  Registro de modelos: mantener un registro de modelos para catalogar y gestionar diferentes versiones de modelos de ML, junto con metadatos y métricas de rendimiento.
-  Pruebas automatizadas: desarrolle pruebas automatizadas para código, validación de datos y evaluación de modelos para garantizar la corrección y solidez del modelo.
-  Monitoreo del modelo: monitoree continuamente los modelos implementados para detectar problemas. Configure alertas y respuestas automáticas cuando
surgen problemas.
-  Reentrenamiento del modelo: programar reentrenamiento periódico del modelo utilizar datos nuevos para garantizar que los modelos sigan siendo precisos y relevantes a lo largo del tiempo.

### Microsoft Azure DevOps

Para herramientas de automatización basadas en scripts, Microsoft Azure DevOps es un motor de automatización potente, multiplataforma y confiable. La creación, prueba e implementación de aplicaciones nativas de la nube y/o no nativas de la nube es posible gracias a
Azure DevOps.[1]

Para crear software, los desarrolladores, administradores de proyectos y contribuyentes trabajan juntos en un entorno colaborativo respaldado por Microsoft Azure DevOps. Permite a las empresas desarrollar y mejorar productos más rápidamente de lo que podrían hacerlo usando métodos convencionales de desarrollo de software.[1]

Microsoft Azure DevOps proporciona funcionalidad integrada al que se puede acceder a través del navegador web o cliente IDE. Se utiliza uno o más de los siguientes servicios dependiendo de las necesidades del negocio [1]:

Azure Boards: para planificar, monitorear y discutir el trabajo entre los equipos. Definir y actualizar problemas.
- Azure Repos: para acceder a un número infinito de repositorios personales de git para nuestro proyecto.
- Microsoft Azure Pipelines: para combinar CI/CD canales para probar y construir el código.
- Planes de prueba de Microsoft Azure: ofrece una variedad de herramientas sólidas que todo el equipo puede utilizar para avanzar en la calidad y el trabajo en equipo en todo el proceso de desarrollo.
- Microsoft Azure Artifacts: para gestionar paquetes completamente integrados en los canales de CI/CD.

Mientras describimos cómo implementar los fundamentos de CI/CD en esta sección, nos concentramos en Microsoft Azure Repos y Azure Pipelines, como se muestra en la Figura:

<img width="418" alt="image" src="https://github.com/psalazar211/RecPatrones_Inv-Corta3/assets/104046146/dc7b26ae-5b58-40ca-9c37-576824757cec">

Esta arquitectura explica cómo podemos usar Microsoft Azure DevOps y Azure Machine Learning para construir integración continua (CI), entrega continua (CD) y reutilización de tuberías para una aplicación de IA. Esta solución se basa en los siguientes tres canales:

- Canalización de compilación de Azure DevOps: lanza una canalización de Azure Machine Learning actualizada después de compilar el código y
ejecutando un conjunto de pruebas. Esta canalización de compilación se compone de código.
calidad, pruebas unitarias y pruebas de datos.

-  Canalización de reentrenamiento: el reentrenamiento se puede activar según un cronograma o cuando haya nuevos datos disponibles llamando al punto final REST del canal publicado en el paso anterior.

-  Canal de implementación: este canal se divide en dos entornos, puesta en escena y producción.

### Amazon SageMaker
Amazon SageMaker es un servicio de aprendizaje automático completamente organizado. Los científicos y desarrolladores de datos pueden
Cree y entrene modelos de aprendizaje automático de forma rápida y sin esfuerzo con SageMaker, luego impleméntelos inmediatamente en
un entorno compartido que está listo para la producción. Ofrece una instancia de cuaderno de escritura Jupyter incorporada para acceder rápidamente a diversas fuentes de datos para su procesamiento y análisis, eliminando la necesidad de administrar servidores. Además, ofrece métodos populares de aprendizaje automático que se han mejorado para entornos dinámicos con conjuntos de datos excepcionalmente grandes. SageMaker ofrece alternativas de capacitación adaptables y escalables
con soporte nativo para marcos y algoritmos únicos. Inicie un modelo con unos pocos clics desde SageMaker Studio o la consola SageMaker para implementarlo de forma segura y
entorno flexible.[1]

La descripción general del proceso MLOps en AWS se muestra en lacsiguiente figura [1]:

<img width="400" alt="image" src="https://github.com/psalazar211/RecPatrones_Inv-Corta3/assets/104046146/91dda0ff-2fb0-4b6c-a35a-154abcafc5f8">

###  Google Vertex AI
Auto ML y AI Platform se combinan en la única API, biblioteca cliente e interfaz de usuario de Google Vertex AI. Si bien la capacitación en AI Platform le permite ejecutar
código de entrenamiento personalizado, Auto ML le permite entrenar modelos en conjuntos de datos de imágenes, tablas, texto y vídeo sin escribir ningún
código. Vertex AI ofrece capacitación automática de aprendizaje automático y personalización. La formación como posibilidades. Cualquiera que sea la opción que elijas
capacitación, puede guardar modelos, implementarlos y solicitar predicciones con Vertex AI.[1]

Vertex AI se puede utilizar para controlar los pasos posteriores del flujo de trabajo [1]:
- Crear un conjunto de datos y cargar datos.
- Entrenamiento de un modelo ML sobre los datos:
• Entrenar el modelo
• Evaluar la precisión del modelo.
• Ajustar hiperparámetros (solo entrenamiento personalizado).
• Descargue y almacene el modelo en Vertex AI.
- Implementar el modelo entrenado para servir las predicciones en un
punto final.
- Envía solicitudes de predicción al punto final.
- Especificar una distribución de tráfico de predicción en el punto final.
- Gestión de modelos y puntos de acceso.

## Hadoop-Sparks

La dificultad para procesar big data proviene de no solo el gran volumen de estos datos, sino también muchas tareas que caracterizan los datos RS, que son la adquisición de datos, preprocesamiento, almacenamiento, procesamiento, análisis e interpretación. En la literatura se proponen muchos marcos para abordar estos problemas. Entre estos marcos, enumeramos dos populares herramientas llamadas Hadoop y Spark.

### Hadoop
Hadoop MapReduce es un marco de programación de código abierto que se utiliza para el procesamiento de grandes conjuntos de datos estructurados y no estructurados que se almacenan en HDFS (Hadoop Distributed File System) en un entorno informático distribuido.El ecosistema Apache Hadoop se basa en varios módulos que son Hadoop Kernel, MapReduce, HDFS, Yarn, Apache Hive, Zookeeper y muchos otros.[2]
Apache Hadoop se compone básicamente de dos componentes principales: Mapreduce y HDFS [2].
A continuación se proporciona una breve descripción de estos dos componentes.
• MapReduce es un modelo de programación que se construyó a partir de modelos encontrados en el campo de la programación funcional y la computación distribuida. Las tareas en MapReduce se desglosan en tres partes: mapa, reducción y controlador. Están organizados en pares de clave y valor. Los mapeadores emiten pares de claves y valores y los reductores los reciben, trabajan en ellos y producen el resultado final. Las aplicaciones que usan MapReduce leen los datos usando la función de mapa (en
en forma de pares clave y valor) y producen una salida también en forma de pares (clave y valor). Este tipo de datos se adapta muy bien al entorno distribuido.
Luego, la función de reducción toma los pares generados y produce los resultados finales. Los pares generalmente están ordenados de acuerdo con las teclas cuando se ingresa a la función de reducción. La lógica reductora funcionaría entonces en cada grupo clave; en este caso, resumiría los valores de cada clave y produciría el resultado final.
La siguiente Figura describe la representación funcional del mapear y reducir funciones. [2]

<img width="277" alt="image" src="https://github.com/psalazar211/RecPatrones_Inv-Corta3/assets/104046146/48355412-2799-42d7-a316-08c722a1bc80">


- HDFS es responsable del almacenamiento de archivos. Fue diseñado y desarrollado para manejar archivos grandes de manera eficiente.. Es un sistema de archivos distribuido diseñado para funcionar en un grupo. El objetivo principal del uso de HDFS es facilitar la almacenamiento de archivos grandes dividiéndolos en bloques y distribuirlos en múltiples nodos de forma redundante. [2]

Hadoop MapReduce almacena y procesa datos en una arquitectura distribuida; para lograr este objetivo, Hadoop implementa un modelo maestro y esclavo. Los demonios namenode y jobtracker son demonios maestros, mientras que los demonios datanode y tasktracker son demonios esclavos en la siguiente figura:

<img width="268" alt="image" src="https://github.com/psalazar211/RecPatrones_Inv-Corta3/assets/104046146/133ae425-67ed-4b9a-a4c4-dc6b5b6ae5a0">


Apache hadoopconsta de los siguientes demonios:
• Namenode
• Secondary namenode
• Jobtracker
• Datanode
• Tasktracker

Apache Spark es una potente plataforma de código abierto para grandes procesamiento de datos. Se considera una plataforma multipropósito que
se caracteriza por su flexibilidad, escalabilidad y rapidez. Además, se considera un marco de computación paralelo común de código abierto que tiene las ventajas de MapReduce. Spark está pensado para ejecutarse sobre Hadoop y puede ser una alternativa al mapa de lotes tradicional y los modelos reducidos. Además, Spark está bien adaptado para procesos iterativos, consultas rápidas y procesamiento de datos en tiempo real.[2]

Spark integra cuatro bibliotecas principales[2]:
• SQL para consultas de datos grandes y estructurados.
• MLlib que contiene los principales algoritmos de aprendizaje y métodos estadísticos.
• GraphX ​​para procesamiento de gráficos y redes.
• Spark Streaming para procesar datos en streaming.

Apache Spark se caracteriza por un conjunto de algoritmos eficientes de aprendizaje automático y bibliotecas de álgebra lineal mejoradas. Se agrega un motor optimizado en Spark para admitir gráficos generales de ejecución. Spark cubre una amplia gama de cargas de trabajo, incluidas consultas interactivas, procesamiento por lotes
aplicaciones, algoritmos iterativos y streaming. Además, al utilizar el marco Spark, se reduce la carga de gestión que supone mantener herramientas independientes. De hecho, integra el concepto de RDD (Resilient Distributed Dataset). Esquemáticamente, cada partición de datos permanece en la memoria de su servidor informático entre dos iteraciones mientras gestiona los principios de tolerancia a fallos.[2] Los comandos específicos de Spark se ejecutan en Java, Scala, y algunos en Python.
La siguiente Figura muestra la arquitectura de Apache Spark:

<img width="264" alt="image" src="https://github.com/psalazar211/RecPatrones_Inv-Corta3/assets/104046146/f75e28bb-40cf-4464-bcae-0111a14d9902">

Los RDD son el núcleo de las funcionalidades de Spark. son un conjunto de registros o sujetos de un tipo específico, particionados o distribuidos en varios nodos del clúster. Si un nodo se ve afectado por un fallo de hardware o de red. La mesa resiliente se reconstruye automáticamente en otros nodos y la tarea se completa. La propiedad principal de los Spark RDD es la capacidad de almacenarlos en la memoria de cada nodo. Esto ahorra una gran cantidad de acceso al disco, que es el bloqueo principal, en términos de tiempo de computación, cuando se ejecutan algoritmos iterativos. Otra especificidad de Spark es las variables de difusión. Estas variables son de solo lectura y están definidas desde el nodo maestro, y son conocidos y guardados en la memoria de todos los demás nodos. Un acumulador es un caso especial de
variables de difusión. Sin embargo, no es una variable de sólo lectura. Cada versión local puede ser incrementada por cada nodo mientras el nodo maestro tiene acceso a la acumulación global.[2]

En la table describe muchas diferencias entre Apache Spark y Hadoop MapReduce[2]:

| --- | Hadoop |   Spark |
| --- | --- | --- |
| Arquitectura  | Hadoop almacena y procesa datos en un almacenamiento externo. |Spark almacena y procesa datos en la memoria interna.|
| Rendimiento |    Hadoop procesa los datos por lotes. |Spark procesa los datos en tiempo real.|
|  Costo |Hadoop es económico.| En comparación, Spark es más caro.  |
|  Escalabilidad |Hadoop se puede escalar fácilmente si se agregan más nodos.| En comparación, Spark supone un reto mayor. |
|  Machine learning |Hadoop se integra con bibliotecas externas para proporcionar capacidades de machine learning. | Spark cuenta con bibliotecas de machine learning integradas.|
|Seguridad | Hadoop cuenta con características de seguridad sólidas, cifrado de almacenamiento y control de acceso. |Spark cuenta con una seguridad básica. El departamento de TI depende de que establezca un entorno operativo seguro para la implementación de Spark. |

# Bibliografía
1. W. E. Moutaouakal and K. Baïna, "Comparative Experimentation of MLOps Power on Microsoft Azure, Amazon Web Services, and Google Cloud Platform," 2023 IEEE 6th International Conference on Cloud Computing and Artificial Intelligence: Technologies and Applications (CloudTech), Marrakech, Morocco, 2023, pp. 1-8, doi: 10.1109/CloudTech58737.2023.10366138. keywords: {Training;Productivity;Cloud computing;DevOps;Web services;Machine learning;Transforms;MLOps;production;automation;Cloud;Azure;AWS;GCP;experimentation;benchmark},

