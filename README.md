# analisis-de-datos-excel
Fórmulas de Excel para Análisis de Datos Avanzado
Cálculo de ingresos de cada producto:


=C2*D2
Multiplica el precio (columna C) por la cantidad vendida (columna D) para obtener los ingresos (columna F).
Suma de ventas por categoría con SUMAR.SI:


=SUMAR.SI($B$2:$B$11;H2;$F$2:$F$11)
Suma los ingresos en la columna F para una categoría específica de la columna B (e.g., Electrodomésticos).
Conteo de productos por categoría con CONTAR.SI:


=CONTAR.SI($B$2:$B$11;H2)
Cuenta cuántos productos hay en una categoría específica en la columna B.
Producto más vendido utilizando BUSCARV y MAX:


=BUSCARV(MAX($D$2:$D$11);$D$2:$A$11;4;FALSO)
Encuentra el producto con la mayor cantidad vendida utilizando la combinación de BUSCARV y MAX.
Cálculo de ganancias totales por región con SUMAR.SI:


=SUMAR.SI($E$2:$E$11;L2;$F$2:$F$11)
Suma los ingresos de la columna F para cada región en la columna E.
Región a promocionar utilizando INDICE y COINCIDIR:


=INDICE(L2:L5;COINCIDIR(MAX(M2:M5);M2:M5;0))
Encuentra la región con mayores ganancias al usar las funciones INDICE y COINCIDIR.
Formato condicional para resaltar ingresos superiores a la media:

Fórmula en formato condicional:
=$F2>PROMEDIO($F$2:$F$11)
Resalta las celdas en la columna F que contienen valores superiores al promedio.
