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


<img width="418" alt="image" src="https://github.com/psalazar211/RecPatrones_Inv-Corta3/assets/104046146/dc7b26ae-5b58-40ca-9c37-576824757cec">


# Bibliografía
1. W. E. Moutaouakal and K. Baïna, "Comparative Experimentation of MLOps Power on Microsoft Azure, Amazon Web Services, and Google Cloud Platform," 2023 IEEE 6th International Conference on Cloud Computing and Artificial Intelligence: Technologies and Applications (CloudTech), Marrakech, Morocco, 2023, pp. 1-8, doi: 10.1109/CloudTech58737.2023.10366138. keywords: {Training;Productivity;Cloud computing;DevOps;Web services;Machine learning;Transforms;MLOps;production;automation;Cloud;Azure;AWS;GCP;experimentation;benchmark},

