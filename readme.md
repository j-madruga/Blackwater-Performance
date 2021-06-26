# BLACKWATER PERFORMANCE
## Información general
Este proyecto consiste en el maquetado de un sitio web para una empresa de fitness que ofrece distintos servicios relacionados al entrenamiento. Busca llamar la atención de la posible clientela ofreciendo un diseño simple, elegante e intuitivo.


Fue desarrollado como proyecto final del curso de Desarrollo Web de Coderhouse.

## Tecnologías utilizadas
- html
- css
- scss
- bootstrap

## Descripción del codigo
### Introducción
El codigo se encuentra comentado tanto en el html como en el scss, pero es posible que una acotada descripción ayude a comprender la estructura del proyecto.

### SEO
Se utlizaron etiquetas meta para aplicarle SEO al sitio asi como tambien etiquetas semanticas que ayudan a su organización. Se estructuro la información respetando la herarquia de las etiquetas h1, h2, etc.

### HTML
El html cuenta con comentarios que ayudan a distinguir sus distintas secciones y esta correctamente tabulado para que sea visualmente sensillo distinguir su estructura; se utilizo tambien la metologia BEM para nombrar las clases en cada una de las páginas.

### SCSS
Se utilizo dicho preprocesador de css para darle estilo al sitio. Se hizo un pequeño script que permite la compilación posterior a css y se dividieron los estilos de la siguiente manera:
- **base**: en este archivo se encuentra el reset del css, las variables, mixins y placeholder classes que van a ser utilizados en el resto del proyecto
- **components**: en este archivo se declararon elementos que las distintas paginas del sitio comparten (como el navbar o el footer), ademas de otros elementos como formularios o llamadas a la acción que son similares en distintas páginas y requerian cierta o poca personalización.
- **views**: en esta carpeta se creo un scss por (casi) cada página donde se agregan los elementos únicos de dicha página o se customizan los elementos que se declaran en components, ademas de contener los media queries de cada página.
- **styles**: en este archivo solo se importan los otros scss respetando el orden en el que se crearon buscando así que el css quede ordenado y el efecto de cascada permita darle el estilo correcto a cada elemento.

Debido a esta organización es que se comentaron los archivos scss y no el css, ya que así facilita su lectura y comprensión.

## Instalación
Descargar proyecto y ejecutarlo
```
$ cd ../path/to/the/folder
$ git clone https://github.com/j-madruga/Blackwater-Performance
```

## Repositorio
https://github.com/j-madruga/Blackwater-Performance