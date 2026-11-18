# Definition of Done (DoD)

Una historia solo pasa a *Hecho (DoD)* si cumple:

## Calidad del código
- [ ] Sigue los estándares de codificación del equipo (ESLint y Prettier en TypeScript; gofmt y golangci-lint en Go)
- [ ] Pull Request revisado y aprobado por al menos un desarrollador adicional
- [ ] Sin errores críticos en la revisión

## Pruebas y validación
- [ ] Pruebas unitarias implementadas (cobertura mínima 80% en componentes críticos)
- [ ] Pruebas de integración ejecutadas si interactúa con otros servicios
- [ ] Pruebas funcionales realizadas por QA
- [ ] Criterios de aceptación validados

## Seguridad
- [ ] Análisis automático de vulnerabilidades ejecutado
- [ ] Sin vulnerabilidades críticas pendientes
- [ ] Verificado el manejo de autenticación, autorización y datos sensibles

## Integración y despliegue
- [ ] Código integrado a la rama principal
- [ ] Pipeline CI/CD exitoso (Linting → Build → Tests → Seguridad → Staging automático → Producción)
- [ ] **Desplegado en producción** detrás de un interruptor de funcionalidad (*feature flag*), con métricas y logs activos

## Documentación y experiencia
- [ ] Documentación técnica actualizada
- [ ] Documentación de uso actualizada (preguntas frecuentes o guía) si cambia algo que ve el usuario
- [ ] Verificación básica de accesibilidad (contraste y navegación por teclado) en pantallas nuevas
