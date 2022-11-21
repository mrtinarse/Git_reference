# GIT REFERENCE

## BIENVENIDOS A LA GUIA GIT

Es ta guia esta creada por Martín Arce Rodrigo para guiar a los nuevos usuarios de MarkDown.

### Git Commit:
Hace un snapshot de los archivos del proyecto en el que estamos trabajando.

```
git commit -a -m "Mi primer commit"
```

### Git Clone

Git clone se utiliza basicamente para apuntar a un repositorio y clonarlo en otro respositorio, en otra ubicación.

```
git clone <URL_REPO>
```

Por ejemplo:
```
git clone https://github.com/mrtinarse/Git_reference
```

### Git Pull
Se utiliza para extraer y descargar contenido desde un repositorio remoto, actualizando automaticamente el repositorio local a donde lo hemos extraido.

##### **_Git Push_**
Git Push es basicamente lo mismo que el anterior, pero este en vez de extraer el contenido, loq ue hace es cargarlo a un repositorio remoto.

**###Git Branch:**
+Nos permite crear ramas

*git branch nombre rama

**###Git Checkout:**
+Nos permite movernos entre las ramas creadas

*git checkout nombre rama **(a la que queremos movernos)**

**###Git merge:**
+Nos permite unir ramas con otras ramas

*git merge bugfix **(nombre de la rama que queremos unir)**
##### **_GIT SWITCH_** 
Sirve para cambiar entre ramas de nuestro repositorio. 

##### **_GIT REBASE_** 
Sirve para recopilar uno a uno los cambios confirmados en una rama, y reaplicarlos sobre otra.

##### **_GIT TAG_** 
Sirve básicamente como una rama firmada que no permuta, es decir, siempre se mantiene inalterable.
