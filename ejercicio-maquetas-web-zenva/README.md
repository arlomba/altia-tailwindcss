# Maquetando y usando media queries

Completa el ejercicio para los tres tamaños posibles de dispositivos. Os recomiendo poner el atributo **class** en todos los elementos HTML relevantes siguiendo la [metodología BEM](https://www.youtube.com/watch?v=YaAkV--25fg).
Intenta conseguir, para todos los tamaños de anchura de viewport del dispositivo, el diseño más aproximado posible a las capturas de pantalla y [vídeo explicativo](https://oscarm.tinytake.com/tt/NDEyODkwOF8xMjcxMjcwMg).

<video width="720" height="480" controls>
  <source src="https://oscarm.tinytake.com/tt/NDEyODkwOF8xMjcxMjcwMg" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Dispositivos de hasta 375px

- Los iconos de menú tienen que verse bien uno al lado del otro. Seguramente puedes usar la propiedad display:inline-block o bien display:flex.
- Tienes que **ocultar** los 'li' que solo contienen texto!
- Hay varias maneras de centrar texto en el dispositivo, y quede a la mitad de la pantalla. Piensa que el texto "Lean coding..." siempre está en la mitad del **alto del viewport**.
- Recuerda visualizar esta parte del ejercicio con el [modo móvil](https://oscarm.tinytake.com/msc/NjMzOTQzM18xODcxNDAyMg) para obtener mejores rsultados

Además, el cliente nos ha pedido unos requisitos:

1. El tamaño de todos los iconos de menú tiene que ser de 70px
2. Las imágenes y el texto estan alineadas en el centro de la página.

## Dispositivos de hasta 959px

1. Ahora los iconos deben desaparecer, y deben verse solo los items de menú que contienen texto (Home, Services...).

## A partir de 959px

1. El menú aparece en horizontal.
2. Todos los elementos del menú estan en la misma línea
3. Todos los elementos de menú están alineados a la derecha
4. Todos los elementos de menú tienen un borde de 1px
5. En esta versión podemos ver como "asoma" el cesped de la imagen del fondo

<img src="https://oscarm.tinytake.com/media/11d8dce?filename=1641038479623_TinyTake01-01-2022-01-01-03_637766352789373945.png&sub_type=thumbnail_preview&type=attachment&width=600&height=339" title="Powered by TinyTake Screen Capture"/><br><a href="https://www.tinytake.com">Powered by TinyTake Screen Capture</a>

6. Las imágenes y el texto de distribuyen en dos columnas del mismo ancho. Puedes reducir el WIDTH de los contenedores o bien probar de usar grid.
