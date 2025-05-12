# Explorador FIPE App (React)

Esta es una aplicación web desarrollada con React y TypeScript que permite a los usuarios explorar información sobre vehículos utilizando la API FIPE (Fundação Instituto de Pesquisas Econômicas). La aplicación consulta precios de diferentes marcas, modelos y años de vehículos.

## Descripción

La aplicación ofrece una interfaz sencilla para:

*   Seleccionar el tipo de vehículo (coches, motos, camiones).
*   Elegir una marca específica.
*   Seleccionar un modelo de la marca elegida.
*   Escoger el año del modelo.
*   Mostrar el precio medio del vehículo según la tabla FIPE para el mes de referencia seleccionado.
*   Visualizar un historial de consultas recientes.
*   Mostrar un dashboard con estadísticas de uso (opcional, si se implementó).

## Estado del Proyecto

Debido a circunstancias personales, no se pudieron completar todos los objetivos originalmente planteados para este proyecto. La funcionalidad implementada corresponde a la versión actual.

## Tecnologías Utilizadas

*   **Frontend:** React, TypeScript
*   **Enrutamiento:** React Router DOM
*   **Estilos:** CSS (o el sistema de estilos que se esté usando, ej. TailwindCSS, Material UI)
*   **Bundler:** Vite
*   **Llamadas API:** Fetch API (o Axios)
*   **Gráficos (si aplica):** Recharts (o la librería que se use)

## Configuración del Proyecto

Sigue estos pasos para configurar y ejecutar el proyecto en tu entorno local:

1.  **Clonar el Repositorio:**
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    cd <NOMBRE_DEL_DIRECTORIO_DEL_PROYECTO>
    ```

2.  **Instalar Dependencias:**
    Asegúrate de tener Node.js y npm (o yarn) instalados.
    ```bash
    npm install
    # o si usas yarn
    # yarn install
    ```

3.  **Configurar Variables de Entorno (si aplica):**
    Si la aplicación requiere claves de API u otras configuraciones sensibles, crea un archivo `.env` en la raíz del proyecto y añade las variables necesarias. Consulta el archivo `.env.example` si existe.
    ```
    VITE_API_BASE_URL=http://localhost:5000/api # Ejemplo
    ```

4.  **Ejecutar la Aplicación en Desarrollo:**
    ```bash
    npm run dev
    # o si usas yarn
    # yarn dev
    ```
    Esto iniciará el servidor de desarrollo (generalmente en `http://localhost:5173`). Abre tu navegador en esa dirección.

## Uso

1.  Abre la aplicación en tu navegador.
2.  Selecciona el tipo de vehículo (coche, moto, camión) en el menú desplegable principal.
3.  Una vez seleccionado el tipo, se cargarán las marcas disponibles. Elige una marca.
4.  A continuación, selecciona un modelo de esa marca.
5.  Finalmente, elige el año del modelo.
6.  La aplicación mostrará el precio FIPE actual para la selección realizada.
7.  Las consultas realizadas se guardarán y mostrarán en la sección de historial (si está implementada).

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un *issue* para discutir cambios importantes antes de crear un *pull request*.
