# Etiquetado de entidades, relaciones, correferencias y vinculación semántica (NER, RE, Coreference & NEL)

Este proyecto presenta la anotación semántica manual de un breve texto biográfico sobre el científico español Severo Ochoa mediante la herramienta de etiquetado de datos *Label Studio*. 

En su desarrollo se han realizado las siguientes tareas de Procesamiento del Lenguaje Natural (PLN): 

a)	Se han identificado y clasificado las entidades nombradas, *Named Entity Recognition* (NER).  

b)	Se han establecido relaciones entre esas entidades.

c)	Las entidades reconocidas se han vinculado (*Named Entity Linking, NEL*) con sus correspondientes entradas en DBpedia . 

d)	Se ha realizado un análisis de correferencias, con el objetivo de reflejar redes semánticas intratextuales.

e)	Se han diseñado tripletas estructuradas de la forma sujeto-predicado-objeto con el fin de codificarlas en lenguaje *Resource Description Framework* (RDF). 

De ese modo, a través de un grafo, se han reflejado visualmente las conexiones entre las entidades identificadas mediante las relaciones establecidas, al tiempo que se ha representado sintéticamente la biografía del científico español.
