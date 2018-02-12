# RESUMEN {#git}

Nace para el control de versiones y su creador es [Linus Torvalds](https://es.wikipedia.org/wiki/Linus_Torvalds)

* #### **Sistema de control de versiones centralizado:** {#sistema-de-control-de-versiones-centralizado}

> Tienen un único servidor. La ventaja que tiene es que hay un control de trabajo que cada desarrollador esta llevando a cabo. Mientras que la peor desventaja es que el desarrollo se encuentra en un único servidor y todos son dependientes de ello, si se cae o corrompe, habría un pare en el trabajo

* #### Sistema de control de versiones distribuido {#sistema-de-control-de-versiones-distribuido}

> Se descarga la última versión de repositorio. Se puede trabajar de manera simultánea en diferentes grupos del mismo proyecto

* #### Objetivos de Git en sus comienzos: {#objetivos-de-git-en-sus-comienzos}

> * Velocidad
> * Diseño
> * Fuerte apoyo al desarrollo no lineal \(miles de ramas paralelas\)
> * completamente distribuido
> * capaz de manejar distintos proyectos

* #### Instantáneas de Git: {#instantáneas-de-git}

> Git almacena los archivos como un conjunto de instantáneas y hace referencia a cada uno de ellos, si hay un archivo no modificado, sólo hace un referencia al archivo anterior

* #### Operaciones en local: {#operaciones-en-local}

> Los recursos que utIliza Git son los locales. Trabaja aunque no estés conectado.

* #### Integridad: {#integridad}

> Para la seguridad de datos git utiliza hash SHA-1. No perderás ningún tipo de información, ni tendrás archivos corruptos sin que Git se entere.

* #### Los tres estados: {#los-tres-estados}

> 1. confirmado \( commit \)
>
> 2. modificado \( modified \)
>
> 3. preparado \(Staged\)
>
> Working directory: Aquí es donde editamos y trabajamos con nuestros proyectos
>
> Staging area: decidimos que archivos pasan y cuales no
>
> Repository: Registro de todo nuestro proyecto



