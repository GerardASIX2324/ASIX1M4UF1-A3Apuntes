# ASIX1M4UF1-A3Apuntes

Repositorio de apuntes de M4

## Primer capítulo: GITHUB

### Creación y clonacion de repositorios

#### Creación

Para crear un repositorio de GitHub iremos a nuestro perfil y le daremos al apartado de "Your repositories". Ya dentro de nuestros repositorios podremos ver todos los que tenemos.

Arriba a la derecha hay un boton en verde que pone "New". Si clicamos encima se nos abrira una pestaña completamente nueva con el titulo de "Create a new repository". En las opcines que hay nos pondremos a nosotros de propietarios y al lado pondremos el nombre que le podemos dar a nuestro repositorio. Si nos equivocamos, mas tarde se puede cambiar. Debajo tenemos una casilla con caracteres ilimitados para poner una descripcion de nuestro proyecto. En el siguiente apartado nos muestra dos opciones donde tenemos que marcar una de ellas preguntandonos si queremos que nuestro repositorio sea publico o privado. Si lo ponemos en publico el repositorio sera visible para cualquier persona que se meta en nuestro perfil. Si lo ponemos en privado solo sera accesible para nosotros.

Como una de las ultimas ociones nos aparece "Initialize this repository with:" Ahi seleccionaremos la opcion de "Add a redme file" para asi tener una archivo y que el repositorio funcione. En ningun caso pulsaremos enter cuando estemos en la pagina de creacion de un repositorio para evitar crearlo por error. Cuando este todo configurado le daremos a "create repository" marcada en verde al final del documento.

#### Clonacion

Lo mas recomendable a la hora de trabajar con GitHub es trabajar en local y luego subirlo a la nube. Para ello necesitaremos la app de Git GUI. Despues de descargarla y tenerlo todo listo, accederemos la explorador de archivos y seleccionaremos donde queremos que se guarden loos repositorios en nuestra maquina local. Una vez dentro de la carpeta deseada, en el panel de la ruta escribiremos "cmd", desde alli guardaremos, clonaremos y subiremos los repositorios por codigo en la terminal. 

Para hacerlo accederemos GitHub y nos dirigiremos a nuestro repositorio. Cuando estemos dentro nos aparecera un boton de color verde con el texto "<>Code" donde si clicamos se nos abrira un desplegable. Alli encontraremos diferentes opciones. La que nos interesa para clonar el codigo en la nube es el link que nos deja copiar en el portapapeles dandole al boton de la derecha del panel. Cuando tengamos ese link copiado, iremos a nuestro explorador de archivos y nos meteremos DENTRO de la carpeta de nuestro repositorio. Comoa antes, escribiremos cmd y ejecutaremos el siguiente comando.

1. git clone (pegamos el link copiado anteriormente sin ningun tipo de parentesis)


### Subida de archivos

Para la subida de archivos tendremos que acceder DENTRO de la carpeta de nuestro repositiorio y escribiremos "cmd" en el panel de la ruta. Con la terminal abierta, pondremos los siguientes comandos:

1. Insertar en la cmd el comando "git init" para iniciarlo.
2. Insertar en la cmd el comando "git add . " para añadir el contenido a la nube.
3. Insertar en la cmd el comando "git commit -m "(titulo de la actualización)" para poner un titulo a la actualización.
4. Insertar en la cmd el comando "git push origin main" para subirlo del origen a la raiz principal.

Una vez hecho esto ya tendriamos nuestro repositorio local identico a nuestro repositorio en la nube siempre que no hayamos puesto mal algun comando o nos de algun error a la hora de subirlo.

NOTA: Si se ha trabajado desde la nube y luego se ha trabajado en local y queremos subirlo, no nos va a dejar actualizar ninguno de los dos ya que ninguno es una version anterior del otro. Para solucionar este error, lo mas sencillo es copiar lo que hayamos hecho en local en la nube a mano, eliminar la carpeta del repositorio local (despues de haber copiado los avances en la nube obviamente) y clonar de nuevo el repositorio en local para tener lo mismo que en la nube. Si volvemos a intentar un archivo despues de seguir lo anteriores pasos nos funcionara.

### Eliminar un repositorio

Eliminar un repositorio es una tarea muy facil pero larga para confirmar que estas seguro de eliminarlo.

