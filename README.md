# 12 Proyectos entidades federativas
Contiene la información que reportan las entidades federativas, municipios y demarcaciones territoriales del Distrito Federal sobre los avances físicos y financieros de los programas y proyectos de inversión que llevan a cabo con recursos que les transfiere la Federación a través de aportaciones federales, subsidios y convenios

## ¿Dónde están los datos?
Dado que estos archivos son bastante grandes (+1 GB) los tendremos disponibles en memorias portátiles durante el datatón.

## ¿Qué campos contiene?
Siglas | Descripción 
------------ | -------------
FOLIO | Clave que la Secretaría de Hacienda y Crédito Público (SHCP) asigna de manera única a cada programa o proyecto de inversión registrado por los ejecutores del gasto de los gobiernos locales en el sistema a través del cual se da seguimiento al ejercicio, destino y resultados de los recursos que la Federación transfiere a los gobiernos locales - SFU - (para conocer la definición completa consultar en el buscador "Sistema de Formato Único" del glosario que se encuentra en el Portal de Transparencia Presupuestaria: http://www.transparenciapresupuestaria.gob.mx/es/PTP/Glosario). El folio es exclusivo para dar seguimiento a los proyectos dentro de dicho sistema, por lo que no puede ser utilizado para comparar proyectos con otros sistemas de la SHCP.
NOMBRE_PROYECTO | Nombre del proyecto registrado por los ejecutores del gasto de los gobiernos locales
NUMERO_PROYECTO | Número del proyecto que es registrado por los usuarios de captura al momento de dar de alta un nuevo programa o proyecto de inversión en el SFU, a través del cual dan seguimiento a los mismos. Dicho número es asignado de acuerdo con los registros internos de las dependencias ejecutoras, por lo que no necesariamente se relaciona con el folio asignado por la SHCP en el SFU.
ID_ENTIDAD_FEDERATIVA | Clave de la entidad federativa, de acuerdo con el catálogo de entidades federativas, municipios y localidades del Instituto Nacional de Estadística y Geografía (INEGI)
ENTIDAD | Nombre de la entidad federativa, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI
ID_MUNICIPIO | Clave del Municipio, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI
MUNICIPIO | Nombre del municipio, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI
ID_LOCALIDAD | Clave de localidad, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI
LOCALIDAD | Nombre de la localidad, de acuerdo con el catálogo de entidades federativas, municipios y localidades del INEGI
LATITUD | Coordenada geográfica en la que se ubica la localidad, de acuerdo con los catálogos del INEGI
LONGITUD | Coordenada geográfica en la que se ubica la localidad, de acuerdo con los catálogos del INEGI
AMBITO | Clasificación del INEGI para determinar si la localidad es rural (menos de 2,500 habitantes) o urbana (más de 2,500 habitantes)
ID_RECURSO | Clave de recurso: 1=Subsidios, 2= Aportaciones Federales; 3 = Convenios; 4=Fideicomisos
RECURSO | Identificador que permite conocer si el proyecto fue financiado a través de subsidios, Fondos de Aportaciones Federales, convenios o fideicomisos, los cuales constituyen los recursos que la Federación transfiere a los gobiernos locales para su ejecución. Se excluyen las participaciones dado que son recursos que se asignan a los gobiernos locales, en virtud de algunos de los ingresos que recauda la Federación, por lo que no cuentan con objetivos específicos definidos para su ejercicio y no deben ser reportados por los gobiernos locales a la Federación.
CLAVE_PROGRAMA_PRESUPUESTARIO | Clave con la cual se identifica a los programas presupuestarios federales. Está compuesta por 4 dígitos, el primero de los cuales señala la modalidad a la que pertenece el programa de acuerdo con sus características y los 3 dígitos restantes representan el número del programa presupuestario, el cual se asigna por las dependencias y entidades a partir del criterio de numeración consecutiva al interior de la modalidad de que se trate. Para mayor información sobre las modalidades que existen para los programas presupuestarios, se puede consultar el Anexo 2 del Manual de Programación y Presupuesto 2015: http://www.hacienda.gob.mx/EGRESOS/PEF/programacion/programacion_15/anexo_2_pyp2015.pdf
PROGRAMA_PRESUPUESTARIO | Nombre del programa presupuestario federal con el que se está financiando el programa o proyecto de inversión, de acuerdo con la estructura programática del PEF vigente. Por programa presupuestario se entiende a la categoría que permite organizar, en forma representativa y homogénea, las asignaciones de recursos de los programas federales y del gasto federalizado a cargo de los ejecutores del mismo, para el cumplimiento de sus objetivos y metas.
ID_RAMO | Clave del Ramo, de acuerdo con la estructura programática del PEF vigente
RAMO | Categoría administrativa a la que pertenece el programa presupuestario, de acuerdo con la estructura programática del PEF vigente
INSTITUCION_EJECUTORA | Ejecutores del gasto de los gobiernos locales, es decir, las dependencias, organismos o entidades de la entidad federativa, municipio o demarcación territorial del Distrito Federal que se encargarán de llevar a cabo el programa o proyecto de inversión
ID_CLASIFICACION | Clave que indica el sector al cual el programa o proyecto de inversión busca impactar de manera positiva:<br>0 = Otros Proyectos<br>1 = Salud<br>2 = Educación<br>3 = Transportes y vialidades<br>4 = Agua y saneamiento<br>5 = Urbanización<br>6 = Cultura y turismo<br>7 = Asistencia Social<br>8 = Deporte<br>9 = Seguridad<br>10 = Vivienda<br>11 = Comunicaciones
CLASIFICACION | Clasificación del programa o proyecto de inversión que realizan los ejecutores de los recursos para identificar categorías generales de atención, por ejemplo, educación, salud, seguridad, etc.
ID_TIPOPPI | Clave que indica el tipo de programa o proyecto de inversión, de acuerdo con la Guía de Criterios para el reporte del ejercicio, destino y resultados de los recursos federales transferidos:<br>0 = Sin tipo de proyecto o programa<br>1 = Proyecto de Inversión de Infraestructura Económica<br>2 = Proyecto de Inversión de Infraestructura Social<br>3 = Proyecto de Inversión de Infraestructura Gubernamental<br>4 = Proyecto de Inversión de Inmuebles<br>5 = Otros proyectos de Inversión<br>6 = Programa de Inversión de Adquisiciones<br>7 = Programa de Inversión de Mantenimiento<br>10 = Otros Programas de Inversión<br>11 = Programa de Estudios de Preinversión<br>Para mayor información, consultar la Guía de Criterios disponible en: http://transparenciapresupuestaria.gob.mx/work/models/PTP/Entidades_Federativas/SFU/Guia%20_de%20criterios%20_SFU%20VF_2.pdf
TIPOPPI | Nombre del tipo de programa o proyecto de inversión de acuerdo con la Guía de Criterios para el reporte del ejercicio, destino y resultados de los recursos federales transferidos, disponible en: http://transparenciapresupuestaria.gob.mx/work/models/PTP/Entidades_Federativas/SFU/Guia%20_de%20criterios%20_SFU%20VF_2.pdf
BENEFICIARIOS | Campo en donde los ejecutores del recursos describen los beneficios esperados del programa o proyecto de inversión.
INICIO | Fecha de inicio del programa o proyecto de inversión que es registrada por los ejecutores de los recursos al momento de dar de alta un programa o proyecto de inversión.
TERMINO | Fecha de término del programa o proyecto de inversión estimada por los ejecutores del gasto de los gobiernos locales.
DIRECCION | Dirección completa en la que, de acuerdo con el ejecutor del recurso, tendrá lugar el programa o proyecto de inversión.
ID_CONCURRENCIA_DE_RECURSOS | Clave que se utiliza para identificar si existen recursos de distintos órdenes de gobierno además del federal (estatal o municipal), éstas pueden ser:<br>Vacías = No se capturó información<br>0 = No existe concurrencia de recursos<br>1 = Coparticipación Federal-Estatal<br>2 = Coparticipación Federal-Estatal-Municipal<br>3 = Coparticipación Federal-Municipal
CONCURRENCIA | En caso de que el programa o proyecto de inversión no únicamente sea financiado con recursos federales sino que incluya recursos de los gobiernos locales, el ejecutor de los recursos deberá especificar qué tipo de concurrencia se utilizará para financiar el proyecto, de acuerdo a la clave de concurrencia de recursos: ID_CONCURRENCIA_DE_RECURSOS.
CICLO_RECURSO | Año en que los ejecutores del gasto de los gobiernos locales reportan que fue asignado el recurso federal
AUTORIZADO /1 | El campo hace referencia al momento contable "Aprobado", que es el momento contable que denota las asignaciones presupuestarias anuales comprometidas en el Presupuesto de Egresos correspondiente. De conformidad con la definición establecida en Normas y Metodología para la Determinación de los Momentos Contables de los Egresos de CONAC http://www.conac.gob.mx/es/CONAC/Normatividad_Vigente
MODIFICADO /1 | Momento contable que denota la asignación presupuestaria que resulta de incorporar, en su caso, las adecuaciones presupuestarias (incremento o disminución) al presupuesto aprobado o autorizado. En caso de no existir adecuaciones, la cantidad registrada es la misma que la autorizada.
MINISTRADO /2 | El campo hace referencia al momento contable "Recaudado", que es el momento contable que denota el cobro efectivo o por cualquier otro medio de pago de los recursos transferidos por la Federación a los gobiernos locales.
COMPROMETIDO /1 | Momento contable que denota la aprobación por la autoridad competente de un acto administrativo, u otro instrumento jurídico que formaliza una relación jurídica con terceros para la adquisición de bienes y servicios o ejecución de obras. En el caso de las obras a ejecutarse o de bienes y servicios a recibirse durante varios ejercicios, el compromiso será registrado durante cada ejercicio
DEVENGADO /1 | Momento contable que denota el reconocimiento de una obligación de pago a favor de terceros por la recepción de conformidad de bienes, servicios y obras oportunamente contratados; así como de las obligaciones que derivan de tratados, leyes, decretos, resoluciones y sentencias definitivas
EJERCIDO /1 | Momento contable que denota la emisión de una cuenta por liquidar certificada o documento equivalente debidamente aprobado por la autoridad competente
PAGADO /1 | Momento contable que refleja la cancelación total o parcial de las obligaciones de pago que se concreta mediante el desembolso de efectivo o cualquier otro medio de pago
AVANCE_FINANCIERO | Porcentaje de avance en la ejecución de los recursos respecto a los recursos modificados de los programas o proyectos de inversión, acumulado al cierre del actual trimestre
UNIDADMEDIDA | Forma de medición que permitirá dar seguimiento a los avances físicos del programa o proyecto de inversión
POBLACION_ANUAL | Población atendida por cada programa o proyecto de inversión, de acuerdo con el ejecutor del recurso
AVANCE_ESTIMADO_ANUAL | Meta estimada que registran los ejecutores del gasto sobre el avance físico al término del programa o proyecto de inversión.
AVANCE_FISICO | Avance en la construcción acumulado al cierre del actual trimestre de los programas o proyectos de inversión
ID_ESTATUS_FLUJO_VALIDACION | Clave del estatus del programa o proyecto de inversión registrado por algún ejecutor
ESTATUS_FLUJO_VALIDACION | Nombre del estatus en el flujo de validación con el que cuenta el sistema donde se hace el registro de la información del programa o proyecto de inversión (Registro: El proyecto se encuentra en ejecución y no se informó sobre el avance físico y financiero)
OBSER_FISICO_PER | Observaciones sobre el avance físico y financiero de los programas o proyectos de inversión realizadas por el ejecutor del proyecto o alguno de los participantes en el flujo de validación
KA_ESTATUS /3 | Clave que indica el estatus en el que se encuentra la ejecución del programa o proyecto de inversión:<br>1 = En Ejecución<br>2 = Terminado
"DESC_ESTATUS /3 | Descripción del estatus en el que se encuentra la ejecución del programa o proyecto de inversión:<br>1 = En Ejecución<br>2 = Terminado

## ¿Quién otorga el dataset?
Secretaría de Hacienda y Crédito Público

## Referencia
https://datos.gob.mx/busca/dataset/proyectos-entidades-federativas