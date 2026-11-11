---
name: guardar-cierre
description: Guarda un cierre recuperable de lo trabajado. Usar cuando digo "guardá lo importante de esta charla", "guardá el cierre" o al terminar una tarea.
---
# Guardar cierre

1. Usá `plantillas/cierre-recuperable.md`: tema y fecha; estado (propuesto / decidido / implementado / verificado / bloqueado); decisión vigente y fuente; resultado; archivos con ruta real; pruebas; faltantes; próximo paso.
2. Separá lo propuesto, lo decidido y lo verificado. No marques como hecho lo que solo se planificó.
3. Guardalo en `OUTPUTS/cierres/AAAA-MM-DD-tema.md` y anotalo en `changelog.md`.
4. Si hay acceso, sincronizá con git. Nunca subas claves, `.env` ni tokens.
5. Decime dónde quedó y cómo recuperarlo en un chat nuevo: "Recuperá el último cierre de [tema]".
