#  Propuesta de Mantenimiento Perfectivo
**Proyecto:** Sistema de Registro de Usuarios  
**Autor:** Erick Arreaga Martínez 
**Fecha:** 12/11/2025  
**Versión:** 1.0  


## 1. Descripción del sistema
El **Sistema de Registro de Usuarios** permite a las personas crear cuentas, iniciar sesión, recuperar contraseñas y editar sus datos personales.  
Su propósito es gestionar usuarios de forma segura y sencilla, garantizando el acceso a las funcionalidades del sistema principal.

Actualmente el sistema cumple sus funciones básicas, pero se han identificado oportunidades de mejora en la **interfaz**, **seguridad** y **rendimiento**.


##  2. Tipo de mantenimiento propuesto
Se propone un **mantenimiento perfectivo**, orientado a **mejorar las características existentes** del sistema sin alterar su propósito principal.

El mantenimiento perfectivo busca **incrementar la eficiencia, usabilidad y seguridad** del software, respondiendo a la retroalimentación de los usuarios y buenas prácticas de desarrollo.


##  3. Mejoras propuestas

| Nº | Área de mejora | Descripción | Beneficio esperado |
|----|----------------|-------------|--------------------|
| 1 | Interfaz del usuario | Rediseñar los formularios con validaciones visuales (por ejemplo, mostrar errores en tiempo real). | Facilita la comprensión y mejora la experiencia del usuario. |
| 2 | Seguridad | Implementar cifrado de contraseñas con algoritmos actualizados (bcrypt o SHA-256). | Protege los datos sensibles frente a accesos no autorizados. |
| 3 | Recuperación de contraseña | Añadir validación mediante token temporal enviado al correo. | Aumenta la seguridad del proceso de recuperación. |
| 4 | Validaciones de entrada | Exigir contraseñas con mínimo 8 caracteres y verificar formato de correo electrónico. | Disminuye registros inválidos y posibles errores de ingreso. |
| 5 | Rendimiento | Optimizar consultas al servidor y reducir carga de scripts innecesarios. | Mejora la velocidad del registro e inicio de sesión. |


##  4. Justificación
El mantenimiento perfectivo permite mantener el sistema actualizado frente a nuevas necesidades de los usuarios.  
Estas mejoras **no corrigen errores** sino que **perfeccionan su funcionamiento**, generando una experiencia más segura, rápida y confiable.

Además, aplicar este tipo de mantenimiento demuestra comprensión de los procesos de **evolución del software** y **ciclo de vida de sistemas** vistos en clase.
 


##  5. Control de versiones

| Versión | Fecha | Descripción | Autor |
|----------|--------|-------------|--------|
| 1.0 | 12/11/2025 | Creación del documento con propuesta de mantenimiento perfectivo. | Erick Arreaga|


##  6. Conclusión
El mantenimiento perfectivo propuesto mejorará el sistema en aspectos clave como **seguridad, rendimiento y experiencia de usuario**.  
Implementar estas mejoras permitirá una evolución controlada y alineada con las buenas prácticas del desarrollo de software.  
