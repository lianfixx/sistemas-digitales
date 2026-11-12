# Sistemas Digitales

Sitio público: https://emiliano-milla.emilianomilla.chatgpt.site

## Estado de recuperación

Sitio/experiencia de Sistemas Digitales. El repositorio fue creado vacío; la fuente editable de la plataforma de origen no está disponible en este repositorio y debe localizarse o reconstruirse con evidencia.

## Regla de diseño

Preservar la identidad visual y los elementos aprobados. No inventar planes, precios, integraciones, funcionalidades ni condiciones comerciales; validar cada dato con fuentes vigentes.

## Reglas de trabajo

- Leer primero `AGENTS.md`, `ia/REGLAS.md` y `ia/PROTOCOLO.md`.
- Separar fuente original recuperada, reconstrucción y propuesta; nunca etiquetar una reconstrucción como fuente original.
- No desplegar, publicar cambios en el sitio, enviar comunicaciones ni activar pagos sin autorización específica.
- Registrar cada cambio y su verificación en `CHANGELOG.md`.
- No incluir secretos, contraseñas, tokens, cookies, datos personales sensibles ni credenciales en Git. Usar variables de entorno locales ignoradas y GitHub Actions Secrets para ejecución protegida.

## Próximos pasos

1. Inventariar la versión pública y sus recursos.
2. Localizar exportaciones, archivos fuente y activos originales.
3. Recuperar la implementación exacta cuando sea posible.
4. Si la exportación no existe, reconstruir con fidelidad y documentar las diferencias.
5. Ejecutar verificaciones y registrar limitaciones antes de declarar recuperación completa.


## Implementación recuperada en este repositorio

- `index.html`: landing de planes con demostración interactiva y formulario local de correo.
- `asistente.html`: catálogo filtrable de 12 capacidades y panel de detalle.
- `contratar.html`: solicitud de plan por correo, sin checkout ni contrato automático.
- `terminos.html` y `privacidad.html`: transcripción de documentos públicos inspeccionados.
- `docs/INSPECCION-PUBLICA.md`: mapa de rutas, precios, capacidades y límites.

**Alcance:** reconstrucción estática, no backend, Stripe, FORJA ni automatizaciones activas. Los precios y documentos deben confirmarse antes de operar. No se ha desplegado esta copia.
