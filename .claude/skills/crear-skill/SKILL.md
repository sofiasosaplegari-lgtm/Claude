---
name: crear-skill
description: Convierte una tarea que se repite en una skill de Claude Code (Nivel 1 a 2). Usar con /crear-skill, "convertí esto en skill" o cuando algo se explica por tercera vez.
---
# /crear-skill

1. **¿Califica?** Se hace 2-3 veces por semana o más y hay un método que se repite. Si no, seguir en N1 y anotarla en `plantillas/skill-candidata.md`.
2. **Entrevista breve:** qué entra · pasos en orden (reconstruidos de lo ya hecho, con confirmación) · una salida buena ya aprobada como ejemplo · 3-5 criterios de "bien hecho" · qué nunca hace (enviar, gastar, publicar) · dónde deja el resultado.
3. Escribir `.claude/skills/<verbo-nombre>/SKILL.md` con frontmatter (`name`, `description` con las frases reales con que se pediría), más: Antes de arrancar, Pasos, Bien hecho es, Nunca, Entrega.
4. Probarla con un caso real. Lo que falle se corrige en la skill, no en la salida. No está terminada hasta que corrió bien una vez.
5. Registrar en `changelog.md`. Si tiene reglas fijas "si X, hacé Y", sugerir `/crear-rutina` (solo sugerir, no subir de nivel sin OK).
