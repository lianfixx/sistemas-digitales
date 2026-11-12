# Inspección pública · Sistemas Digitales

**Fecha:** 12 de noviembre de 2026. **Fuentes:** https://emilianomilla.site/negocios, `/negocios/asistente` y `/negocios/terminos`. Inspección de solo lectura; no se contrataron servicios ni se enviaron formularios.

## Diseño

Landing minimalista de fondo claro, tipografía sans-serif, tarjetas redondeadas, botones oscuros y mucho espacio en blanco. Página de capacidades en dos columnas, con filtros y panel de detalle. Acentos naranja #FF6700 y durazno #FECB8B en la página de asistente.

## Landing y planes

- Presencia: $7,900 MXN IVA incluido; mantenimiento opcional $790/mes; entrega estimada 7–10 días hábiles.
- Conversión: $14,900 MXN IVA incluido; mantenimiento opcional $1,690/mes; entrega estimada 15–20 días hábiles.
- Sistema: $28,900 MXN IVA incluido; mantenimiento opcional $3,990/mes; entrega estimada 20–30 días hábiles; piloto de 21 días.
- La página indica que dominio, licencias, consumo IA/mensajería, comisiones y publicidad pueden ser conceptos separados.
- La demo de asistente es demostrativa y declara que no envía mensajes ni reserva citas.

Los precios se transcribieron del sitio público inspeccionado y requieren confirmación antes de aceptar pedidos, cotizaciones o pagos.

## Capacidades del asistente (12)

**Confianza:** Blindaje anti-invento; Vigilante con IA; Handoff que sí atina; Voz de marca.

**Conversión:** Cazador de ventas; Multi-idioma; Recupera no-shows; Pide reseñas; Cobros por WhatsApp.

**Operación:** Oído y vista; Reportes automáticos; Encuestas de satisfacción.

La página pública detalla para cada capacidad qué evita, cómo se usa y reglas visibles. La implementación `asistente.html` reproduce las 12 tarjetas, filtros y panel de detalle a partir de esos textos. Las reglas y umbrales descritos son afirmaciones comerciales de la página, no una verificación independiente de que FORJA esté desplegado.

## Condiciones

Se incorporó a `terminos.html` el texto público inspeccionado, versión **sd-2026-09-05**, actualizado el 5 de septiembre de 2026. Incluye alcance, dependencias, pagos, responsabilidades, límites de resultados, piloto, cancelación, propiedad intelectual, seguridad y privacidad. Confirmar vigencia legal antes de usarlo para una contratación real.

## Rutas observadas

- `/negocios` landing y planes.
- `/negocios/asistente` capacidades.
- `/negocios/contratar?plan=presencia|conversion|sistema` selección de plan.
- `/negocios/terminos` condiciones.
- `/privacidad` aviso de privacidad de negocio.
- `/aviso-de-privacidad` aviso del portafolio.

## Límites y pendientes

1. Recuperar el aviso de privacidad completo.
2. Recuperar la página de contratación y confirmar si el flujo de pago está activo.
3. No integrar Stripe, FORJA, WhatsApp, Google Calendar ni proveedores sin credenciales gestionadas y pruebas reales.
4. No guardar secretos en Git. Usar variables protegidas del entorno.
5. Confirmar precios, alcance y condiciones antes de cotizar o cobrar.
6. Ejecutar pruebas de teclado, móvil, formularios y rutas, y comparación visual.

La implementación en este repositorio es reconstrucción estática; no contiene backend, checkout, automatizaciones ni integración real con FORJA.