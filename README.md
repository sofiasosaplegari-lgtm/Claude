# Segundo cerebro con Claude Code — plantillas y skills abiertas

**ES:** Un sistema simple, en archivos Markdown, para usar [Claude Code](https://claude.com/claude-code) como un "segundo cerebro": una carpeta de conocimiento que Claude lee, ordena y mantiene, más un método para convertir tareas repetidas en *skills* y *rutinas*. Pensado para emprendedores y personas sin formación técnica. Todo es texto: lo copiás, lo adaptás y lo usás.

**EN:** A lightweight, Markdown-only system for using Claude Code as a "second brain": a knowledge folder that Claude reads and maintains, plus a method to turn repeated tasks into reusable *skills* and automated *routines*. Written for non-technical founders. Everything is plain text you can copy and adapt. (Docs are in Spanish; the structure is language-agnostic.)

> Este repo no contiene datos personales, de clientes ni de ningún negocio. Son solo estructura y método.

## Qué incluye

| Carpeta | Para qué sirve |
|---|---|
| `CLAUDE.md` | Manual de instrucciones base para tu cerebro (rellená los `[corchetes]`). |
| `plantillas/` | Plantillas: brief para otro proyecto, cierre recuperable, contrato de rutina, skill candidata, día de mañana, revisión semanal. |
| `.claude/skills/` | Skills listas para usar: `crear-skill`, `crear-rutina`, `guardar-cierre`, `retomar`, `recordar`, `matriz`. |
| `RUTINAS/REGLAS-GENERALES.md` | Reglas comunes para cualquier automatización (reintentos, avisos, qué nunca hace sola). |
| `docs/los-3-niveles.md` | El método central: Nivel 1 (hablar), Nivel 2 (skill), Nivel 3 (rutina). |

## Estructura recomendada del cerebro

```
RAW/       material en crudo (nunca se modifica)
WIKI/      un archivo por tema, resumido y con enlaces [[tema]]
OUTPUTS/   entregables con fecha: AAAA-MM-DD-tema.md
RUTINAS/   contratos de automatizaciones
changelog.md
```

## Cómo empezar (5 minutos)

1. Copiá `CLAUDE.md`, `plantillas/` y `.claude/skills/` a tu carpeta de trabajo.
2. Abrí la carpeta con Claude Code y completá los `[corchetes]` de `CLAUDE.md`.
3. Cargá algo en `RAW/` y pedile: *"procesá RAW"*.
4. Al terminar una tarea: *"guardá lo importante de esta charla"* (skill `guardar-cierre`).
5. Si explicás lo mismo por tercera vez: `/crear-skill`.

## Principios

- **Nada inventado:** separar siempre propuesto / decidido / verificado, y modificado / probado / publicado.
- **Nada se borra solo:** lo viejo se archiva.
- **Delegar la ejecución, nunca el criterio:** la persona aprueba lo que sale al mundo.
- **Sin secretos en archivos:** nunca claves ni contraseñas en el repo.

## Licencia

MIT. Usalo, copialo, mejoralo. Las contribuciones son bienvenidas (issues y pull requests).
