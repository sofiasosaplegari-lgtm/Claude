---
name: crear-rutina
description: Convierte una skill con reglas fijas en una rutina que corre sola (Nivel 2 a 3). Usar con /crear-rutina o "que esto corra solo".
---
# /crear-rutina

1. **¿Califica?** (a) 2-3 veces por semana o más; (b) si hay que ver el resultado antes de que salga, queda en N2; (c) se escribe como "si pasa X, hacé Y" con condición medible.
2. **Reglas:** disparador · `si <condición> → <acción>` · qué NUNCA hace · a quién avisa · qué pasa si falla una fuente (un error jamás se reporta como "todo bien").
3. **Dónde corre:** todo por API → nube; navegador logueado → compu; chequeo simple y frecuente → script con cron.
4. Escribir `RUTINAS/<nombre>.md` con `plantillas/contrato-rutina.md` más `RUTINAS/REGLAS-GENERALES.md`. Si toca dinero, clientes o publicaciones: por defecto solo lectura, aviso y borrador.
5. Probarla a mano una vez y leer su registro. Estados: solo diseñada → programada → verificada. Decir en cuál quedó y anotar en `changelog.md`.
