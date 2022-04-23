# TB_10_FakeTwitter

## Indice
* Sobre el proyecto
    * Instalacion y despliegue
    * Tecnologias usadas
    * Origen
    * Objetivo
* Recursos
    * Fuentes utilizadas
    * Inspiracion
* Retos presentados
    * Mobile firs
    * :focus-within
    * SVG invisibles
* Siguientes pasos
* Autor


## Sobre el proyecto

### Instalacion y despliegue

Para ver el proyecto simplemente tienes que entrar en [esta pagina](https://feiktwitah.netlify.app/) o ejecutar en la terminal `https://github.com/MrSetOne/TB_10_FakeTwitter.git` y ejecutar el archivo index.html.

### Tecnologias usadas

Para este proyecto he usado HTML, CSS y JavaScript sin frameworks

### Origen

Es un ejercicio para el Bootcamp de FullStack impartido en TheBrige, a modo de afianzar los conocimientos adquiridos en el rampup.

### Objetivo

El objetivo de este proyecto es crear un clon de Twitter, para practicar la maquetacion y responsividad.

## Recursos
### Fuente utilizada
Para este proyecto he utilizado la fuente original de Twitter, usando la propiedad `@font-face` de la siguiente manera. (Gracias Gabo por la ayuda :wink:)
```CSS
@font-face {
    font-family: TwitterChirp;
    src: url(https://abs.twimg.com/fonts/v2/chirp-regular-web.woff2) format('woff2');
    src: url(https://abs.twimg.com/fonts/v2/chirp-regular-web.woff) format('woff');
    font-weight: 400;
    font-style: 'normal';
    font-display: 'swap';
}

@font-face {
    font-family: TwitterChirp;
    src: url(https://abs.twimg.com/fonts/v2/chirp-medium-web.woff2) format('woff2');
    src: url(https://abs.twimg.com/fonts/v2/chirp-medium-web.woff) format('woff');
    font-weight: 500;
    font-style: 'normal';
    font-display: 'swap';
}

@font-face {
    font-family: TwitterChirp;
    src: url(https://abs.twimg.com/fonts/v2/chirp-bold-web.woff2) format('woff2');
    src: url(https://abs.twimg.com/fonts/v2/chirp-bold-web.woff) format('woff');
    font-weight: 700;
    font-style: 'normal';
    font-display: 'swap';
}

@font-face {
    font-family: TwitterChirp;
    src: url(https://abs.twimg.com/fonts/v2/chirp-heavy-web.woff2) format('woff2');
    src: url(https://abs.twimg.com/fonts/v2/chirp-heavy-web.woff) format('woff');
    font-weight: 800;
    font-style: 'normal';
    font-display: 'swap';
}
```

### Inspiracion
La version exacta que hay en el momento de redactar este radme (23/04/2022)

## Retos presentados
### Mobile firs
Normalmente trabajo con la metodologia "Desktop firs", pero para esta pagina a modo de reto personal me he forzado a ralizarla basado en "Mobile first", lo cual me ha complicado mas la elaboracion de la pagina.

### :focus-within
Esta pseudo-clase no la habia utilizado hasta la fecha, esta pseudo-clase lo que te permite es poder modificar las propiedades del padre una vez se hace focus en uno de los hijos. Para esta pagina lo he usado en el campo de busqueda de main.html para que cuando se haga click dentro del input se modifiquen las propiedades de su elemento padre.

### SVG invisibles
Durante el proceso de maquetado de la web, traté de generar archivos .svg para evitar "ensuciar" el html, pero al tratar de ralizarlo no se veian, siquiera asignandoles la propiedad `fill:` dentro de css o dentro de propio .svg, tras varias pruebas intenté meterlo dentro del html y funcionó correctamente.

- [ ] Estudiar con mas detalle el comportamiento y modificacion de los archivos .svg


## Proximos pasos
Cuando adquiera conocimientos de BackEnd y DB me gustaria poder dotar a la aplicacion de funcionalidad, para así poder experimentar con un proyecto ya realizado por mi parte.

## Autor

Esta pagina ha sido realizada por Michael Lara Sánchez, para ver mas de mis repositorios puedes acceder a mi [GitHub](https://github.com/MrSetOne)