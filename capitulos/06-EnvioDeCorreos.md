# Configuración de un servidor de correos

**Haraka** es un servidor de correos basado en nodejs que en este caso nos sirve para probar el envió de correos desde bash.

```bash
npm install Haraka
mkdir haraka_server
node_modules/Haraka/bin/haraka -i haraka_server/
```
Agrege el plugin de 

 queue/test

Agregu destino.com al host_list

Envie correo con

swaks --add-header "MIME-Version: 1.0" --add-header "Content-Type: text/plain" -h aretico.com -f notifications@dominio.com -s localhost -p 25 -t alejandro.leon@destino.com

Revise el correo en

```bash
cat /tmp/mail.eml
```
