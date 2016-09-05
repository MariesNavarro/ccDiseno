## ccDiseno

Algunos ejercicios realizados en la Especialidad de Codigo Creativo para Diseño. CENTRO.

_______________________________________
## Ejercicios
 ej 1. Poner su nombre en este archivo readme.md

    1.1 Hacer tutorial de comandos de git (tomen nota y sean pacientes).

    1.2 Agregar carpeta con su nombre al repositorio.

 ej 2.

## Participantes:

 - Eduardo H. Obieta
 - Maries N
 -
 -

_______

_______

### Ejercicio 1.
##### Incorporar su nombre en este archivo (readme.md), para ello utilizaremos github desde la terminal.
##### Agregar una carpeta con su nombre al repositorio.
_______

 Una vez teniendo instalado git en su sistema, sigue estos pasos:
A. Clonar el repositorio,
 * desde la terminal navega a la carpeta destino "cd tusDocumentos/tuCarpetaGit", acá dejo un link con los comandos básicos UNIX

 > http://www.dummies.com/computers/macs/mac-operating-systems/how-to-use-basic-unix-commands-to-work-in-terminal-on-your-mac/
 -  Clona el repositorio con:

 ```sh
$ git clone https://github.com/laadeho/ccDiseno.git
```
 - Te pedirá nombre de usuario y contraseña.

> Si quedaron dudas de los comandos de git (cosa que es muy probable), pueden hacer este tutorial express, que es sin dudas muy bueno, (redomendado por Diego Beauroyre). https://try.github.io/levels/1/challenges/1

Una vez clonado el repositorio:

B. Abre el archivo "readme.md" de /tuCarpetaGit que se descargó al clonar el repositorio, está generado en el formato Markdown ".md", que puede ser editado con cualquier editor de texto; o bien, si quieren visualizar mientras editan, pueden hacerlo en http://dillinger.io. Ahí mismo se encuentran las instrucciones para editar un archivo md.

-  En este caso solo necesitamos incorporar nuestro nombre a la lista de participantes.

C. Crea una carpeta con tu nombre en la ubicación de git (puede ser desde finder), y ejecuta los comandos necesarios para subir dicha carpeta al repositorio:

```sh
$ cd miCarpetaGit
$ cd git status   // conocer el estado del repositorio git
$ cd git pull     // solo en caso de que status nos indique que es necesario actualizar
$ cd git add      // agreguemos nuestros archivos y/o carpetas nuevas
$ cd git commit -am "mensaje"      // Poner mensaje al resto del equipo sobre los cambios
$ cd git push     // Subir nuestros archivos nuevos
introducir nombre de usuario y contraseña (en caso de que lo solicite)
```
