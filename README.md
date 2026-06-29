# Ritmo

App minimalista para llevar hábitos sin complicarse.

## Qué hace

- Añadir hábitos que quieres hacer.
- Añadir hábitos que quieres dejar.
- Marcar cada día los hábitos de hacer.
- Registrar solo los días de recaída en hábitos de dejar.
- Usar un objetivo por defecto de 30 días, editable por hábito.
- Mantener, repetir o archivar un hábito cuando se cumple el objetivo.
- Ver progreso simple por hábito.
- Exportar e importar datos.
- Sincronizar con Supabase cuando las tablas están configuradas.
- Funcionar como PWA con soporte offline básico.

## Datos

Ritmo guarda los datos primero en este dispositivo con `localStorage`.

También está conectado al proyecto de Supabase de la app anterior, usando tablas propias:

- `ritmo_habits`
- `ritmo_logs`
- `ritmo_relapses`

Si aparece `falta configurar`, abre `Archivo`, copia el SQL de `Sincronización` y ejecútalo una vez en el editor SQL de Supabase.
