### COMANDOS

* `$ git init`

* `$ git status`

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

* `$ git branch -D RAMA //borrar ramas`

* `$ git branch -b RAMA //crea la rama y la mueve`

---

#### Head:

Es el commit donde nos encontramos

---

#### Ramas:

Es una linea de tiempo de nuestro proyecto

Cuando se crea una rama, se crea a partir de donde esta nuestro head

Nos sirve para movernos entre commits y entre ramas:

`$ git checkout Test`

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



