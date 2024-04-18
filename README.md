# <h1 align="center"> Análisis y segmentación de clientes mediante la metodología RFM  </h1>

El Mercado es una tienda especializada en productos alimenticios importados, y se encuentra en un entorno altamente competitivo con cambios significativos en las preferencias de los consumidores, busca mantener y aumentar sus ingresos mediante una mejor comprensión de sus clientes y estrategias de marketing personalizadas. La estrategia adoptada implica analizar las ventas y segmentar la base de clientes utilizando la metodología RFM (Recency, Frequency, Monetary Value) para tomar decisiones estratégicas basadas en datos.

## Objetivo del proyecto

A través de esta segmentación, se busca lograr los siguientes objetivos:

▪️ Mejor Comprensión de la Base de Clientes: Identificar quiénes son los clientes más valiosos, cuáles son sus patrones de compra y qué factores influyen en su lealtad hacia la marca.

▪️ Personalización de Estrategias de Marketing y Retención: Utilizar los insights obtenidos de la segmentación RFM para diseñar estrategias de marketing y retención más efectivas y personalizadas. Esto incluye adaptar ofertas promocionales, programas de fidelización y comunicaciones de marketing según las necesidades y comportamientos específicos de cada grupo de clientes.

▪️ Toma de Decisiones Estratégicas Basadas en Datos: Utilizar la información derivada de la segmentación RFM para tomar decisiones estratégicas informadas, como ajustar inventarios, optimizar la distribución de productos y asignar recursos de manera más eficiente para maximizar los ingresos y la retención de clientes.

## Insumos

El conjunto de datos está disponible para descargar en este enlace 'https://bit.ly/445mkxS'

## Herramientas que se usaron para el análisis

### Herramientas:

▪️ Google Sheets 

▪️ Google Slides

▪️ Looker Studio

### Lenguajes:

▪️ En este proyecto se utilizó solamente las fórmulas de Google Sheets

## ¿Cuál fue el proceso de trabajo?

| **Procesar y preparar la base de datos**  | **Análisis exploratorio** | **Técnica de análisis** |
|---|---|---|
| ▪️ Dataset con tres tablas en Google Sheets | ▪️ Agrupar datos según variables categóricas | ▪️ Creación de las categorías de clientes según los cuartiles de las variables utilizando la fórmula IFS |
| ▪️ Identificar nulos utilizando COUNTBLANK | ▪️ Visualizar las variables categóricas |
| ▪️ Identificar duplicados a través de las herramientas de Google Sheets| ▪️ Aplicar fórmula de cuartiles para dividir clientes en grupos en referencia al RFM | 
| ▪️ Identificar registros que no son relevantes para el propósito del análisis | 
| ▪️ Unión de tablas utilizando VLOOKUP |
| ▪️ Creación de nuevas variables utilizando MONTH, YEAR, SUM | 

## Chequea este proyecto en Google Sheets

▪️ Aquí 'https://bit.ly/3xPbIqG'

## Segmentación | Dashboard en Looker Studio

![Segmentación](https://raw.githubusercontent.com/MayteLlerena/Segmentacion/main/Dashboard%20-%20Segmentaci%C3%B3n%20de%20clientes%20mediante%20la%20metodolog%C3%ADa%20RFM.png)


