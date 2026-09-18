# CampusShop - E-Commerce 

Bienvenido a la documentación de **CampusShop**, la maquetación web de la interfaz frontal para un E-Commerce académico enfocado en la compra y venta de productos en el entorno universitario. Este proyecto replica con precisión la estética y experiencia *mobile-first* definida en los mockups y wireframe oficiales.

## Vistas del Proyecto

- [Home / Inicio](Index.html): Pantalla principal con buscador, categorías y productos destacados.
- [Catálogo](Index.html): Malla responsive de productos con filtros visuales.
- [Detalle de Producto](Airpods.html): Vista de producto con imágenes, características, selección de opciones y relacionados.
- [Carrito de Compras](carritolleno.html): Resumen visual de artículos seleccionados y desglose de costos.
- [Checkout](checkout.html): Formulario de compra, datos de envío y resumen de orden.
- [Perfil de Usuario](perfil.html): Información de la cuenta, configuraciones y accesos directos.
- [Historial de Pedidos](historiallleno.html): Listado y estado de compras anteriores.
- [Estado Vacío / Error](vacio.html): Pantalla de retorno con ilustración y guía al catálogo.

## Arquitectura y Tecnologías

El desarrollo fue construido respetando estrictamente los requisitos técnicos solicitados:

* **HTML5 Semántico**: Uso correcto de etiquetas de estructura (`header`, `nav`, `main`, `section`, `article`, `footer`).
* **CSS3 Puro**: Estilos modulares sin uso de preprocesadores, librerías o frameworks externos.
* **Diseño Mobile-First**: Adaptación progresiva mediante Media Queries para móviles, tablets y computadoras.
* **Sin JavaScript**: Interacciones visuales y estados simulados mediante pseudo-clases y transiciones CSS (`:hover`, `:checked`).

## Estructura de Archivos

```text
CampusShop/
 ├── index.html
 ├── catalogo.html
 ├── producto.html
 ├── carrito.html
 ├── checkout.html
 ├── perfil.html
 ├── historial.html
 ├── vacio.html
 ├── css/
 │    ├── base.css
 │    ├── layout.css
 │    ├── components.css
 │    └── responsive.css
 └── img/
      └── (imágenes de productos)


| Imagen 1 | Imagen 2 |
| :---: | :---: |
| ![](img/imagen01.png) | ![](img/imagen02.png) |
| ![](img/imagen03.png) | ![](img/imagen04.png) |
| ![](img/imagen05.png) | ![](img/imagen06.png) |
| ![](img/imagen07.png) | ![](img/imagen08.png) |
| ![](img/imagen09.png) | ![](img/imagen10.png) |
| ![](img/imagen11.png) | ![](img/imagen12.png) |
| ![](img/imagen13.png) | ![](img/imagen14.png) |
| ![](img/imagen15.png) | ![](img/imagen16.png) |
| ![](img/imagen17.png) | ![](img/imagen18.png) |