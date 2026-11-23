# MI DINERO — versión actualizada

## Funciones
- Presupuesto 50/30/20 calculado sobre cada ingreso confirmado, no solo sobre el sueldo mensual estimado.
- Al registrar una quincena, muestra cuánto va a Necesidades (50%), Gustos (30%) y Ahorro obligatorio (20%).
- Calcula las reservas para compromisos según la quincena: teléfono e internet en la primera; aire e internet en la segunda.
- Muestra cuánto queda libre dentro de Necesidades después de reservar las deudas y cuánto puedes usar sin tocar el ahorro.
- Permite registrar ingresos externos o extraordinarios por separado. También se distribuyen 50/30/20; no se les asignan reservas quincenales automáticamente.
- Permite añadir deudas y pagos propios con nombre, descripción, valor mensual, primer vencimiento y frecuencia permanente o por cuotas.
- Las deudas personalizadas se reservan en partes iguales entre las dos quincenas y se descuentan del presupuesto de Necesidades.
- Permite marcar pagos, llevar cuotas restantes, registrar gastos y confirmar ahorro.
- Historial de ingresos y movimientos, recordatorios dentro de la aplicación y respaldo JSON.
- Diseño oscuro, adaptable a iPhone y caché para uso sin conexión.

## Compromisos iniciales
- Teléfono: $40 al mes, cuatro cuotas desde noviembre de 2026; asignado a la primera quincena.
- Aire acondicionado: $40 al mes, tres cuotas desde diciembre de 2026; asignado a la segunda quincena.
- Internet: $13 al mes, permanente; se reserva $6,50 por quincena.

Revisa las fechas y cuotas en la pestaña Pagos. Puedes editarlas si ya cambió alguna obligación.

## Cómo se calcula una quincena de $120,50
- Necesidades (50%): $60,25.
- Gustos (30%): $36,15.
- Ahorro obligatorio (20%): $24,10.
- En la primera quincena se reservan inicialmente $40 de teléfono y $6,50 de internet; quedan $13,75 libres dentro de Necesidades.
- En la segunda quincena se reservan inicialmente $40 de aire y $6,50 de internet; quedan $13,75 libres dentro de Necesidades.
- Por tanto, con esas reservas, puedes usar $49,90 por quincena sin tocar el ahorro: $13,75 de Necesidades libres + $36,15 de Gustos.

Las deudas nuevas se añaden a esas reservas y la aplicación muestra si las reservas superan el 50% disponible.

## Actualizar GitHub Pages
1. Descarga y descomprime el ZIP.
2. En tu repositorio de GitHub, reemplaza `index.html` y `sw.js` por los archivos nuevos. Puedes subir también este README.
3. Confirma los cambios con Commit changes.
4. Espera a que GitHub Pages publique la actualización.
5. En el iPhone, cierra MI DINERO por completo y vuelve a abrirla. La caché de la app se actualizó a v2; si todavía ves la versión anterior, abre el enlace en Safari y recarga.

## Privacidad y respaldo
Los datos continúan guardándose localmente en el navegador del iPhone; esta actualización no los envía a Supabase ni a otro servidor. Se conserva la misma clave de almacenamiento local para que los datos existentes permanezcan en el mismo navegador y dominio. Antes de actualizar, exporta un respaldo desde la aplicación por precaución.

La app no mueve dinero ni verifica depósitos bancarios. Debes confirmar manualmente ingresos, pagos y ahorros. Las alertas se muestran al abrir la app; las notificaciones push de iOS requieren una configuración adicional.
