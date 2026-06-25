# Impulsos

App minimalista para registrar impulsos superados o recaídas, organizarlos por etiquetas y ver estadísticas de progreso.

Incluye:

- dos pestañas: Inicio y Estadísticas;
- etiquetas editables;
- varios registros por día;
- intensidad del impulso;
- índice de calma, tasa de control, recaídas, intensidad media y racha;
- gráficas globales y por etiqueta;
- sincronización con Supabase cuando las tablas están configuradas;
- PWA con soporte offline básico.

## Supabase

La app ya está cableada al proyecto de Supabase usado por la app de referencia, pero usa tablas propias para no mezclar datos.

Si aparece `falta configurar`, abre `Sincronización` en el menú de la app, copia el SQL y ejecútalo una vez en el editor SQL de Supabase.
