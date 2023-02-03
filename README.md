# Ejemplo de fichero README.md
## (CC-BY-NC-SA) Julio Vega

El objetivo de este **fichero README.md de ejemplo** es conocer el uso básico de *MarkDown* para que los estudiantes se familiaricen con este lenguaje.

## 0. Introducción

Las secciones van precedidas de varias almohadillas, según el anidamiento de la sección. Se añade el número de la sección y el título.

## 1. Uso básico

### 1.1. Cursiva y negrita

Para poner un texto en cursiva, se mete este entre asteriscos simples. Por ejemplo, para escribir términos anglosajones como *dashboard* o *upgrade*.

Si quiero poner un texto en negrita, seguiremos la misma sintaxis, pero usando dobles asteriscos, por ejemplo para resaltar alguna palabra **importante**.

### 1.2. Enumerados

Simplemente, hago un listado de ítems, precedidos por su número o posición. Por ejemplo, el siguiente listado:

1. Primer ítem
2. Segundo ítem
3. Y así sucesivamente...

## 2. Incluir texto especial

### 2.1. Snippets

Un *snippet* es un trozo de código, muy útil en el contexto de programación para, por ejemplo, resaltar alguna funcionalidad del programa. En este ejemplo, exponemos un *snippet* en lenguaje Python:

```python
for fila in range(0, len(misFilas)): # recorro todas la filas del vector
    a = procesar (fila) # rellenamos toda la info de la fila "a" actual
    if (a.codigoControl == -1):
        print ("FATAL ERROR al leer fila: " + a.digito1 + " " + a.digito2 + ", " + a.tipo)
    else:
        filaValida = Convertir (a)
```

### 2.2. Instrucciones de Terminal (bash)

Si queremos incluir las instrucciones de Terminal que usamos, por ejemplo, para ejecutar nuestro programa, tenemos el entorno *bash*. Ejemplo:

```bash
make
make install
./miprograma
```

## 3. Incluir recursos

### 3.1. Imágenes

Aquí podemos ver el logo de GitHub:

![alt text](https://github.githubassets.com/images/modules/logos_page/GitHub-Logo.png "Logo de GitHub")

### 3.1. Enlaces

Recordad que podréis acceder a todas las prácticas en nuestro [repo *clases-julio*](https://github.com/clases-julio)


## clase de hoy (subir a wiki)

 comandos aprendidos --> gedit README.md, git clone https://cnebril2020@github.com/clases-julio/p0-welcome-cnebril2020, git status --> si sale algo sin seguimiento lo podemos añadir con --> git add "nombre del archivo" o "*"
 --> para confirmar los cambios, es decir, subirlo a la nube, hacemos un **git commit -m "funcionalidad nueva"**(cuando ya he puesto las cosas en seguimiento). Si no estuviese en seguimiento hariamos un gt commit -a (amen).
 consejo con github --> leer.
 Cuando estas adelantado a lo que hay en la nube, realizar un git push --> pongo el TKN. En este caso el git push ha fallado ¿Por qué? partir de un master modificado a posteriori de tu modificacion. Si permite la fusión (merge)
 es que GitHub lo puede solucionar solo, en caso de que esto no este disponible --> crear otra carpeta de trabajo, donde vuelves a clonar el repositorio, e intento meter todas las modificaciones anteriores (fusión manual)
 Cuando he hecho varias modificaciones (borrar, modificar...) se suele hacer el git commit -a. Te despliega un editor de texto "vim" o el que sea, añades un comentario y lo sube.
 gitHub ignora las Carpetas vacías (problema) --> solución para esto: crear un archivo vacio "touch .aa".
 
 Si has hecho varias modificaciones se puede hacer sin el amen --> se puede hacer manualmente, es decir, git rm para sacar del seguimiento un archivo y git add para añadir al seguimiento.
 
 archivos compilados --> no se meten en seguimiento. Los codigos se compilan en cada maquina, para que subir un compilado si lo vas a volver a generar. Se puede dejar sin seguimiento a alguenos archivos, en este caso,
 el compilado ".o" (como los archivos en c).
 
 
 git clone https://github.com/clases-julio/p0-welcome-cnebril2020 pc0 --> te renombra el prompt a "p0" (probar)

 

