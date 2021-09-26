DESCRIPCIÓN DEL CÓDIGO IMPLEMENTADO:

En el siguiente código escrito en un Notebook de Jupyter, "Clasificadores_flujos_de_datos.ipynb", se hace una implementación de tres algoritmos para CLASIFICACIÓN DE FLUJOS DE DATOS.
Se trata de los algoritmos siguientes:
• Clasificador por clase previa.
• Clasificador por clase mayoritaria.
• Clasificador media más cercana.

Se implementa cada uno de los clasificadores en una clase, la cual hereda de `BaseSKMObject` y `ClassifierMixin`, que son clases base para todos los estimadores en Scikit-Multiflow (adjunto su código en el fichero "Scikit-Multiflow GitHub Base class.pdf").

Además se realiza una prueba del funcionamiento de cada uno de dichos clasificadores mediante el empleo de dos funciones, `prueba_clasificador()` y `prueba_evaluacion_clasificador()`, cuyo código también se proporciona.

NOTA: Para el clasificador de media más cercana, el cálculo de la probabilidad de que una instancia pertenezca a cada una de las clases se realiza según lo indicado en el siguiente fichero adjunto "Cálculo Probab Clasific Media más Cercana - Héctor J.pdf".

NOTA: Todo el código, clases y métodos están convenientemente comentados y explicadas en su funcionamiento.

