# Integracion_MELI_Tiendanube
integracion tienda nube y mercado libre
# Integración Mercado Libre ↔ Tiendanube (Proyecto Académico)

Prototipo funcional desarrollado como trabajo práctico universitario para implementar y validar una integración basada en APIs REST entre **Mercado Libre** y **Tiendanube**.

## Propósito

El proyecto tiene fines estrictamente educativos y de prueba técnica. Su objetivo es experimentar con arquitecturas de integración entre plataformas de comercio electrónico, aplicando autenticación segura y sincronización asíncrona de datos en un entorno controlado (Sandbox).

## Alcance técnico

- **Autenticación OAuth 2.0:** Implementación del flujo de autorización, obtención de tokens y renovación mediante `refresh_token`.
- **Consumo de APIs REST:** Lectura y actualización de recursos básicos (ítems, stock, precios y órdenes de prueba).
- **Webhooks:** Recepción y procesamiento de notificaciones en tiempo real ante eventos de cambio en publicaciones o generación de órdenes.
- **Entorno aislado:** Todas las pruebas se realizan exclusivamente mediante usuarios de prueba (*Test Users*) y tiendas demo, sin impacto ni acceso a cuentas productivas reales.

## Estado del proyecto

🎓 **Prototipo académico / Entorno de pruebas**  
En fase de configuración inicial y validación de endpoints.
