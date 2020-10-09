# See What You Want to See: Visual User-Driven Approach for Hybrid Recommendation

En este *paper* escrito por Parra, Brusilovsky y Trattner, se muestra, principalmente,  una interfaz mediante la cual se realizan recomendaciones de lecturas académicas. Esta es una interfaz en la que al usuario se le entrega bastante control, ya que se le permite ir modificando y mezclando varios parámetros, para obtener una recomendación que él crea que pueda gustarle en ese momento.

La interfaz *SetFusion* muestra los resultados en forma de diagrama de Venn, en el que cada partición representa un parámetro distinto,el cual se puede ir ajustando. Esta visualización permite que el usuario sepa por qué le fue recomendado un ítem, lo que incrementa su percepción de transparencia en el sistema.

Hay una parte de la lectura que me pareció bastante explicativa, en la que se muestran los distintos elementos de la interfaz mediante las imágenes de estos. Aquí se listan las distintas partes de estos elementos, con una explicación para cada una. Esto permite al usuario tener un alto entendimiento acerca de la interfaz, ya que, a pesar de no estar usándola realmente, se puede imaginar perfectamente su funcionamiento, viendo las imágenes y relacionándolas a las explicaciones en el listado de *SetFusion Interface Interactions*.

Más adelante se explican los algoritmos utilizados para generar estas recomendaciones. El primero es *Content-base Recommendation* en el que se obtiene un perfil de usuario compuesto por palabras clave, obtenidas desde los títulos o *abstracts* de los *papers* que el usuario guardó desde conferencias pasadas. Me parece que esto definitivamente puede personalizar bien las recomendaciones, y que junto a los otros dos algoritmos de popularidad, se podrían lograr recomendaciones acordes a lo que los usuarios buscan. Esto, debido a que encuentro que la popularidad de un ítem puede reflejar fielmente su calidad, ya que, generalmente, la opinión de la mayoría tiene una enorme importancia, en especial cuando se trata de *papers* académicos, los que son leídos por gente muy experimentada en estos temas.

Finalmente, se habla sobre los estudios con usuarios que se realizaron en distintas conferencias. En resumen, se confirma que una interfaz visual que entregue cierto grado de control de elección al usuario, es bastante más llamativa que una no visual. Esto puede resultar evidente, sobre todo en campos o áreas en las que se mueve una enorme cantidad de expertos, por sobre el público común, ya que los usuarios no buscan solo entretención, sino que pretenden informarse con material de calidad sobre los temas que les interesen.