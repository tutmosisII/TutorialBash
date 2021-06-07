# Variables

Las **variables** son muy útiles para programar y controlar el sistema, acontinuación algunos de sus usos y manejos.

## Definición de variable

Las variables en shell no tienen tipos de datos y se declaran con el **nombre** al asignarle (=) un valor.

```bash
mi_saludo="Bienvenido a BASH"
```

La anterior variable solo esta disponible en la termina que estamos y no es accesible a otros programas que se ejecuten en la terminal.

```bash
echo echo '$mi_saludo' > tmpleerVarible.sh
chmod +x tmpleerVarible.sh 
./tmpleerVarible.sh 
```

El código anterior, trata de imprimir en consolo la variable recién declarada. Dado que la variable no ha sido compartida solo se ve un mensaje vacio en la cosola.

Para que la variable pueda ser impresa dentro del programa shell que se creó se debe exportar. Y luego si ejecutar el programa que va hacer uso de ella

```bash
export mi_saludo
./tmpleerVarible.sh 
```

## ¿Qué variables estan declaradas en mi ambiente?

Las variables declaradas en una termina se peuden ver al ejecutar el comando **env**

```bash
env
```
Si quieres resaltar la variable recien creada usa

```bash
env|grep mi_saludo
```
## Declaración de constantes

Por convención las constantes son declaradas en mayúsculas.

```bash
export NOMBRE="Alejandro"
```

```bash
echo echo '$mi_saludo $NOMBRE' > tmpleerVarible.sh
chmod +x tmpleerVarible.sh 
./tmpleerVarible.sh 
```