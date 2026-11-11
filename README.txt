# MI DINERO — aplicación web personal

## Qué incluye
- Presupuesto mensual de referencia de $241 con regla 50/30/20.
- Ingresos quincenales variables: registra la fecha y el valor real.
- Compromisos iniciales: teléfono ($40, 4 cuotas), aire acondicionado ($40, 3 cuotas) e internet ($13 permanente, dividido en $6,50 por quincena en la planificación).
- Registro manual de pagos y cuotas restantes.
- Registro de gastos y ahorros confirmados.
- Recordatorios dentro de la aplicación al abrirla.
- Exportar e importar respaldo JSON.
- Diseño oscuro adaptable a iPhone.

## Importante sobre las fechas y cantidades
Los datos de cuotas se cargaron según lo explicado en la conversación: teléfono con cuatro cuotas hasta febrero de 2027; aire acondicionado con tres cuotas de diciembre de 2026 a febrero de 2027; internet permanente. Revisa los vencimientos exactos en la pestaña Pagos antes de confiar en ellos.

El sistema no mueve dinero ni verifica depósitos bancarios. Debes confirmar manualmente los ingresos, pagos y dinero que guardas en tu alcancía.

El teléfono se configuró con vencimiento a fin de mes (primera cuota 30-nov-2026); el aire con día 15 (primera cuota 15-dic-2026, porque noviembre ya estaba pagado); internet con día 10 (próximo vencimiento inicial 10-dic-2026). Revisa estas fechas y ajústalas si hace falta.\n\nLas notificaciones automáticas push de iOS no se incluyen en esta versión offline. La app muestra recordatorios cuando la abres. Para notificaciones push reales se necesita un servicio push y configuración adicional.

## Cómo usarla gratis
1. Publica estos archivos en un hosting estático HTTPS gratuito, por ejemplo GitHub Pages.
2. Abre el enlace publicado en Safari desde tu iPhone.
3. Pulsa Compartir > Añadir a pantalla de inicio.
4. Abre desde el icono Mi Dinero.

## Privacidad y respaldo
Los datos se guardan en el almacenamiento local del navegador del dispositivo. No hay cuenta ni servidor de datos. Usa Exportar respaldo con regularidad y guarda el archivo en Archivos/iCloud Drive o en otro lugar seguro. Si borras los datos del sitio o cambias de navegador/dispositivo, puedes perder los registros locales.

## Archivos
- index.html: aplicación completa.
- manifest.json: configuración instalable.
- sw.js: caché offline.
