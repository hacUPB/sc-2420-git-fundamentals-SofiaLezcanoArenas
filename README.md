# Proyecto: Sistemas de Control de Versión
## Descripción
Este proyecto explora los fundamentos de los sistemas de control de versión, con un enfoque principal en Git. Se aborda desde su definición hasta los comandos esenciales por consola para la gestión de repositorios.
## Estado del proyecto
Aunque podría parecer terminado, el proyecto podría seguir recibiendo actualizaciones, específicamente en el archivo ``evidencia.md``, puesto que hay más comandos por añadir a la lista.
## Experiencia trabajando con un disco duro externo
Con el objetivo de evitar transportar un portátil a la universidad constantemente, se intentó trabajar almacenando los repositorios localmente en un disco duro extraíble.

Al comienzo no se visualizaba problema aparente, hasta que en el ejercicio de clonar un repositorio remoto, al cambiar de computador, salían varios errores, además que no se podía observar el `(main)` o `(master)`, cosa que generaba desconfianza. Al no ver futuro por ese camino, se movió el repositorio a la carpeta Documents del computador, allí, ya se podía observar la rama, sin embargo, los errores para conectar con el repositorio remoto continuaban, es así, que se inició el proceso de la actividad desde el primer paso en una ubicación propia del computador.

En conclusión, si el proyecto es muy largo y debe trabajarse tanto en clase como en casa, lo ideal será transportar el portátil para evitar problemas y ahorrar pasos.
## Bibliografía
- [Página del curso sistemas computacionales](https://confusion-snapper-025.notion.site/Control-de-Versi-n-857e02a8a3074f53a1a0d511e0d6ef65)
- [Qué es el control de versiones](https://www.atlassian.com/es/git/tutorials/what-is-version-control#:~:text=Los%20sistemas%20de%20control%20de,a%20lo%20largo%20del%20tiempo.)
- 
- [Gitignore Explicado: ¿Qué es Gitignore, y cómo agregarlo a tu repositorio?](https://www.freecodecamp.org/espanol/news/gitignore-explicado-que-es-y-como-agregar-a-tu-repositorio/)
- [Conversación con ChatGPT sobre el archivo .gitignore](https://chatgpt.com/share/1954c76b-78f6-4fcc-91a7-2654c2a29d14)
## Anexo
### Clonar y configurar un repositorio
Para clonar este repositorio de GitHub a Git, primero debe entrar al directorio del computador donde desee ubicarlo.

Introduzca el comando
```
git clone https://github.com/hacUPB/sc-2420-git-fundamentals-SofiaLezcanoArenas.git
```
Tenga en cuenta, que ya contiene el enlace de este repositorio.

Cuando realice algún cambio, agregue los archivos a la zona STAGE utilizando 
```
git add nombreArchivo.extensión
```
En caso de querer añadir todos los archivos a la zona STAGE, se puede usar
```
git add .
```
Realice el commit con 
```
git commit -m "mensaje descriptivo del commit"
```
Finalmente, para sincronizar los cambios realizados con el repositorio correspondiente en GitHub, debe usar el comando
```
git push
```

Para una guía más visual del proceso, puede revisar el siguiente tutorial de YouTube:

[Clonar un repositorio Git de GitHub](https://www.youtube.com/watch?v=kw72-dm7yNI)