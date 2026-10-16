# Registro de pruebas — TecnoReview

Este repositorio reúne la documentación y las evidencias de prueba de los tres Sprints del proyecto de Desarrollo de Software.

## Objetivo

Registrar de forma trazable qué se probó, en qué entorno, cuál fue el resultado y qué defectos o pendientes se identificaron. Los resultados deben basarse en ejecuciones reales; las plantillas no representan pruebas ya ejecutadas.

## Estructura

- [Plan de pruebas del Sprint 1](docs/sprint-1/plan-pruebas.md): alcance y casos de prueba propuestos.
- [Registro de evidencias](docs/sprint-1/registro-evidencias.md): índice para capturas, logs y resultados.
- [Registro de defectos](docs/sprint-1/registro-defectos.md): plantilla para defectos encontrados.
- [Revisión y cierre del Sprint 1](docs/sprint-1/cierre-sprint.md): checklist para S1-30.

## Cómo registrar una prueba

1. Ejecutar el caso y anotar fecha, entorno y resultado real.
2. Guardar evidencia sin secretos, tokens ni datos personales.
3. Registrar cada defecto reproducible en Jira y enlazar la evidencia.
4. No marcar una historia como terminada hasta validar sus criterios de aceptación y la Definition of Done acordada por el equipo.
5. Mantener las conclusiones como «pendientes de verificar» hasta contar con evidencia.

## Entornos previstos

- Frontend: Vercel.
- Backend/API: Render.
- Base de datos y autenticación: Supabase.
- Código y pruebas automatizadas: GitHub y entorno local.

La disponibilidad de logs y la información visible depende de la configuración de cada servicio. No se deben subir archivos de entorno, credenciales, claves, tokens ni exportaciones con datos sensibles.
