* ¿Qué comando utilizaste en el paso 11? ¿Por qué?

git reset --hard HEAD~1  porque se pide que se pierdan los datos del working copy, y por eso se pone el modificador  --hard

* ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Hice  git reflog  para conseguir el id del commit, y despues  git reset --hard 860d230 para recuperar el commit moviendo el HEAD.

* El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No causo ningun conflicto ya que la rama Style estaba mas avanzada que la rama master y ya tenia todos los cambios en ella.

* El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 

Si causó conflicto, porque el archivo git-nuestro.md estaba modificado en las dos ramas de manera distinta en lineas coincedentes.

* El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 

No causó conflicto porque el archivo solo estaba modificado en la rama Styled.

* ¿Qué comando o comandos utilizaste en el paso 25?

utilice primero  git log --graph  y luego  git log --graph --decorate --pretty=oneline  para ver el grafo mas claro

* El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

Si podria ser fast forward porque no hay commits nuevos en la rama master desde que se creó la rama title, las dos ramas forman una lista.

* ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1

* ¿Qué comando o comandos utilizaste en el paso 28? 

git checkout -- git-nuestro.md

* ¿Qué comando o comandos utilizaste en el paso 29? 

git branch -D title

* ¿Qué comando o comandos utilizaste en el paso 30? 

git reflog  y luego  git reset --hard 380ed0f

* ¿Qué comando o comandos usaste en el paso 32?

git reflog  y luego  it reset --hard 9fdf4c7

* ¿Qué comando o comandos usaste en el punto 33?

git reflog  y luego  git reset --hard 6c76f20
