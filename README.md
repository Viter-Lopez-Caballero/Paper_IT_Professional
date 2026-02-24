# Dataset de Imágenes Reales de Cultivos de Maíz para Detección de Plagas

---

## Descripción general

Este repositorio contiene un **dataset de 2,500 imágenes reales de cultivos de maíz**, diseñado para el **entrenamiento, validación y evaluación de modelos de Machine Learning y Deep Learning enfocados en la detección automática de plagas en entornos agrícolas reales**.

El conjunto de datos está **balanceado**, e incluye:

-  **1,250 imágenes de cultivos de maíz sanos**
-  **1,250 imágenes de cultivos de maíz afectados por plagas**

Este balance permite reducir sesgos durante el entrenamiento y mejorar el desempeño de los modelos predictivos.

---

##  Área geográfica de adquisición

Las imágenes fueron capturadas directamente en **parcelas agrícolas reales** ubicadas en el estado de Morelos, México, específicamente en los municipios de:

- Jojutla  
- Emiliano Zapata  
- Tlaltizapán  

Estas regiones representan zonas agrícolas activas y relevantes para la producción de maíz en México.

---

##  Método de adquisición

Las imágenes fueron adquiridas utilizando múltiples plataformas de captura, simulando condiciones reales de monitoreo agrícola:

- Dispositivos móviles (captura a nivel de cultivo)
- Vehículo Aéreo No Tripulado (UAV / dron) (captura aérea)

Esto permitió obtener imágenes con:

- Diferentes alturas
- Diversos ángulos de captura
- Variabilidad en la resolución espacial

---

## Etiquetado de datos

Todas las imágenes fueron **etiquetadas manualmente**, clasificándolas en dos categorías:

| Clase | Descripción |
|------|-------------|
| Sano | Cultivos sin evidencia visible de plagas |
| Plaga | Cultivos con daño visible causado por plagas |

El proceso de etiquetado fue realizado mediante inspección visual directa, garantizando la calidad del dataset.

---

## Condiciones reales de campo

El dataset incluye variabilidad natural presente en entornos agrícolas reales, como:

- Variaciones en iluminación
- Diferentes ángulos de captura
- Fondos complejos
- Oclusiones parciales
- Diferentes etapas de crecimiento del cultivo

Estas características hacen que el dataset sea adecuado para desarrollar **modelos robustos y aplicables en escenarios reales**.

---

## Características del dataset

| Característica | Valor |
|---|---|
| Total de imágenes | 2,500 |
| Número de clases | 2 |
| Dataset balanceado | Sí |
| Tipo de imágenes | RGB |
| Entorno | Campo abierto |
| Etiquetado | Manual |
| Plataformas | Smartphone y UAV |

---

## Aplicaciones

Este dataset puede utilizarse para:

- Clasificación de imágenes
- Detección de plagas
- Agricultura de precisión
- Computer Vision
- Deep Learning
- Transfer Learning
- Redes Neuronales Convolucionales (CNN)
- Sistemas de monitoreo agrícola inteligente

---

## Frameworks compatibles

Este dataset es compatible con:

- TensorFlow
- PyTorch
- Keras
- Scikit-learn
- OpenCV

---

## Estructura sugerida del dataset

```
dataset/
│
├── train/
│   ├── sano/
│   └── plaga/
│
├── validation/
│   ├── sano/
│   └── plaga/
│
└── test/
    ├── sano/
    └── plaga/
```

---

## Objetivo

Este dataset fue creado para apoyar el desarrollo de soluciones basadas en Inteligencia Artificial para la **detección temprana de plagas en cultivos de maíz**, contribuyendo a la agricultura de precisión y la seguridad alimentaria.

---

## Uso académico

Este dataset puede ser utilizado para:

- Investigación científica
- Desarrollo de tesis
- Publicaciones académicas
- Proyectos de aprendizaje automático

---

## Contacto

Si utiliza este dataset en su investigación, por favor considere citar este repositorio.

Autor: **Vitervo López Caballero**, **Andrea Sánchez Ruíz**, **Antonio Juan Capistran Abundez**

Institución: Centro Nacional de Investigación y Desarrollo Tecnológico (CENIDET)

México

---

## Keywords

maize, corn, pest detection, agriculture, deep learning, computer vision, UAV, drone, dataset, precision agriculture, artificial intelligence

---

## Licencia

Este dataset es de uso académico.

---

## Agradecimientos

A los productores agrícolas del estado de Morelos por permitir la adquisición de las imágenes.



