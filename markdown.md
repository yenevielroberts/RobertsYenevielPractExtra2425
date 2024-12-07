# Actividad: git add y Patrones

### Estructura Inicial del Proyecto

- He creado los siguientes archivos y directorios con los comandos mkdir -p y touch

![Parte1](Imagenes-consola/Parte1.png)

- Inicialización del repositorio con el comando git init

![Parte1-3-1](Imagenes-consola/Parte1-3-1.png)

- Con el comando git add se han pasado todos los archivos al staging area
![PArte1-3-2](Imagenes-consola/Parte1-3-2.png)

- Primer commit con el comando git commit -m""
![Parte1-3-3](Imagenes-consola/Parte1-3-3.png)

### Prepara archivos con patrones simples
-Con el comando git add docs/*.txt he pasado al staging area todos los archvivos con extension .txt dentro del directorio docs.
Con el alias git s puedo ver el estado de los archivos. 
![Parte2-1](Imagenes-consola/Parte2-1.png)

- Commit de los archivos con extension .txt dentro del directorio doc con el alias git (git commit -m "")
![Parte2-2](Imagenes-consola/Parte2-2.png)

### Trabaja con subdirectorios y extensiones
-Con el comando git add scripts/*.js ':!scripts/config.js' he pasado al staging area todos los archivos con extension .js del directorio scripts excepto cnfig.js
Con git s (git status --short) muestro el estado.

![parte2-2-1](Imagenes-consola/parte2-2-1.png)

- Commit con el alias git c (git commit -m "")
![pare2-2-2](Imagenes-consola/parte2-2-2.png)

- Con el alias git s puedo mostrar lo arhivs con cambios no rastreaados
![pare2-3-2](Imagenes-consola/parte2-3-1.png)

### Máscaras en niveles 
- Con el comando git add images/ ':!images/*.gif' he pasado al taging area todos las imagenes dentro de la crpeta imagenes excepto las que tienen la extensin .gif
Con el alias git  pueo mostrar el estado de los archivos
![pare2-3-2](Imagenes-consola/parte2-3-2.png)

- Con el alias git c he hecho un commit 
![parte2-3-3](Imagenes-consola/parte2-3-3.png)

- Push al repositorio remoto con el comando git push origin main

![push-repositorio-remoto](Imagenes-consola/push-repositorio-remoto.png)

Se me olvido hacer una capture de cuando vincule el repositorio local con el remoto pero l he hecho desde la consola con el comando git remote ad origin más la url del reositorio del git hub



