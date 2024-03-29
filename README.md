# Proyecto integral y evolutivo para el sup 06 del cohorte 08 Henry

La idea de este proyecto es que a medida que avancen con los módulos puedan ir actualizando e incluyendo las nuevas herramientas que van aprendiendo, dado que están en el M1 la idea está restringida solo al uso de Python y Pandas.

Lo que se pide para este proyecto es la limpieza de los datos de los datasets entregados, su concatenación para la creación de una tabla única y limpia, y la realización de algunas que otras consultas.

No hay límite de tiempo y mucho está dejado a la creatividad de cada uno, así que no se limiten ni restringan en lo que pueden o no hacer.

Como una list to do podemos enumerar lo siguiente:

1. Carga de los distintos datasets, recomiendo explorarlos antes de cargarlos en pandas además sugiero hacer un EDA en cada uno de los datasets y aplicar lo que sea necesario antes de la concatenación.

2. Crear un id, está librado a la imaginación de cada uno.

3. Observar Nulos, verificar y merituar si pueden ser completados, inferirlos o eliminarlos.

4. Realizar las consultas específicas que se solicita, como plus, pueden crear una función que automatice la consulta de manera que solo sea necesario ingresar las variables. Como punto extra pueden crear una clase que posea todas las funciones de consulta, y que se activen con un menu de usuario.

a)  Cantidad de veces que se repite un género y plataforma con mayor frecuencia del mismo. (Dificil)

b)  Actor que más se repite según plataforma y año. (Dificil)

c)  Cantidad de películas y series (separado) por plataforma. (Medio) 

d)  Máxima duración según tipo de film (película/serie), por plataforma y por año (Medio)

e)  Peliculas que son exclusiva de una sola plataforma (hay que ingresar la plataforma ej. Netflix y debe retornar todas las peliculas que no aparezcan en las otras plataformas.

f)  Autor o Autores que posean la mayor cantidad de peliculas filtrado por plataforma.

Pueden usar Google Colab, jupyter o los notebook de VSC, pero los archivos deben estar subidos a github. Deberán aprender a usar codigo de github o usar Github Desktop. 

El código debe estar comentado, con nombre y apellido explicando y justificando las medidas tomadas. Lo más ordenado posible y llevar registro de las modificaciones hechas.

----------------------------------------------------------------------
MODULO 2

En este apartado veremos que implementaciones podemos realizar a partir de lo enseñado en el modulo N° 2 de Henry. 

ESTADISTICA Y PROBABILIDAD

- Calcular PROMEDIO Y MEDIANA de la duración de peliculas y series agrupado por plataforma.
- Calcular MODA del tipo de género y autor.
- ¿Qué probabilidad hay de eliminar 4 peliculas o series al azar y que todas ellas pertenezcan a NETFLIX?
- ¿Qué probabilidad hay de que al elegir 10 peliculas o series no se repita en ningún caso ningúno de los géneros?

SQL

-Deberás crear una conexión a base de datos para conectar lo realizado en el MODULO 1 y exportarlo a MySQL o Postgresql. AVANZADO: Crear un script que automatice la conexión, se genere un pool de conexiones junto con el cursor y una clase que contenga las consultas de CRUD. Luego generar la interfaz de input para la gestión de las consultas.

-Realizada la creación de la base de datos debes verificar y realizar un EDA desde Workbench o similiar controlando nulos, duplicados, codificación, etc.
