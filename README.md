# Mi primera práctica con Git

Este repositorio fue creado para aprender los fundamentos de Git.

¿Qué es un sistema de control de versiones?
Es una herramienta que permite registrar, organizar y consultar los cambios realizados en los archivos de un proyecto a lo largo del tiempo.

Qué problema resuelve.
Resuelve el problema de llevar un seguimiento de los cambios del código. Permite saber qué se modificó, quién realizó el cambio y cuándo se hizo.

Por qué es útil cuando desarrollamos software.
Es útil porque facilita el trabajo individual y el trabajo colaborativo al permitir ciertas cosas, como: 
Mantener un historial de los cambios realizados.
Recuperar versiones anteriores del código.
Trabajar en nuevas funciones sin afectar inmediatamente la versión principal.
Comparar cambios entre diferentes versiones.
Permitir que varios desarrolladores trabajen sobre el mismo proyecto.

Qué ventajas ofrece frente a guardar copias manuales de un proyecto.
Ahorra espacio, ya que no es necesario guardar una copia completa por cada cambio.
Mantiene un historial organizado de las modificaciones.
Permite regresar fácilmente a versiones anteriores.
Facilita el trabajo colaborativo entre desarrolladores.
Reduce el riesgo de perder código o sobrescribir accidentalmente el trabajo de otra persona.

# ¿Qué es Git?
Es un sistema de control de versiones que permite registrar y administrar los cambios realizados en los archivos de un proyecto, especialmente en proyectos de software.

# Quién creó Git.
Git fue creado por Linus Torvalds, el mismo desarrollador que inició el proyecto del kernel de Linux.

# En qué año fue creado.
Git fue creado en 2005.
# Para qué proyecto fue creado originalmente.
Fue creado originalmente para ayudar a gestionar el desarrollo del kernel de Linux
# Qué significa que Git sea un sistema de control de versiones distribuido.
Cada desarrollador que trabaja con un proyecto puede tener una copia completa del repositorio, incluyendo su historial de cambios.

# Parte 2 — Git vs GitHub
Git es una herramienta de control de versiones. Se instala en tu computadora y sirve para registrar cambios en un proyecto, crear versiones, regresar a estados anteriores y trabajar con ramas.

# Instalación y configuración de Git
Sistema operativo utilizado: macOS
Versión de Git instalada: Git 2.50.1 (Apple Git-155)
Comando utilizado para verificar la instalación: git --version


# Working Directory
Es la carpeta donde se encuentran los archivos del proyecto que estamos modificando.
# Staging Area
Es una zona intermedia donde colocamos los cambios que queremos incluir en el próximo commit.
# Repository
Es donde Git guarda de forma permanente el historial de versiones del proyecto. Cada commit que realizamos queda registrado dentro del repositorio.
# git add
Sirve para mover cambios del Working Directory al Staging Area.
# git commit
Sirve para guardar permanentemente en el repositorio los cambios que se encuentran en el Staging Area.


# ¿Qué es una rama?
Es una línea de trabajo independiente dentro del mismo proyecto. Permite hacer cambios sin afectar directamente la versión principal.
# ¿Por qué un equipo de desarrollo utilizaría ramas?
Permiten que varias personas trabajen al mismo tiempo en diferentes funciones, correcciones o pruebas sin estorbarse entre sí.
# ¿Qué hace git merge?
sirve para combinar los cambios de una rama con otra.

# Para qué sirve .gitignore.
sirve para indicarle a Git qué archivos o carpetas no debe tomar en cuenta ni subir al repositorio.

# Por qué normalmente no incluimos node_modules.
Porque contiene todas las dependencias instaladas y puede ocupar mucho espacio, al igual son demasiados archivos, y eso se puede generar con un npm install.

# Por qué un .env puede contener información que no debería publicarse.
Suele utilizarse para guardar variables de entorno y datos de configuración.


# ¿Qué diferencia existe entre git add y git commit?
git add prepara los cambios y los coloca en el Staging Area. git commit guarda esos cambios preparados de forma permanente en el historial del repositorio.

# ¿Qué ventaja tiene realizar varios commits pequeños en lugar de un solo commit grande?
Permite llevar un historial más ordenado, identificar con mayor facilidad qué cambio causó un problema y regresar solamente a una modificación específica si es necesario.

# ¿Qué diferencia existe entre Git y GitHub?
Git es el sistema de control de versiones que administra los cambios del proyecto. GitHub es una plataforma en línea donde se pueden almacenar repositorios Git y colaborar con otras personas.

# ¿Qué problema resuelven las ramas?
Permiten trabajar en nuevas funciones, correcciones o pruebas sin modificar directamente la versión principal del proyecto. Después, los cambios pueden integrarse mediante un merge.

# ¿Qué información no debería normalmente almacenarse en Git?
No deberían guardarse contraseñas, tokens, claves de APIs, credenciales de bases de datos u otra información privada. Por eso archivos como .env normalmente se agregan al .gitignore.

# ¿Qué ocurriría si borras tu proyecto local pero está publicado en GitHub?
El proyecto puede recuperarse utilizando git clone, ya que GitHub conserva los archivos y el historial de commits que hayan sido enviados al repositorio remoto.

# ¿Por qué Git es especialmente importante cuando varias personas trabajan sobre el mismo proyecto?
Porque permite que varias personas trabajen simultáneamente, mantener un historial de quién realizó cada cambio, utilizar ramas separadas y posteriormente combinar el trabajo de todos de manera controlada.

# ¿Cuál es la diferencia entre git clone, git pull y git push?
git clone descarga por primera vez una copia completa de un repositorio remoto. git pull descarga e integra cambios nuevos del repositorio remoto en una copia que ya tienes. git push envía tus commits locales al repositorio remoto.

# ¿Por qué un commit no aparece automáticamente en GitHub?
Porque git commit guarda los cambios únicamente en el repositorio local de tu computadora. Para enviarlos a GitHub es necesario realizar un git push.









