#### Repositorio:

Todo lo que hemos estado viendo es para gestionar las versiones de nuestro proyecto de manera local, pero que pasa si deseo que otros colaboren con mi proyecto o incluso colaborar en proyectos??

Por eso el uso de **repositorios remotos** \(repositorios alojados en Internet

Repositorios conocidos:

1. **Github**, los repositorios privados son de pago

2. **GitLab**, aquí no pagas nada \(tip: Si utilizas este repositorio y te registraste con gitHub\(cómo lo hice yo\)deberás añadirle una contraseña en opciones de la cuenta \)

3. **Bitbucket**, aquí tampoco

Pasos:

  
1.  Debes tener creado una carpeta tanto local y remoto con el mismo nombre, pero sólo para facilitar su uso.

2. Copia el link que encontraras una vez creado el repositorio remoto, algo así:

```
https://gitlab.com/usurio/proejctPrivate.git
```

3. Vamos al termial \(si usas mac\) o al cmd\(Windows\).

Es igual que un nuevo proyecto

a. `$ git remote add origin [DIRECTORIO GIT ] // conecta el remoto con el local`

b. `$ git remote -v //listado`

c. `$ git remote remove origin //quita esa conexión`

d.  `$ git push origin RAMA (master)// manda nuestro cambios al servidor`



Vale, todo esto nos ha servido para enlazar nuestro proyecto con un repositorio remoto, ahora vamos a ver como clonamos un repositorio para colaborar con este o simplemente, examinar el código:

```
git clone https://gitlab.com/usurio/proejctPrivate.git
```

Y listo !!!!✌️✌️✌️✌️

