# **Vamos a ello !**

#### **Para los de MAC: **

Pues para hacer más fácil la instalación te recomiendo como hice yo, instalar [https://brew.sh/ ](https://brew.sh/ "Homebrew")[🍺](http://emojipedia.org/beer-mug/), sólo tienes que copiar el código que te pone ahí y ta tan !!! instalado:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Un vez que tengas homebrew instalado sólo tienes que intalar git y es así de fácil:

```
brew install git
```

Luego tienes que pulsar enter y la magia lo hará todo, en algún momento te pedirá la contraseña de usuario de tu sesión, la escribes y terminado ! . Me ha tomado más tiemo escribirlo que instalarlo, la verdad jejje

### Para los de Windows:

Bueno Windows tambíen dispone de su instalador de paquetes desde consola, mira este: [https://chocolatey.org/,](https://chocolatey.org/ "chocolatey") a que es mono ese nombre !! .

Bueno lo que tienes que hacer ahora es abrir el cmd con preferencia de administrador, lo has hecho ya ??

Vale, pues ahora copia este código y pégalo :

```
@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin
```

Instalado, ahora instalamos GIT:

```
choco install git.install
```

> #### y .... linux ??? . Pues es que no lo uso, sorry [😳](http://emojipedia.org/flushed-face/)[😳](http://emojipedia.org/flushed-face/)[😳](http://emojipedia.org/flushed-face/)[😳](http://emojipedia.org/flushed-face/)[😳](http://emojipedia.org/flushed-face/)

### Configuramos GIT

---

Configuramos nuestro nombre de usuario:

> ```
> $ git config --global user.name "Margaret"
> ```

Configuramos nuestro email:

```
$ git config --global user.email "margaret@ejemplo.com"
```

eyyy !!! Pero lo estoy haciendo bien ???. Si, mira pon esto:

```
git config --list
```

Sale tu correo y tu nombre de usuario, pues sigue !

Ahora nos queda enlazarlo a nuestro repositorio

## Repositorio

---

Desde el terminal, nos situamos en el repositorio ! y cha cha cha chan !!!

```
git init 
```

Repositorio listo, ten en cuenta que no estamos usando ninguna interfaz y que el uso de git no requiere Internet.

