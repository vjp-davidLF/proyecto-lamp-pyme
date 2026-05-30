# Informe de Revisión y Reflexión del Proyecto

## 1. Conflictos y Resoluciones
- **Primer Conflicto (docs/01-analisis.md):** Provocado intencionadamente para simular trabajo concurrente. Se resolvió mediante merge local en el editor unificando las tablas de análisis.
- **Segundo Conflicto (docs/04-instalacion/ssh-firewall.md):** Resuelto y consolidado mediante la estrategia `git pull --rebase` en la terminal local de Daniel. Integró limpiamente las reglas HTTP de David, SSH de Daniel y las ampliaciones de puertos de HAProxy en un único historial cronológico lineal en el servidor remoto.

## 2. Comandos Git más utilizados
`git checkout -b`, `git pull origin main`, `git add .`, `git commit -m`, `git push -u origin` y `git pull --rebase`.

## 3. Conclusiones e Intercambio de Roles
El intercambio de roles a mitad del desarrollo fue clave para comprender la estructura global de la red. Obligó a ambos miembros a auditar el código y la documentación del compañero, asegurando la consistencia del despliegue del balanceador HAProxy y los servicios LAMP.