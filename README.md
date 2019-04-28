# Libreria CSS de Animaciones

Es una libreria de animaciones empaquetados en mixins de Sass. Esta inspirado en animate.css

## Como usarlo?

Puedes usar Animate con CSS o con SASS(recomendado)

### Con CSS

Descarga el archivo ``public/css/animate.css`` e incluyelo en tu proyecto.

Luego puedes agregar las siguientes clases a los elementos que deseas que se animen.



```scss
.fade-in
.fade-out
.slide-left
.slide-right
.slide-top
.slide-bottom
.slide-down
.slide-up
.zoom-in
.zoom-out
.bounce-left
.bounce-right
.bounce-top
.bounce-bottom
.animated-bordes
```



### Con Sass

* Instale Animate con el comand ``npm intall --save-dev animate``
* Importe ``animate/animate`` en su proyecto.
* Establezca la variable ``animateHelpers: false`` para compilar solo lo necesario.
* Los mixins disponibles son:

```scss
fadeIn($time)
fadeOut($time)
slideLeft($time)
slideRight($time)
slideTop($time)
slideBottom($time)
slideDown($time, $height)
slideUp($time, $height)
zoomIn($time)
zoomOut($time)
bounceLeft($time)
bounceRight($time)
bounceTop($time)
bounceBottom($time)
animatedBordes($time, $color)
```

