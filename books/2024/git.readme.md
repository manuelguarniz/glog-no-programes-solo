# Git

Git es una herramienta para gestionar versiones de un proyecto, principalmente para programadores.

## Conceptos importantes

- **Branch (rama):** Es el nombre que se asigna a una nueva versión del codigo original, se considera una ramificiación de la primera versión.

  - **main:** Es la rama principal donde se debe tener unicamente versiones finales de un desarrollo
  - **develop:** Es la rama secundaria donde se debe utilizar para compartir versiones casi terminadas con el equipo

![1728967202179](image/git.readme/1728967202179.png)

- **Commit (proteger):** Es el codigo (hash) asignado a un conjunto de cambios. Se le puede decir que protegemos los cambios realizados y se guardan en la historia de git.

![1728967168963](image/git.readme/1728967168963.png)

- **Merge (fusionar):** Es un commit que contiene el consolidado de todos los cambios. Se le puede decir que fusiona cambios entre ramas.

![1728967455747](image/git.readme/1728967455747.png)

- **Clone (clonar):** Es la descarga que se realiza del codigo fuente de un proyecto que incluye el historico de commits. Se le dice clonar por que es una copia identica al proyecto original.

![1728967686539](image/git.readme/1728967686539.png)

## Poniendo en practica nivel 1

Para empezar a trabajar hay que conocer el flujo basico de trabajo, se describe en la siguente imagen.

![1728969613682](image/git.readme/1728969613682.png)

1. La forma mas simple es utilizar herramientas que nos ayude a entender como trabajar en equipo, entre muchas herramientras yo prefiero utilizar [Sourcetree](https://www.sourcetreeapp.com/).

![1728969421787](image/git.readme/1728969421787.png)

### Ejemplo

1. Instalar Git (hay un monton de videos en youtube para eso 🙂)
2. Instalar [SourceTree](https://www.sourcetreeapp.com/)
3. Registrarse en github
4. Clonar repositorio

   ![1728970199443](image/git.readme/1728970199443.png)
5. Abrir proyecto y dar un vistazo a la historia

   ![1728970038224](image/git.readme/1728970038224.png)
6. Crear una rama `develop`

   ![1728970392323](image/git.readme/1728970392323.png)
7. Escribe codigo, prueba, revisa y describe que estas haciendo

   ![1728970752342](image/git.readme/1728970752342.png)
8. Sube tu codigo para que los demas pueda descargarlo

   ![1728970958989](image/git.readme/1728970958989.png)

> [!IMPORTANT]
> Si trabajas en el proyeto de alguien más, necesitarás permiso para subir tu rama al repositorio.
