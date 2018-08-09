## ¿Y esto para qué?

Pues con esto vamos a dar acceso a una computadora específica, usamos esta llave en lugar de un nombre de usuario y un password, este tipo de conexión nos hará mejorar nuestra experiencia como desarrollador. Por tanto, usemos el loggin por medio de ssh en el servidor , en este caso nuestro servidor sería \(GitHub\).

## Comando rápidos:

---

#### Comprobar una SSH-Key

1. $ ls -al ~/.ssh

#### Generar una SSH-Key

1. ssh-keygen -t rsa -b 4096 -C "your\_email@example.com"
2. Enter a file in which to save the key \(/Users/you/.ssh/id\_rsa\): \[Press enter\]
3. Enter passphrase \(empty for no passphrase\): \[Type a passphrase\]
4. Enter same passphrase again: \[Type passphrase again\]

#### Añadiendo SSH key a the ssh-agent:

1. $ eval "$\(ssh-agent -s\)" Agent pid 59566  
2. $ ssh-add -K ~/.ssh/id\_rsa

#### Añadiendo SSH key a la cuenta GitHub:

1. $ pbcopy &lt; ~/.ssh/id\_rsa.pub
2. Settings &gt;&gt; SSH and GPG keys &gt;&gt;  New SSH key or Add SSH key &gt;&gt; Add SSH key &gt;&gt; 

#### Testeando:

1. $ ssh -T git@github.com
2. "Hi username! You've successfully authenticated, but GitHub does not provide shell access"

#### Empezando a trabajar:

1. $ ssh-keygen -p



