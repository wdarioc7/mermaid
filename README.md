OBJETIVO GENERAL

Desarrollar un sistema basado en inteligencia artificial capaz de generar diagramas arquitectónicos en lenguaje Mermaid a partir de descripciones en lenguaje natural, y que a partir de dichos diagramas sea capaz de construir automáticamente arquitecturas para nubes públicas como AWS, Azure y GCP, generando los correspondientes archivos de infraestructura como código (IaC) en formato YAML, Bicep, Terraform u otros, listos para su despliegue.

OBJETIVOS ESPECÍFICOS

Diseñar e implementar un módulo de procesamiento de lenguaje natural que interprete instrucciones o requerimientos descriptivos y los convierta en diagramas en código Mermaid válidos y estructurados.

Construir un motor de análisis arquitectónico que tome el código Mermaid generado y lo transforme en un modelo estructurado de componentes, relaciones y dependencias técnicas.

Implementar generadores de plantillas de arquitectura para los principales proveedores de nube (AWS, Azure, GCP), adaptando el modelo arquitectónico a los servicios específicos de cada plataforma.

Automatizar la generación de archivos de infraestructura como código (IaC), incluyendo CloudFormation, Terraform, Bicep, ARM y demás formatos necesarios para desplegar los recursos en cada nube.

Desarrollar una interfaz web que permita a los usuarios ingresar descripciones, visualizar el código Mermaid generado y descargar los archivos IaC correspondientes.

Incorporar validaciones automáticas que verifiquen la coherencia del código generado, la sintaxis Mermaid y la validez de los archivos IaC antes de su descarga.

Diseñar el sistema con una arquitectura modular que facilite su ampliación, permitiendo agregar nuevos tipos de diagramas, servicios de nube o formatos de despliegue en el futuro.

ALCANCE DEL PROYECTO
Alcance incluido

Implementación de una interfaz web para ingresar requerimientos en lenguaje natural.

Generación automática de código Mermaid mediante un modelo de inteligencia artificial.

Conversión del código Mermaid en un modelo arquitectónico estructurado.

Mapeo del modelo arquitectónico a servicios y patrones de las nubes AWS, Azure y GCP.

Generación de archivos de infraestructura como código en los formatos compatibles de cada nube.

Descarga de los archivos generados por parte del usuario.

Validación básica de sintaxis, integridad y consistencia de los diagramas y plantillas generadas.

Diseño modular que permita la incorporación futura de otros proveedores o formatos IaC.

Fuera de alcance (inicial)

Despliegue automático de la infraestructura generada en la nube.

Generación de costos, cálculos financieros o estimaciones económicas de los recursos.

Integración con herramientas externas de diagrama como Draw.io, Lucidchart u otras.

Gestión completa de pipelines CI/CD, monitoreo o automatización de operaciones.

Pruebas de rendimiento, disponibilidad o análisis de carga sobre la infraestructura propuesta.
