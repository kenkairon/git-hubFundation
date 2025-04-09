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

