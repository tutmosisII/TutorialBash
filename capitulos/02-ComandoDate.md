# Date

Las siguientes lines muestran el comando y la ayuda del mismo.

```bash
date

date --help

man date
```

**date:** Imprime la fecha del sistema

**date --help o  man date:** Muestran la documentación.

Por lo general los comandos de linux reciben varios parámetros para interpretar y ejecutar. La ayuda muestra el comando date y sus parámetros

```
SYNOPSIS
       date [OPTION]... [+FORMAT]
       date [-u|--utc|--universal] [MMDDhhmm[[CC]YY][.ss]]

DESCRIPTION
       Display the current time in the given FORMAT, or set the system date.

       Mandatory arguments to long options are mandatory for short options too.

       -d, --date=STRING
              display time described by STRING, not 'now'

       --debug
              annotate the parsed date, and warn about questionable usage to stderr

       -f, --file=DATEFILE
              like --date; once for each line of DATEFILE
```

### **Trabajo 1**: Imprimir la fecha dd/yyyy/mmm   09/2021/jun


```
date "+%d/%Y/%b"
```