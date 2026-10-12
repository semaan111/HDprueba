# RIDE HOUSE Medellín — Harley-Davidson · versión de presentación

Una experiencia responsive de comunidad y fidelización, con identidad visual basada en Harley-Davidson Colombia y Harley-Davidson LATAM. Incluye logotipo, fotografías de la marca y tipografía de encabezados del sitio colombiano.

## Publicar en GitHub Pages

1. Descomprime el paquete.
2. En tu repositorio, selecciona **Add file → Upload files**.
3. Sube **index.html** a la raíz y confirma con **Commit changes**. El archivo contiene todos los estilos, código, fuentes e imágenes; no necesita carpetas adicionales.
4. En **Settings → Pages → Build and deployment**, elige **Deploy from a branch**.
5. Selecciona **main** y **/(root)**. Pulsa **Save**.
6. Espera el despliegue y abre la dirección que aparezca en Pages. Comparte esa URL para presentar la plataforma.

No subas el ZIP como sustituto de index.html. Los archivos de `source/` son la versión editable, no se requieren para publicar. No hay paquetes que instalar ni un servidor que configurar.

Guía oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Accesos de presentación

- **Alex / Future Rider**: alex@ridehouse.demo
- **Santiago / Rider**: santiago@ridehouse.demo
- **Contraseña de ambos**: Ride2026!

También puedes crear perfiles con un nombre de presentación. No uses información personal. Los perfiles nuevos se reabren desde el selector del acceso local; no tienen contraseñas reales.

## Recorrido recomendado (5 minutos)

1. Recorre la portada y las dos rutas: Future Rider / Rider.
2. Entra como Alex y abre **Mi club**. Explora el carné y los puntos de bienvenida.
3. Registra la primera visita: suma 100 puntos una sola vez.
4. Abre **Motocicletas** y guarda una favorita: completa una misión de 75 puntos.
5. Registra un consumo de ejemplo desde **Mi club**, por ejemplo DEMO-001 por $40.000: suma 20 puntos. La misma referencia no se acepta dos veces en el perfil.
6. Canjea un café desde **Beneficios**: descuenta 100 puntos y crea un comprobante descargable.
7. Reserva una experiencia: se guarda la reserva y la primera reserva completa la misión de comunidad. Descarga el archivo de calendario o cancela el plan.
8. Abre **Mi perfil** para editar el nombre, descargar el carné o cerrar sesión.
9. Entra como Santiago para mostrar un perfil independiente.
10. Abre **Vista negocio** para ver la actividad local, exportar CSV y cambiar los supuestos del piloto de 90 días.

## Incluido y operativo

- Portada, Mi club, Beneficios, Experiencias, Motocicletas, sede y Vista negocio.
- Acceso con dos perfiles de demostración y creación de perfiles locales.
- Sesión y actividad persistidas en localStorage; modo de memoria si el navegador bloquea el almacenamiento.
- Carné descargable SVG, saldo, nivel e historial.
- Misiones sin repetición de puntos, consumos de ejemplo con validación de referencia y monto.
- Canjes con saldo suficiente, comprobantes e historial.
- Reservas sin duplicados, cancelación y exportación iCalendar.
- Favoritos y preparación de interés para asesoría.
- Enlaces reales al catálogo, tienda, datos de la sede, llamada y Google Maps.
- Métricas de la actividad local, exportación CSV y proyección matemática editable.
- Diseño adaptativo con menú y navegación para móvil; modales con Escape y control de foco.

## Alcance exacto

Esta es la versión completa de **presentación**, no un servicio de producción conectado a Harley-Davidson. El programa Ride House, los beneficios y las actividades son conceptuales. La ubicación y los canales de la sede remiten al sitio colombiano.

El acceso es una simulación local. Las credenciales de muestra están en el código, no protegen información y no deben usarse para cuentas reales. La vista negocio está abierta para presentación. El archivo no envía correos, valida facturas, realiza pagos ni confirma cupos en eventos reales.

La actividad no se sincroniza entre dispositivos y no es un CRM. Borrar los datos del navegador elimina la información local. **Vista negocio → Reiniciar demostración** permite restaurar los perfiles iniciales.

Para operar con clientes: conectar un proveedor de autenticación y base de datos, mover el saldo y las validaciones al servidor, restringir los roles administrativos e integrar los consumos y las reservas con el operador. Esas integraciones no están activadas en esta entrega.

## Validación realizada

Se comprobaron sintaxis JavaScript, cálculo y conciliación del saldo, prevención de duplicados, aislamiento de perfiles, acceso válido e inválido, persistencia, navegación de todas las vistas, reservas/cancelación, generación de descargas, edición local y escape de texto mediante pruebas de DOM.

No se pudo ejecutar una revisión visual en navegador real en este entorno. No se afirma compatibilidad probada en todos los dispositivos. La vista dentro del chat usa el mismo código y adapta la posición de los diálogos a la conversación.

## Identidad y fuentes

Ver FUENTES.md. Los recursos de Harley-Davidson pertenecen a sus titulares y se incluyen para esta propuesta de presentación. Su uso aquí no acredita afiliación, aprobación o licencia comercial.
