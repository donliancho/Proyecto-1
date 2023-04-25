Inicio mi proyecto 1 creando dos ficheros con index.html y style.css los cuales los he vinculado con link.
En HTML5,  genero un link favicon, generando una carpeta assets y arrastrnado la imagen de la web.
Adiciono al head el link de font style y font awesome
Establezco la estructura de mi maqueta html con secciones como header, main y footer
Dentro de mi header creo un nav con un input para crear mi nav burguer 
Creo un elemento de sección de navegación <nav> donde incorporo un div y dentro una etiqueta <img> para adicionar el logotipo de mi página, dentro de este div creo un input  de tipo checkbox con el id de check para crear el menú hamburguesa de mi header.
Introduzco el icono de barras tomado de Font awesome
Introduzco dentro de una etiqueta <ul> la lista de mi menú desplegable
En el body abro una etiqueta <main> con la clase” new-album”
Genero una etiqueta <h1> seguido de un párrafo <p> con los títulos
Creo un contenedor <div> con la clase play y allí introduzco un anchor e introduzco dentro de una etiqueta <picture >la imagen para el álbum nuevo y le ajusto las medidas
Creo dentro del main otra sección con la clase música, introduzco el título dentro una etiqueta <h1>, creo un contenedor con clase carousel , dentro creo más <div> con las fotos de los álbumes musicales y sus respectivas leyendas en etiquetas <h2> y un elemento de salto de linea <br>
Creo ota seccion que contiene imagnes con la class container, pongo titulos con las etiquetas <h1> y <p>
Creo varios div dentro de un div ccontenedor con la clase "follow" con las diferentes imagenes integrtadas con la etiqueta <img> y con los items del 1-9
Creo otra sección con la clase “container-super-tshirt” seguido del título >SHOP<,  que contiene diferentes div con las imágenes de los producto de la tienda con el título de los productos en una etiqueta <h3> y el precio del producto dentro de una etiqueta <span>, adiciono una carrito de compra con font awesome
Creo el footer con un contenedor <div> con la clase “foot” donde introduzco una lista <li> para los componentes del pie de página; creo además otro contenedor con la etiqueta <nav> para introducir los iconos de las diferentes redes sociales 
En CSS Defino los estilos generales de mi página web con  border box, margin y padding 0, defino la fuente de mis textos, defino aquí mismo que no hayan estilos de listas ni textos decorados, así como el color de la página y del texto 
Ataco a la etiqueta nav dándole una altura y un ancho , determino el display flex, justifico el contenido con espacio entre sus componentes y que queden centrados, seguido a la barra del menú hamburguesa le doy un tamaño, color a la barras y un margen a la derecha de 20px, le aplico un cursor pointer.
Ataco los componentes del menú desplegable, lo ubico en posición fija le doy una ancho del 100% y 100 px desde el top  y alineo el texto en el centro para terminar de centrar todos los componentes,  le aplico un fondo oscuro para cuando se despliegue.
Le adiciono una transición de .5 segundos para suavizar la transición 
Ataco el nav-menu y sus hijos li para dividirlo en líneas y poderlo ocultar 
Ajusto el tamaño de la letra  y el grosor , adiciono un hover con una de .3 seg.
Ataco el id check para ocultarlo con display none
Ataco el id check y lo vinculo con un selector de hermanos generales (~) para que cuando el input esté en estado cheked se muestre el nav  en bloque, con una altura del 100 hv y por medio de z-index de 10 se posicione por delante del resto de contenidos.
Pongo en posiciones relative el contenedor del “new-album” para poder manipular la imagen, el h1 y el p a los cuales los posiciono en relación con la imagen.
La clase “new-album” y su hijo <a>que contiene un anchor con el botón de play, lo posiciono respecto a la imagen, le doy tamaños, color y bordes.
En la discografía ataco el contenedor que contiene la clase <music>, le doy un ancho máximo, padding de 4 rem y le defino márgenes 0.
Al elemento del continuer el texto con el título de la sección lo centro y le doy un tamaño en rem.
Al contenedor con la clase <carousel> que contiene las imágenes de los diferentes albúmenes le doy un alto y un ancho del 100%, le defino display flex -wrap: nowrap para que los elementos permanezcan en una sola fila.
Le defino la visibilidad de los elementos por medio de un overflow-scroll para que funcione mi carrete.
Le defino un borde sólido de color amarillo para definir el campo del carrete.
A las imágenes del carrete le defino margen y relleno para ajustarlas dentro del contenedor.
A los títulos de las imágenes de mi carrete le doy tamaño al texto, los alineo en el centro y lo ubico en el pie de foto con el margin bottom.
A la clase <carousel> y su hijo <a> que contiene el texto al anchor de la playlist le doy hover con transición de color amarilla y la que previamente le he dado tamaño, márgenes y color con la clase <album-description a>
En la sección de social network centro el título y ajusto su tamaño.
Al contenedor principal con la clase <follow> le aplico el display grid, le asigno el número de columnas y el espacio entre ellas, así como el tamaño de las filas, de doy una relleno y un espacio adicional entre todos los componentes con el grid-gap.
Al conjunto de imágenes del contenedor, les doy dimensiones y la ajusto dentro del mismo por medio de object-fit: cover.
Al enlace del contenedor que lleva la etiqueta insta lo posiciono, le doy color, tamaño y bordes, lo ubico por medio de coordenadas x/y, y le aplico z index para que se posición delante de las imágenes a esta misma clase le doy un hover con transición de color amarillo.
A las imágenes.
Adicionalmente a las imágenes les doy una posición relative para poder manipular el texto dentro de ellas, le aplico un filtro y una opacidad para darles dinamismo.
A los textos de la galería los posiciono, les doy color y les doy un backgroud gradiente para integrarlos a la imagen.
Selecciono las imágenes 4, 5 y 9 para darles diferentes posiciones dentro de las filas y columnas para darle estilo al grid .
En la sección de store le doy posicionamiento, lo defino con display grid, con el número de columnas y su espacio entre ellas.
Al contenedor de las imágenes le doy relleno, le alineo el texto y les ajusto el tamaño.
Los textos de las imágenes los alineo en el centro , al precio de doy color y le doy grosor al mismo con la propiedad <font-weight>.
Al icono de la compra lo centro en la imagen con display block.
A las imágenes específicamente le doy tamaños y los fijo en contenedor.
Al título del contenedor le doy tamaño, márgenes y lo ubico en el centro. 
A la sección foot le doy tamaños y rellenos al contenedor principal, alineo todos los textos al centro.
Al contenedor de las redes sociales le aplico una altura mínima  con un viewport height de 30, le defino el display flex, justifico y alineo los diferentes iconos en el centro, por medio de la clase :button a, les doy tamaño, altura, les defino la distancia entre elementos , le otorgo un color de fondo y un color de icono, con bordes radius del 50% para que quede circular, y le defino una transición con sombra seguido de un hover.
En el responsive a los 760 px ajusto el tamaño del logo y sus márgenes, así como las dimensiones del contenedor <nav> principal, la barra del menú desplegable le adiciono display none para que desaparezca y al contenedor del menú desplegable le ajusto la posición para quede recostado a la derecha, sin background ni transition.
A los elementos del menú desplegable, les indico que con este tamaño de pantalla aparezcan en bloque de línea con altura de 110px, le adiciono background scroll para dejar los elementos fijos y no se desplacen.
A estos mismos elementos le adiciona un hover para que disminuyan hasta 12 px.
Le indico tamaño y centralizo el título.
En la sección social network ajusto las imágenes para que a este tamaño de pantalla se comporten de una manera determinadas ocupando ciertos columnar y filas determinadas, se lo aplico a las imágenes 3, 4, 5, 9.
El botón de follow con la clase insta le modifico la ubicación para que se desplace con este tamaño de pantalla.
En la sección store, ajusto los componentes para que a este tamaño de pantalla se pongan en línea con y con determinados dimensiones y márgenes, lo mismo aplico para el texto de las imágenes .
En la sección foot determino que con este tamaño los componentes queden en línea horizontal alineados en el centro y con márgenes establecidas.
En el resposive para desktop establezco a los 1024 px que el texto del new álbum tenga una posición absolute aumentado el tamaño y ajustando su posición, de igual forma los textos complementarios los ajusto en el espacio dentro del contenedor.
En la sección social network termino de ajustar los componentes al tamaño de pantalla adicionándole columnas al grid y modificando la posición de las imágenes 1 y 4.
Ajusto la posición del class insta.
En la sección store continúo definiendo la posición de los elementos en bloque de línea, con márgenes y tamaños tanto de las imágenes como de los textos.

