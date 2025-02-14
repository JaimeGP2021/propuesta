% ViaBus
% Jaime García Pedrote
% Curso 2024/25

# Descripción general del proyecto

Viabus se trata de una aplicación web centrada en la gestión de líneas de autobuses de transporte urbanos y en operaciones centradas en las mismas.

## Funcionalidad principal de la aplicación

El usuario medio de ViaBus se encontrará con un mapa interactivo con las distintas líneas de autobuses de su localidad así como de sus paradas. Podrá obtener información de las rutas, horarios y ubicaciones de las paradas. Además de poder calcular la ruta óptima a seguir entre dos puntos designados por el usuario haciendo uso de los autobuses.
Por otro lado será posible dar de alta líneas de autobuses, añadir interactivamente sus paradas en el mapa de la aplicación y agregar y modificar sus horarios.

## Objetivos generales

* Objetivo: Gestión de usuarios.
  * Casos de uso: Registrar adecuadamente un usuario responsable de la administración de las líneas de autobús de una localidad.
  
* Objetivo: Gestionar líneas de autobús y sus paradas y horarios.
  * Casos de uso: Crear una línea de autobus para una localidad, agregar paradas a la línea, agregar horarios a las paradas.
  
* Objetivo: Navegabilidad.
  * Casos de uso: El usario podrá moverse libremente por un mapa interactivo estilo Google Maps.

* Objetivo: Ubicar paradas.
  * Casos de uso: Seleccionar una parada en un mapa interactivo mientras ves tu ubicación para visualizar los horarios de las lineas de esa parada.
  
* Objetivo: Cálculo de ruta.
  * Casos de uso: Seleccionar dos ubicaciones interactivamente y obtener una ruta óptima para llegar de un punto a otro haciendo uso del mapa interactivo.

# Elemento de innovación

Como elemento de inovación haré uso de la tecnología de la librería de Inertia para unir el lado servidor de Laravel con el lado cliente de React y crear una SPA.
