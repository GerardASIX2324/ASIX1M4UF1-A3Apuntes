# ASIX1M4UF1-A3Apuntes

Repositorio de apuntes de M4

## Primer capitulo: MARKDOWN

### Titulos y subtitulos

Para poner el titulo en grande en el encabezado hay que poner el simbolo del hashtag ( # ). Cada hashtag que se ponga singifica lo grande que va a ser el titulo o el subtitulo. Si se pone un solo # hace que el titulo o el subtitulo sea el mas grande de todos.

Contantra mas hashtag pongamos mas pequeño es el subtitulo y ams subapartados se pueden hacer. El limite esta en 6.

Aqui un ejemplo de como seria y el codigo de la estructura justo debajo:

## subtitulo
### subtitulo
#### subtitulo
##### subtitulo
###### subtitulo

```
## subtitulo
### subtitulo
#### subtitulo
##### subtitulo
###### subtitulo
```

### Cursiva y negrita

Para poner un texto en cursiva se utiliza el simbolo del asterisco ( * ) o la barra baja ( _ ) poniendo uno a cada lado del texto que queramos poner en cursiva.

Aqui un ejemplo de como queda con el codigo debajo:

Este texto esta en *cursiva*.
Este texto esta en _cursiva_.

```
Este texto esta en *cursiva*.
Este texto esta en _cursiva_.
```

Para poner un texto en negrita se utiliza el simbolo del asterisco ( * ) o la barra baja ( _ ) poniendo dos a cada lado del texto que queramos pones en negrita.

Aqui un ejemplo de como queda con el codigo debajo:

Este texto esta en **negrita**.
Este texto esta en __negrita__.

```
Este texto esta en **negrita**.
Este texto esta en __negrita__.
```

Si se desea en algun caso tambien se pueden combinar las dos poniendo uno para cada una de las condiciones que quiera cumplir. Si se quiere utilizar el asterisco para la cursiva, obligatoriamente se debe utilizar el hashtag para la negrita.

Ejemplo:

Este texto esta en _**negrita y cursiva**_.
Este texto esta en __*negrita y cursiva*__.

```
Este texto esta en _**negrita y cursiva**_.
Este texto esta en __*negrita y cursiva*__.
```

### Listas ordenadas y desordenadas y subapartados

#### Lista ordenada

Para hacer una enumeracion o una lista de valores ordenada se utilizan numeros seguidos de un punto.

Ejemplo:

1. primera opción del menú
2. segunda opción del menú
3. tercera opción del menú

```
1. primera opción del menú
2. segunda opción del menú
3. tercera opción del menú
```

#### Lista desordenada

Tambien se puede utiliza el guion ( - ) el asterisco ( * ) o el simbolo de mas ( + ) para hacerlo en una lista desordenada o sin enumeracion.

* primera opción de lista desordenada
* segunda opción de lista desordenada
- tercera opción de lista desordenada
- cuarta opción de lista desordenada
+ quinta opción de lista desordenada
+ sexta opción de lista desordenada

```
* primera opción de lista desordenada
* segunda opción de lista desordenada
- tercera opción de lista desordenada
- cuarta opción de lista desordenada
+ quinta opción de lista desordenada
+ sexta opción de lista desordenada
```

#### Subapartados

Para crear subapartados en listas oedenadas o desordenadas solo hay que pulsar el tabulador (tecla a la izquierda de la 'Q') en la linea donde queramos poner el subapartado.
Los subaparados pueden ser tambien ordenados o desordenados siguiendo la regla anterior.

Un ejemplo seria el siguiente:

* primera opción de lista desordenada
* segunda opción de lista desordenada
- tercera opción de lista desordenada
    1. primer sub menú
    2. segundo sub menú
- cuarta opción de lista desordenada
    *tercer sub menú
    *cuarto sub menú
+ quinta opción de lista desordenada
+ sexta opción de lista desordenada

```
* primera opción de lista desordenada
* segunda opción de lista desordenada
- tercera opción de lista desordenada
    1. primer sub menú
    2. segundo sub menú
- cuarta opción de lista desordenada
    *tercer sub menú
    *cuarto sub menú
+ quinta opción de lista desordenada
+ sexta opción de lista desordenada
```

### Mostrar codigo en el documento sin que este activo

Para mostar una parte de codigo en un documento lo que hay que hacer es poner tres tildes abiertas (`) una linea mas arriba del codigo que se quiera mostrar y otras tres tildes una linea mas abajo del codigo que quieras mostrar.

Ejemplo:

```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
</html>
```

```

```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
</html>
```

```