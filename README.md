__Ejercicio 1__

_Crear una funci�n en python que dada una lista de n�meros indique para cada n�mero si es
un n�mero perfecto, abundante o defectivo.
� Un n�mero perfecto es aquel que es igual a la suma de sus divisores propios positivos,
excluy�ndose a s� mismo. Por ejemplo 6 = 1+2+3
� Un n�mero abundante es aquel que la suma de los divisores propios es mayor que el
n�mero.
� Un n�mero defectivo es aquel que la suma de los divisores propios es menor que el n�mero.
Se deber� usar Python 2.7 y no se permitir� el uso de librer�as externas que obtengan la
clasificaci�n del n�mero._


__Ejercicio 2__

_Dados 3 juegos de datos, se solicita que se cree una p�gina web que mediante ajax lea las
3 fuentes de datos y muestre 2 gr�ficas de highcharts, una gr�fica de l�neas con la fecha en
eje x y tantas series como categor�as, y un pie chart por categor�a agrupando los datos
totales (sumatorio de los valores de cada categor�a).
Las fuentes tienen informaci�n temporal una fecha, categor�a y un valor. Se deben combinar
las series de tal modo que si en m�s de una serie para una misma fecha y categor�a hay
datos estos se sumar�n. Las categor�as deber�n normalizarse para que todas est�n en
may�sculas, �Cat 1� y �cat 1� son equivalentes a �CAT 1�_

La serie 1 tiene datos en el siguiente formato:
{"d":1435708800000,"cat":"Cat 1","value":832.803815816826}
donde d es la fecha en milisegundos, cat es la categor�a y value el valor
Est� accesible en http://s3.amazonaws.com/logtrust-static/test/test/data1.json

La serie 2 tiene datos en el siguiente formato:
{"myDate":"2015-06-02","categ":"CAT 1","val":46.300059172697175}
donde mydate es fecha en formato YYYY-MM-DD categ es la categor�a y val el valor
Est� accesible en http://s3.amazonaws.com/logtrust-static/test/test/data2.json

La serie 3 tiene datos en el siguiente formato:
{"raw":"9OHbc9 O1 WHTxiBPa auwZIVD6 j8jMWWVH UdB6hy 2015-06-18 XF 5xhcx15DD
sbYFRPn dyoH1OOIF 6meHw pANknwa2h T imhs24gR5 #cat
1#","val":39.38690127513058}
donde raw contiene datos en raw con palabras la fecha en formato YYYY-MM-DD y la
categor�a entre #, se deber� hacer un procesado del raw para sacar la categor�a y la fecha.
val es el valor. En el ejemplo la fecha ser�a 2015-06-18 y categor�a normalizada CAT 1.
Est� accesible en http://s3.amazonaws.com/logtrust-static/test/test/data3.json
Se permite el uso de librer�as para la resoluci�n del problema.