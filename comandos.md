### COMANDOS

* `$ git init`

* `$ git status`

  * Si el nombre de tus ficheros aparecen en rojo, no están ~~guardados ~~

* `$ git add ..`

* `$ git add -A //AGREGA TODOS`

* `$ git commit -m “mensaje”`

* `$ git log //lista todos los commit`

* `$ git checkout  // viajamos a través de nuestros commits o nuestras ramas`

* `$ git reset // similar a checkout a diferencia que elimina los commits`

* `$ git reset ——soft //No toca nuestro working area`

* `$ git reset ——mixed //borra el “staging area”, sin tocar el “working area”`

* `$ git reset ——hard // borra absolutamente todo`

* `$ git help`

* `$ git branch // nos sirve para ver las ramas`

  * La rama principal estará señalada por un asterisco. 

* `$ git branch -D NOMBRE_RAMA//borrar ramas`

* `$ git branch -l RAMA //crea la rama`

---

#### Head:

Es la rama actual, actúa algo así como un puntero, cuando la cambiamos de rama esta apunta hacía esta nueva, mira este gif que es precioso !

![](/assets/git_detached_head_commit.gif)

---

#### Ramas:

Es una linea de tiempo de nuestro proyecto

Cuando se crea una rama, se crea a partir de donde esta nuestro head

Nos sirve para movernos entre commits y entre ramas.

`$ git checkout Test //Para cambiar de rama `

Pues si nos cambiamos de rama podemos avanzar independientemente de lo que haga la master, ya que en la master va la versión final. 

```
$ git checkout -b test // Esta linea lo que hace es crear la rama y apuntar a esta rama, sustituye dos lineas 
```

![](/assets/import.png)

#### Rama Master:

git init lo genera por default

#### Funciones de Ramas :

1. Nos situamos en la rama maestra

2. `$ git merge Rama`

3. fast forward \(avance rápido\): simple y automático, archivos diferentes o lineas de código distintas

4. Manual merge: Indica que cambios se desean grabar, mismos archivos, mismas lineas de código

---

#### Repositorio:

Es igual que un nuevo  proyecto

* `$ git remote add origin DIRECTORIO GIT // conecta el remoto con el local`

* `$ git remote -v //listado`

* `$ git remote remove origin //quita esa conexión`

* `$ git push origin RAMA (master)// manda nuestro cambios al servidor`



