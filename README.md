# Primer día con Git y GitHub

Lista de comandos GIT

- Para poder ver la versión de git, ejecutamos el siguiente comando en nuestra terminal

```bash
git --version
git -v
```

- Para configurar el correo y el nombre (solo la primera vez en mi máquina)

```bash
git config --global user.email "micorreo@gmail.com"

git config --global user.name "Mi nombre"

```

- Para ver la configuración de git

```bash
git config --list
```

- Para inicializar nuestro repositorio en git:

```bash
git init
```

- Para ver el estado de nuestros cambios:

```bash
git status
```

- Para preparar nuestros archivos para la zona de stage (prepararlos para commit)

```bash
git add .
git add nombreDelArchivo.extensión
```

- Crear el registro de los cambios registrados:

```bash
git commit -m "comentario relacionado al cambio"
```

- Para ver una linea de tiempo de los commits que hemos realizado(para salir presionamos la letra q):

```bash
git log
```

- Para poder ver el detalle de un commit específico usamos:

```bash
git show id-de-commit
```
