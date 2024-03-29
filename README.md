# Proyecto EUROSAT Dataset

Este proyecto utiliza un conjunto de datos basado en EUROSAT, un conjunto de
imágenes satelitales de alta resolución que representa diez clases de uso de la
tierra. Hemos preprocesado y dividido este conjunto de datos en un conjunto de
entrenamiento y un conjunto de prueba, con una división del 90% para
entrenamiento y 10% para pruebas.

## Descripción del Dataset

### EUROSAT Dataset

EUROSAT es un conjunto de datos que contiene 27000 imágenes satelitales de 10
clases de uso de la tierra en diferentes condiciones atmosféricas y estaciones
del año. Las clases incluyen: agricultura, bosque, hielo, etc. Para obtener más
información sobre el dataset EUROSAT, puedes visitar
[el sitio web oficial de EUROSAT](https://github.com/phelber/EuroSAT).

### Estructura del Dataset

Nuestro conjunto de datos, derivado de EUROSAT, está organizado de la siguiente
manera:

eurosat-dataset/<br> ├── train/<br> │ ├── AnnualCrop/<br> │ │ ├──
AnnualCrop_1.jpg<br> │ │ ├── AnnualCrop_2.jpg<br> │ │ └── ...<br> │ ├──
Forest/<br> │ │ ├── Forest_1.jpg<br> │ │ ├── Forest_2.jpg<br> │ │ └── ...<br> │
└── ...<br> └── test/<br> ├── AnnualCrop/<br> │ ├── AnnualCrop_2401.jpg<br> │
├── AnnualCrop_2402.jpg<br> │ └── ...<br> ├── Forest/<br> │ ├──
Forest_2401.jpg<br> │ ├── Forest_2402.jpg<br> │ └── ...<br> └── ...<br>

## División del Dataset

Hemos dividido el dataset en un conjunto de entrenamiento y un conjunto de
prueba para facilitar el desarrollo y la evaluación de modelos de aprendizaje
automático. El conjunto de entrenamiento contiene el 80% de las imágenes,
mientras que el conjunto de prueba contiene el 20% restante.

## Uso del Dataset

Este dataset puede ser utilizado para diversas aplicaciones, incluyendo:

- Entrenamiento y evaluación de modelos de clasificación de imágenes.
- Investigaciones sobre el cambio en el uso de la tierra a lo largo del tiempo.
- Desarrollo de algoritmos de procesamiento de imágenes satelitales.
- Experimentación con técnicas de aumento de datos para mejorar la precisión del
  modelo.

## Contribución

Si encuentras problemas con el dataset o deseas contribuir con mejoras, por
favor abre un issue o una solicitud de pull en este repositorio.

## Licencia

Este dataset está disponible bajo la licencia
[especificada en el dataset original EUROSAT](https://github.com/phelber/EuroSAT).

## Contacto

Si tienes preguntas adicionales o necesitas ayuda, no dudes en ponerte en
contacto con nosotros en [carlos.gaubert1801@alumnos.ubiobio.cl].

¡Gracias por utilizar el dataset EUROSAT! Esperamos que sea de gran utilidad en
tus proyectos de investigación y desarrollo.
‣慤慴敳⵴略潲慳⵴ⴹ਱