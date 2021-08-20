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

Sensor de detección de detección mediante un aptámero dirigado a un marcado específico basado en un cristal líquido nemático (4-ciano-4'-
pentilbifenilo [5CB]). Consiste en Monocapas autoensambladas de cloruro de dimetiloctadecil [3 (trimetoxisilil) propil] amonio (DMOAP) 
inmovilizadas en un portaobjeto de vidrio que  que mantienen las moléculas de cristal líquido (LC) en
una orientación homeotrópica. Se utiliza el glutaraldehído  para inmovilizar el aptámero sobre la
superficie de los  portaobjetos de vidrio.

La unión específica del aptámero y el marcador específico interrumpe la orientación homeotrópica del cristal líquido, induciendo así un
cambio en la orientación de homeotrópico a una alineación aleatoria. Este cambio de orientación se puede convertir y visualizar
simplemente como una transición de una imagen cristal liquido óptica oscura a una imagen más brillante bajo un microscopio óptico
polarizado (POM), lo que permite la detección del marcador.


## Resultados


<img src="Marcadores tumorales.png" width=450>

<img src="Aptámeros.png" width=600>

Existen 4 tipos de cáncer de mamá  en donde se pueden expresar o no los marcadores del receptor de estógeno (ER) y del receptor
de factor de crecimiento epidérmico 2(HER2)y algunos tratamientos seran efectivos o no, por lo tanto, es importante detectar el
tipo de cáncer que esta presentando el paciente.

<img src="Tipos de cáncer.png" width=600>

```

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
 
```
 
Por otra parte se han estudiado a la nucleolina y HER2, que forman un complejo, como biomarcadores para la formación de tumores y la
progresión del cáncer de mamá, por lo que se propone usar el aptámero AS1411, dirigido a la nucleolina, en conjunto con el aptámero H2,
para saber si un tratamiento de cancer de mamá está teniendo efecto en el paciente. Es decir, si se observan una gran cantidad de
cristales líquidos en el microscopio, el tratamiento no está teniendo efecto.

Por último también se propone usar el sensor para la detección de una predisposición al cáncer de mama. Se ha estudiado a la proteína
MUC1 como un biomarcador de la metástasis del cáncer de mamá, es decir, un tumor maligno, por lo que se propone usar el aptámero MUC1.
Si hay poca detección quiere decir que el cáncer está en etapas tempranas mientras que si hay mucha detección quiere decir que el cáncer
ya está avanzado.

Como control positivo se propone usar el aptámero para el gen BRCA1, ya que está presente en todas las células y por lo tanto siempre
será positivo.


## Conclusión

Hemos propuesto el desarollo de un sensor de marcadores tumorales a base del cristal líquido 5CB y de aptámeros para detectar:
* La predisposición que tiene un paciente al cáncer de mama.
* El tipo de cancer de mamá
* El feceto del tratamiento sobre la progresión del cáncer de mama.


## Referencias
