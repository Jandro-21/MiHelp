## Índice de contenidos

- Índice de contenidos
- Encabezados de nivel 1, 2, 3, y 4
- Cambios tipográficos: negrita, cursiva, negrita y cursiva, tachado, remarcados
- Listas sin orden (usa distintos niveles)
- Listas ordenadas (usa distintos niveles)
- Snippets de código
- Citas
- Enlaces a páginas o elementos externos
- Enlaces a otros elementos del mismo documento (encabezados u otros)
- Imágenes externas
- Imágenes con enlace
- Tablas
- Líneas horizontales
- Saltos de línea
- Lista de tareas
- Emojis
- Fórmulas matemáticas
- Referencias
- Referencias al pie





# Bienvenido al MiHelp, esto sirve para guiarte a través del Markdown. Esto es un enunciado de nivel uno

## Este es un enunciado de nivel 2, se hace poniendo dos almoadillas "##" 

### podemos seguir con el nivel 3

#### Llegando a los enunciados de nivel 4

##### Cuantos mas # pongas mas pequeño será


# ahora voy a explicar los diferentes tipos de cambios tipográficos

*Las palabras entre un solo * van a estar en cursiva*

**Sin embargo si pones 2 * van a estar en negrita**

***Y si mezclas ambas y pones 3 * mezclas todo***

~~Este texto será tachado al poner 2 ~ cejillas~~

* para hacer listas sin orden (lo que en html es un ul):
+ pueden ponerse con * y espacio 
+ con + y espacio
- o con - y espacio

1. Si pones números seguido de un . puedes
2. crear listas de numeros
    - y si tabulas y pones elementos de lista
    1. ya sean ordenadas o no
    + Puedes concatenar listas


java
```java
public class main{
    public static void main(String[] args){
        System.out.println("Si usas 3 ` y pones un lenguaje de programación");
    }
}
```
python
````python
print("Podrás hacer Snippets de código")
````
c++ (o al menos el Cout)
`````c++
Cout>> "Pero cuidado, debes cerrarlas de la misma forma, es decir, si abres este archivo c++ con 5 ` lo tienes que cerrar igual"
``````

>Si usas ">" vas a crear una **Cita**


[Si entre [ ] pones un texto y ente ( ) pones un enlace a un archivo externo o local te genera un link ](README.md)

[Y Lo mismo con webs, como esta que enseña Markdown](https://www.luisllamas.es/curso-markdown/)

![También funciona con imágenes](tux-1080.webp)
también va con fotos, tanto locales como en web

[Aqui puedes ver una foto de mi película favorita, puesta copiando la dirección de imagen y pegandola como un link.](https://static.wikia.nocookie.net/featteca/images/9/98/Shrek.png/revision/latest?cb=20220713043820&path-prefix=es)

![Esta foto me hace gracia, sin más](https://pbs.twimg.com/media/GBKc-zRbEAAzzkx.jpg)


| Tablas 1 | Tablas 2 |
| -------- | -------- |
| Texto    | Incluso dejando huecos en blanco |
|

## Ahora vamos con los saltos de linea[^1]

usando backslash \
 haces un salto de linea\
 \
 como este.

 - [x] Haciendo corchetes y x 
-  [ ] Creas una lista de tareas
 
💩 haciendo :shit: pones un emoji (o copiandolo de la web)


Para poner Fórmulas mátematicas sirve con poner la formula en formato LaTeX
\
$\sqrt{9} = 3$

 frac{1+2}{3} -> (ejemplo, para que vaya bien tiene que ir ente $)




[^1]: De esta forma se añaden las referencias a los pies de pagina.
