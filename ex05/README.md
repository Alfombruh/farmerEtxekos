Nombre del ejercicio    :   amongus
Files a entregar        :   amongus.c main.c
Funciones Permitidas    :   write
--------------------------------------------------------------------------------

Escribe un programa que se llame amongus que reciba 2 strings y escriba 1
seguido de una nueva linea si el primer string se encuentra escondido dentro 
del segundo. Si no escribe 0 seguido de una nueva linea

Dados que s1 y s2 deben ser strings.  Consideramos que s1 se encuentra en s2 
si podemos encontrar cada caracter de s1 en s2 en el mismo orden en el que
aparencen en s1.
Tambien, un string vacio esta escondido en cualquier string.

Si el numero de parametros no es 2, el programa unicamente escribe una nueva
linea.

$> ./amongus "hola" "hxyolzazzz" | cat -e
1$
$> ./amongus "gato" "gotxao" | cat -e
0$
$> ./amongus "casa" "abracadabra" | cat -e
0$
$> ./amongus "luna" "estrella" "galaxia" | cat -e
$
$> ./amogus | cat -e
$
$> ./amongus "oraculo" "orrlllrlllaraalllalllcuullluullllollloooo" | cat -e
1$



