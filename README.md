# Course

## Angular avanzado 🌊🌟🌠

## La arquitectura que se usara será la siguiente

En la carpeta app se encontraran las carpetas </br>

**404:** En esta guardaremos cualquier ruta no existente redireccionara aquí.

**login:** En esta guardaremos toda la parte del login y registro

**pages:** En esta guardaremos las páginas o pantallas de nuestra aplicación.
> En la carpeta **pages** encontraremos esto:

- **component**
    > Aquí van todos los componentes personalizados que vamos a poder reutilizar, como un progres-bar o cosas así.
- **form**
    > Los formularios que se utilizaran para la app.
- **icons**
    > Los iconos de la aplicación.
- **starter**
    > Lo que iniciara la página normalmente.
- **table**
    > Aquí van las páginas que realicen tareas específicas

Las **pages** también tendran su propio modulo de rutas, ya que, se tendran rutas dentro de otras rutas. También tendran su propio module, este se encargara de agrupar todas las páginas y empaquetarlos para poder manejar la app.

**shared:** En esta guardaremos los componentes que son utilizados por toda la aplicación (Menos el login y el registro).


para comenzar a generar nuestra aplicacion crearemos una carpeta auth en la cual estara el login de nuestra aplicación y el register, utilizaremos las banderas --skip-tests (para que se salte la creación de los archivos de testing) y -is (para que salte la creación de los archivos de estilos).
**ng g c auth/login --skip-tests -is** & **ng g c auth/register --skip-tests -is**

Luego comenzaremos a crear los componentes para la página en la carpeta **pages**
**ng g c pages/nopagefound --skip-tests -is**
**ng g c pages/dashboard --skip-tests -is**

Comenzaremos a crear dentro de la carpeta shared los componentes como breadcrumbs.
**ng g c shared/breadcrumbs --skip-tests -is**
**ng g c shared/sidebar --skip-tests -is**
**ng g c shared/header --skip-tests -is**

## Optimización y creación de modulos personalizados.


## Sección 4

Esta sección esta enfocada en módulos principalmente:

* Crear un módulo personalizado
* Crear rutas hijas
* Comenzaremos a crear módulos para agrupar tareas específicas
* Realizar cambios en GitHub
* Crear Release Tags que nos permitan descargar el código fácilmente, 
    en caso de que necesitemos volver a comenzar donde nos quedemos.

En clases más adelante del curso, seguimos creando módulos, por lo que esta sección es muy importante