# Reglas generales para cualquier rutina

1. **Contrato primero.** Toda rutina tiene su archivo `RUTINAS/<nombre>.md` (ver `plantillas/contrato-rutina.md`).
2. **Reintentar antes de avisar.** Ante un fallo, reintentar y probar un camino alternativo. No abortar ni molestar a la persona a la primera.
3. **Alerta urgente solo si hay pérdida real** y ya se agotaron los reintentos.
4. **Un error nunca es éxito.** Un 401, un timeout o una fuente caída se reportan como falla.
5. **Ejecutar solo lo autorizado por el contrato.** Todo lo demás: leer, avisar o dejar borrador.
6. **Acciones reservadas a la persona:** enviar mensajes, publicar, cobrar, gastar, borrar.
7. **Nube primero:** si todo se hace por API, corre en la nube y no depende de una compu prendida.
8. **Sin secretos en archivos.** Las claves viven en la herramienta que las usa.
9. **Evitar duplicados:** la rutina reconoce lo ya procesado.
10. **Registro:** cada corrida deja una línea en `RUTINAS/registro/<nombre>.md`.
