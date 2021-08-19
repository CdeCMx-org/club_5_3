# Oncosensor para la detección del cáncer de mama

## Introducción

Hablemos del Cáncer de mama, pero no solo de él sino de la gran problemática que representa entre las mujeres mexicanas y en todo el mundo
tan solo el decir que es el tumor más frecuente entre las mujeres en México nos da una idea a todo lo que esto representa, la primer causa
de muerte entre mujeres por cáncer, puesto que cada dos horas una mujer muere por esta causa en México, pero, a todo esto ¿Qué es el cáncer
de mama? entendemos como cáncer de mama al tumor maligno que se origina en las células de la mama, dando por concepto  tumor maligno al
grupo de células que crecen de manera desordenada e independiente, que tiende a invadir los tejidos que lo rodean, así como órganos distantes
(metástasis) dando por hecho que el cáncer de mama no solo acepta a mujeres sino también a hombres.

Las mujeres diagnosticadas con cáncer de mama en etapas iniciales, si reciben tratamiento, tienen un buen pronóstico, con tasas de
supervivencia a 5 años del 80% al 90 %, lamentablemente, en muchos de los países en América Latina y el Caribe las mujeres son diagnosticadas
con cáncer de mama en etapas tardías.El cáncer de mama es el tipo de cáncer más común y la segunda causa de muerte por cáncer entre las mujeres
de América. Cada año se producen en esta región más de 462,000 casos nuevos y casi 100,000 muertes por cáncer de mama. Si tuvieramos un mejor
método para la deteccion de cancer de mama el numero de casos y muertes se podría  reducir en hasta un 70%.

### Crsitales líquidos

Los cristales líquidos son materiales que poseen propiedades intermedias: pueden fluir como un líquido pero también poseen orden
orientacional de corto alcance como los sólidos cristalinos. 

#### ¿Qué es el orden oriental?

Las sustancias que forman cristales líquidos están formadas por moléculas con una forma alargada o de disco de esta
manera pueden tener sus centros de gravedad posicionados al azar (desorden posicional) pero mantener su orientación en una dirección
determinada (orden orientacional) y es esto lo que crea la estructura ordenada de un cristal líquido.
Los cristales líquidos, en función de sus propiedades, pueden utilizarse para diferentes fines. Por ejemplo, aquellos que reflejan
luz de diferente color según sea la temperatura se utilizan en termómetros o detectores de tumores.


## Metodología

Sensor de detección de detección de niveles altos de HER2 mediante aptámero ( anti-HER2) basado en Cristal líquido nemático (4-ciano-4'-
pentilbifenilo [5CB]). Consiste en Monocapas autoensambladas de cloruro de dimetiloctadecil [3 (trimetoxisilil) propil] amonio (DMOAP) 
inmovilizadas en portaobjetos de vidrio sostienen las largas cadenas de alquilo que mantienen las moléculas de cristal líquido (LC) en
una orientación homeotrópica. El glutaraldehído (GA) se utiliza como reticulante para inmovilizar el aptámero ( anti-HER2) sobre la
superficie de los  portaobjetos de vidrio.

La unión específica del aptámero H2 (anti-HER2) y HER2 interrumpe la orientación homeotrópica del cristal líquido, induciendo así un
cambio en la orientación de homeotrópico a una alineación aleatoria. Este cambio de orientación se puede convertir y visualizar
simplemente como una transición de una imagen cristal liquido óptica oscura a una imagen más brillante bajo un microscopio óptico
polarizado (POM), lo que permite la detección de H2.


## Resultados

Existen 4 subtipos de cáncer de mamá que ayudan a tomar decisiones sobre que tratamientos son los más adecuados:
Grupo 1 - Luminal A: Tumores que son positivos para el receptor de estrógeno (ER) y negativos para el receptor del factor de crecimiento epidérmico 2 (HER2). Pueden beneficiarse de tratamientos hormonales y de quimioterapia.
Grupo 2 - Luminal B: Tumores que son positivos para el receptor de estrógeno (ER) y positivos para el receptor del factor de crecimiento epidérmico 2 (HER2). Pueden beneficiarse de tratamientos hormonales, de quimioterapia y de tratamiento dirigido a HER2.
Grupo 3 - HER2+: Tumores que son negativos para el receptor de estrógeno (ER) y positivos para el receptor del factor de crecimiento epidérmico 2 (HER2). Pueden beneficiarse de quimioterapia y de tratamiento dirigido a HER2.
Grupo 4 - Basal: Tumores que son negativos para el receptor de estrógeno (ER) y negativos para el receptor del factor de crecimiento epidérmico 2 (HER2). Pueden beneficiarse de quimioterapia.
Para saber que tipo de cáncer de mama se está presentando, en el sensor de cristal líquido se usarán los aptámeros H2 y ERaptD4, que están dirigidos a las proteínas HER2 y ER, respectivamente, para decidir el tratamiento del paciente.

er=input("ER:")
her=input("HER2:")
if er=="+" and her=="-":
 print("Cáncer tipo Luminal A. Se puede aplicar quimioterapia y tratamientos hormonales.")
elif er=="+" and her=="+":
 print("Cáncer tipo Luminal B. Se puede aplicar quimioterapia, tratamientos hormonales y dirigidos a HER2.")
elif er=="-" and her=="+":
 print("Cáncer tipo HER2+. Se puede aplicar tratamientos dirigidos a HER2.")
elif er=="-" and her=="-":
 print("Cáncer tipo basal. Se puede aplicar quimioterapia.")

## Conclusión
