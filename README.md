# gl_fsd0423_css_retoConsola
Proyecto 1 - Videoconsola con CSS

## Tabla de contenidos

- [Descripción del proyecto🕹️](#Descripción-del-proyecto)
- [Tecnologías utilizadas📷](#Tecnologías utilizadas)
- [Desarrollo⛏️](#desarrollo)
- [Errores conocidos⛑️](#errores-conocidos)
- [Licencia y Copyright📃](#licencia-y-copyright)

### Descripción del proyecto



<!-- Esta réplica de la videoconsola portátil Nintendo Game Boy Color puede ejecutarse desde el navegador web y es capaz de realizar varias acciones:
- Pulsando el botón **START**, la consola lanza en su pantalla una animación del arranque original de la consola, además de iluminar el piloto **led** que encontramos junto al símbolo **POWER**. -->

Se trata de una reproducción -salvando las diferencias- de la videoconsola portátil Game & Watch: Super Mario Bros lanzada en El 35 aniversario de Super Mario Bros (fabricadas por Nintendo y creadas por Gunpei Yokoi de 1980 a 1991.) conocidas popularmente en España como "maquinitas".

![image](/img/readmeimagen1.webp)

- Pulsando el botón **GAME**, la consola lanza en su pantalla una imagen del famoso juego MBros.

Este proyecto se ha desarrollado en un ámbito educativo con fines didácticos para la Academía GeeksHubs.




<!-- - Situando el cursor sobre el cartucho que encontrarás a la derecha de la consola, este realizará una transición, aumentando de tamaño, si pulsas sobre él, la animación que la consola lanzará esta vez será de una de las escenas más representativas del juego original, Pokémon Amarillo. -->

<!-- ![image](https://user-images.githubusercontent.com/122631261/213938710-b0904325-911b-4f54-a3cd-6fad655169cb.png) -->

<!-- - Todos los botones **cambiarán de aspecto al clicar** sobre ellos, aunque a excepción del botón START, ninguno realizará otra acción. -->

### Tecnologías utilizadas

El modelo y todos los detalles que incluye están basados en la videoconsola portátil **Nintendo Game Boy Color**, lanzada al mercado en Japón el 22 de octubre de 1998.

![image](/img/readmeimagen2.png)

<!-- El cartucho que acompaña a la videoconsola corresponde a **Pokémon Edición Amarilla: Edición Especial Pikachu**, una revisión de los Pokémon Azul y Rojo, siendo uno de los juegos más importantes de lanzamiento de la videoconsola. -->

![image](/img/comparacion.png)

### Desarrollo

En el desarrollo de la videoconsola y del cartucho del videojuego se ha empleado HTML y CSS, con algunos elementos Javascrip.
- El cuerpo de la consola está construido con un **display:grid**, dividiendo así los elementos principales, herramienta que también se ha empleado para la cruceta y el altavoz frontal.
- Todos los elementos están creados de cero con HTML y CSS, a excepción de los logotipos de Nintendo, Game Boy Color, la imagen de la pegatina del cartucho y el logotipo de Nintendo GameBoy integrado en el frontal superior del cartucho. Sin embargo, tanto el logotipo de Nintendo del frontal de la máquina como el del cartucho, están tratados con filtros de opacidad y brillo desde CSS.
- Los únicos elementos de javascript se encuentran en el botón START y en el cartucho. Con elementos oneclick y función de cambio de clases para lograr los efectos deseados.
![image](https://user-images.githubusercontent.com/122631261/213939728-91b64e91-5dc0-4ead-9623-39a0b0a86bc8.png)

### Errores conocidos

Aunque no se trata de un error que impida el buen funcionamiento de la web, el piloto led de encendido funciona junto al activado y desactivado del botón START y haciendo click sobre el CARTUCHO. Si en lugar de activar y desactivar cada una de las animaciones, se pulsan seguidas, las animaciones y el piloto led se desincronizarán.

### Licencia y Copyright

El logotipo de Nintendo y Game Boy Color, son propiedad de Nintendo Co., Ltd. Las imágenes representadas en el cartucho del juego pertenecen a Nintendo y The Pokémon Company.
