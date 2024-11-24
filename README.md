# RETO_3
## En este repositorio se encuentran los pasos a seguir para hallar los números primos, esta serie de pasos esta basada en la Criba de Eratóstenes.
### Pasos a seguir:
### 1. Crear una lista de números desde 2 hasta n, en este caso tomaremos como ejemplo **n=24**.

[2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]

### 2. Seleccionamos el primer numero de la lista **"i"**.
En este caso **i=2**.

### 2. Eliminamos todos los multiplos de **i** hasta n (exepto el número mismo) de la lista.

 [2, 3, ~~4~~ , 5 , ~~6~~ , 7 , ~~8~~ , 9 , ~~10~~ , 11 , ~~12~~ , 13 , ~~14~~ , 15 , ~~16~~ , 17 , ~~18~~ , 19 , ~~20~~ , 21 , ~~22~~ , 23 , ~~24~~]

 ### 3. Tomamos el siguiente número de la lista que no ha sido eliminado "k". 
 En este caso **k=3**
 
