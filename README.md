# Lista_To_Do
1. Presentación<a name="_page2_x72.00_y72.00"></a> del proyecto

‘Doer', es una página web diseñada y creada para facilitar la gestión de tareas y mejorar la productividad personal mediante un “To Do List” integrado en la página.

La idea nace de poder ofrecer un “To Do List” minimalista y atractivo a la vista que permita a los usuarios organizar sus actividades diarias de manera muy sencilla y visual. El propósito principal de 'Doer' es ofrecer una interfaz intuitiva y amigable:

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.002.png)

El boceto inicial, nos muestra la idea de inicio. “Doer list” se trata de una rectángulo con bordes redondeados que permite introducir la tarea y un botón “Ok” para confirmar la tarea. A continuación las tareas confirmadas se mostrarán en orden de entrada. Las tareas se pueden indicar como hechas (botón verde) o borrarlas directamente (botón rojo). Las que están realizadas se indican con una línea por encima.

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.003.jpeg)

El resultado final después de implementarlo en html, css y JavaScript es el siguiente:

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.004.jpeg)

2. Metodología<a name="_page3_x72.00_y72.00"></a> y herramientas de trabajo
1. Metodología

<a name="_page3_x72.00_y104.45"></a>El proyecto se dividió en etapas cortas. Mediante Git y Github como plataforma para gestionar el código fuente del proyecto. Se ha configurado un repositorio para desarrollar, realizar seguimiento de cambios, y mantener un histórico completo de versiones, lo que ha permitido un trabajo fluido. El link del repositorio: <https://github.com/IsaacLaaouaj/Doer>

El siguiente gráfico muestra la frecuencia de código a lo largo del tiempo (20/11/23 al 03/12/23), donde refleja las adiciones y eliminaciones de código por día:

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.005.jpeg)

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.006.jpeg)

2. Herramientas<a name="_page4_x72.00_y72.00"></a> de Trabajo

<a name="_page4_x72.00_y99.16"></a>VisualStudio Code

Este IDE nos proporciona funcionalidades avanzadas y extensiones que facilitan la escritura eficiente de código HTML, CSS y JavaScript. La extensión utilizada es “Live Server” que permite plasmar en tiempo real los cambios:

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.007.jpeg)

<a name="_page4_x72.00_y438.59"></a>Netlify

Para el despliegue y hosting continuo de 'Doer', se optó por Netlify, una plataforma de alojamiento web que ofrece despliegues automáticos directamente desde repositorios de Github. Netlify permite ver de forma rápida y sencilla los cambios de la web. Imagen de la plataforma:

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.008.jpeg)No se ha utilizado “GitHub pages” porque demoraba mucho en los despliegues a la hora de realizar cambios en la web.

3. Funcionalidades<a name="_page5_x72.00_y101.09"></a> de la página web
1. Apartados

<a name="_page5_x72.00_y153.54"></a>La web se ha estructurado en cuatro apartados:

- Página de inicio: Explicamos las ideas principales y el objetivo del sitio web.
- Doer list: Donde va a estar la propia “list to do” minimalista.
- Bibliografía: Se detalla el proceso de desarrollo del sitio web.
- Contacto: Información de contacto.

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.009.png)

Donde cada apartado de la página web es enlazada a los otros apartados. Esto lo hemos conseguido mediante el atributo “href” de html, que permite integrar una dirección a un atributo de html.

2. Diseño

<a name="_page5_x72.00_y388.26"></a>Se ha procurado ser lo más minimalista posible tomando de inspiración sitios web como <https://www.onedesigncompany.com/> y <https://www.leemons.io/> .

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.010.jpeg)

La tipografía escogida es “Montserrat”. Se trata de una tipografía de uso libre, bajo la licencia “SIL Open Font License”, lo que permite que se pueda utilizar en el ámbito académico. La tipografía es proveniente de Google Fonts, que mediante su API (application programming interface) se ha podido integrar en la web vía html:

<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Font+Montserrat"/>![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.011.png)

Para no saturar la página y que favorezca a su sencillez los colores escogidos son únicamente tres: el blanco, el negro y el gris (para solo los rellenos). Tenemos como excepción los botones de “realizar” y “borrar” la tarea, que están marcados con verde y rojo.

Para el logotipo, se ha utilizado la herramienta de [Photopea | Online Photo Editor](https://www.photopea.com/), donde se se ha ido realizando pruebas y bocetos hasta decidir el más visual y con mejor aspecto:

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.012.png)

4. Desarrollo<a name="_page6_x72.00_y291.72"></a> del código de la página web

El desarrollo del sitio web se han empleado las metodologías presentadas en los ejemplos de "**w3schools.com**", y se han utilizado los tutoriales de HTML, CSS y JS de "**scrimba.com**" como referencia para el desarrollo del proyecto.

<a name="_page6_x72.00_y402.35"></a>HTML

Definimos la estructura básica de html: Declaración del Tipo de Documento (DOCTYPE), el encabezado (Head), el cuerpo (Body) y el pie de página (Footer). Para luego implementar el contenido de texto e imágenes de los cuatro apartados.

<a name="_page6_x72.00_y484.50"></a>CSS

El código CSS proporciona estilos y los diseños visuales para los elementos que hemos realizado en HTML. Estos son los estilos que hemos definido en el código css:

