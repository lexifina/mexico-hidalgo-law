# Hidalgo: law history in git

The law of the State of Hidalgo (Estado Libre y Soberano de Hidalgo, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-hid/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

143 ordenamientos with 1581 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO DE HIDALGO | 185 | as first published, then each reform: 4 October 1920 to 9 July 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE HIDALGO | 28 | as first published, then each reform: 1 December 1940 to 23 August 2025 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO LIBRE Y SOBERANO DE HIDALGO | 11 | as first published, then each reform: 4 December 1940 to 27 June 2017 |
| `codigo-de-procedimientos-familiares/` | CODIGO DE PROCEDIMIENTOS FAMILIARES PARA EL ESTADO DE HIDALGO | 5 | as first published, then each reform: 8 June 2007 to 11 July 2017 |
| `codigo-electoral/` | CODIGO ELECTORAL DEL ESTADO DE HIDALGO | 37 | as first published, then each reform: 25 December 2014 to 14 September 2026 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE HIDALGO | 36 | as first published, then each reform: 1 January 2001 to 1 January 2026 |
| `codigo-fiscal-municipal/` | CODIGO FISCAL MUNICIPAL PARA EL ESTADO DE HIDALGO | 15 | as first published, then each reform: 1 January 2012 to 28 July 2026 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE HIDALGO | 64 | as first published, then each reform: 9 July 1990 to 25 September 2026 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE HIDALGO | 55 | as first published, then each reform: 1 January 2008 to 19 September 2026 |
| `ley-de-adquisiciones-arrendamientos-y-servicios-del-sector-p/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y SERVICIOS DEL SECTOR PUBLICO DEL ESTADO DE HIDALGO | 9 | as first published, then each reform: 17 September 2015 to 18 December 2025 |
| `ley-de-albergues-privados-para-personas-adultas-mayores/` | LEY DE ALBERGUES PRIVADOS PARA PERSONAS ADULTAS MAYORES DEL ESTADO DE HIDALGO | 5 | as first published, then each reform: 3 September 2013 to 19 August 2023 |
| `ley-de-alianzas-productivas-de-inversion/` | LEY DE ALIANZAS PRODUCTIVAS DE INVERSION PARA EL ESTADO DE HIDALGO | 1 | as first published: 3 April 2018 |
| `ley-de-amnistia/` | LEY DE AMNISTIA PARA EL ESTADO DE HIDALGO | 1 | as first published: 21 July 2020 |
| `ley-de-archivos/` | LEY DE ARCHIVOS PARA EL ESTADO DE HIDALGO | 3 | as first published, then each reform: 18 December 2019 to 29 January 2025 |
| `ley-de-asentamientos-humanos-desarrollo-urbano-y-ordenamient/` | LEY DE ASENTAMIENTOS HUMANOS, DESARROLLO URBANO Y ORDENAMIENTO TERRITORIAL DEL ESTADO DE HIDALGO | 24 | as first published, then each reform: 18 September 2007 to 20 November 2025 |
| `ley-de-asistencia-social/` | LEY DE ASISTENCIA SOCIAL PARA EL ESTADO DE HIDALGO | 21 | as first published, then each reform: 31 July 2012 to 27 June 2026 |
| `ley-de-becas/` | LEY DE BECAS DEL ESTADO DE HIDALGO | 7 | as first published, then each reform: 23 April 2013 to 31 May 2024 |
| `ley-de-bienes/` | LEY DE BIENES DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 28 March 1991 to 1 January 2017 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 3 September 2013 to 1 January 2017 |
| `ley-de-control-vehicular/` | LEY DE CONTROL VEHICULAR PARA EL ESTADO DE HIDALGO | 14 | as first published, then each reform: 1 January 2014 to 1 January 2025 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL PARA EL ESTADO DE HIDALGO | 51 | as first published, then each reform: 1 January 1990 to 10 January 2026 |
| `ley-de-coordinacion-para-el-desarrollo-metropolitano/` | LEY DE COORDINACION PARA EL DESARROLLO METROPOLITANO DEL ESTADO DE HIDALGO | 5 | as first published, then each reform: 11 August 2009 to 20 January 2024 |
| `ley-de-cultura-fisica-deporte-y-recreacion/` | LEY DE CULTURA FISICA, DEPORTE Y RECREACION PARA EL ESTADO DE HIDALGO | 27 | as first published, then each reform: 1 March 2009 to 23 October 2026 |
| `ley-de-cultura-y-derechos-culturales/` | LEY DE CULTURA Y DERECHOS CULTURALES DEL ESTADO DE HIDALGO -- ANTES LEY DE CULTURA DEL ESTADO DE HIDALGO -- | 19 | as first published, then each reform: 1 August 2018 to 29 August 2026 |
| `ley-de-derechos-de-las-personas-jovenes/` | LEY DE DERECHOS DE LAS PERSONAS JOVENES DEL ESTADO DE HIDALGO | 5 | as first published, then each reform: 16 July 2024 to 9 July 2026 |
| `ley-de-derechos-humanos/` | LEY DE DERECHOS HUMANOS DEL ESTADO DE HIDALGO | 13 | as first published, then each reform: 6 December 2011 to 9 July 2026 |
| `ley-de-derechos-linguisticos/` | LEY DE DERECHOS LINGÜISTICOS DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 25 March 2014 to 16 July 2024 |
| `ley-de-derechos-y-cultura-indigena/` | LEY DE DERECHOS Y CULTURA INDIGENA PARA EL ESTADO DE HIDALGO | 9 | as first published, then each reform: 1 January 2011 to 29 August 2026 |
| `ley-de-desarrollo-agricola-sustentable/` | LEY DE DESARROLLO AGRICOLA SUSTENTABLE PARA EL ESTADO DE HIDALGO | 24 | as first published, then each reform: 8 August 2006 to 9 July 2026 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE HIDALGO | 13 | as first published, then each reform: 6 October 2006 to 16 January 2026 |
| `ley-de-desarrollo-pecuario/` | LEY DE DESARROLLO PECUARIO PARA EL ESTADO DE HIDALGO | 5 | as first published, then each reform: 4 July 2006 to 19 August 2023 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL DEL ESTADO DE HIDALGO | 22 | as first published, then each reform: 30 December 2006 to 23 October 2026 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA PARA EL ESTADO DE HIDALGO | 2 | as first published, then each reform: 19 June 2018 to 14 February 2023 |
| `ley-de-economia-social-y-solidaria/` | LEY DE ECONOMIA SOCIAL Y SOLIDARIA DEL ESTADO DE HIDALGO | 1 | as first published: 17 August 2024 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO HIDALGO | 54 | as first published, then each reform: 1 December 2020 to 29 August 2026 |
| `ley-de-educacion-superior/` | LEY DE EDUCACION SUPERIOR DEL ESTADO DE HIDALGO | 7 | as first published, then each reform: 4 August 2023 to 29 August 2026 |
| `ley-de-ejecucion-de-penas/` | LEY DE EJECUCION DE PENAS DEL ESTADO DE HIDALGO | 3 | as first published, then each reform: 16 June 1972 to 20 August 2010 |
| `ley-de-entidades-paraestatales/` | LEY DE ENTIDADES PARAESTATALES DEL ESTADO DE HIDALGO | 9 | as first published, then each reform: 30 July 2013 to 18 December 2025 |
| `ley-de-entrega-recepcion-de-los-recursos-publicos/` | LEY DE ENTREGA RECEPCION DE LOS RECURSOS PUBLICOS DEL ESTADO DE HIDALGO | 5 | as first published, then each reform: 13 October 2015 to 12 June 2026 |
| `ley-de-expropiacion-por-causa-de-utilidad-publica/` | LEY DE EXPROPIACION POR CAUSA DE UTILIDAD PUBLICA | 2 | as first published, then each reform: 4 May 1932 to 14 December 2010 |
| `ley-de-fiscalizacion-superior-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION SUPERIOR Y RENDICION DE CUENTAS DEL ESTADO DE HIDALGO | 7 | as first published, then each reform: 11 July 2017 to 9 July 2026 |
| `ley-de-fomento-al-desarrollo-energetico-sustentable/` | LEY DE FOMENTO AL DESARROLLO ENERGETICO SUSTENTABLE DEL ESTADO DE HIDALGO | 1 | as first published: 3 April 2018 |
| `ley-de-fomento-cooperativo/` | LEY DE FOMENTO COOPERATIVO PARA EL ESTADO DE HIDALGO | 5 | as first published, then each reform: 30 April 2013 to 7 August 2025 |
| `ley-de-fomento-para-la-lectura-y-el-libro/` | LEY DE FOMENTO PARA LA LECTURA Y EL LIBRO DEL ESTADO DE HIDALGO | 12 | as first published, then each reform: 28 August 2012 to 22 May 2026 |
| `ley-de-fomento-y-desarrollo-economico/` | LEY DE FOMENTO Y DESARROLLO ECONOMICO PARA EL ESTADO DE HIDALGO | 11 | as first published, then each reform: 1 January 2008 to 9 July 2026 |
| `ley-de-fomento-y-promocion-al-emprendimiento/` | LEY DE FOMENTO Y PROMOCION AL EMPRENDIMIENTO DEL ESTADO DE HIDALGO | 4 | as first published, then each reform: 15 December 2015 to 11 July 2025 |
| `ley-de-fomento-y-proteccion-a-la-zona-tipica-de-atotonilco-e/` | LEY DE FOMENTO Y PROTECCION A LA ZONA TIPICA DE ATOTONILCO EL CHICO, HIDALGO | 1 | as first published: 16 December 1961 |
| `ley-de-fomento-y-proteccion-del-maiz-nativo/` | LEY DE FOMENTO Y PROTECCION DEL MAIZ NATIVO DEL ESTADO DE HIDALGO | 1 | as first published: 22 October 2022 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE HIDALGO | 36 | as first published, then each reform: 1 January 2004 to 1 January 2026 |
| `ley-de-hacienda-para-los-municipios/` | LEY DE HACIENDA PARA LOS MUNICIPIOS DEL ESTADO DE HIDALGO | 17 | as first published, then each reform: 22 November 2011 to 1 January 2026 |
| `ley-de-humanidades-ciencias-tecnologias-e-innovacion/` | LEY DE HUMANIDADES, CIENCIAS, TECNOLOGIAS E INNOVACION DEL ESTADO DE HIDALGO | 4 | as first published, then each reform: 18 September 2024 to 7 August 2026 |
| `ley-de-imagen-urbana/` | LEY DE IMAGEN URBANA PARA EL ESTADO DE HIDALGO | 3 | as first published, then each reform: 6 October 2023 to 12 April 2025 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO LIBRE Y SOBERANO DE HIDALGO, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-acatlan-hidalgo-corresp/` | LEY DE INGRESOS PARA EL MUNICIPIO DE ACATLAN, HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 2 | as first published, then each reform: 1 January 2026 to 8 May 2026 |
| `ley-de-ingresos-para-el-municipio-de-acaxochitlan-hidalgo-co/` | LEY DE INGRESOS PARA EL MUNICIPIO DE ACAXOCHITLAN, HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-actopan-hidalgo-corresp/` | LEY DE INGRESOS PARA EL MUNICIPIO DE ACTOPAN, HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-agua-blanca-de-iturbide/` | LEY DE INGRESOS PARA EL MUNICIPIO DE AGUA BLANCA DE ITURBIDE, HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-ajacuba-hidalgo-corresp/` | LEY DE INGRESOS PARA EL MUNICIPIO DE AJACUBA, HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-alfajayucan-hidalgo-cor/` | LEY DE INGRESOS PARA EL MUNICIPIO DE ALFAJAYUCAN, HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-almoloya-hidalgo-corres/` | LEY DE INGRESOS PARA EL MUNICIPIO DE ALMOLOYA, HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | oldest version available: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-apan-hidalgo-correspond/` | LEY DE INGRESOS PARA EL MUNICIPIO DE APAN, HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-francisco-i-madero-hida/` | LEY DE INGRESOS PARA EL MUNICIPIO DE FRANCISCO I. MADERO HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-san-agustin-tlaxiaca-hi/` | LEY DE INGRESOS PARA EL MUNICIPIO DE SAN AGUSTIN TLAXIACA HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-san-bartolo-tutotepec-h/` | LEY DE INGRESOS PARA EL MUNICIPIO DE SAN BARTOLO TUTOTEPEC HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-san-felipe-orizatlan-hi/` | LEY DE INGRESOS PARA EL MUNICIPIO DE SAN FELIPE ORIZATLAN, HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-santiago-de-anaya-hidal/` | LEY DE INGRESOS PARA EL MUNICIPIO DE SANTIAGO DE ANAYA, HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-singuilucan-hidalgo-cor/` | LEY DE INGRESOS PARA EL MUNICIPIO DE SINGUILUCAN HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-tulancingo-de-bravo-hid/` | LEY DE INGRESOS PARA EL MUNICIPIO DE TULANCINGO DE BRAVO HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-villa-de-tezontepec-hid/` | LEY DE INGRESOS PARA EL MUNICIPIO DE VILLA DE TEZONTEPEC HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-yahualica-hidalgo-corre/` | LEY DE INGRESOS PARA EL MUNICIPIO DE YAHUALICA HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-zapotlan-de-juarez-hida/` | LEY DE INGRESOS PARA EL MUNICIPIO DE ZAPOTLAN DE JUAREZ HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-zempoala-hidalgo-corres/` | LEY DE INGRESOS PARA EL MUNICIPIO DE ZEMPOALA HIDALGO, CORRESPONDIENTE AL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-inscripciones-de-honor-para-el-reconocimiento-de-muje/` | LEY DE INSCRIPCIONES DE HONOR PARA EL RECONOCIMIENTO DE MUJERES HIDALGUENSES DESTACADAS | 1 | as first published: 25 July 2025 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores-antes-le/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES -- ANTES LEY DE LOS DERECHOS DE LOS ADULTOS MAYORES -- DEL ESTADO DE HIDALGO | 43 | as first published, then each reform: 13 April 2010 to 29 August 2026 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES PARA EL ESTADO DE HIDALGO | 66 | as first published, then each reform: 21 April 2015 to 23 October 2026 |
| `ley-de-los-trabajadores-al-servicio-de-los-gobiernos-estatal/` | LEY DE LOS TRABAJADORES AL SERVICIO DE LOS GOBIERNOS ESTATAL Y MUNICIPALES, ASI COMO DE LOS ORGANISMOS DESCENTRALIZADOS DEL ESTADO DE HIDALGO | 31 | as first published, then each reform: 1 January 1988 to 9 July 2026 |
| `ley-de-mecanismos-alternativos-de-solucion-de-controversias/` | LEY DE MECANISMOS ALTERNATIVOS DE SOLUCION DE CONTROVERSIAS PARA EL ESTADO DE HIDALGO | 4 | as first published, then each reform: 3 September 2013 to 18 September 2024 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA PARA EL ESTADO DE HIDALGO | 3 | as first published, then each reform: 18 April 2017 to 18 September 2024 |
| `ley-de-migrantes-hidalguenses-y-en-contexto-de-movilidad/` | LEY DE MIGRANTES HIDALGUENSES Y EN CONTEXTO DE MOVILIDAD | 10 | as first published, then each reform: 18 August 2020 to 28 July 2026 |
| `ley-de-mitigacion-y-adaptacion-ante-los-efectos-del-cambio-c/` | LEY DE MITIGACION Y ADAPTACION ANTE LOS EFECTOS DEL CAMBIO CLIMATICO PARA EL ESTADO DE HIDALGO | 12 | as first published, then each reform: 27 August 2013 to 29 August 2026 |
| `ley-de-movilidad-y-transporte/` | LEY DE MOVILIDAD Y TRANSPORTE PARA EL ESTADO DE HIDALGO | 22 | as first published, then each reform: 31 July 2018 to 23 October 2026 |
| `ley-de-obras-publicas/` | LEY DE OBRAS PUBLICAS DEL ESTADO DE HIDALGO | 1 | as first published: 12 August 2003 |
| `ley-de-obras-publicas-y-servicios-relacionados-con-las-misma/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON LAS MISMAS PARA EL ESTADO DE HIDALGO | 10 | as first published, then each reform: 26 March 2013 to 20 November 2025 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA PARA EL ESTADO DE HIDALGO | 3 | as first published, then each reform: 17 February 2015 to 31 March 2023 |
| `ley-de-pesca-y-acuacultura-sustentable/` | LEY DE PESCA Y ACUACULTURA SUSTENTABLE PARA EL ESTADO DE HIDALGO | 2 | as first published, then each reform: 11 August 2015 to 18 May 2024 |
| `ley-de-planeacion-y-prospectiva/` | LEY DE PLANEACION Y PROSPECTIVA DEL ESTADO DE HIDALGO | 9 | as first published, then each reform: 1 January 2017 to 8 May 2026 |
| `ley-de-poblacion/` | LEY DE POBLACION PARA EL ESTADO DE HIDALGO | 12 | as first published, then each reform: 4 July 2006 to 7 August 2026 |
| `ley-de-prestacion-de-servicios-para-la-atencion-cuidado-prot/` | LEY DE PRESTACION DE SERVICIOS PARA LA ATENCION, CUIDADO, PROTECCION Y DESARROLLO INTEGRAL INFANTIL DEL ESTADO DE HIDALGO | 6 | as first published, then each reform: 26 May 2015 to 29 August 2026 |
| `ley-de-prestamos-compensaciones-por-retiro-y-jubilaciones/` | LEY DE PRESTAMOS, COMPENSACIONES POR RETIRO Y JUBILACIONES | 2 | as first published, then each reform: 1 January 1957 to 17 January 1981 |
| `ley-de-presupuesto-y-contabilidad-gubernamental/` | LEY DE PRESUPUESTO Y CONTABILIDAD GUBERNAMENTAL DEL ESTADO DE HIDALGO | 11 | as first published, then each reform: 28 October 2014 to 1 January 2026 |
| `ley-de-prevencion-del-delito/` | LEY DE PREVENCION DEL DELITO PARA EL ESTADO DE HIDALGO | 5 | as first published, then each reform: 8 December 2009 to 18 September 2024 |
| `ley-de-prevencion-y-gestion-integral-de-residuos/` | LEY DE PREVENCION Y GESTION INTEGRAL DE RESIDUOS DEL ESTADO DE HIDALGO | 10 | as first published, then each reform: 25 January 2011 to 21 August 2024 |
| `ley-de-procesos-productivos-eficientes/` | LEY DE PROCESOS PRODUCTIVOS EFICIENTES DEL ESTADO DE HIDALGO | 3 | as first published, then each reform: 8 February 2011 to 18 September 2024 |
| `ley-de-propiedad-en-condominio-de-inmuebles/` | LEY DE PROPIEDAD EN CONDOMINIO DE INMUEBLES PARA EL ESTADO DE HIDALGO | 7 | as first published, then each reform: 28 August 2012 to 19 April 2024 |
| `ley-de-proteccion-a-denunciantes-y-testigos-de-hechos-de-cor/` | LEY DE PROTECCION A DENUNCIANTES Y TESTIGOS DE HECHOS DE CORRUPCION PARA EL ESTADO DE HIDALGO | 1 | as first published: 22 April 2021 |
| `ley-de-proteccion-a-personas-defensoras-de-derechos-humanos/` | LEY DE PROTECCION A PERSONAS DEFENSORAS DE DERECHOS HUMANOS Y SALVAGUARDA DE LOS DERECHOS PARA EL EJERCICIO DEL PERIODISMO EN EL ESTADO DE HIDALGO | 3 | as first published, then each reform: 28 August 2012 to 8 April 2026 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL PARA EL ESTADO DE HIDALGO | 18 | as first published, then each reform: 6 December 2011 to 7 October 2026 |
| `ley-de-proteccion-contra-los-efectos-nocivos-del-tabaco/` | LEY DE PROTECCION CONTRA LOS EFECTOS NOCIVOS DEL TABACO PARA EL ESTADO DE HIDALGO | 5 | as first published, then each reform: 8 June 2010 to 20 January 2024 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS PARA EL ESTADO DE HIDALGO | 5 | as first published, then each reform: 25 July 2017 to 7 October 2026 |
| `ley-de-proteccion-y-trato-digno-para-los-animales-en-el-esta/` | LEY DE PROTECCION Y TRATO DIGNO PARA LOS ANIMALES EN EL ESTADO DE HIDALGO | 21 | as first published, then each reform: 1 March 2005 to 29 August 2026 |
| `ley-de-proteccion-salvaguarda-y-explotacion-de-la-abeja/` | LEY DE PROTECCION, SALVAGUARDA Y EXPLOTACION DE LA ABEJA PARA EL ESTADO DE HIDALGO (ANTES: LEY APICOLA PARA EL ESTADO DE HIDALGO) | 5 | as first published, then each reform: 11 August 2015 to 18 September 2024 |
| `ley-de-regulacion-de-desarrollos-industriales/` | LEY DE REGULACION DE DESARROLLOS INDUSTRIALES DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 17 July 2014 to 27 December 2022 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE HIDALGO | 1 | as first published: 28 July 2022 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 10 August 2022 to 9 July 2026 |
| `ley-de-responsabilidades-de-los-servidores-publicos/` | LEY DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS | 16 | as first published, then each reform: 9 June 1984 to 14 December 2017 |
| `ley-de-revocacion-de-mandato/` | LEY DE REVOCACION DE MANDATO DEL ESTADO DE HIDALGO | 1 | as first published: 23 August 2023 |
| `ley-de-salud-mental-y-prevencion-del-suicidio/` | LEY DE SALUD MENTAL Y PREVENCION DEL SUICIDIO PARA EL ESTADO DE HIDALGO | 3 | as first published, then each reform: 23 August 2024 to 7 August 2026 |
| `ley-de-salud/` | LEY DE SALUD PARA EL ESTADO DE HIDALGO | 56 | as first published, then each reform: 31 August 2004 to 18 August 2026 |
| `ley-de-seguridad-privada/` | LEY DE SEGURIDAD PRIVADA PARA EL ESTADO DE HIDALGO | 2 | as first published, then each reform: 3 September 2013 to 30 March 2023 |
| `ley-de-seguridad-publica/` | LEY DE SEGURIDAD PUBLICA PARA EL ESTADO DE HIDALGO | 17 | as first published, then each reform: 18 November 2014 to 9 July 2026 |
| `ley-de-transito-y-seguridad-vial/` | LEY DE TRANSITO Y SEGURIDAD VIAL PARA EL ESTADO DE HIDALGO | 11 | as first published, then each reform: 21 July 2020 to 15 April 2026 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA PARA EL ESTADO DE HIDALGO | 8 | as first published, then each reform: 4 November 2016 to 7 October 2026 |
| `ley-de-turismo-sustentable/` | LEY DE TURISMO SUSTENTABLE DEL ESTADO DE HIDALGO | 32 | as first published, then each reform: 11 December 2012 to 23 October 2026 |
| `ley-de-victimas/` | LEY DE VICTIMAS PARA EL ESTADO DE HIDALGO | 4 | as first published, then each reform: 2 September 2021 to 18 August 2026 |
| `ley-de-vivienda/` | LEY DE VIVIENDA DEL ESTADO DE HIDALGO | 11 | as first published, then each reform: 19 July 2011 to 18 September 2024 |
| `ley-de-voluntad-anticipada/` | LEY DE VOLUNTAD ANTICIPADA PARA EL ESTADO DE HIDALGO | 3 | as first published, then each reform: 15 May 2011 to 16 August 2016 |
| `ley-del-centro-de-conciliacion-laboral/` | LEY DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE HIDALGO | 3 | as first published, then each reform: 16 May 2018 to 9 July 2026 |
| `ley-del-colegio-de-bachilleres/` | LEY DEL COLEGIO DE BACHILLERES DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 3 July 2007 to 5 July 2016 |
| `ley-del-ejercicio-profesional/` | LEY DEL EJERCICIO PROFESIONAL PARA EL ESTADO DE HIDALGO | 10 | as first published, then each reform: 1 January 2002 to 15 June 2024 |
| `ley-del-instituto-catastral/` | LEY DEL INSTITUTO CATASTRAL DEL ESTADO DE HIDALGO | 4 | as first published, then each reform: 26 February 2013 to 6 April 2015 |
| `ley-del-instituto-hidalguense-de-financiamiento-a-la-educaci/` | LEY DEL INSTITUTO HIDALGUENSE DE FINANCIAMIENTO A LA EDUCACION SUPERIOR DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 31 July 2012 to 18 November 2014 |
| `ley-del-instituto-hidalguense-de-las-mujeres/` | LEY DEL INSTITUTO HIDALGUENSE DE LAS MUJERES | 5 | as first published, then each reform: 1 January 2016 to 29 January 2025 |
| `ley-del-instituto-para-el-desarrollo-y-fortalecimiento-munic/` | LEY DEL INSTITUTO PARA EL DESARROLLO Y FORTALECIMIENTO MUNICIPAL DEL ESTADO DE HIDALGO | 4 | as first published, then each reform: 8 December 2011 to 9 July 2026 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE HIDALGO | 6 | as first published, then each reform: 24 July 2010 to 3 January 2027 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE HIDALGO | 4 | as first published, then each reform: 11 March 2008 to 20 April 2021 |
| `ley-del-registro-publico-de-la-propiedad/` | LEY DEL REGISTRO PUBLICO DE LA PROPIEDAD DEL ESTADO DE HIDALGO | 7 | as first published, then each reform: 21 April 2015 to 23 August 2025 |
| `ley-del-sistema-de-administracion-tributaria/` | LEY DEL SISTEMA DE ADMINISTRACION TRIBUTARIA DEL ESTADO DE HIDALGO | 4 | as first published, then each reform: 3 January 2014 to 6 April 2015 |
| `ley-del-sistema-estatal-anticorrupcion-de-hidalgo/` | LEY DEL SISTEMA ESTATAL ANTICORRUPCION DE HIDALGO | 3 | as first published, then each reform: 11 July 2017 to 18 September 2024 |
| `ley-del-tribunal-de-justicia-administrativa/` | LEY DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 11 July 2017 to 14 September 2021 |
| `ley-en-materia-de-desaparicion-de-personas/` | LEY EN MATERIA DE DESAPARICION DE PERSONAS PARA EL ESTADO DE HIDALGO | 2 | as first published, then each reform: 25 August 2021 to 14 July 2023 |
| `ley-estatal-de-agua-y-alcantarillado/` | LEY ESTATAL DE AGUA Y ALCANTARILLADO PARA EL ESTADO DE HIDALGO | 22 | as first published, then each reform: 31 December 1999 to 7 August 2026 |
| `ley-estatal-de-derechos/` | LEY ESTATAL DE DERECHOS DEL ESTADO DE HIDALGO | 13 | as first published, then each reform: 1 January 2016 to 28 February 2026 |
| `ley-estatal-de-fomento-y-fortalecimiento-a-las-acciones-de-l/` | LEY ESTATAL DE FOMENTO Y FORTALECIMIENTO A LAS ACCIONES DE LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL DEL ESTADO DE HIDALGO | 6 | as first published, then each reform: 21 January 2021 to 11 June 2025 |
| `ley-estatal-del-procedimiento-administrativo/` | LEY ESTATAL DEL PROCEDIMIENTO ADMINISTRATIVO | 4 | as first published, then each reform: 31 December 2002 to 22 October 2022 |
| `ley-integral-para-las-personas-con-discapacidad/` | LEY INTEGRAL PARA LAS PERSONAS CON DISCAPACIDAD DEL ESTADO DE HIDALGO | 22 | as first published, then each reform: 1 January 2011 to 23 October 2026 |
| `ley-organica-de-la-administracion-publica/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA PARA EL ESTADO DE HIDALGO | 5 | as first published, then each reform: 1 April 2023 to 7 October 2026 |
| `ley-organica-de-la-agencia-estatal-de-energia-de-hidalgo/` | LEY ORGANICA DE LA AGENCIA ESTATAL DE ENERGIA DE HIDALGO | 2 | as first published, then each reform: 3 April 2018 to 2 September 2021 |
| `ley-organica-de-la-universidad-autonoma/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 1 January 2016 to 10 October 2017 |
| `ley-organica-de-la-universidad-tecnologica-de-tula-tepeji/` | LEY ORGANICA DE LA UNIVERSIDAD TECNOLOGICA DE TULA-TEPEJI | 4 | as first published, then each reform: 23 September 2008 to 16 August 2016 |
| `ley-organica-del-colegio-de-estudios-cientificos-y-tecnologi/` | LEY ORGANICA DEL COLEGIO DE ESTUDIOS CIENTIFICOS Y TECNOLOGICOS DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 7 July 1992 to 1 June 2023 |
| `ley-organica-del-instituto-de-defensoria-publica/` | LEY ORGANICA DEL INSTITUTO DE DEFENSORIA PUBLICA DEL ESTADO DE HIDALGO | 3 | as first published, then each reform: 11 November 2014 to 18 August 2026 |
| `ley-organica-del-ministerio-publico/` | LEY ORGANICA DEL MINISTERIO PUBLICO DEL ESTADO DE HIDALGO | 10 | as first published, then each reform: 18 November 2014 to 9 July 2026 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE HIDALGO | 2 | as first published, then each reform: 10 May 2024 to 9 July 2026 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
