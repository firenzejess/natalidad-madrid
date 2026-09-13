# Análisis de la natalidad en la Comunidad de Madrid (1985-2024)

Proyecto de análisis de datos sobre la evolución de la natalidad en la Comunidad de Madrid, desarrollado como portfolio para la candidatura a **Administrativos/as - Tramitación de Ayudas a la Natalidad** (Tragsatec / Comunidad de Madrid).

## Contexto

La Comunidad de Madrid gestiona, a través de Tragsatec, la tramitación de la **Ayuda económica a la natalidad**: 500 €/mes durante 24 meses, dirigida a gestantes y madres o padres con hijos menores de 24 meses, con requisitos de edad (hasta 30 años), empadronamiento (mínimo 5 de los últimos 10 años en la Comunidad de Madrid) y renta (hasta 30.000 €/año individual o 36.200 €/año conjunta).

Este proyecto explora la evolución de la natalidad en la región durante las últimas cuatro décadas, con el objetivo de entender mejor el contexto demográfico en el que se enmarca esta ayuda: cómo ha cambiado el número de nacimientos, el perfil de edad de las madres, su distribución geográfica y su origen.

## Objetivos

- Analizar la evolución de la tasa de natalidad y de la edad media de la madre en la Comunidad de Madrid entre 1985 y 2024.
- Identificar los municipios con mayor número de nacimientos de madres jóvenes (perfil que se ajusta a los requisitos de edad de la ayuda).
- Estudiar el peso y la evolución de los nacimientos de madres de origen extranjero en la región.
- Aportar un contexto basado en datos que ayude a comprender mejor la población destinataria de este tipo de ayudas.

## Fuentes de datos

Instituto de Estadística de la Comunidad de Madrid — [datos.comunidad.madrid](https://datos.comunidad.madrid) (grupo Demografía):

- **Indicadores de natalidad y fecundidad** (1985-2024, Comunidad de Madrid)
- **Nacidos vivos por grupo de edad y nacionalidad de la madre. Municipios** (1995-2024, por municipio)
- **Nacidos vivos por nacionalidad de la madre: Total** (1995-2024, Comunidad de Madrid)

## Estructura del repositorio

```
natalidad-madrid-portfolio/
├── EDA_Natalidad_Madrid.ipynb                     Análisis exploratorio en Python
├── indicadores-de-natalidad-y-fecundidad.csv       Dataset 1
├── nacidos-vivos-de-madres-residentes-...          Dataset 2 (municipios)
├── nacidos-vivos-de-madres-residentes-...           Dataset 3 (nacionalidad)
├── Natalidad_Madrid.pbix                           Informe interactivo en Power BI
├── Analisis_natalidad_Madrid_diseño.pptx           Presentación final
└── README.md
```

## Herramientas

- **Python** (pandas, seaborn, matplotlib) — limpieza y exploración de datos
- **Power BI** — construcción del informe visual interactivo

## Resultados principales

- La natalidad en la Comunidad de Madrid está en mínimos históricos, tras dos ciclos de subida y bajada ligados a la evolución económica y migratoria.
- La maternidad se retrasa de forma constante: la edad media de la madre ha subido casi 5 años desde 1985.
- Los nacimientos de madres jóvenes (≤29 años) se concentran en Madrid capital y en municipios del sur y este metropolitano.
- Más de una cuarta parte de los nacimientos corresponden a madres extranjeras, con predominio del origen americano.

## Autora

**Jessica Hernández** — Septiembre 2026
