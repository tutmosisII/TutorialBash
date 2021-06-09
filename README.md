# Uso de comandos Bash

Este documento es una recopilación de herrmientas usadas en el día a dia de mi trabajo.
También hace uso de docker para manejar un paso a paso a manera de tutorial.

Por lo que se require docker installado en tu máquina.
También se asume que se tiene una de las últimas versiones de VSCode.
---
## 1. Inicialización del ambiente de trabajo.

**ctrl+p** > Reopen in Container

En la esquina inferior izquierda aparce el icono que indica en que ambiente estamos trabajando.

![Icono devconatiner](media/devcontainerEnv.png)

**Nota:** Si no tiene instalado docker puede usar vagrant en windows como se indica en el punto 1.1

Una vez abierto en el contenedor habra una terminal y coloquela paralela a este README.


**ctrl+ñ**

alt >> view >> Apparence >> Move Panel Left

Durante esta presentación usaremos Zend mode, para reducir las distracciones del IDE.
devcontainerEnv
**ctrl+k z**  Para activar o desactivar el moddo Zend


### 1.1 Iniciando una máquina virtual con Hyper-V y Vagrant

En el directorio v_ubuntu hay una script de Vagrant para iniciar un Ubuntu 20.04

```powershell
cd v_ubuntu
Start-Process powershell -Verb runAs
vagrant up
```
Cuando la máquina sube, se le preguntará por el switch virtual que se quiere usar.

En este caso par aseguir adelante lo ideal seria usar este ambiente de desarroll de manera remota.

**ctrl+p** REMOTE-SSH..

---

## 1. [Historial de Shell](capitulos(01-HistoriaShell.md))

Se presenta un diagrama con la evolucíón de diferentes tipos de línea de comandos.

---


## 2. [Imprimiendo Fecha del sistema](capitulos/02-ComandoDate.md)
 
  Esta sección muestra el comando **fecha** y la ayuda del mismo para familiarizarse.


---

## 3. [Comandos básicos para la manejar archivos.](capitulos/03-ManejoDeArchivos.md)

  El manejo de directorios y archivos es escencial para manipular adecuadamente el sistema.



