# Instagram Photo feed.

Creando una landing page que simula los posts de Instagram.

### Pre-requisitos 📋

1. Ordenador o dispositivo movil.
2. Programa donde copiar el repositorio. (Gitpod, VisualStudioCode, Pycharm ....)
3. Navegador web donde visualizar el resultado del codigo.


## Construido con 🛠️

* [HTML5] - Base del Front-end
* [CSS3] - Genera los estilos del HTML.

## Deployment

Para lanzar este proyecto introducir en la consola:

```bash
  pip3 install flask && python server.py


## Estructura y explicación del codigo ⚙️

* Landing page en HTML5 y CSS3. Se crea la estructura de los posts con HTML en el archivo index. Se usa flex container por lo tanto dentro del container principal se crea un div de clas post que sera el contenedor de cada post como su nombre indica. Dentro de este se encuentra un div post-header con el titulo, un div con la imagen del mismo y un div final con la descripcion del post.
* El CSS es el encargado de darle una mejor visualizacion al HTML de esa forma hacemos que el body tenga un fondo gris y que cada post tenga un fondo blanco para que destaquen sobre este. Hacemos que el contenedor principal tenga un ancho de 600 px y margin auto para que los post que contendra se centren en la pantalla. Estos post se separan entre ellos con un margin y se usan reglas de especificidad para ordenar cada uno de los elementos interiores. Para la imagen se usa un ancho del 100% del contenedor padre.


## Autor ✒️

* **Jose Luis Gil** - *Ejercicio terminado* - [JoseLike](https://github.com/JoseLike)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/JoseLike/excuse-generator/contributors) quíenes han participado en este proyecto. 