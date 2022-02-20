# Proyecto-Matematicas-Discretas
# Maneras de proteger para la información de los usuarios aplicando las matemáticas discretas
Proyecto matematicas discretas - Grupo D1

Un banco planea implementar unos nuevos cajeros en sus principales sucursales para esto contrata unos ingenieros de sistemas que busquen la manera 
mas segura de proteger la base de datos dentro de estos cajeros.
Los datos que obtienen los bancos y cajeros automaticos no suelen ser del todo seguros, se propone cambiar esto haciendo uso de la encriptación,
de esta manera se puede garantizar la seguridad y privacidad 
de la informacion de los datos de los usuarios que utilizen el cajero y sentirse seguros usando el mismo.

Para poder lograr el cometido crearemos un algoritmo en python que nos permita
encriptar y desencriptar las distintas tuplas de una base de datos donde obtendremos
los datos a encriptar (Numero de identificación, tipo de transacción, monto de la transacción, fecha, balance)
Nota: el tipo de la transacción puede ser retiro o ingreso
Para ello usaremos dos formas de encriptación que se le aplicarán a cada elemento de la tupla, los métodos a usar son: 
Cifrado cesar para los elementos que únicamente contienen números y usaremos el cifrado Sha256 para el resto de elementos de la tupla que contiene
una mezcla entre numeros,letras y simbolos.
