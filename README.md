# Sistema de registro de usuarios

**Descripción breve**  
Aplicación para el registro, autenticación y gestión básica de usuarios: registro con confirmación por email, inicio de sesión, recuperación de contraseña y edición de perfil.


## Tabla de contenidos
- [Descripción](#descripción)
- [Estado](#estado)
- [Requerimientos](#requerimientos)
- [Cómo probar / Plan de pruebas (resumen)](#cómo-probar--plan-de-pruebas-resumen)
- [Estructura del repositorio](#estructura-del-repositorio)
- [Documentos principales](#documentos-principales)
- [Propuesta de mantenimiento (resumen)](#propuesta-de-mantenimiento-resumen)
- [Investigación sobre Markdown](#investigación-sobre-markdown)
- [Evidencias](#evidencias)
- [Reflexión sobre control de versiones](#reflexión-sobre-control-de-versiones)
- [Autor / Entrega](#autor--entrega)


## Descripción
Este repositorio contiene los artefactos para el caso de uso *Sistema de registro de usuarios*: requerimientos (v1 y v2), plan de pruebas, propuesta de mantenimiento, investigación sobre Markdown y evidencias.


## Estado
- Documentación:  completada (DRS_v1, DRS_v2)  
- Plan de pruebas:  completado  
- Propuesta de mantenimiento:  pendiente (plantilla incluida en `mantenimiento/`)  
- Investigación Markdown:  pendiente (plantilla en `investigacion/`)  

## Requerimientos
Los documentos con detalle están en:
- `requerimientos/DRS_v1.docx`  
- `requerimientos/DRS_v2.docx`

Resumen rápido: registro con email único, hashing de contraseñas, bloqueo por intentos, tokens para recuperación, compatibilidad móvil y disponibilidad.


## Cómo probar — Plan de pruebas (resumen)
Los casos esenciales (ver `pruebas/PlanPruebas.docx`):
1. Registro válido — se crea cuenta + email de confirmación.  
2. Registro con email duplicado — mostrar error y no crear cuenta.  
3. Inicio de sesión con credenciales incorrectas — 401 y bloqueo tras 5 intentos.

## Estructura del repositorio
/Sistema_registro_usuarios

├── README.md

├── requerimientos/

│ ├── DRS_v1.docx

│ └── DRS_v2.docx

├── pruebas/

│ └── PlanPruebas.docx

├── mantenimiento/

│ └── Propuesta_Mantenimiento.md

├── investigacion/

│ └── Uso_de_Markdown.md

└── evidencias/

├── historial_commits.png

├── versionado_docs.png

└── estructura_repo.png

---

## Documentos principales
- **DRS_v1**: `requerimientos/DRS_v1.docx`  
- **DRS_v2**: `requerimientos/DRS_v2.docx`  
- **Plan de pruebas**: `pruebas/PlanPruebas.docx`  
- **Propuesta de mantenimiento**: `mantenimiento/Propuesta_Mantenimiento.md`  
- **Investigación Markdown**: `investigacion/Uso_de_Markdown.md`  

## Propuesta de mantenimiento (resumen)
Tipo: **Mantenimiento Correctivo**.  
Objetivo: corregir fallas que impidan el registro o autenticación (p. ej. problemas en validaciones, fallas en envío de email, condiciones de carrera en la DB).  
Ver `mantenimiento/Propuesta_Mantenimiento.md` para el proceso completo (detección, análisis, corrección, despliegue, cierre).


## Investigación sobre Markdown
Incluye: qué es Markdown, ejemplos (encabezados, listas, tablas, código) y ventajas de usarlo con GitHub. Ver `investigacion/Uso_de_Markdown.md`.


## Evidencias
En la carpeta `evidencias/` encontrarás capturas que muestran:
- `historial_commits.png` — historial con al menos 3 commits descriptivos.  
- `versionado_docs.png` — ejemplo de cambios en un documento (diff o versiones).  
- `estructura_repo.png` — captura de la estructura antes de comprimir.

## Reflexión sobre control de versiones
El uso de Git/GitHub permite:
- Rastrear cambios y autores (historial de commits).  
- Revertir a versiones anteriores si un cambio rompe documentación o código.  
- Documentar decisiones mediante mensajes de commit.  
- Colaborar sin sobreescribir trabajo (branches/PRs).

## Autor / Entrega
- Nombre: Arreaga Martinez Erick Miguel 
- Curso: B "3"
