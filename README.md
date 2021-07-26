# PPS-Secundario-AppWeb
Desarrollo de Aplicación Web aplicado a la concientización sobre el consumo de tabaco

## Instrucciones para Git
Todos los comandos se deben aplicar en la consola de git (Git Bash). 

_Aclaración 1: Si es la primera vez que abren la consola y quieren realizar algunos de los comandos, lo mas probable es que les pida iniciar sesion con su cuenta de Git_.

### Clonar este repositorio:
```
git clone https://github.com/Chrisnb1/PPS-Secundario-AppWeb
```
_Aclaración 2: Una vez clonado el repositorio, para realizar alguna accion sobre el mismo, abran la consola en la carpeta del repositorio._

### Crear una rama:
```
git branch nombreRama  (Ponerle un nombre a la rama)
```

### Ubicarse sobre la rama creada:
```
git checkout nombreRama
```

### Ver todas las ramas creadas:
```
git show-branch
```

### Subir al repositorio (Añadimos todos los archivos al commit y hacemos un push):
```
git add .   (espacio y punto)
git commit -m "comentario"  (el comentario tiene que ir entre comillas)
git push origin nombreRama  (Poner el nombre de la rama actual)
```
_Aclaración 3: Siempre que queramos subir algo a una rama especifica observar si estamos ubicados sobre esa rama (aparece entre parentesis en la consola)_
### Fucionar ramas (merge):
```
git merge otraRama  (otra rama a fucionar)
git push origin nombreRama (rama en la que estamos ubicados)
```
