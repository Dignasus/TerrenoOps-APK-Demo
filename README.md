# TerrenoOps — Descarga pública de APK

Aplicación Android nativa (Kotlin y Jetpack Compose) desarrollada por Cristian Millaqueo y Matías Carrasco para el Proyecto Integrado INACAP 2026, caso académico de la Dirección de Seguridad Pública de San Pedro de la Paz.

## Versión actual para exposición: V2.0.2

**[Abrir release TerrenoOps V2.0.2](https://github.com/Dignasus/TerrenoOps-APK-Demo/releases/tag/v2.0.2)**

**[Descargar APK V2.0.2](https://github.com/Dignasus/TerrenoOps-APK-Demo/releases/download/v2.0.2/TerrenoOps-v2.0.2.apk)**

Archivo: `TerrenoOps-v2.0.2.apk`. Release pública de presentación, marcada como prerelease. Requiere un dispositivo Android compatible; en la evaluación se ejecutó en Motorola Edge 50 Fusion. La prueba de instalación anónima desde otro dispositivo debe verificarse antes de la presentación.

### Funcionalidades de V2

- Acceso mediante credenciales de prueba de **Operador** y **Consulta** con Supabase académico.
- Lista, búsqueda y filtros de tickets; Consulta en modo solo lectura.
- Creación de tickets con códigos del sandbox, estados y cierre con descripción y evidencia fotográfica.
- Persistencia remota según confirmaciones mostradas por la app.
- Caché local Room y acceso de consulta con PIN offline previamente configurado.

**Acceso:** V2.0.2 requiere cuentas de prueba Supabase entregadas por el equipo al docente mediante canal privado. No colocar contraseñas, tokens ni credenciales sensibles en este repositorio público.

**Límites:** entorno académico con datos ficticios; no es despliegue municipal de producción. La validación de permisos HTTP/RLS contra el backend debe documentarse por separado de la restricción de botones.

### Código y pruebas

- [Repositorio institucional privado](https://github.com/inacap-proyecto-integrado-2026-2/TerrenoOps-GrupoA) (requiere acceso autorizado).
- [Rama con código de integración Supabase/offline](https://github.com/inacap-proyecto-integrado-2026-2/TerrenoOps-GrupoA/tree/feature/evidencias-offline).
- [Plan de 15 casos de prueba](https://github.com/inacap-proyecto-integrado-2026-2/TerrenoOps-GrupoA/blob/master/docs/plan-pruebas.md).
- [Índice de las 20 capturas](https://github.com/inacap-proyecto-integrado-2026-2/TerrenoOps-GrupoA/blob/master/docs/evidencias-v2.0.2.md). Las imágenes están pendientes de incorporarse al repositorio.
- **Trazabilidad pendiente:** registrar el SHA-256 de V2.0.2 y el commit exacto desde el cual se construyó el APK. No se presume correspondencia exacta solo por el número de versión.

## Versión anterior conservada

La [Demo V1 v0.1.0](https://github.com/Dignasus/TerrenoOps-APK-Demo/releases/tag/v0.1.0-demo) sigue disponible como versión histórica, con perfiles locales «Demo Consulta» y «Demo Operador» sin autenticación real. **No es la versión recomendada para la evaluación final.**

## Instalación en Android

1. Descargar la APK desde el enlace de V2.0.2.
2. Abrir el archivo APK en el dispositivo Android.
3. Autorizar la instalación desde esta fuente cuando el sistema lo solicite.
4. Iniciar TerrenoOps y utilizar las credenciales de sandbox entregadas privadamente.

Proyecto académico. Ningún dato se envía a la municipalidad de producción.
