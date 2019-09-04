Introducción
TED es una organización sin fines de lucro dedicada a difundir ideas, generalmente en forma de conversaciones breves y contundentes. La organización nació en 1984 por iniciativa de Richard Saul Wurman y Harry Marks como una conferencia donde convergieron Tecnología, Entretenimiento y Diseño (de ahí las siglas TED). Actualmente, hay más de 3000 charlas TED disponibles para ver online, las cuales cubren una amplia variedad de temas, desde ciencia hasta negocios y asuntos globales.

Contamos con un dataset que contiene información sobre todas las charlas TED subidas al sitio web oficial hasta el 21 de septiembre de 2017. Entre las variables, se incluyen el número de visualizaciones, el número de comentarios, descripciones, oradores y título de cada disertación. El dataset es de tamaño pequeño, pero tiene algunas particularidades a las que deberán prestarle atención, principalmente la cantidad de información almacenada de forma textual, que será necesario procesar y codificar adecuadamente.

Objetivos (elegir uno y focalizarse en él):
● Entrenar y optimizar una red neuronal que se capaz de predecir la cantidad de visualizaciones que tendrá una charla en base a la información provista en el dataset.

● Entrenar y optimizar una red neuronal que se capaz de predecir la categoría de una charla en base a la información provista en el dataset.

Requisitos y material a entregar
La exploración, análisis y modelado de los datos deberán ser entregados en una Jupyter notebook que satisfaga los requerimientos del proyecto. La notebook deberá estar debidamente comentada. Además, los grupos deberán crear un repositorio para el proyecto en Github.

Para la presentación en clase se deben armar algunos slides no técnicos para exponer en no más de 20 minutos (PPT o Google Slides). La presentación debe constar de una introducción (planteo del problema, la pregunta, la descripción del dataset, etc.), un desarrollo de los análisis realizados (análisis descriptivo, análisis de correlaciones preliminares, visualizaciones preliminares) y una exposición de los principales resultados de los modelos y conclusiones.

Fecha de entrega
● El material deberá entregarse en la clase 13 del curso, día jueves 12 de septiembre.

Dataset
El dataset contiene información sobre todas las charlas TED subidas al sitio web oficial hasta el 21 de septiembre de 2017. Las variables que se incluyen son:

comments: el número de comentarios de primer nivel realizados en la charla
description: una descripción de lo que se habla
duration: la duración de la charla en segundos
event: el evento TED/TEDx en el que tuvo lugar la charla
film_date: el Unix timestamp de la fecha de filmación
languages: número de lenguajes disponibles de la charla
main_speaker: nombre del principal orador
name: nombre oficial de la charla TED
num_speaker: cantidad de oradores
published_date: el Unix timestamp de la fecha de publicación
ratings: un diccionario de las diversas calificaciones otorgadas a la charla (inspiradora, fascinante, asombrosa, etc.)
related_talks: una lista de diccionarios de charlas recomendadas para ver a continuación
speaker_occupation: la ocupación del principal orador
tags: temas asociados a la charla
title: título de la charla
url: link al video
views: cantidad de visualizaciones de la charla
¿Cómo empezar? Sugerencias
Agreguen toda otra información construida a partir de los datos originales (o incluso información externa, por ejemplo, las transcripciones de las charlas) que consideren relevante y útil para resolver los objetivos planteados.

El dataset fue publicado en la plataforma Kaggle, una suerte de red social de Data Scientists y practicantes de Machine Learning y Deep Learning. Aprovechen los kernels y discusiones del sitio, comenzar explorando los análisis que ya han hecho otras personas puede ser de mucha ayuda.

En la presentación de los resultados tengan en cuenta que es altamente probable que la audiencia no tenga un nivel técnico, así que mantengan el lenguaje en un nivel accesible.

En términos generales, recuerden las siguientes sugerencias:

● Escribir un pseudocódigo antes de empezar a codear. Suele ser muy útil para darle un esquema y una lógica generales al análisis.

● Leer la documentación de cualquier tecnología o herramienta de análisis que usen. A veces no hay tutoriales para todo y los documentos y las ayudas son fundamentales para entender el funcionamiento de las herramientas utilizadas.

● Documentar todos los pasos, transformaciones, comandos y análisis que realicen.
