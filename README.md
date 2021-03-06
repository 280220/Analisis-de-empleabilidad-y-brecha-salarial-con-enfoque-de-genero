# Haciendo-visible-lo-invisible: Análisis de empleabilidad y brecha salarial con enfoque de género

## Introducción

Proyecto finalista entregado de parte del equipo "Ironwomen" (Guadalupe Moreno, Marian Aguilera y Anna Heuberger) en el marco del "Desafío DataMéxico: Datos con Perspectiva de Género" organizado por DataMéxico (https://datamexico.org/) por encargo de la Secretaría de Economía en México.

Esta segunda edición del desafío de análisis de datos tiene como objetivo promover el uso y consulta de DataMéxico entre las comunidades de científicas de datos, tecnólogas y hacedoras de políticas públicas, contribuir al cierre de la brecha de análisis de datos con perspectiva de género y buscar que los proyectos y datos tengan incidencia en las decisiones de política pública en los sectores público, privado y social.

## Objetivo

Según el Global Gender Gap Report del Foro Económico Mundial (2020) aún hay una brecha de género global promedio de 31.4%, se estima puede tomar 100 años en cerrarse.

¿Cuál sería la estimación hacia el futuro para México? Ayudándonos a determinar el objetivo del proyecto: “Haciendo visible lo invisible: Análisis de empleabilidad y brecha salarial en México” para hacer visible la situación de empleabilidad y de brecha salarial actual, desde distintos ángulos a través de los datos disponibles, con la finalidad de
que se generen herramientas adecuadas de política pública para mejorar la situación de las mujeres.

## Metodología

Las herramientas utilizadas para el desarrollo de este proyecto fueron diversas. Para la obtención de los datos se utilizó la API de Data Mexico. Para la visualización se utilizó Power BI. La limpieza y procesamiento de los datos y predicciones se realizaron en Python, utilizando Jupyter Notebook.

Se trabajó con los datos de la Encuesta Nacional de Ocupación y Empleo (ENOE) reportados desde 2010 hasta el 2020, la representatividad de esta encuesta es de nivel estatal.

## Producto del proyecto

A fin de visibilizar nuestro análisis de datos de empleabilidad y brecha salarial, elaboramos un dashboard interactivo y público en Power BI que se puede consultar bajo el siguiente link:

https://app.powerbi.com/view?r=eyJrIjoiNzJlNWE3M2ItZGRkMS00NWY3LWFlOWYtN2Q1YjUxNmM0NzI4IiwidCI6IjA0OTI0YjZmLWQ4ZGMtNDlkMS1hOThmLTM5NWQ3NjYxZDBlZSJ9

Esta es una herramienta que ayuda a generar evidencia actual e histórica ya que en este reporte se incluyeron las visualizaciones del último trimestre del 2020 y en el se pueden observar las tendencias de cada uno de los trimestres desde 2010. Se puede obtener información sobre la brecha salarial desde distintas perspectivas que abordan las ocupaciones, la escolaridad, la segregación por estado mexicano y el comportamiento hacia el futuro.

## Fuente de datos utilizados

Encuesta Nacional de Ocupación y Empleo (ENOE). Cubo de datos de DataMexico
https://api.datamexico.org/ui/?cube=imss&drilldowns%5B0%5D=Date+Month.Date.Month&measures%5B0%5D=Insured+People&measures%5B1%5D=Insured+Employm

## Referencias

Forbes (2020). Las 100 Mujeres Poderosas de México 2020, lista completa. Consultado en:
https://www.forbes.com.mx/mujeres-poderosas-mexico-2020-listas-revista-forbes/

World Economic Forum (2020). Global Gender Gap Report 2020. Consultado en:
http://www3.weforum.org/docs/WEF_GGGR_2020.pdf

Instituto Mexicano Para la Competitividad A.C. (2021). ¿CUÁLES SON LOS BENEFICIOS
ECONÓMICOS DE SUMAR A MÁS TRABAJADORAS? Consultado en:
https://imco.org.mx/cuales-son-los-beneficios-economicos-de-sumar-a-mas-trabajadoras/

Facebook (2021). Facebook Prophet: Forecasting at scale. Consultado en:
https://facebook.github.io/prophet/
