MECÁNICO CRISTIAN - PROYECTO ANDROID
=====================================

Este paquete contiene el código fuente de una primera versión Android.
No es todavía un APK compilado.

REQUISITOS
- Android Studio instalado en una computadora.
- Android SDK Platform 35 (Android Studio puede descargarlo).
- JDK 17 o el JDK integrado en Android Studio.

CÓMO GENERAR EL APK
1. Descomprimir MecanicoCristianAndroid.zip.
2. Abrir Android Studio.
3. Elegir Open y seleccionar la carpeta MecanicoCristianAndroid.
4. Esperar la sincronización de Gradle y aceptar la instalación de componentes SDK si se solicita.
5. En el menú Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Al finalizar, Android Studio mostrará la ubicación del APK. Normalmente:
   app/build/outputs/apk/debug/app-debug.apk
7. Pasar ese APK al teléfono Android y abrirlo para instalarlo.
   Si Android lo solicita, permitir instalar aplicaciones desde esa fuente.

FUNCIONES INCLUIDAS
- Clientes
- Presupuestos con cálculo automático
- Tickets guardados y vista de impresión / PDF
- Inventario básico
- Caja con ingresos, gastos y abonos
- Exportar e importar respaldo JSON
- Datos locales mediante almacenamiento del navegador WebView

IMPORTANTE
- Los datos se guardan localmente en el dispositivo; no hay sincronización en la nube.
- Exportá respaldos regularmente. Borrar datos de la app o desinstalarla puede borrar información local.
- El inventario inicial y la caja son registros manuales en esta versión.
- La impresión usa el sistema de impresión de Android; para impresora térmica Bluetooth se requiere integración específica según marca/modelo.
- El proyecto es una base inicial que debe probarse en el teléfono antes de usarlo con datos reales.
- Se incluyó como ejemplo la línea telefónica 0976 473 176 / 0992 964 498 y el encabezado del taller. Revisar los datos antes de producción.
