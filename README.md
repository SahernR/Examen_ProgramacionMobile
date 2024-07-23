# Planificador de Vacaciones

## Descripción

Este proyecto es una aplicación móvil para Android que permite a los usuarios planificar sus vacaciones de manera eficiente. Incluye características para agregar y gestionar lugares de interés, tomar fotografías, visualizar ubicaciones en un mapa y almacenar datos en una base de datos SQLite. Además, integra un servicio web para mostrar los costos en dólares en lugar de la moneda local.

## Características

- **Planificación de Lugares:** Agrega lugares que deseas visitar, incluyendo nombre, orden, URL de imagen, latitud, longitud, costos de alojamiento y transporte, y comentarios adicionales.
- **Visualización de Mapa:** Muestra lugares planificados en un mapa utilizando osmdroid y coloca marcadores en las ubicaciones.
- **Agregar Fotos:** Permite tomar fotografías desde la aplicación y asociarlas con los lugares visitados.
- **Persistencia de Datos:** Almacena datos de lugares, imágenes y fotos en una base de datos SQLite.
- **Conversión de Moneda:** Consume un servicio web para obtener la tasa de cambio entre CLP y USD.
- **Multilenguaje:** La aplicación está disponible en inglés y español.

## Requisitos

- **Android Studio**
- **Kotlin**
- **Jetpack Compose**
- **osmdroid para visualización de mapas**
- **SQLite o ROOM para persistencia de datos**
- **Coil para carga de imágenes**

## Estructura del Proyecto

- **VisorImagen:** Actividad para mostrar una imagen en pantalla completa y rotada.
- **RegistrarPlanificador:** Actividad para registrar un nuevo lugar de interés con datos y fotos.

## Instalación

1. Clona el repositorio:
   ```sh
   git clone <url-del-repositorio>
