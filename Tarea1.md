Estimad@s,

La actividad de Apriori que comenzaron ayer es considerada como la Tarea 1 del curso.

# Formato de entrega: 
zip o rar mediante cuestionario habilitado del Siding.
# Deadline: 
martes 30 de agosto a las 14:00

# Input:
Archivo de texto* con separador*, en cada línea una transacción. 
Ejemplo:
```
i1,i2,i4
i3,i2,i1,i5
i1,i2
i1,i4,i6,i9,i10
```

1.* Especificar cómo entregar el path del archivo de input.

2.** El separador puede estar (o ser solicitado como input) en una variable del programa.

3.*** Debe ser posible asignar una variable con el soporte mínimo con el que correrá el algoritmo.


# Output: 
Debe contar con todas las reglas de asociación para un soporte, confianza y lift dado dado. Y cumplir con el siguiente formato:
Ejemplo:
```
A;B;support;confidence;lift
i1,i2;i3;.8;.7;.8
i1;i3;.8;.8;.9

```
Donde los items están ordenados ascendentemente.
Además, debe ser posible pedir el output ordenado por cada una de las tres medidas mencionadas anteriormente.
Como buena práctica y para facilitar la corrección deben adjuntar un *README* (.txt, .md, etc.) con instrucciones sobre el software.


# Corrección: 
Dentro de los criterios de corrección se revisará que el algoritmo cumpla con cada uno de los pasos señalados y que forman parte de Apriori, además de la correctitud de output. Y todas las correcciones anteriormente mencionadas.

# Tip: 
Recuerden que siempre es más eficiente trabajar con ints que con strings, sobre todo si harán comparaciones.

# Recepción de dudas: 
Tema habilitado en el Foro. Por favor revisen periódicamente estos comentarios.

Saludos!
bs
