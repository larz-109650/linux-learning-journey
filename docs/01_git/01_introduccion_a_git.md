# Introducción a Git

## Objetivo

Comprender qué es Git, cómo funciona un repositorio y cuál es la diferencia entre un repositorio local y uno remoto.

---

## Conceptos importantes

### Git

Sistema de control de versiones distribuido.

Permite registrar todos los cambios realizados en un proyecto.

---

### GitHub

Servicio que aloja repositorios Git en la nube.

Facilita compartir proyectos y trabajar en equipo.

---

### Repositorio

Conjunto de archivos junto con toda la historia de cambios almacenada por Git.

---

### Repositorio local

Es la copia del proyecto que existe en mi computadora.

---

### Repositorio remoto

Es la copia del proyecto alojada en GitHub.

Por defecto Git utiliza el nombre **origin** para referirse al repositorio remoto.

---

### git clone

Crea una copia local del repositorio remoto.

Además:

- descarga todos los archivos;
- descarga el historial completo;
- crea la carpeta `.git`;
- configura el remoto `origin`.

---

### Carpeta `.git`

Contiene toda la información que Git necesita para administrar el proyecto.

Algunas carpetas importantes son:

- objects
- refs
- hooks
- logs

Y algunos archivos importantes:

- HEAD
- config

---

### ~/.gitconfig

Configuración global del usuario.

Ejemplo:

- nombre
- email

---

### .git/config

Configuración específica del repositorio.

Ejemplo:

- URL del remoto
- origin
- ramas remotas

---

## Laboratorio realizado

- Instalación de Git
- Configuración del usuario
- Clonado del repositorio
- Exploración de la carpeta `.git`

---

## Comandos utilizados

```bash
git clone
git status
git branch
git remote -v
cat HEAD
cat config
ls -la
```

## Qué aprendí

## Qué aprendí

En este laboratorio comprendí que Git y GitHub son herramientas diferentes:
Git administra el historial del proyecto en mi computadora, mientras que 
GitHub aloja una copia remota del repositorio.

Aprendí que el comando `git clone` no solo descarga los archivos del 
proyecto, sino también todo su historial y crea la carpeta `.git`, 
que contiene la información necesaria para que Git administre el repositorio.

También entendí la diferencia entre la configuración global del usuario 
(`~/.gitconfig`) y la configuración específica de cada repositorio (`.git/config`).

Además, este laboratorio me permitió seguir practicando el uso de la 
terminal de Linux y familiarizarme con la estructura de directorios 
y los archivos ocultos.
