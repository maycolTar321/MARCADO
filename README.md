# Mi Marcado Seguro — GitHub + Vercel

Aplicación web estática con PWA, uso offline después de la primera carga, registros en IndexedDB y copia secundaria en localStorage, exportación/restauración JSON, exportación CSV e impresión/PDF.

## Publicar
1. Descomprime el ZIP.
2. Crea un repositorio privado en GitHub recomendado para mantener privado el código y evita subir copias de datos personales.
3. Sube el contenido de esta carpeta a la raíz del repositorio.
4. En Vercel, importa el repositorio. Framework preset: Other. No se requiere build command ni output directory.
5. Publica y abre el enlace HTTPS desde tu celular.
6. Android/Chrome: menú ⋮ → Añadir a pantalla principal. iPhone/Safari: Compartir → Añadir a pantalla de inicio.

## Respaldo: leer antes de usar
- El sistema no envía marcaciones a GitHub ni a Vercel. Los datos permanecen en el almacenamiento local de ese navegador/dispositivo.
- IndexedDB y localStorage son dos mecanismos en el mismo dispositivo, no son dos copias independientes ni una garantía contra pérdida.
- Usa el botón “Descargar copia completa (.json)” cada día. Guarda el archivo en otra ubicación segura. Para cambiar de celular, instala/abre la app y usa “Restaurar copia JSON”.
- No guardes archivos JSON con datos personales en un repositorio público.
- El reloj usa la fecha/hora del dispositivo y no se conecta al sistema oficial de asistencia. Para incidencias laborales conserva también reportes/correos oficiales.
- Una web estática con solo GitHub y Vercel no puede sincronizar ni recuperar automáticamente los datos después de perder el dispositivo. Para recuperación remota automática haría falta un servicio de almacenamiento autenticado o sincronización en nube.
