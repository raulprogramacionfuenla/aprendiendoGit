#### Head:

Es la rama actual, actúa algo así como un puntero, cuando la cambiamos de rama esta apunta hacía esta nueva, mira este gif que es precioso !

![](/assets/git_detached_head_commit.gif)

---

#### Ramas:

Es una linea de tiempo de nuestro proyecto

Cuando se crea una rama, se crea a partir de donde esta nuestro head

Nos sirve para movernos entre commits y entre ramas.

`$ git checkout Test //Para cambiar de rama`

Pues si nos cambiamos de rama podemos avanzar independientemente de lo que haga la master, ya que en la master va la versión final.

```
$ git checkout -b test // Esta linea lo que hace es crear la rama y apuntar a esta rama, sustituye dos lineas
```

![](/assets/import.png)

#### Rama Master:

git init lo genera por default

#### Funciones de Ramas :

1. Nos situamos en la rama maestra
   1. `$ git checkout master`
2. Para incorporar los cambios a la rama _master _
   1. `$ git merge [Rama]`
3. fast forward \(avance rápido\): En respuesta al comando git muestra esta frase, lo que hace es cambiar el puntero a la rama especificada de manera. simple y automática.
4. **No olvides**, eliminar la rama que fusionaste con la master:
   1. `$ git branch -d [Rama`



