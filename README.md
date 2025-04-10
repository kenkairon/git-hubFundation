# git-hubFundation
Educativo y de Aprendizaje Personal

## Tabla de Contenidos
- [Requisitos](#requisitos)
- [Lista de Comandos](#Lista-de-Comandos)
---
## Requisitos

- Github-Foundation: 
---

## Lista de Comandos

1. :Git 
   ```bash
        Es un Sistema de Control de Versiones 
        -Distribuido
        -Integridad de Datos

        - Revisar el historial 
        Descripción: Muestra el historial de commits, incluyendo autor, fecha y mensaje.
        git log
        git log --oneline → versión compacta
        git log --graph --all → visualización en forma de rama

        - Verificar quien hizo cada cambio y cuándo lo realizo
            git blame <archivo>

        - 🔸 Revertir un cambio
            Comandos según la situación:

            Revertir un commit específico sin alterar historial:
            git revert <id-del-commit>

            Deshacer cambios locales (sin haber hecho commit):
            git checkout -- <archivo>

            Restaurar el estado de un archivo al último commit:
            git restore <archivo>

        🔸 Crear un punto único de verdad (snapshot confiable del proyecto)
            git add .
            git commit -m "mensaje claro y descriptivo"


2. :git
    ```bash
   Fue Desarrollado por linus Torvalds su fin es
   Hacer los opuesto CVS(Concurrent Version System)
   Soportar un flujo de trabajo distribuido
   Evitar corrupción o intencional

3. Git
    ```bash
   Es open source
   Es gratuito
   Funciona offline(sin internet)

4. Repositorio de Git
    ```bash
    Un repositorio guarda tu código y su historial de cambios
    El subirectorio .git almacena toda la información del repositorio
    Esto permite colaborar y enviar cambios, facilitando el trabajo en equipo

5. Clonar
   ```bash
   git clone <archivo>

6. Github
    ```bash
   Es una plataforma en la nube para colaborar
   va más alla de almacenar código parte del ciclo de vida desarrollo software

7. Github Puedes
    ```bash
    Almacenar Historial repositorios
    Dar a conocer tu trabajo publicamente
    Administrar los cambios requeridos y bugs

8. Markdown
    ```bash
    Git hub ofrece varios espacios para escribir texto,como el Readme
    issues, pull request

    Sirve para añadir titulos , link, imagenes, bloques de código, formatear texto

9. Diferencias entre git y github
    ```bash
    git funciona offline, Código abierto, software en pc, movil y CLI

    github si depende de git , Plataforma privada, puedes generar equipos de trabajo, redes

10. Explicación de Comandos
    ```bash
    graph : Dibuja un gráfico de commits
    all: Muestra los commits de todas las ramas
    stat: Muestra archivos y cantidad de lineas modificadas
    patch: Muestra los detalles de los cambios
    oneline: Muestra cada commit en una sola linea(mejor lectura)

11. git cherry-pick
    ```bash
    Selecciona commit específicos 
    Cuando deseas incorporar un cambio sin fusionar la rama completa
    git cherry-pick <commit>

12. git reset 
    ```bash 
    Deshacer cambios en el repositorio
    --soft: Mueve el HEAD a otro commit pero deja los cambio en el stagging
    --mixed: Mueve el HEAD a otro commit, mantiene cambios pero lo quita de stagging
    --hard: Mueve el HEAD y elimina los cambios

13. git reflog
    ```bash 
    Recupera y rastrea el historial
    Lista con todas las actualizaciones de los HEAD

14. git commit--amend
    ```bash 
    Modifica el último commit realizado
    Reescribe el historial por lo que se debe usarse en commits que no han sido subido(push)

15. git blame
    ```bash 
    Identifica el responsable de un cambio
    git blame <archivo>

16. git bisect
    ```bash 
    Identifica commit que introdujo errores
    git bisect start
    git bisect bad
    git bisect good
    git bisect reset

17. git revert
    ```bash 
    Revierte los cambios de un commit específico
    No modifica el historial anterior
    Crea un nuevo commit

18. git tag 
    ```bash 
    Marca puntos importantes en el historial
    Versiones o Cambios significativos
    Facilita la navegación por el historial 

19. Configuración Inicial
    ```bash 
    Configurar nombre de usuario
    git config --global user.name "usuario"
    Configurar correo electronico
    git config --global user.email "ejemplo@email.com"

20. Funcionamiento de Git
    ```bash 
    Area de Trabajo: Las carpetas o Archivos que quieres gestionar
    Area de Preparación: Stagging : Guardar los Cambioscon  un commit
    Repositorio: Se Encuentra Area de Trabajo, Area Preparación y toda la información

21. Commit
    ```bash 
    HAcer un snapshot del proyecto , representa los registro de cambios realizados del proyecto

22. Comandos Básicos
    ```bash 
    git init : Inicicializamos un inicio de un trabajo para el repositorio
    git clone: Clonamos el proyecto
    git status: Saber en que status esta el archivo
    git add <nombre archivo> git add . / git add -A / git add --all = Agregamos todos los archivos al area stagging
    git branch  = ramas
    git merge

23. Verificacos los archivos ocultos ./  ../ .git/ 
    ```bash 
    ls -a

24. Commit 
    ```bash 
    touch index.html
    git add index.html
    git commit -m "Creamos el archivo index.html "

25. Historial de los cambios
    ```bash 
    git log

26. Para Ver la diferencias de dos commit
     ```bash 
    git diff

27. Para ver el historial mas comprimido
     ```bash 
    git log --oneline

28. Para ver commit específicos
    ```bash 
    git log --oneline
    git show 32f39f1