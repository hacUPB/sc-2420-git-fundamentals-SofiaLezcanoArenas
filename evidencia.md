# Sistemas de control de versión
## ¿Qué son?
Los sistemas de control de versión ayudan a mantener un historial de cambios realizados a archivos. Evita procesos manuales, que son más demorados y pueden conllevar a errores, ya que gestiona automáticamente las versiones de los archivos seleccionados.
## Importancia
Al hacer seguimiento y guardar información de los archivos elegidos a medida que se trabaja en ellos, estos sitemas permiten recuperar versiones anteriores, lo cual es bastante útil si se ha cometido un error en la versión actual o si se desea recuperar información que en esta versión se ha eliminado.

Además, los sistemas de control de versión que cuentan con acceso a un servidor, facilitan el trabajo en equipo. Cada integrante puede ir generando su historial de versiones sin afectar las de los demás y todos tienen acceso al mismo.

# Comandos por consola para la gestión de repositorios
- `pwd` dice la ruta del directorio en el que te encuentras
- `cd ~` lleva al home del computador
- `ls` muestra el contenido de la carpeta
- `ls -al` lista el contenido de la carpeta incluyendo archivos y carpetas ocultas
- `cd nombreCarpeta` permite entrar a un directorio/carpeta
- `cd ..` retrocede una carpeta (lleva a un espacio más afuera que el actual)
- `clear` limpia la consola
- `cat nombreArchivo` muestra lo que hay dentro del archivo
- `mkdir nombreDirectorio` crea un nuevo directorio
- `git --version` indica la versión de Git instalada en el computador
- `rmdir nombreDirectorio` borra un directorio vacío
- `rm nombreArchivo` borra un archivo
- `touch nombre.extensión` crea un archivo del tipo indicado
- `git add nombre.ext` el archivo indicado se lleva a la zona STAGE
- `git add .` todos los archivos del directorio se llevan a la zona STAGE
- `git commit -m "mensaje"` se realiza un commit de los archivos que se encuentren en la zona STAGE
- `git rm --cached nombre.ext` se saca el archivo indicado de la zona STAGE
- `vi nombre.ext` abre el archivo en un editor de texto dentro de la consola
- `i` dentro del editor anterior, este comando se utiliza para editar
- `esc` dentro del editor anterior, este comando es para salir del modo edición
- `:x` dentro del editor anterior, este comando es para guardar los cambios
- `git config --list` lista las configuraciones de Git
- `code .` abre el directorio actual en visual studio code
- `git status` muestra el estado del directorio actual
- `git log` muestra el historial de commits
- `git restore nombre.ext` borrar cambios en el archivo
- `git log --oneline` muestra el historial de mensajes de los commits
# Repositorios
## ¿Qué son?
Es donde se almacenan archivos y carpetas junto con su historial de cambios a lo largo del tiempo.
## ¿Cuál es su papel en el trabajo colaborativo?
Facilita el desarrollo de un proyecto en equipo al dar la posibilidad de trabajar en simultáneo sin miedo a afectar el trabajo de los demás. También ofrece el poder unir las partes deseadas para el producto final.