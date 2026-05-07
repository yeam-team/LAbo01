# TechFix - E-commerce de Tecnología y Servicios de Reparación

## 💻 Descripción del Proyecto
[cite_start]**TechFix** es una plataforma B2C (Business to Consumer) diseñada para la venta de productos tecnológicos y la gestión de servicios técnicos[cite: 2, 4, 5]. [cite_start]Permite a los clientes comprar accesorios y repuestos, además de reservar citas para la reparación de equipos como laptops y celulares[cite: 6, 7].

## 🚀 Tecnologías Utilizadas
* [cite_start]**CMS:** WordPress con WooCommerce[cite: 2, 9].
* [cite_start]**Gestión de Citas:** Plugin WooCommerce Bookings[cite: 11].
* [cite_start]**Pasarelas de Pago:** Integración con Culqi, Izipay y PayPal[cite: 12].
* [cite_start]**Prototipado:** Diseñado en Figma.

## 📋 Requisitos Funcionales Clave
* [cite_start]**RF03/RF04:** Catálogo de productos con filtros y módulo de servicios de reparación con precios estimados[cite: 17].
* [cite_start]**RF09/RF10:** Carrito de compras con cálculo de subtotal e IGV, integrado a pasarela de pagos[cite: 17].
* [cite_start]**RF12:** Sistema de agenda para técnicos con calendario de citas[cite: 17].
* [cite_start]**RF14:** Seguimiento de pedidos en tiempo real[cite: 17].
* [cite_start]**RF15:** Integración con APIs de courier (Olva, Shalom) para cálculo de envíos[cite: 19].

## 🗺️ Estructura del Sitio (Sitemap)
* [cite_start]**Nivel Público:** Home con productos destacados, Catálogo con filtros y sección de Servicios de Reparación[cite: 23, 24, 26].
* [cite_start]**Nivel Transaccional:** Flujo de compra optimizado en 3 pasos (Carrito, Checkout y Confirmación)[cite: 31, 32, 33, 34].
* [cite_start]**Área Privada:** Panel de usuario para ver historial de pedidos, citas y gestionar direcciones[cite: 36, 38, 39, 40].

## ⚙️ Flujos Principales (Happy Paths)
1. [cite_start]**Compra de Producto:** El usuario busca un producto, lo añade al carrito, inicia sesión y procesa el pago mediante Culqi[cite: 44, 84].
2. [cite_start]**Reserva de Servicio:** El cliente selecciona un servicio de reparación, elige una fecha en el calendario interactivo y describe el problema de su equipo[cite: 89].

## 🛠️ Administración
El sistema cuenta con un panel administrativo para:
* [cite_start]Gestión de inventario con alertas de stock bajo[cite: 121].
* [cite_start]Asignación de técnicos a citas programadas[cite: 121].
* [cite_start]Generación de reportes de ventas exportables a Excel o PDF[cite: 122].
