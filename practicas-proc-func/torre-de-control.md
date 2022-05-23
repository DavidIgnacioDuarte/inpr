En este ejercicio las columnas del tablero representan canales aéreos por los que
despegan y aterrizan aviones. Se considera que un canal está libre para aterrizar si
no hay avión en ninguna de las posiciones de ese el canal. Los aviones se
representan con tantas bolitas azules como el número de su vuelo, y con una bolita
Roja en la misma celda si está aterrizando o con una bolita Verde si está
despegando. El tablero representa a todo el aeropuerto; en cada celda hay a lo
sumo un avión. Implementar las siguientes operaciones:

1. La función **cantidadDeCanalesLibres()**, que devuelva la cantidad de
canales sin aviones.
2. La función **cantidadDeAvionesDespegando()**, que devuelva la cantidad
total de aviones que están despegando en todo el aeropuerto.
3. El procedimiento **IrACanalLibreParaDespegar()**, que deje el cabezal
en el primer canal libre más cercano al Sureste del aeropuerto.
4. La función **cantidadDeAvionesTotales()**, que devuelva la cantidad
total de aviones que están despegando/o aterrizando en todo el aeropuerto.
5. El procedimiento **IrACanalLibreParaAterrizar()**, que debe dejar al
cabezal en el primer canal libre más cercano al Noroeste del aeropuerto.
6. La función **cantidadDeCanalesConColisiónInminente()**, que
devuelva la cantidad de carriles con posibles colisiones en todo el
aeropuerto. Se considera que hay una colisión posible si en el mismo carril
hay un avión que está despegando debajo de un avión que está aterrizando.
7. El procedimiento **IrACanalConColisiónInminente()**, que deje el
cabezal en el primer Carril con una colisión inminente (desde el extremo
Suroeste del aeropuerto).
8. La función **mayorNroDeVueloDespegando()**, que retorne el número de
vuelo más grande que esté despegando en el aeropuerto.
