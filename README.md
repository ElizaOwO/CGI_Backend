# Backend

Este repositorio contiene el código del backend de la aplicación.

## Pasos para configurar y ejecutar el backend:

1. **Actualizar el código:** Primero, asegúrate de tener la última versión del código ejecutando los siguientes comandos:

    ```bash
    git fetch
    git pull
    ```

2. **Migraciones de base de datos:** Ejecuta las migraciones de base de datos para asegurarte de que tu base de datos esté actualizada:

    ```bash
    db-migrate up
    ```

3. **Instalar dependencias:** Instala las dependencias necesarias utilizando Yarn:

    ```bash
    yarn
    ```

4. **Ejecutar en modo de desarrollo:** Inicia el servidor en modo de desarrollo. Asegúrate de mantenerlo encendido mientras trabajas en el backend:

    ```bash
    yarn run dev
    ```

    Deberías ver el mensaje "Server on Port 3002" en la consola si el servidor se inicia correctamente.

