# GIT FLOW

Esta mañana en el trabajo he tenido la suerte de poder conocer GIT-FLOW, me ha explicado la gran utilidad que conlleva tener modularizada las ramas, de poder aislar cada funcionalidad. Ahora para poder entenderlo mejor haremos un resumen:

fuente: [http://nvie.com/posts/a-successful-git-branching-model/](http://nvie.com/posts/a-successful-git-branching-model/)

Miremos lo más importante, el gráfico en el que podremos ver la estructura real, los flujos de trabajo:

![](/assets/git-flow)

Expliquemos como va esto:

1. Las dos ramas principales:
   1. \_MASTER: \_Es la rama 10, la que se debe llevar a producción.
   2. \_DEVELOP: \_Es la rama que llevará la planificación del proyecto
2. Ramas auxiliares:
   1. \_FEATURE: \_Esta rama se utiliza para crear nuevas características del proyecto, se origina de la rama develop  y se incorpora en la rama develop.
      1. #### Creando un feature branch: {#creating-a-feature-branch}
      2. ```
         $ git checkout -b myfeature develop
         Switched to a new branch "myfeature"
         ```
      3. #### Incorporando feature on develop: {#creating-a-feature-branch}
      4. ```
         $ git checkout develop
             Switched to branch 'develop'
         $ git merge --no-ff myfeature
             Updating ea1b82a..05e9557
             (Summary of changes)
         $ git branch -d myfeature
             Deleted branch myfeature (was 05e9557).
         $ git push origin develop
         ```
   2. \_RELEASE: \_Esta rama que casi está en producción, realiza los últimos ajustes y se corrigen los últimos bugs. Se originan a partir de la rama develop y se incorporan a master y develop
   3. \_HOTFIX: \_Esas ramas se utilizan para corregir errores y bugs en el código en producción. Se origina a partir de la rama master y se incorporan a la master y develop.



