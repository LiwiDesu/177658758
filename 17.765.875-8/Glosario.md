# Taller Nº0: Git y Bitbucket
## Glosario:

1. ***Control de versiones (VC):***
El control de versiones es un sistema que permite almacenar un registro de cambios realizados en diferentes archivos a lo largo del tiempo, logrando así organizar diferentes versiones de un determinado documento para acceder a versiones específicas de los mismos.
Cabe destacar que a pesar de que esté pensado  para registro de códigos también se puede llevar un control de versiones de cualquier archivo que se encuentre en un ordenador.
https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones
2. ***Control de versiones distribuido (DVC):***
En un sitema de control distriuido tanto los usuarios como el servidor tienen los mismos archivos, esto hace el sitema mas seguro ya que si el servidor muere
podriamos restaruar los archivos desde los colaboradores copiando algun repositorio al servidor nuevamente.
https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones
3. ***Repositorio remoto:***
Son versiones del proyecto que se encuentran depositados en Internet o en la red. Se puede 
tener varios,  puede ser de sólo lectura, o lectura y escritura.
git-scm.com
4. ***Repositorio local:***
El repositorio local es el que se encuentra en el computador.
git-scm.com
5. ***Copia de trabajo / Working Copy:***
Aquí es donde podemos hacer cualquier cambio y no afectar nuestro repositorio en lo absoluto.
En cuanto modificamos algo de nuestro código, éste tiene status de modificado.
https://medium.com/laboratoria-how-to/describiendo-el-flujo-de-trabajo-en-git-ede2eee5b589
6. ***Área de Preparación / Staging Area:***
El área de preparación es un sencillo archivo, generalmente contenido en tu directorio de Git, que almacena información 
acerca de lo que va a ir en tu próxima confirmación. A veces se le denomina índice, pero se está convirtiendo en estándar 
el referirse a ella como el área de preparación.
https://git-scm.com/book/es/v1/Empezando-Fundamentos-de-Git
7. ***Preparar Cambios / Stage Changes:***
Se preparan los archivos, añadiendolos a tu área de preparación.
https://git-scm.com/book/es/v1/Empezando-Fundamentos-de-Git
8. ***Confirmar cambios / Commit Changes:***
Se confirman los cambios, lo que toma los archivos tal y como están en el área de preparación, y 
almacena esas instantáneas de manera permanente en tu directorio de Git.
https://git-scm.com/book/es/v1/Empezando-Fundamentos-de-Git
9. ***Commit:***
Corresponde a la acción de guardar o subir archivos al repositorio remoto (una actualización de cambios) también 
puede hacerse al repoitorio local (dependiendo de donde se haya creado el repositorio).
https://codigofacilito.com/articulos/commits-administrar-tu-repositorio
10. ***clone:***
Crea una copia del repositorio desde una fuente externa. También añade la localización original
https://www.siteground.es/kb/tutorial-git-comandos/
para que puedas llamarla de nuevo y hacer push si dispones de los permisos necesarios.
11. ***pull:***
Hace una llamada a los archivos del repositorio remoto y los fusiona con el local. Este 
comando equivale a una secuencia de git fecth y git merge.
https://www.siteground.es/kb/tutorial-git-comandos/
12. ***push:***
Push envía los cambios que se han hecho en la rama principal de los repertorios remotos que están asociados con el directorio que está trabajando.
https://www.hostinger.es/tutoriales/comandos-de-git
13. ***fetch:***
Hace una llamada a todos los objetos de un repositorio remoto que no están presentes en el local.
https://www.siteground.es/kb/tutorial-git-comandos/
14. ***merge:***
Este comando se usa para fusionar una rama con otra rama activa.
https://www.hostinger.es/tutoriales/comandos-de-git
15. ***status:***
Este comando muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser añadidos o 
comprometidos. Imprime un reporte del estado actual del árbol de trabajo local.
https://apuntes-snicoper.readthedocs.io/es/latest/git/comandos_basicos.html
https://www.hostinger.es/tutoriales/comandos-de-git
16. ***log:***
Este comando muestra una lista de commits en una rama junto con todos los detalles.
https://www.hostinger.es/tutoriales/comandos-de-git
17. ***checkout:***
El comando checkout se puede usar para crear ramas o cambiar entre ellas.
https://www.hostinger.es/tutoriales/comandos-de-git
18. ***Rama / Branch:***
Una rama o branch es una copia exacta del proyecto principal en el cual debemos crear como primer paso antes de realizar realizar un cambio.
Es una buena práctica generar un branch por cada cambio a realizar.
Git no almacena los datos de forma incremental, al crear una rama se crea una copia exacta de la versión principal donde comenzaremos a realizar nuestras modificaciones.
Debemos realizar commits por cada modificación realizada en el branch. Éstos sí se acumulan en la rama actual creando de esta manera una versión independiente de la rama principal (master).
https://posicionamiento-web-seo.com.ar/github-comandos-basicos/
19. ***Etiqueta / Tag:***
Etiqueta (tag) puntos específicos en la historia como importantes. Generalmente la gente usa esta
funcionalidad para marcar puntos donde se ha lanzado alguna versión (v1.0, y así sucesivamente).
https://git-scm.com/book/es/v1/Fundamentos-de-Git-Creando-etiquetas
