# Practica02-Mi_Sitio_Web_CSS

 <h2>1._Implementacion de la Pagina Home </h2>
 <p>Estructura del código </p>
 <p>La pagina home o index.html se compone de 3 partes, Una cabecera la cual contiene el logo un input de tipo búsqueda y 3 imágenes mas. También esta compuesta por el menú de navegación. Luego tenemos una sección dividida en 2 columnas la cual tiene un mensaje y una foto, posteriormente vamos a la sección de ventas la cual se acomodaron las imágenes mediante un float left, de igual manera para la parte de presentación de equipo de trabajo, para finalizar tenemos una tabla con datos personales y dos logos. </p>
<p></p>
 <h2>2._Implementacion de una página con 2 columnas </h2>
 <p>Implementación del Código</p>
 <p>La Página Armonía Musical o armonía.htm está conformada de por una cabecera la cual consta del logo, un input de tipo search y unas imágenes adicionales, luego tenemos el menú de navegación, luego tenemos la parte del body el cual está dividido en 2 partes: la parte izquierda consta la parte de un subíndice la parte derecha va el contenido principal. Al final encontramos el footer o pie de pagina con los datos del estudiante. <h2>3._Implementacion Pagina con 3 Columnas </h2>
 <p>Implementación del Código </p>
 <p>La página composición Musical o composición.html este compuesto por su cabecera que contiene un logo un input de tipo search y varias imágenes, así como del menú de navegación. Luego tenemos el body el cual esta dividido en 3 secciones, la primera contiene un subíndice, la segunda contiene la parte central o principal de la pagina y la tercera parte es solo un complementa de la segunda, finalmente tenemos el pie de pagina con los datos del estudiante. </p>
 <p></p>
<h2>4._Vista de los archivos CSS Desarrollados</h2>
<p>2columnas.css: Hace referencia a los atributos que se les otorgo a las paginas que disponen de el requerimiento 2 columnas. </p>
<p>3columnas.css: Hace referencia a los atributos que se les otorgo a las paginas que disponen de el requerimiento 3 columnas</p>
<p>Edición.css:  Hace referencia a las reglas aplicadas a tipo de letra, color, tamaño de títulos,etc. </p>
<p>Formulario.css: Hace referencia a las reglas css aplicadas al formulario requerido. </p>
<p>Index.html: Hace referencia a los atributos aplicados a la pagina home. </p>
<p></p>
<h2>4._Selectores Empleados </h2>
<p>Por ID </p>
<p>Selector Universal </p>
<p>Selector de Tipo o Etiqueta </p>
<p>Selectores Decendentes </p>
<p>Selectores Por Clases </p>
<p></p>
<h2>5._Menu horizontal de navegación y pseudoclases </h2>
<p>Menu Principal </p>
<p>Cada Item tiene Su respectivo Submenu de Contenido </p>
<p>NOTA. El menú de navegación se ocupo en todas las paginas html a excepción del formulario de Registro. </p>
<p>Implementación del código html </p>
<p>Básicamente lo primero que había que hacer es crear una lista, empezando por la etiqueta <nav>, luego pasábamos a la etiqueta <ul>, luego empezábamos a llenar la lista con los ítems mediante <li>, para poder lograr la sublista dentro de cada <li> agregábamos una etiqueta <ul> y dentro de ella los ítems con <li>. Para que se vea de esa forma es necesario usar CSS. </p>
<p>Implementación CSS </p>
<p>.navegacion._ Clace que pone el tamaño vertical del menú, pone un margen de 5px, un color medio verdoso oscuro, y la fuente importada</p>
<p>.navegacion ul._ Esta regla ccs nos dice que se va a aplicar a todos los <nav> que tengan como clase a .navegacion.</p>
<p>.menu > li  Selector que va aplicar una posición relativa y un display de tipo inline a cualquier elemento li que sea hijo de la clase .menu. </p>
<p>.menu > li >a>_ Clase que va a dar un relleno de 15px, cambiar la fuente y va quitar cualquier texto decorativo a cualquier elemento tipo <a> que sea hijo de <li> y que este a su vez sea hijo de la clase .menu. </p>
<p>.menu li a:hover._  Clase que posibilita el despliegue del submenú al pasar el mouse sobre una etiqueta tipo <a> con una demora o transición de 1.5 segundos. </p>
<p>.submenu li a._ Regla que se va a aplicar a todos los elementos a y li que tengan la clase .submenu. </p>
 <p></p>
