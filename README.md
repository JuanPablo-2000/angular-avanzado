# Course

## Angular avanzado 馃寠馃専馃尃

## La arquitectura que se usara ser谩 la siguiente

En la carpeta app se encontraran las carpetas </br>

**404:** En esta guardaremos cualquier ruta no existente redireccionara aqu铆.

**login:** En esta guardaremos toda la parte del login y registro

**pages:** En esta guardaremos las p谩ginas o pantallas de nuestra aplicaci贸n.
> En la carpeta **pages** encontraremos esto:

- **component**
    > Aqu铆 van todos los componentes personalizados que vamos a poder reutilizar, como un progres-bar o cosas as铆.
- **form**
    > Los formularios que se utilizaran para la app.
- **icons**
    > Los iconos de la aplicaci贸n.
- **starter**
    > Lo que iniciara la p谩gina normalmente.
- **table**
    > Aqu铆 van las p谩ginas que realicen tareas espec铆ficas

Las **pages** tambi茅n tendran su propio modulo de rutas, ya que, se tendran rutas dentro de otras rutas. Tambi茅n tendran su propio module, este se encargara de agrupar todas las p谩ginas y empaquetarlos para poder manejar la app.

**shared:** En esta guardaremos los componentes que son utilizados por toda la aplicaci贸n (Menos el login y el registro).


para comenzar a generar nuestra aplicacion crearemos una carpeta auth en la cual estara el login de nuestra aplicaci贸n y el register, utilizaremos las banderas --skip-tests (para que se salte la creaci贸n de los archivos de testing) y -is (para que salte la creaci贸n de los archivos de estilos).
**ng g c auth/login --skip-tests -is** & **ng g c auth/register --skip-tests -is**

Luego comenzaremos a crear los componentes para la p谩gina en la carpeta **pages**
**ng g c pages/nopagefound --skip-tests -is**
**ng g c pages/dashboard --skip-tests -is**

Comenzaremos a crear dentro de la carpeta shared los componentes como breadcrumbs.
**ng g c shared/breadcrumbs --skip-tests -is**
**ng g c shared/sidebar --skip-tests -is**
**ng g c shared/header --skip-tests -is**

## Optimizaci贸n y creaci贸n de modulos personalizados.


## Secci贸n 4

Esta secci贸n esta enfocada en m贸dulos principalmente:

* Crear un m贸dulo personalizado
* Crear rutas hijas
* Comenzaremos a crear m贸dulos para agrupar tareas espec铆ficas
* Realizar cambios en GitHub
* Crear Release Tags que nos permitan descargar el c贸digo f谩cilmente, 
    en caso de que necesitemos volver a comenzar donde nos quedemos.

En clases m谩s adelante del curso, seguimos creando m贸dulos, por lo que esta secci贸n es muy importante