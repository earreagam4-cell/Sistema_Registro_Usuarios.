#  Investigación: Uso de Markdown en proyectos de software

##  ¿Qué es Markdown?

**Markdown** es un lenguaje de marcado ligero que permite escribir texto con formato utilizando una sintaxis sencilla, clara y legible incluso sin procesar.  
Fue creado por *John Gruber* en 2004 con el propósito de hacer que la escritura de documentos web fuera más accesible y rápida.

A diferencia de los procesadores de texto tradicionales, Markdown se basa en símbolos simples como `#`, `*`, `-` o `` ` `` para definir títulos, listas, negritas, enlaces, tablas y fragmentos de código.  
Esto facilita la redacción de documentación técnica que luego puede convertirse fácilmente a HTML, PDF o presentarse directamente en plataformas como **GitHub** o **GitLab**.

---

##  ¿Por qué se utiliza en proyectos de software?

Markdown es ampliamente utilizado en el desarrollo de software porque:
-  **Facilita la documentación técnica** (por ejemplo, en archivos `README.md` o manuales de usuario).  
-  **Es fácil de aprender**: la sintaxis es intuitiva y no requiere herramientas especiales.  
-  **Se integra perfectamente con Git y GitHub**, mostrando los archivos directamente en formato visual.  
-  **Permite versionar la documentación** junto con el código fuente.  
-  **Es multiplataforma y portable**: se ve igual en Windows, Linux o macOS.

En resumen, Markdown ayuda a que la documentación sea **ligera, colaborativa y siempre actualizada**.

##  Sintaxis básica y ejemplos prácticos

A continuación, algunos ejemplos que se usan con frecuencia:

###  Encabezados
```markdown
# Título principal
## Subtítulo
### Encabezado de tercer nivel

## Listas
Lista desordenada:
- Elemento 1
- Elemento 2
  - Sub-elemento

Lista ordenada:
1. Paso uno  
2. Paso dos  
3. Paso tres

## Énfasis en texto
**Texto en negrita**  
*Texto en cursiva*  
~~Texto tachado~~

## Tablas
| Campo       | Tipo   | Descripción                   |
|--------------|--------|-------------------------------|
| email        | texto  | Correo del usuario (único)    |
| contraseña   | texto  | Contraseña cifrada (hash)     |
| rol          | texto  | Rol del usuario en el sistema |


##  Ventajas de usar Markdown junto con GitHub

| Ventaja | Descripción |
|----------|-------------|
| **Versión controlada** | Markdown se guarda como texto plano, por lo que Git puede rastrear cada cambio línea por línea. |
| **Visualización automática** | GitHub renderiza los archivos `.md` de forma legible sin necesidad de convertirlos. |
| **Integración con issues y wikis** | Markdown se usa para describir errores, tareas y notas de proyecto. |
| **Facilita colaboración** | Los equipos pueden revisar, comentar y modificar la documentación en tiempo real. |
| **Compatibilidad con GitHub Pages** | Permite publicar documentación o portafolios técnicos directamente desde el repositorio. |


##  Ejemplo aplicado: README en Markdown

A continuación, un extracto real de cómo podría iniciarse un `README.md` de un proyecto de software:

```markdown
# Sistema de Registro de Usuarios

Aplicación web que permite registrar, autenticar y gestionar cuentas de usuario.  
Incluye funcionalidades de verificación por correo electrónico y recuperación de contraseña.

## Características principales
- Registro con validación de email único
- Inicio de sesión seguro con contraseñas cifradas
- Recuperación de contraseña mediante enlace temporal

Como se observa, Markdown hace que la documentación sea clara, organizada y fácil de mantener sin necesidad de software complejo.

## Reflexión final
Markdown es una herramienta esencial en el ciclo de vida del software moderno.
Su sencillez permite centrarse en el contenido, no en el formato, mientras que su compatibilidad con Git y GitHub promueve la trazabilidad, la colaboración y la transparencia.
En proyectos técnicos, usar Markdown no solo mejora la presentación de los documentos, sino que también fomenta la disciplina de mantener la documentación viva y sincronizada con el código.

Autor: Arreaga Martinez Erick 
Fecha: Noviembre 2025
Asignatura: Ingeniería de Software
Caso de uso: Sistema de registro de usuarios