Para eliminar un repositorio iremos al repositorio que queremos eliminar, nos meteremos en settings, en la pestaña de "General" scrolearemos hasta abajo del todo y nos situaremos en el apartado de "Danger Zone". Alli tendremos que tener sumo cuidado. Seleccionaremos la opcion de "Delete this repository" y clicaremos en el boton rojo situado a la derecha con el mismo texto. Luego nos aparecera un pop-up pidiendonos la confirmacion para elimiar el repositorio. Para hacerlo haremos clic en el boton inferior con la inscripcion "I want to delete this repository". Si aun no estamos seguros del todo nos va a salir otro pop-up para verificar la confirmacion. Para continuar, pulsaremos el boton con la inscripcion "I have read and understand these effets". Después de haber clicado nos va a salir otro pop-up pidiendo que copiemos el nombre del repositorio que queramos elimiar para asi estar seguros del todo. En la parte superior nos saldra el nombre para copiarlo. El nombre tiene que ser exacto, sino no nos aceptara la opcin de eliminarlo. Si queremos hacerlo rapido copiando el texto superior, no nos va a dejar. Esta hecho expresamente para eso. Cuando este copiado indetico se nos habilitara un boton debajo con la inscripcion "Delete this repository". Para colmo y para asegurarnos de que somos nosotros nos pedira la contraseña de nuestro usuario para poder eliminar definitivamente el repositorio. Una vez seguidos todos estos pasos al pie de la letra tendremos eliminado por completo el repositorio.

NOTA: Si queremos salir o en cualquier momento nos arrepentimos de eliminarlo, nada mas con hacer click fuera de cualquier pop-up que nos salga se cancelara la accion.

### Pages

El apartado de pages sirve para la visualizacion total de una pagina web creada en HTML hasta lo que sabemos hasta la fecha.

Para crear un pages tendremos que hacer lo siguiente:

+ Acceder al repositorio del cual querramos crear un pages.
+ Ir al apartado de settings.
+ Seleccionar en la columa de la izquierda el apartado de"Pages".

Cuando estemos dentro de esa pestaña, no dirigiremos al apartado de "branch" y le daremos al boton donde pone "none" para seleccionar el lugar donde queramos situarlo. Normalmente es en "main".

Luego se nos mostrara una opcion en la misma linea que pondra "Save". Cuando hayamos clicado solo faltara esperar a que se cree el link automaticamente en la parte superior de la pestaña de pages. No es instantaneo. Depende del peso y la extension de la pagina puede tardas mas o menos tiempo. Normalmente son un par de minutos como maximo.

## Segundo capítulo: MARKDOWN

### Titulos y subtitulos

