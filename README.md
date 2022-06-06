# Prac2-Visualizaci-n-de-datos
Repositorio documental de la práctica 2 de la asignatura Visualización de datos del master en ciencia de datos de la UOC

Para la práctica de la asignatura Visualización de datos, he seleccionado como temática el empleo por sexo en Europa. La información está disponible en la web oficial de la comisión europea.  
FUENTES:
https://ec.europa.eu/eurostat/web/lfs/data/database?p_p_id=NavTreeportletprod_WAR_NavTreeportletprod_INSTANCE_IFjhoVbmPFHt&p_p_lifecycle=0&p_p_state=normal&p_p_mode=view

### Desempleo en Europa por edad, nivel educativo y sexo.  
Entre las personas desempleadas figuran las personas de 15 a 74 años sin trabajo durante la semana de referencia, que actualmente están disponibles para trabajar y que están buscando trabajo activamente en las últimas cuatro semanas o que ya han encontrado un empleo para comenzar en los próximos tres meses. Periodo de datos 2009 a 2021.
https://ec.europa.eu/eurostat/web/lfs/data/database
metadatos (https://ec.europa.eu/eurostat/cache/metadata/en/lfsi_esms.htm)

Se complementa con otras bases de datos que tratan las políticas de trabajo implantadas en europa, proyección del mercado de trabajo hasta el 2060 por países, y resultado de la encuesta de condiciones de trabajo del año 2010.

### Participantes en las medidas de política del mercado de trabajo, por tipo de acción.  
Las medidas de política del mercado laboral se refieren a intervenciones públicas en el mercado de trabajo en las que la actividad principal de los participantes no está relacionada con la búsqueda de empleo y en las que la participación suele dar lugar a un cambio en la situación del mercado laboral. Las medidas de PMP abarcan principalmente las intervenciones que proporcionan apoyo temporal a los grupos desfavorecidos en el mercado laboral (desempleados, empleados en situación de riesgo y personas inactivas). Las medidas de PMP se clasifican por tipo de acción y abarcan las siguientes categorías: formación, rotación y reparto de puestos de trabajo, incentivos al empleo, apoyo al empleo y rehabilitación, creación directa de empleo e incentivos para la puesta en marcha. Los participantes en las medidas de PMD se presentan aquí como existencias medias anuales, es decir, el número medio de personas que participan en una intervención en cualquier momento del año. El stock medio anual también puede interpretarse como el número de personas-año de participación en una intervención.
https://data.europa.eu/data/datasets/55x3na5heuwamjpmwulna?locale=es
metadatos (https://ec.europa.eu/employment_social/employment_analysis/lmp/lmp_esms.htm).

### Participación en las políticas de activación del mercado laboral por sexo.  
Las medidas de política del mercado laboral se refieren a intervenciones públicas en el mercado de trabajo en las que la actividad principal de los participantes no está relacionada con la búsqueda de empleo y en las que la participación suele dar lugar a un cambio en la situación del mercado laboral. Las medidas de PMP abarcan principalmente las intervenciones que proporcionan apoyo temporal a los grupos desfavorecidos en el mercado laboral (desempleados, empleados en situación de riesgo y personas inactivas). Las medidas de PMP se clasifican por tipo de acción y abarcan las siguientes categorías: formación, rotación y reparto de puestos de trabajo, incentivos al empleo, apoyo al empleo y rehabilitación, creación directa de empleo e incentivos para la puesta en marcha. Los datos sobre los participantes en las medidas de PMP se definen como el número de participantes en las medidas de activación regulares (categorías 2 a 7 de la LMP) dividido por el número de personas que desean trabajar.
https://data.europa.eu/data/datasets/585k0himwitjgrrqwg4w?locale=es
metadatos (https://ec.europa.eu/employment_social/employment_analysis/lmp/lmp_esms.htm)

### UDP — Empleo total por regiones metropolitanas, 2000-2060 (JRC LUISA Escenario de referencia 2016).   
Datos históricos (observaciones) y proyecciones (modelados) del empleo total por región metropolitana (unit:employees). Los datos regionales históricos se extrajeron de la base de datos en línea de EUROSTAT y se calcularon los datos que faltaban para completar la serie histórica. Los datos de las proyecciones se calcularon suponiendo un escenario de tendencia en el que las tasas de crecimiento del sector regional anteriores convergen linealmente con las tasas de crecimiento del sector nacional en 2035, y a partir de 2035, cada sector crece al mismo ritmo en todas las regiones de cada país. Finalmente, las proyecciones se reescalaron para respetar los totales de los países de las proyecciones de referencia de la DG ECFIN.
https://data.europa.eu/data/datasets/jrc-luisa-udp-emptrend-reference-2016?locale=es   

 1. Considero es un tema de actualidad, y con grandes posibilidades para visualización. Se busca la evolución del desempleo en Europa, a lo largo de un periodo, sobre distintas variables relativas al desempleo por razón de sexo, políticas  ocupación, educación, descapacidad, edad, nivel educativo, autoempleo, etc. La serie temporal abarca desde 2009 a 2021.

2. La información se encuentra muy actualizada, pues la serie temporal alcanza hasta el Q4 del 2021. La fuente es muy fiable, pues procede del data hub de la comisión europea. Por último, indicar que se ha tenido en consideración la variable sexo, para incorporarla como filtro de la visualización.

3. La información es de tipo categórico y numérico. Existen valores ausentes que habrá de depurar previo a la visualización. Según que ficheros, el número de filas puede llegar hasta 372.995 observaciones.

4. Desde la página de Eurostat, pueden consultarse visualizaciones sobre esos datos, que en mi opinión, son ampliamente mejorables. Mi intención es combinar los diferentes ficheros, y construir visualizaciones con mayor visibilidad en el que enfrentar diferentes variables, entorno a la evolución del desempleo en Europa.

5. Me he decidido por estos conjuntos de datos, para preparar una visualización con la que dar respuesta a las siguiente cuestiones;
- ¿Se discrimina de igual modo el empleo por sexo, edad o nivel educativo en todos los países de Europa?.
- ¿Qué perfil de persona tiene más facilidad para el autoempleo?.
- ¿Las políticas puestas en marcha en Europa, para mejorar el empleo, han tenido efecto por igual en los direntes segmentos de población?.
