# TechFix - E-commerce de Tecnología y Servicios de Reparación 🛠️💻

## Descripción del Proyecto
[cite_start]**TechFix** es una plataforma digital diseñada bajo un modelo de negocio **B2C** (Business to Consumer)[cite: 22, 24]. [cite_start]El sistema permite a los usuarios finales adquirir productos tecnológicos (accesorios, periféricos, repuestos) y gestionar servicios técnicos especializados para laptops, celulares y tablets[cite: 26].

[cite_start]La solución combina la venta directa con un sistema de reserva de citas para atención en tienda física o a domicilio[cite: 27].

---

## 🚀 Tecnologías Utilizadas
[cite_start]El proyecto se fundamenta en un ecosistema robusto y escalable[cite: 29]:
* [cite_start]**Plataforma:** WordPress con el plugin **WooCommerce** para la gestión de e-commerce[cite: 22, 29].
* [cite_start]**Gestión de Citas:** WooCommerce Bookings para la reserva de servicios de reparación[cite: 31].
* [cite_start]**Pasarelas de Pago:** Integración con Izipay, Culqi y PayPal[cite: 33].
* [cite_start]**Diseño y Prototipado:** Figma + Stitch AI para el desarrollo de interfaces de alta fidelidad[cite: 149].

---

## 📊 Modelo de Negocio (Business Model Canvas)
[cite_start]El sistema ha sido modelado para cumplir con los siguientes requisitos funcionales clave[cite: 39, 41]:

| Bloque BMC | Requisito Funcional (RF) |
| :--- | :--- |
| **Segmento de Clientes** | Registro de usuarios, perfiles con historial de pedidos y citas. |
| **Propuesta de Valor** | Catálogo con filtros avanzados y módulo de servicios con precios estimados. |
| **Canales** | Web responsiva y notificaciones por correo electrónico. |
| **Fuentes de Ingreso** | Carrito de compras con cálculo de impuestos (IGV) y pasarelas integradas. |
| **Recursos Clave** | Panel de administración de inventario y agenda para técnicos. |
| **Actividades Clave** | Checkout en 3 pasos y seguimiento de pedidos en tiempo real. |

---

## 🗺️ Arquitectura de Información
[cite_start]La plataforma se organiza en tres niveles principales[cite: 43]:

1.  [cite_start]**Nivel Público:** Home con productos destacados, catálogo filtrable, detalle técnico de productos y servicios de reparación[cite: 45, 46, 48].
2.  [cite_start]**Nivel Transaccional:** Flujo de carrito, checkout (datos de envío y pago) y confirmación de orden[cite: 53, 54, 56].
3.  [cite_start]**Área Privada:** Gestión de perfil, historial de compras, reprogramación de citas y reseñas[cite: 58, 60, 61, 63].

---

## 🔄 Flujos de Usuario (Userflows)

### Compra de Producto (Happy Path)
1. [cite_start]**Búsqueda:** El usuario filtra productos en el catálogo[cite: 66].
2. [cite_start]**Selección:** Añade al carrito desde el detalle del producto[cite: 66].
3. [cite_start]**Autenticación:** El sistema solicita inicio de sesión si no está autenticado[cite: 66].
4. [cite_start]**Pago:** Selección de método de envío y procesamiento de pago vía Culqi[cite: 66].

### Reserva de Servicio
1. [cite_start]**Selección:** Elige el tipo de reparación (ej. Cambio de pantalla)[cite: 111].
2. [cite_start]**Agenda:** Selección de fecha y hora según disponibilidad del técnico[cite: 111].
3. [cite_start]**Detalle:** Descripción del problema del equipo y confirmación[cite: 111].

---

## ⚙️ Módulo de Administración
[cite_start]El panel administrativo permite el control total de la operación[cite: 141]:
* [cite_start]**Gestión de Pedidos:** Actualización de estados (Pendiente, En camino, Entregado)[cite: 142].
* [cite_start]**Inventario:** Control de stock, edición de precios y alertas de stock bajo[cite: 143].
* [cite_start]**Gestión de Citas:** Asignación de técnicos y cierre de servicios atendidos[cite: 143, 144].
* [cite_start]**Reportes:** Exportación de métricas de ventas en formatos Excel y PDF[cite: 144].

---

## 👥 Equipo de Trabajo
[cite_start]Proyecto desarrollado por estudiantes de la **Universidad Nacional de San Cristóbal de Huamanga**[cite: 1, 3]:
* [cite_start]RODRIGUEZ RUIZ, JHORVIN [cite: 9]
* [cite_start]SANTIAGO SOSA, JAYRO RENZO [cite: 10]
* [cite_start]QUISPE CARPIO, KEVIN ANDY [cite: 11]
* [cite_start]PIZARRO LAVIO, ADERLY [cite: 12]
* [cite_start]HUAMAN PERALTA, RICHARD BRUNO (80%) [cite: 13]
* [cite_start]YUPARI RAMOS, GABRIEL (80%) [cite: 14]

[cite_start]**Profesor:** Espinoza Reina, Stivens Rayli [cite: 16]
[cite_start]**Curso:** Comercio Electrónico - 2026 [cite: 18, 20]
