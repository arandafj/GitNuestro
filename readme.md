# Practica 1 — Git Hub

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1. Permite deshacer el último commit realizado. Perdiendo los cambios 
del working copy y quedándose vacía el stagin area.   

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog para localizar el commit. Y con git reset --hard 92952dd,  restauramos el commit 
indicado dejándolo como estaba. 

- El merge del paso 13, ¿Causó algún conflicto? No ¿Por qué? Ya contiene el trabajo de la 
rama absorbida. La rama que está tratando de fusionar(master) es padre de la rama actual (styled).

- El merge del paso 19, ¿Causó algún conflicto? Si ¿Por qué? En las dos ramas se tocan las mismas 
lineas del mismo archivo.

- El merge del paso 21, ¿Causó algún conflicto? No ¿Por qué? No crea conflictos porque las líneas 
de los archivos no están en la misma posición, por lo que no coinciden y no genera conflictos.  

- ¿Qué comando o comandos utilizaste en el paso 25?
git graph. Alias obtenido con git --global alias.graph “log --graph --decorate --pretty=oneline”.
 
 - El merge del paso 26, ¿Podría ser fast forward? Si ¿Por qué? Puedo acceder por el grapho en una 
única dirección hacia la rama title.
 
- ¿Qué comando o comandos utilizaste en el paso 27? 
git reset HEAD~1. Este comando me permite deshacer el commit manteniendo el working copy, y al 
deshacer el commit que se crea al mergear, deshago el ‘merge no fast-forward’.

- ¿Qué comando o comandos utilizaste en el paso 28?
git checkout -- git-nuestro.md
 
- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog
git reset --hard 73b8581

- ¿Qué comando o comandos usaste en el paso 32? 
git reflog 
git reset --hard e4ce971 

- ¿Qué comando o comandos usaste en el punto 33? 
git reflog
git reset --hard 73b8581