<h2>6._Formulario de Registro de Usuario y pseudoclases </h2>
<p>Implementación código html </p>
<p>Para poder elaborar este formulario empleamos 5 etiquetas input 2 de tipo texto, una de tipo email, una de tipo password, una de tipo párrafo y una de tipo submit, todo esto en la parte de section.  </p>
<p>Implementación del código CSS </p>
<p>.* Selector Universal que ubica a la pagina sin bordes y cambia el modelo de caja por defecto </p>
<p>Body._ Selector que da un color de fondo color crema y da la fuente de letra. </p>
<p>.registro._ Aplica un tamaño total al formulario con 400 px, le da un color medio plomo, un relleno de 30px, un margen automático, un margen de 100px en la parte superior, un color de letra blanco y su fuente. </p>
<p>.registro h2._ Le da un tamaño de letra de 22px y un margen en la parte inferior de 20px a todas las etiquetas h2 que estén dentro de la clase .registro.</p>
<p>.controles._  Clase que da un tamaño del 100% de ancho un color blanco un relleno de 10px, un borde inferior de 16px, un borde de 1px de grosor de tipo solido y color negro, un tamaño de letra de 18px, y la fuente de letra. </p>
<p>.registro p._  A todas las etiquetas p que estén dentro de una clase .registro se les dará un tamaño de ancho de 40px, centrado, tamaño de letra de 18px y la fuente respectiva. </p>
<p>.registro a._ a todas las etiquetas <a> que estén dentro de la clase registro se les dará un color medio crema,sin decoración y la respectiva fuente. </p>
<p>.registro a:hover._ A todas las etiquetas que <a> que estén dentro de la clase registro y que el cursor este sobre dicha etiqueta se les dará un color crema, un subrayado y un tipo de letra.</p>
 <p></p>
<h2>7._ Código CSS </h2>
<p>En esta parte vamos a omitir la explicación del menú de navegación y formulario ya que se la planteo en el punto anterior. </p>
<p>2columnas.css </p>
<p>#menu._ Funciona como id ya que no se puede utilizar para otra ocasión. Tiene la propiedad de float left que nos permite acomodar automáticamente las cajas una a lado del otro empezando desde la izquierda, el tamaño de ancho de esta sección será del 15% del total de la pagina con un largo de 2711px (esta medida varia conforme a la pagina, pero todas tienen la misma estructura), es de un color gris, tiene un margen superior de 50px y define el tipo de letra. </p>
<p>#contenido._ De igual manera esta sección mediante el float left me acomoda automáticamente cada subsección desde la parte izquierda, toma el 85% restante de la pagina, es de un color medio blanco, tiene un margen superior de 50 px y también se define un tipo de letra. </p>
<p>#pie._ El pie de pagina corresponde a la parte donde ira el footer, ocupa el 100% de ancho de la pagina, es de un color gris oscurotiene un margen alto de 50px y también se define un tipo de letra. </p>
<p>H2._ La etiqueta h2 se modifico para que actue como títulos, se le asigno un tamaño de 50px, centrada y la fuente elegida. </p>
<p>.separacion._ Esta clase se utilizo para dar un margen de separación entre artículos y párrafos, con un alto de 15px, 10 px a los lados y 20px en la parte baja </p>
<p>.subt._ Esta clase se empleo para dar una separación o margen a los videos y fotos. </p>
<p>#menuone._Funciona para dar una margen y ubicación mas vistosa a la parte del submenú ubicado en la parte superior izquierda. </p>
<p>3columnas.css</p>
<p>#menu._ Funciona como id ya que no se puede utilizar para otra ocasión. Tiene la propiedad de float left que nos permite acomodar automáticamente las cajas una a lado del otro empezando desde la izquierda, el tamaño de ancho de esta sección será del 12% del total de la pagina con un largo de 1930px (esta medida varia conforme a la pagina, pero todas tienen la misma estructura), es de un color gris, tiene un margen superior de 50px y define el tipo de letra. </p>
<p>#contenido._ De igual manera esta sección mediante el float left me acomoda automáticamente cada subsección desde la parte izquierda, toma el 88% restante de la pagina, es de un color medio blanco, tiene un margen superior de 50 px y también se define un tipo de letra. </p>
<p>#contenido #principal._ Se aplica a todos los #principal que estna dentro del id #contenido, Básicamente se ubica desde la izquierda y toma un 75% de ancho del 88% tomando en la sección anterior, da una tonalidad gris, y una altura de 1930.  </p>
<p>#contenido #secundario._  Se aplica a todos los #secundario que están dentro de #contenido. Ubica a las secciones dentro de el desde la izquierda uno a lado de otro, toma el 25% restante del 88% tomado en contenido y da un color medio blanco. </p>
<p>.separacion._ Esta clase se utilizo para dar un margen de separación entre artículos y párrafos, con un alto de 15px, 10 px a los lados y 20px en la parte baja</p>
<p>.subt._ Esta clase se empleo para dar una separación o margen a los videos y fotos. </p>
 <p></p>
