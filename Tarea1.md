# Diferencia entre `git merge` y `git merge --no-ff`

El comando `git merge`  nos permite fucionara dos ramas que usualmente suele ser una fucion entre una rama experimental y la rama master siempre y cuando no haya ningun cambio en la rama principal se puede hacer esta union 

El comando  `git merge --no-ff` tambien fucionara las ramas pero previo nos mostrara un editor de texto donde nos dira que coloquemos un mensaje de commit indicando porque es necesario hacer la fusion de las ramas.

Por lo tanto la diferencia entre ambos es que con el `git merge --no-ff` nos mostrara el editor de texto para asi tener mas control de los cambios realizados esto nos es util cuando trabajamos en equipo pues se mantiene un registro de todos los cambios.