- Estilos de Texto (p, h1, .titulo\_contenido).
- Barra de Navegación (.navbar).
- Contenido (.contenido).
- Imágenes (#imagen\_contenido, .slider-frame, .slider-frame ul, .slider-frame li, .slider-frame img).
- Contenedor de Entrada de Texto (.inputcol, .textarea, .textarea::-webkit-scrollbar, .buttoninput).
- Elementos de la Lista de Tareas (.itemall, .check-button, .trash-button, .item, .checklist).
- Pie de Página (footer)

Para realizar el “Slider” de la página web, se ha utilizado la herramienta de “keyframes” de CSS, que permite determinar el tiempo de la animación y duración de cada imagen. En este caso, la animación está destinada a desplazar elementos horizontalmente. Todas las imágenes de la página web no disponen de derechos de autor y son de uso libre (fuente de las imágenes “freepik”):

![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.013.jpeg)

En el 75% hasta el 100% del tiempo de la animación, el contenido continúa desplazándose hacia la izquierda, aplicando un margen izquierdo de -300%. Este movimiento hacia la izquierda fuera del área visible se mantiene durante el resto de la animación:

@keyframes slide { 0![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.014.png)% {margin-left: 0;} 20% {margin-left: 0;}

25% {margin-left: -100%;} 45% {margin-left: -100%;}

50% {margin-left: -200%;} 70% {margin-left: -200%;}

75% {margin-left: -300%;} 100% {margin-left: -300%;} }

<a name="_page8_x72.00_y72.00"></a>Javascript

Programamos en JavaScript para crear la función de lista de tareas (To-Do List), donde seleccionamos los elementos de HTML mediante las variables:

const inputtdl = document.querySelector('.textarea') const buttontdl = document.querySelector(![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.015.png)'.buttoninput') const listtdl = document.querySelector('.todolist')

Programamos la función “cickButton”, con la entrada “e”. La función se ejecuta cuando se hace click en el botón “Ok” que tiene la clase definida '.buttoninput' y llama a la función “addTodo()”:

function clickButton(e) {![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.016.png)

e.preventDefault() addTodo()

}

Esta función (addTodo()) agrega los elementos a la lista de tareas, es decir por cada click en el botón “Ok” crea un elemento <div> con la clase “.itemall” junto con elemento <p> que le asignamos el texto de la variable “inputtdl”. En el caso de que este vacío la función termina.

Para poder dar por hecho o eliminar la tarea, programamos dos botones: uno para marcar la tarea como completada (checkbutton) y otro para eliminar la tarea (trashbutton).

Finalmente agregamos los elementos creados al elemento “.todolist” referencias por “listtdl”:

function addTodo() {![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.017.png)

const itemall = document.createElement('div') itemall.classList.add('itemall')

const item = document.createElement('p') item.classList.add('item') item.innerText = inputtdl.value itemall.appendChild(item)

if (inputtdl.value === '') return

const checkbutton = document.createElement("button") checkbutton.innerHTML = '<i class="fa-solid fa-check"></i>' checkbutton.classList.add("check-button") itemall.appendChild(checkbutton)

const trashbutton = document.createElement("button") trashbutton.innerHTML =![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.018.png) '<i class="fa-solid fa-trash"></i>' trashbutton.classList.add("trash-button") itemall.appendChild(trashbutton)

listtdl.appendChild(itemall) inputtdl.value = ''

}

La función `okdel()` lo hacemos para que maneje los eventos de click dentro del contenedor de la lista de tareas (`listtdl`).

Si el clic es en un botón de clase `check-button`, alterna la clase `checklist` del elemento padre del botón (`todolist`) para marcar como completado el ítem. Si el clic es en un botón de clase `trash-button`, elimina el elemento padre (`todolist`) de la lista:

function okdel(e) {![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.019.png)

const item = e.target

// check

if (item.classList[0] === 'check-button') {

const todolist = item.parentElement todolist.classList.toggle('checklist')

}

// delete

if (item.classList[0] === 'trash-button') {

const todolist = item.parentElement todolist.remove()

}

}

Y ya para acabar el botón asociado a la clase `.buttoninput` activa la función `clickButton` cuando se hace click.

Y ya para acabar la fundación “clickButton” se activa al hacer clic en el botón “.buttoninput” y la función “okdel” se activa al hacer clic en cualquier parte de la lista “.todolist”:

buttontdl.addEventListener('click', clickButton) listtdl.addEventListener(![](Aspose.Words.a4bb75e9-960c-4a8c-abdd-a8ec187d58cc.020.png)'click', okdel)

5. Bibliografía

<a name="_page10_x72.00_y72.00"></a>Ejemplos HTML, CSS y JavaScript, <https://www.w3schools.com/>

Tutorial de como hacer la de barra de búsqueda y botones en HTML y CSS, <https://scrimba.com/learn/htmlandcss/google-clone-recap-co87d46689d640c87caec96fa> | [https://scrimba.com/learn/htmlandcss/centering-both-buttons-with-flexbox-co21c47f987bd27 3e0569b86a](https://scrimba.com/learn/htmlandcss/centering-both-buttons-with-flexbox-co21c47f987bd273e0569b86a)

Tutorial de JavaScript, función para el Doer list, [How To Create To-Do List App Using HTML CSS And JavaScript | Task App In JavaScript - YouTube](https://www.youtube.com/watch?v=G0jO8kUrg-I)

Herramienta gratuita de diseño online (parecida a photoshop): [Photopea | Online Photo Editor](https://www.photopea.com/)

Fuente de imagenes sin derechos de autor [Freepik: Descarga gratis vídeos, vectores, fotos y PSD](https://www.freepik.es/)
