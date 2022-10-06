# Cuestionario

A) ¿Qué comando utilizaste en el paso 11? ¿Por qué?  

> `git reset --hard HEAD~1`

> Porque este comando permite deshacer el último commit perdiendo los cambios.

B) ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?   Primero el comando git reflog para ver el historial de mis acciones y así poder acceder al hash del commit que tenía que rehacer. Y posteriormente el comando git reset hash, es decir el comando git reset más el hash del commit borrado. Al presionar enter se rehace el commit que había eliminado. Y usar finalmente el comando git restore don-quijote.md para restaurar el contenido el archivo.  


C) El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No causó ningún conflicto por que no lo llegué a hacer. Por que sé que un merge se puede hacer de abajo hacia arriba y en este caso si lo intentase haciendo un merge en el que styled absorviese a main, el programa no me lo permitiria al estar este último más abajo que styled. 



D) El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí se causo un conflicto ya que las ramas que se querían fisionar no tenían exactamente el mismo contenido. 


E) El merge del paso 20, ¿Causó algún conflicto? ¿Por qué? 
No se causó ningún conflicto, por que este paso era posible entre las ramas y main y styled por sus posiciones y por sus contenidos. 


F) El merge del paso 24, ¿Podría ser fast forward? ¿Por qué? 
Podría serlo, pero como en el ejercicio se señaliza que se ha de realizar un no fast forward, en este caso no lo será. 


G) ¿Qué comando o comandos utilizaste en el paso 25?  
Utilicé git reset HEAD~1 para volver al working copy. 



H) ¿Qué comando o comandos utilizaste en el paso 26?   
Utilicé git checkout don-quijote.md



I) ¿Qué comando o comandos utilizaste en el paso 27? 
 Utilicé el comando git branch -d title y no me lo permitía por lo que lo forcé utilizando el comando git branch -D title y se pudo hacer correctamente la acción.


J) ¿Qué comando o comandos utilizaste en el paso 28? git reset fa1ea71 para recuperar el commit y posteriormente he utilizado git add . y git commit 


K) ¿Qué comando o comandos utilizaste en el paso 30? git tag nombre para crear los tags y git checkout para moverme entre los commits. 
