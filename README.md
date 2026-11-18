# Specless — Backlog y tableros ágiles

Repositorio de backlog del proyecto Specless (Administración de Sistemas de Información, 2026).
Las historias viven como *issues* y se gestionan en GitHub Projects: https://github.com/users/FrancoV20/projects/4

| Vista | Para qué sirve |
|---|---|
| [Specless Core (génesis)](https://github.com/users/FrancoV20/projects/4/views/4) | Tablero Kanban único de los 6 fundadores (M1–M6), con carriles |
| [Producto (Scrum)](https://github.com/users/FrancoV20/projects/4/views/1) | Tablero del equipo de Producto desde validación (M7) |
| [Backlog](https://github.com/users/FrancoV20/projects/4/views/3) | Backlog completo con equipo, épica, story points, MoSCoW, clase de servicio y KR |

## Políticas del equipo
- [Definition of Ready](DoR.md)
- [Definition of Done](DoD.md)

## Metodología por etapa
| Etapa | Equipo | Marco |
|---|---|---|
| Génesis (M1–M6) | Los 6 fundadores | Kanban con un único tablero «Specless Core» |
| Validación (M7–M18) | Producto · Plataforma · Soporte | Scrum · Scrumban · Kanban |
| Escalado (M19–M36) | Los tres equipos | Igual que en validación, con prácticas XP en Producto y Plataforma |

## Génesis — tablero «Specless Core»
Hipótesis / ideas → Lista (WIP 8) → En curso (WIP 5) → En revisión / prueba (WIP 3) → Experimento en medición (WIP 3) → Hecho / aprendido

Carriles: Producto · Plataforma · Validación y negocio.

## Producto (Scrum, sprints de 2 semanas)
Product Backlog → Refinement (DoR) → Sprint Backlog → En curso → Code Review / PR → QA / Pruebas → Hecho (DoD)

- Sin clase Expedite: las urgencias de infraestructura van a Plataforma.
- Los límites WIP son un acuerdo interno del sprint.
- Todas las historias se estiman en story points con Planning Poker.
- Staging no es una columna: el pipeline lo recorre de forma automática.

## Plataforma (Scrumban)
Backlog → Listo (punto de pedido: 4) → En curso (WIP 3) → Revisión (WIP 2) → Despliegue y verificación (WIP 2) → Hecho

Carril de urgencias (Expedite, WIP 1): solo incidentes que afectan a usuarios; puede superar los WIP de columna.

## Clases de servicio
- **Expedite:** incidentes que afectan a usuarios (solo en Plataforma); se atienden en enjambre.
- **Fixed Date:** entregas con fecha comprometida (por ejemplo, HU9 antes de la beta, HU19 antes del lanzamiento pago).
- **Standard:** flujo normal, según la prioridad de la revisión de roadmap.
- **Intangible:** *spikes* y deuda técnica, hasta el 15% de la capacidad.

## Campos y etiquetas del backlog
- **Equipo:** Producto o Plataforma (equipo dueño).
- **Épica:** E1 Acceso seguro, cuentas y pagos · E2 Sesiones y experiencia de uso · E3 Instituciones · E4 Plataforma de sesiones.
- **Story points** y **MoSCoW** (Must, Should, Could, Won't).
- **Etiqueta de KR:** cada historia lleva el objetivo que mueve (`O-G1`, `O-G2`, `O-V1`, `O-V2`, `O-V3`, `O-E2`, `O-E3`).
