# DetectorSesgo
# PROYECTO DE DETECCIÓN DE SESGO TEXTUAL
## Introducción
Un sesgo textual es un forma de influenciar implícita o explícita en un texto, que puede llegar a manipular la opinion del lector al presentar la información. Este sesgo puede aparecer mayormente en titulares, redacciones periodísticas, publicaciones en redes sociales.
En este proyecto se aplico técnicas de aprendizaje automático y procesamiento de lenguaje natural (NLP).

## Problema que se pretende resolver

En la actualidad, donde el mundo esta lleno de medios digitales y redes sociales, la desinformación se propaga facilmente. Las noticias falsas pueden generar caos social, formar creencias falsas, influir en la calidad de las decisiones colectivas e individuales o incluso poner en peligro la salud pública. Detectarlas manualmente es difícil y propenso a cometerse errores humanos. 

## Objetivo del proyecto

El objetivo principal de este proyecto es entrenar un modelo de clasificación de texto que permita detectar si una noticia es verdadera o falsa, a apartir del contenido textual de la misma. 

- Clasificar noticias como falsas o verdaderas.
- Evaluar el rendimiento mendiante métricas.
- Probar con ejemplos de noticias reales para observar el comportamiento del modelo.

## Tecnologías utilizadas

- **Python**: Lengiaje de programación principal, para procesas datos, entrenar el modelo y evaluar los resultados.
- **Transformers (de Hugging Face)**: Biblioteca especializada en modelos de lenguaje preentrenados (como BERT), facilita el usos de modelos de NPL.
- **Scikit-learn**: Librería de machine learning.
- **Pandas**: Librería para manipulación y análisis de datos.
- **PyTorch**:Framework de deep learning.
- **BERT (`bert-base-uncased`)**: Modelo de lenguaje de tipo Transformer desarrollado por Google.
- **Google Colab**: Entorno gratuito en la nube.

## Resultados

- **Clasificación de noticias**: Obtener predicciones confiables que permitan distinguir entre las noticias falsas y verdaderas.
- **Contrarrestar la desinformación**: Contribuir a reducir la propagación de información manipulada o falsa en los entornos digitales y medios sociales.

## Conclusión

Este proyecto aborda un problemo critico en la era digital, la desinformación. Utilizando modelos de lenguaje como BERT y tecnicas de aprendizaje automatico. Este proyecto busca ser de utilidad para lectores, investigadores, periodistas o plataformas que buscan proteger la integridad de la información en la era digital.

