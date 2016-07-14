# MongoDB - Aula 01 - Exercício
autor: Wesley vieira

## Importando os restaurantes

	mongoimport --db be-mean --collection restaurantes --drop --file restaurantes.json
	2016-07-13T21:10:56.329-0300	connected to: localhost
	2016-07-13T21:10:56.329-0300	dropping: be-mean.restaurantes
	2016-07-13T21:10:57.650-0300	imported 25359 documents


## Contando os restaurantes

	> use be-mean
	switched to db be-mean
	> db.restaurantes.find({}).count()
	25359






