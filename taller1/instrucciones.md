1.	Descargue el siguiente Dataset: https://www.kaggle.com/datasets/kyanyoga/sample-sales-data/data 
2.	Realice el análisis exploratorio
3.	Crear un nuevo DataFrame con: ORDERNUMBER, PRODUCTLINE, COUNTRY, CUSTOMERNAME, QUANTITYORDERED, PRICEEACH, SALES, DEALSIZE.
4.	Filtrar únicamente los pedidos de la línea Vintage Cars.
5.	Dentro de ese filtro, quedarse solo con los pedidos donde el país sea distinto de USA.
6.	Ordenar ese resultado por SALES de mayor a menor y mostrar los primeros 10.
7.	Responder con código: ¿qué país aparece con más frecuencia entre esos pedidos?
8.	Comparar df.loc[5] vs df.iloc[5] sobre el DataFrame ya ordenado, y explicar la diferencia en una frase.
9.	Revisar el tipo de dato de ORDERDATE. ¿Llegó como fecha o como texto?
10.	Convertirla a fecha con pd.to_datetime().
11.	Convertir COUNTRY a tipo category y comparar df.memory_usage(deep=True) antes y después.
12.	Realice 4 reportes libres (únicos por cada grupo). Que se encontró, como fue comprobado y recomendación de negocio ( presentar en la siguiente clase). 