Para poner el titulo en grande en el encabezado hay que poner el simbolo del hashtag ( # ). Cada hashtag que se ponga singifica lo grande que va a ser el titulo o el subtitulo. Si se pone un solo # hace que el titulo o el subtitulo sea el mas grande de todos.

Contantra mas hashtag pongamos mas pequeño es el subtitulo y ams subapartados se pueden hacer. El limite esta en 6.

Aqui un ejemplo de como seria y el codigo de la estructura justo debajo:

#### subtitulo
##### subtitulo
###### subtitulo

```
# subtitulo
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
    * tercer sub menú
    * cuarto sub menú
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

### Insetar un enlace

Para insertar un enlace en el documento hay que seguir las siguientes indicaciones poniendolo todo en la misma linea y sin espacios excepto en los lugares donde va texto visible:

1. Poner entre corchetes como queremos que se muestre el enlace.
2. Abrir un parentesis y poner la URL donde queremos que nos lleve el enlace.
3. Sin cerrar el parentesis anterior, pulsar la tecla 'espacio' y poner entre comillas un texto adicional donde se explica donde lleva esa URL. Cuando pasemos por encima el raton y lo mantengamos un segundo quieto encima del enlace saldra este texto adicional.

[Web J23](https://www.fje.edu "Enlace a la web del colegio Jesuites Bellvitge. Centre d'Estudis Joan XXIII")

```
[Web J23](https://www.fje.edu "Enlace a la web del colegio Jesuites Bellvitge. Centre d'Estudis Joan XXIII")
```

### Insetar una imagen

Para insertar una imagen en un documento hay que seguir las siguietes indicaciones poniendo todo en la misma linea y sin espacios excepto en los lugares donde va texto visible:


1. Situar la imagen a la carpeta local.
2. Subir la imagen a GitHub de la misma forma con la cual guardamos los documentos.
    1. Abrir la carpeta donde esta situado el archivo.
    2. Escribir "cmd" en la barra de la direccion de la carpeta.
    3. Insertar en la cmd el comando "git init" para iniciarlo.
    4. Insertar en la cmd el comando "git add . " para añadir el contenido a la nube.
    5. Insertar en la cmd el comando "git commit -m "(titulo de la actualización)" para poner un titulo a la actualización.
    6. Insertar en la cmd el comando "git push origin main" para subirlo del origen a la raiz principal.
3. Entrar en el repositorio de GitHub correspondiente.
4. Hacer click en el link de la imagen situado encima de la visualización del documento.
5. Copiar la URL del navegador
6. Ir al codigo del documento (en mi caso VisualStudioCode)
7. Poner un simbolo de exclamación (!)
8. Poner entre corchetes un titulo para la imagen (este no va a aparecer en pantalla).
9. Abrir un parentesis y pegar la URL del lugar donde esta ubicada la imagen.
10. Sin cerrar el parentesis anterior, pulsar la tecla 'espacio' y poner entre comillas un texto adicional donde se explica el contenido de la imagen. Cuando pasemos por encima el raton y lo mantengamos un segundo quieto encima de la imagen saldra este texto adicional.

![Meme Ibai PSOE](https://github.com/GerardASIX2324/ASIX1M4UF1-A3Apuntes/blob/main/F7BWCNibMAAPu05.jpg "Meme de Ibai sugetando con orgullo la carta de la Kings League del PSOE")

```
![Meme Ibai PSOE](https://github.com/GerardASIX2324/ASIX1M4UF1-A3Apuntes/blob/main/F7BWCNibMAAPu05.jpg "Meme de Ibai sugetando con orgullo la carta de la Kings League del PSOE")
```

### Insetar una tabla

Para insertar una tabla en un documento se hace de la siguente forma.

La primera linea sirve para determinar el numero de columnas que vamos a insertar. Se inserta sin espacios, exceptuando los lugares donde va el texto, una barra vertical al principio de la linea seguido del texto que va a aparecer en a primera columna. Al acabar de escribir el texto de la primera columna, insetar una barra vertical sin espacio para cerrar la columna. Si se desea añadir mas colunmas solo hay que seguir el mismo procedimiento para las demas, el unico cambio es que no hara falta insertar otra barra vertical para insertar otra columna, con seguir escribiendo en la misma linea funciona.

La segunda linea se usa para indicar el grosor de las columnas mediante guiones. Se inserta una barra vertical a principio de linea y se añaden los guiones preferidos segun el grosor de la columna a la que pertenecen. Si se desea la primera columna igual que la segunda y la tercera un poco mas fina, se tendrian que añadir los mismos guiones en la primera y en la segunda columna respectivamente y poner menos guiones en la tercera.

Para la posicion del texto tambien se usa la segunda linea. El texto viene por defecto pegado a la izquierda. Para ponerlo en el lado izquierdo basta con no poner nada o poner dos puntos(:) en el lado izquierdo antes de los guiones. Si se desea poner el texto pegado a la derecha solo se necesita poner los dos puntos (:) al lado derecho de la columna despues de los guiones. Por ultimo, si se desea poner el texto centrado, es necesario poner los dos puntos en ambos lados de los guiones.

Ejemplo:

|Primera Col.|Segunda Col.|3 Col.|
|----------------------------|:------------:|----:|
|Izquierda|Centrada|Dch.|
|Clase|ASIX1|M1|
|Clase|ASIX2|M2|
|Clase|ASIX1|M4|
|Clase|ASIX2|M13|

```
|Primera Col.|Segunda Col.|3 Col.|
|----------------------------|:------------:|----:|
|Izquierda|Centrada|Dch.|
|Clase|ASIX1|M1|
|Clase|ASIX2|M2|
|Clase|ASIX1|M4|
|Clase|ASIX2|M13|
```

### Insertara seleccion de casillas

Para insertar una selecion de casillas basta con poner dos corchetes,([]) uno abierto y el otro cerrado seguidos de la opcion que se quiera seleccionar separada con un espacio de la casilla de seleccion. Para seleccionar una casilla basta con poner una 'X' entre los dos corchetes.


-[ ] Opción A

-[X] Opción B

-[ ] Opción C

```
-[ ] Opción A

-[X] Opción B

-[ ] Opción C
```

## Tercer capítulo: HTML