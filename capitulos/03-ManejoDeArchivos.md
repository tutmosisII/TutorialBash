# Comandos para el manejo de archivos.

En el directorio donde esta ubicado pruebe cada uno de lo sigueintes comandos

```bash
    ls                      #Lista archivos del directorio actual.
    mkdir  datos            #Crea un directorio llamado datos
    mkdir -p datos/json/a   #Crea de manera recursiva los archivos.
    touch datos/json/a/primer.json  #Crea un archivo vacio o modifica la fecha de creación.
    cd datos                #Cambia de directorio e ingresa a la carpeta datos.
    cd ../                  #retorna a la carpeta anterior.
    rm datos/json/a/primer.json #Elmina  el archivo en la ruta indicada.
    mv exammple.json datos/ #Mueve el archivo a la carpeta de datos
```

```bash
log_name="logs"$(date "+%d-%Y-%b")".log"
mkdir -p datos/logs/
touch "datos/logs/$log_name"
```