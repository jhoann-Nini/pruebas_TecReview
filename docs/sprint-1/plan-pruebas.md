# Plan de pruebas — Sprint 1

## 1. Propósito

Documentar la verificación del incremento del Sprint 1 de TecnoReview y generar evidencia para las tareas Jira **S1-28 — Registrar defectos y resultados en Jira** y **S1-30 — Realizar revisión y cierre del sprint**.

Este documento es un plan. Los casos no se consideran ejecutados hasta completar el resultado, la fecha y el enlace a la evidencia.

## 2. Alcance a verificar

Confirmar contra las historias de usuario y criterios de aceptación reales del Sprint:

- Arranque y disponibilidad del backend.
- Despliegue y navegación del frontend.
- Consulta del catálogo y detalle de productos.
- Integración entre frontend y API.
- Conexión y datos esperados en Supabase.
- Registro e inicio de sesión, si forman parte del alcance comprometido.
- Pruebas automatizadas disponibles en el repositorio del producto.

## 3. Casos de prueba

| ID | Área | Procedimiento | Resultado esperado | Resultado real | Estado |
|---|---|---|---|---|---|
| S1-T01 | Render / API | Revisar el estado del servicio y consultar el endpoint de salud si está configurado. | Servicio disponible y respuesta esperada del endpoint. | Pendiente de ejecutar | Pendiente |
| S1-T02 | API | Ejecutar una consulta GET a un endpoint público del catálogo. | Respuesta HTTP y estructura de datos esperadas según la API. | Pendiente de ejecutar | Pendiente |
| S1-T03 | Vercel / frontend | Abrir el despliegue correspondiente y navegar por la página principal. | La página carga sin errores bloqueantes. | Pendiente de ejecutar | Pendiente |
| S1-T04 | Catálogo | Consultar el listado de productos desde la interfaz. | Se muestran los productos esperados y no hay errores de integración. | Pendiente de ejecutar | Pendiente |
| S1-T05 | Detalle | Abrir un producto del catálogo. | Se presenta el detalle correcto del producto seleccionado. | Pendiente de ejecutar | Pendiente |
| S1-T06 | Supabase / datos | Revisar las tablas y los registros de prueba pertinentes. | Existen las tablas y datos esperados; no se modifica información de producción. | Pendiente de ejecutar | Pendiente |
| S1-T07 | Autenticación | Probar registro/inicio de sesión con una cuenta de prueba, si aplica. | El flujo funciona y los errores se manejan de forma adecuada. | Pendiente de ejecutar | Pendiente |
| S1-T08 | Integración | Verificar en navegador las solicitudes a la API y revisar errores de consola/red. | Las solicitudes esperadas responden correctamente; no hay fallos bloqueantes. | Pendiente de ejecutar | Pendiente |
| S1-T09 | Automatización | Ejecutar las pruebas automatizadas documentadas para el commit evaluado. | Se registra el comando, versión/commit y resultado real. | Pendiente de ejecutar | Pendiente |

## 4. Registro por ejecución

Para cada caso completado, anotar:

- Fecha y hora (con zona horaria).
- Persona que ejecuta.
- Entorno y URL sin parámetros secretos.
- Commit/despliegue evaluado, cuando corresponda.
- Resultado: Aprobado, Fallido, Bloqueado o No aplica.
- Evidencia enlazada desde `registro-evidencias.md`.
- Jira relacionado y defecto creado, si corresponde.

## 5. Seguridad y calidad de evidencia

- Ocultar tokens, cookies, claves, contraseñas, cadenas de conexión y datos personales.
- No ejecutar operaciones destructivas ni modificar datos de producción para probar.
- Un despliegue en estado correcto o la ausencia de errores en logs no prueba por sí solo el funcionamiento de una historia.
- No inventar resultados, defectos, métricas, fechas ni claves de Jira.
- Si no se puede verificar un caso, marcarlo Bloqueado o Pendiente e indicar la razón.

## 6. Criterios de salida

La revisión puede documentarse cuando los casos comprometidos tengan resultados y evidencias; los defectos estén registrados y priorizados en Jira; y las historias se clasifiquen según sus criterios de aceptación y la Definition of Done acordada por el equipo.
