Nombre del ejercicio  : elMasCercano
Files a entregar   : elMasCercano.c main.c
Funciones Permitidas:
--------------------------------------------------------------------------------

Escribe la siguiente funcion:

int elMasCercano(int *arrayInts, int sizeArray, int number);

El primer parametro es un array de ints, el segundo el tamaño del array y el 
tercero es un numero.

La funcion debe devolver el numero mas cercano en el array al numero que
le llega en el tercer parametro.

En caso de que haya dos numeros que esten a la misma distancia del numero que
buscamos, nos quedaremos con el mas pequeño.

Obviamente debes presentar un main que pruebe tu codigo (que no sea una copia
de los ejemplos dados) y al main no se aplican las funciones permitidas

Ejemplos:

1)
int array[] = {1, 5, 10, 20, 25};
int size = 5;
int number = 12;
printf("%d\n", elMasCercano(array, size, number));

salida=> 10

2)
int array[] = {3, 8, 15, 22, 30};
int size = 5;
int number = 20;
printf("%d\n", elMasCercano(array, size, number));

salida=> 22

3)
int array[] = {2, 6, 10, 14, 18};
int size = 5;
int number = 12;
printf("%d\n", elMasCercano(array, size, number));

salida=> 10

4)
int array[] = {-10, -5, 0, 5, 10};
int size = 5;
int number = -3;
printf("%d\n", elMasCercano(array, size, number));

salida=> -5