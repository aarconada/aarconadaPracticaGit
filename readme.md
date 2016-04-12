-Comando en el paso 11

	git reset --hard HEAD~1
	He usado este comando para volver un paso atrás (HEAD~1) y que cambie
	el working copy con el modificador --hard.

-Comandos para el paso 12

	git reflog
	git reset --hard HEAD@{1}
	He usado estos comandos primero para verificar el orden de los commits
	y el segundo para avanzar otra vez al commit que ya teníamos creado
	con las modificaciones del texto. También utilizando --hard para que
	actualice el working copy

-Merge del paso 13
	
	No  ha causado ningún conflicto porque la rama styled ya contiene
	toda la info de master.

-Merge paso 19

	Ha causado conflicto porque en la rama htmlify habíamos cambiado
	líneas del archivo de forma distinta a como estaban en la rama style
	Por esto hemos tenido que cambiar a mano el archivo.

-Merge paso 21
	
	No ha causado conflicto porque ha realizado un merge fast forward por 
	defecto ya que la rama styled contenía a master. El mismo resultado
	se habría conseguido forzando que no fuera fast forward pues no se
	habrían generado conflictos.

-Comandos paso 25
	
	git log --graph

-Merge paso 26

	Podría ser fast forward porque la rama title ya contiene a master,
	forman una lista.

-Comandos paso 27

	git reflog	
	git reset HEAD@{1}

-Comandos paso 28

	git checkout git-nuestro.md

-Comandos paso 29

	git branch -D title

-Comandos paso 30
	
	git reflog
	git checkout e0986f6
	git branch title
	git checkout master
	git merge  --no-ff title 

-Comandos paso 32

	git log
	git checkout 337808449d05ad78a602990cc189a8fb2c9e55a0

-Comandos punto 33

	git log
	git checkout 99c987f0f660934153cd778fc1c323ba84838a5b
