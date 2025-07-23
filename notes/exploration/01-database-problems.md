# Algunos Problemas en la Base de Datos

## Desbalance de Clases

![alt text](image-1.png)

## Datos Contradictorios (Learning Conflicts)

En la base de datos completa existen algunos datos contradictorios.

![alt text](image.png)

Estos permanecen al hacer la partición. Por ejemplo, las contradicciones en los datos de prueba (entre `k0`, `k1`, `k2` y `value`) se ven de la siguiente forma:

![alt text](image-3.png)

Condensando los datos repetidos utilizando su probabilidad empírica, se obtiene la siguiente proyección a `k1` y `k2`.

![alt text](image-4.png)

De forma similar a lo anterior ahora los datos se proyectan a `k1`, `k2`, `ValueLog10`.

![alt text](image-5.png)

### Dispersión de Datos en Paternidad

![alt text](image-6.png)

![alt text](image-9.png)

### Dispersión de Datos en Hermandad

![alt text](image-7.png)

![alt text](image-8.png)