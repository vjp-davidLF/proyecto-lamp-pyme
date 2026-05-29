# 6. Plan de Recuperación ante Desastres (DRP)

## Protocolo de Restauración de Base de Datos
En caso de corrupción de datos, se restaurará el último volcado con:
`mysql -u root -p base_datos < /backups/db_backup.sql`

## Restauración de Archivos Web
Reemplazar el directorio dañado con la copia de rsync:
`rsync -avz /backups/html/ /var/www/html/`