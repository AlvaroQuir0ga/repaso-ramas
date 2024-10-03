# Clase 06 - Bootcamp 

# Creo el repositorio de GIT 

```sh 
git init 
``` 
# Listo el estado de los archivos

```sh
git status
```


# Haciendo un commit 

1. Agrego al area de staging, los archivos que necesito que formen parte del commit 
```sh
git add <nombre-archivo> 
git add . # Agrega todos los archivos que tengo el working directory (WD) 
```

2. Hago el commit 
```sh
git commit -m "titulo descriptivo" 
git commit
```

# Ver listado de commits que hice en el repo

```sh
git log
git log oneline
```

# Agregar un remoto a mi repositorio local

```sh
git remote add origin <url-al-repo-remoto> 
git remote add origin https://github.com/AlvaroQuir0ga/repaso-ramas.git  
```

# Para ver si se agrego el repo remoto 

```sh
git remote -v
```

# Subo al remoto el repositorio local

```sh
git push -u origin main # La primera vez
git push 
``` 