<h2>7._Validacion HTML </h2>
<p>Index.html (HOME)._sin errores</p>
<p>Formulario.html (Formulario de registro de Usuario).sin errores </p>
<p>Armonía.html.sin errores </p>
<p>Componer.html.sin errores </p>
<p>Ritmos.html.sin errores</p>
<p>Teoría.html.sin errores</p>
<p>Acordes.html.sin errores</p>
<p>Canciones.html.sin errores</p>
<p>Escalas.html.sin errores </p>
<p>Bt.html.sin errores </p>
<h2>8._Validacion CSS </h2>
<p>2columnas.css </p>
<p>3columnas.css </p>
<p>Index.css </p>
<p>Formulario.css </p>
<p>Edicion.css </p>
 <p></p>
 <p></p>
<h1>RESULTADO(S) OBTENIDO(S):</h1>

<ul>
    <li type="circle">1. Los estudiantes son capaces de utilizar e implementar herramientas basadas en html y css. </li>
    <li type="circle">2. Los estudiantes son capaces de satisfacer requerimientos de Hypermedia basándose en html y css. </li>
    <li type="circle">3. Los estudiantes saben manejar de forma correcta y eficiente código html y css. </li>
    <li type="circle">4. Los estudiantes son capaces de diseñar y estructurar un sitio web </li>
    <li type="circle">5. Los conceptos analizados en clase se implementaron de forma correcta y satisfactoria. </li>
</ul>
<p></p>
<h1>CONCLUSIONES:</h1>

<ul>
    <li type="circle">1. Para poder implementar un diseño web primero se debe aprender bien la estructura html y como funciona cada etiqueta y sección, posteriormente para que un sitio web se vea de forma mucho mas llamativa y vistosa se debe implementar css. </li>
    <li type="circle">2. El uso de css es una herramienta muy útil al momento de diseñar a nuestro gusto o al gusto del cliente una pagina web. </li>
</ul>
<p></p>
<h1>RECOMENDACIONES: </h1>

<ul>
    <li type="circle">1. Tratar de verificasr el diseño en diferentes navegadores.  </li>
    <li type="circle">2. En caso de dudas proceder a preguntar al docente.</li>
    <li type="circle">3. El modelo de cajas es la mejor opción para organizar a nuestro gusto una pagina web.</li>
    <li type="circle">4. Tener cuidado con los nombre repetidos de una regla css </li>
    <li type="circle">5. Verificar que los id no se repitan en toda la pagina.  </li>
</ul>


# Bibliografias
https://www.colorzilla.com/
https://validator.w3.org/
https://www.flaticon.com/
https://www.mclibre.org/consultar/htmlcss/index.html
https://www.mclibre.org/
https://www.w3schools.com/


