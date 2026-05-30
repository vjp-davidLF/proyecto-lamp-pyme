# 2. Diseño de la Infraestructura

| Componente | Versión / Herramienta | Función |
| :--- | :--- | :--- |
| Sistema Operativo | Ubuntu Server | Base del sistema |
| Servidor Web | Apache 2.4 | Procesamiento de peticiones HTTP |
| Base de Datos | MySQL Server | Almacenamiento relacional |
| Lenguaje | PHP | Backend dinámico |

- **Balanceador de Carga:** HAProxy actuando como proxy inverso en el puerto 80 para distribuir el tráfico de forma equitativa hacia los servidores Apache backend.