# Robot Guía

El objetivo de este proyecto es desarrollar un Robot que se ubique a sí mismo, que pueda detectar a una persona y se le acerque. Luego, la persona debería de proveer algún tipo de “input” al robot para que este lo dirija hacia un destino específico.

## Manejo del Repositorio

En RAS IEEE UTEC seguimos las pautas Git Karma al momento de realizar commits. Si no las conocen o no se sienten muy familiarizados con estas, los invitamos a leer este pequeño artículo [Pautas Git Karma](http://karma-runner.github.io/5.0/dev/git-commit-msg.html)

Con esto en mente, cabe resaltar que no se aceptarán pull requests que no sigan las pautas mencionadas.

El idioma que se utilizará en el repositorio es el inglés. Este README es lo único que estará en español, como documento introductorio al proyecto.

## Pasos para generar un issue

1. Ir al [enlace](https://github.com/IEEE-RAS-UTEC/Robot-Guia/projects) de proyectos del repositorio y seleccionar el proyecto donde se desee generar el *issue*.
2. Asegurarse que no haya dependencia de otros *issues*, es decir, que el código a desarrollar no dependa de otro *issue* que no esté cerrado (terminado).
3. En la columna "To Do" presionar en el símbolo '+' y crear una nota con el nombre y descripción del *issue*.
4. Convertir la nota a un *issue*, autoasignarse y asignarle un *label* de los que ya están predeterminados.
5. Si es que se va a empezar a desarrollar inmediatamente, colocar la tarjeta en la columna "In Progress".

## Pasos para hacer un pull request

1. Ejecutar el comando *git fetch* para comprobar si hay nuevos cambios en el repositorio.
2. Si es que se considera necesario, ejecutar *git pull* y resolver conflictos si hay.
3. Recomendación: Utilziar gitflow y crear un feature para cada *issue* con el formato "feature/issue[número]".
4. Si no se está seguro de la lógica o de la respuesta **no** hacer un pull request. Solo hacer pull request cuando el *issue* se pueda cerrar.
5. Asignar como revisores a la directiva de RAS IEEE UTEC.
6. Opcional: Avisar por el grupo de whatsapp que se ha hecho un pull request.

## Recomendaciones

* Crear un virtual environment en python con los siguientes paquetes isntalados:
    * Opencv
    * numpy
    * matplotlib (todos los gráficos e imágenes deberán ser ploteados con este paquete)
    * scikit-learn
    * scikit-image

## Directiva RAS IEEE

* Facundo García - fgarciacardenas
* Alessio Ghio - alessioghio
* Nelson Soberón - Nelsonxxji