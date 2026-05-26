# Monitorización del Servidor

Para investigar los logs, existen analizadores como GoAccess y AWStats. Utilizaremos GoAccess para procesar el registro principal, ubicado en `/var/log/apache2/access.log`.

Generaremos un archivo HTML estático en tiempo real con este comando:
`goaccess /var/log/apache2/access.log -o /var/www/html/report.html --log-format=COMBINED --real-time-html`. 