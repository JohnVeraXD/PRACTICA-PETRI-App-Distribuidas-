# PRACTICA-PETRI-App-Distribuidas-
PRACTICA PETRI 

Problema planteado: 

Diseño del prototipo de una fábrica en donde se simule la línea de proceso de producción de un producto de todas sus fases, que parta desde un inicio con la materia prima, sea procesado por las máquinas y que después de cierto tiempo determinado (el cual es el necesario para que la maquina transforme la materia prima en producto final) devuelva el producto final para ser empacado como pedido y que pueda ser enviado, es decir que haya cumplido con cada una de sus fases, cabe mencionar que el procedimiento se debe de realizar de forma lineal, de manera consecutiva, es decir que las actividades no se deben de realizar sin antes verificar que la materia prima haya pasado por cada una de las fases correspondientes de manera completa, de tal forma que se pueda verificar que el producto ha realizado el proceso de producción de manera completa y correcta. Para llegar a un producto terminado se necesitará de dos materias primas y un ensamblado. La línea de producción debe de verse de la siguiente manera: materia prima -> tarea 1 – tarea 2 -> almacén -> tarea 3 -> Producto. Considerando el siguiente contexto: existe una maquina por cada tarea, las maquinas solo podrán procesar una unidad al tiempo incluye un almacén entre tareas con la capacidad de uno.

Solución:

Se implementará una metodología de tipo Pull, propio de redes de Petri, la cual nos permite pasar de una acción a otra por medio de una señal, por lo que, si no se envía la señal de terminado en un área, no se podrá continuar al siguiente proceso y se plantearán de dicha forma para verificar que el procedimiento se lleve a cabo de manera correcta y completa. Cuando un pedido se genera la información se da a través de una señal a todas las fases de trabajo. Para representar una maquina: tendrá un inicio y un fin que vendrán marcadas como “transiciones” y la tarea será representada por dos “plazas” en donde una de ellas tendrá un token indicando que la maquina esta disponible para procesar materia prima.


![image](https://github.com/JohnVeraXD/PRACTICA-PETRI-App-Distribuidas-/assets/108051712/4d5aa0d6-85ec-4429-95b9-2b5d308cbd07)


![image](https://github.com/JohnVeraXD/PRACTICA-PETRI-App-Distribuidas-/assets/108051712/1d8ca212-87a7-479b-b83d-5bc669ba2122)


![image](https://github.com/JohnVeraXD/PRACTICA-PETRI-App-Distribuidas-/assets/108051712/531f9cb8-9b2b-429d-bcba-da597817183b)
