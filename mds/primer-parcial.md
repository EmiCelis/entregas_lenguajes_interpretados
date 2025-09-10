# Examen Primer Parcial

#### - ¿Qué es y para qué sirve Visual Studio Code?

Visual studio code es una herramienta de codigo que sirve principalmente para programacion en lenguaje html o web siendo que se conforma por una terminal a la que se le pueden integrar varios aditamientos para programar en la consola.

#### - Qué es y para qué sirve la Terminal de Comandos?
La terminal sirve para poder ejecutar acciones dentro de la consola solamente usando comandos sin tener que hacerlo de manera externa.

#### ¿Qué es y para qué sirve Markdown?
Markdown es un formato de texto que sirve para la redacción de archivos, a la par que se puede usar ya sea para paginas web y documentos 

#### ¿Qué es y para qué sirve Git?
Git es una terminal que hace de consola de comandos siendo que se puede usar junto a git-hub para ser quien transporte los archivos locales a los repositorios correspondiente.

#### ¿Qué es y para qué sirve GitHub?
Git-Hub es una herramienta de trabajo que sirve para subir la documentacion y almacenamiento de proyectos en un repositorio, adjunto a un back log que muestra todo lo hecho previamente por el usuario.

#### ¿Para qué sirven los siguientes comandos: pwd, whoami, touch, mkdir, cp, mv, ls, clear, cd y rm?
pwd sirve para ver la ruta actual del directorio.
whoami nos enseña la información de nuestro user.
touch es un comando que se usa para crear otros archivos en la ruta del directorio actual.

#### ¿Qué significan los siguiente caracteres en la terminal de Comandos: ./, ../, /, y ~?
Son los niveles de la carpeta actual, es decir que al ejecutar alguno de estos comandos te pueden llegar a subir o bajar un nivel en la carpeta del repositorio.

#### ¿Cómo se inicializa un repositorio en Git?
Para hacer un repositorio basico en git, tenemos que tomar en cuenta lo basico de la terminal que en este caso obligatoriamente
debemos de tener la herramienta de Git-Bash. Viendo que podemos crear una carpeta o cualquier documento dentro de la ruta, se debe antes usar los comando de git config para poder agregar nuestro correo y nombre de usuario durante la sesion que vamos a crear el repositorio. Para crear el repositorio como tal hay ejecutar el comando "mkdir" para hacer una subcarpeta que podra contener archivos md de nuestro repositorio, adjunto a que podemos igualmente usar "touch + (nombre_del_archivo.extension)" para agregar un README en la carpeta.
#### ¿Cómo creas un repositorio en GitHub?
 Luego de haber hecho un repositorio en Guit (tanto la config como el contenido), vamos a crear un repositorio directamente en la pagina de git hub viendo que sera la ruta donde subiremos todo el contenido de local a remoto para luego proceder a subir todo con "git add .". Esto nos ayudara a subir todos los cambios realizados y usar un commit con el nombre de la accion que estamos haciendo en la terminal como por ejemplo: "git commit -m "Realizando cambios examen primer parcial". Despues de ello hacemos el comando "Git Push" el cual nos servira para subir todo el contenido creado al repositorio que se encuentra en nuestro sitio de git hub

#### ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
Puedes realizar el comando git add ., git commit -m y git push para subir este contenido a tu pagina de git-hub siendo que al hacer esto te redirigira a iniciar sesion con tu cuenta de it-hub.

#### ¿Cuál es el flujo básico de trabajo en Git y GitHub?, explicalo indicando la secuencia de comandos.
git add .

git commit -m "Creando documento Examen.md"

git push

git log --oneline

#### ¿Para qué sirve el archivo .gitignore?
El archivo .gitignore sirve para anular ciertos archivos en el repositorio por ejemplo ejecutables que se pueden anular con el comando "*.exe" dentro del documento.

#### ¿Cuál es el propósito de una rama?
Crear un espacio especificamente para esa documentación evitando hacer todo en la rama main.

#### ¿Qué es una fusión?
Es cuando fusionas los contenidos de una rama con otra estando en la rama que quieres que reciba los contenidos de la otra usando el el comando git merge.

#### Explica los diferentes tipos de fusión que existen.
Fusion Fast Foward cuando es una fusion hecha rapidamente y una fusion manual que tarda un poco más. 

#### ¿Cómo puedes ver el historial de tu repositorio?
Escribiendo git log --oneline

#### ¿Cuál es el propósito de una etiqueta?
Marcar con un tag aquella parte del repositorio siendo que ver a que se referia.