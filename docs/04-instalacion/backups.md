# Política de Copias de Seguridad

1. **Base de datos:** Volcado automatizado diario usando `mysqldump`.
2. **Archivos web:** Sincronización del directorio `/var/www/html` mediante `rsync`.