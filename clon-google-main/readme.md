# Clon de buscador de google
## CDN bootsrap

## ¿Qué es bootstrap?

Contruir sitios responsivos(adaptables a diversos tamaños de pantalla) por medio de clases pre-hechas de css.

### ¿Por qué es importante entender que es bootstrap?

Cuando nosotras hacemos css, tenemos qué tener acceso a el HTML donde se van a utilizar, y para que nuestras sentencias que indica como cambiar las propiedades, como:

 ``background-color: red;``

Debemos utilizar un selector (elemento, clase, id), por lo tanto, para usar bootstrap se van a poder utilizar estos mismos selectores, sólo que ya van a estar predefinidos.

## Instalación

Para instalar bootstrap, lo que realemnte vamos a hacer es lo mismo que se hace con todos los recursos del mismo tipo, por ejemplo:

Para ligar un archivo de CSS, ocupamos:
``<link rel="stylesheet" href="style.css">``

En este caso, ligaremos con un archivo en internet:
    ``<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">``

Bootstrap es uno de un montón de frameworks de CSS que podems ocupar. Todos se pueden traer por medio de un CDN e importar con un link a nuestro archivo.

Por otro lado, bootstrap requiere de JS para hacer componentes dinámicos, como el carrusel.

Por lo tanto voy a necesitar ese link en mi archivo, solo que este link va a tener código de JS, por lo tanto como cualquier link de JS deberá ir al final de mi body, arriba de la etiqueta de cierre.

``<script src="archivoJS.js"></script>``

En este caso, la linea para ligarlo contiene el link al archivo de JS, se pone al final para que una vez que se cargaron todos los elementos de HTML, ahora sí lo empecemos a hacer dinámicos, por que si ponemos el SCRIPT arriba, y el HTML se tarda en cargar, podriamos estar intentando hacer dinámico un elemento que todavía no existe.

``<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>``

Con esto ya tenemos nuestro sitio listo para usar bootstrap.

## Uso de bootstrap

Es importante entender que como es un marco de trabajo va a tener sugerencias de como ocupar diversas cosas que ya se usan en CSS.

Y además va a tener los elementos más comunes usados en los sitios web ya con la sugerencia de cómo estruturarlos y en donde acomodarlos.

Y por último va a tener maneras de cambiar las cosas importantes extra, hablamos de colores, hablamos de box-model(padding, margin, border,content[width, heigh]), el tipo de display.

