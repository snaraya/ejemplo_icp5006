# Elecciones en Chile: Participación ciudadana y democracia

## Introducción

Este proyecto realiza un análisis longitudinal de los resultados electorales en Chile, abarcando el periodo desde el retorno de la democracia hasta la actualidad. El objertivo es investigar las principales tendencias en la participación ciudadana y la evolución de las preferencias políticas, considerando tanto elecciones municipales como nacionales.

## Fuente de datos

Para el desarrollo de este proyecto, se utilizarán las siguientes fuentes de información:

-   **Servicio Electoral de Chile (SERVEL)**: El Servel proporciona datos abiertos sobre resultados de elecciones presidenciales, parlamentarias, municipales y de plebiscitos desde 1989. Incluye estadísticas de participación, padrones electorales y financiamiento de campañas.

-   **Biblioteca del Congreso Nacional (BCN)**: Reúne información histórica oficial desde 1989 en adelante, validada por el Tribunal Calificador de Elecciones (TRICEL).

-   **Encuesta CEP**: Ofrece una base de datos consolidada con más de 30 años de encuestas de opinión pública, útil para correlacionar resultados electorales con percepciones ciudadanas.

## Estructura del proyecto

El proyecto estará dividido en tres etapas que estarán contenidas en los siguientes enlaces:

1.  **Transformación y limpieza de bases de datos**: En esta primera etapa se busca **preparar los datos para el análisis**, garantizando consistencia y coherencia entre años, tipos de elección (municipales y nacionales) y formatos. Dado que las fuentes oficiales —como el Servel y la BCN— pueden tener estructuras diferentes, aquí se aplican técnicas de procesamiento de datos en R para depurar y unificar la información.
2.  **Análisis y modelamiento de los datos**: En esta etapa se realiza el **análisis longitudinal de patrones electorales** a lo largo del tiempo. Aquí se extraen estadísticas descriptivas, se modelan tendencias y se identifican relaciones relevantes entre variables (como participación, preferencias partidarias o abstención).
3.  **Visualización y comunicación de resultados**: En esta fase se presentan los resultados del análisis mediante **gráficos, mapas y dashboards** que faciliten la interpretación de tendencias y comparaciones entre períodos.
