# Política de seguridad

## Alcance inicial

Esta política cubre repositorios, automatizaciones, documentación y recursos bajo administración directa de YaskCode Academy. Los proyectos educativos pueden incluir ejemplos, plantillas o servicios de terceros; cada repositorio puede añadir instrucciones específicas sin ampliar por ello la responsabilidad de YaskCode Academy sobre servicios externos.

## Qué reportar

Reporta de forma responsable vulnerabilidades o exposiciones relacionadas con código, configuraciones, workflows, secretos, credenciales, dependencias, datos personales, permisos incorrectos, contenido que facilite un daño técnico significativo o fallos que afecten la seguridad de participantes.

No abras un Issue público para vulnerabilidades sensibles, secretos, datos personales o detalles explotables. Antes de publicar esta política como canal operativo definitivo, debe definirse y publicarse un canal privado de reporte. Si un repositorio ya tiene un canal seguro indicado, utiliza ese canal. Si no existe, limita cualquier comunicación pública a una descripción no sensible y espera instrucciones de quienes mantienen el repositorio.

## Qué incluir en un reporte seguro

Incluye el repositorio o componente afectado, versión o commit si se conoce, pasos de reproducción no destructivos, impacto observado y una forma segura de continuar la conversación. No incluyas credenciales reales, datos personales, expedientes académicos ni información que permita explotar el problema públicamente.

## Expectativas de respuesta

YaskCode Academy procurará confirmar recepción, evaluar el alcance y coordinar una respuesta razonable según disponibilidad y riesgo. No se promete un SLA, recompensa, soporte continuo ni una fecha de corrección. La prioridad será reducir exposición, proteger a las personas y documentar de forma responsable las correcciones que puedan hacerse públicas.

## Prácticas para proyectos educativos

- Nunca subas claves, tokens, contraseñas o archivos `.env` con valores reales.
- Usa ejemplos y datos sintéticos o autorizados; minimiza datos personales.
- Mantén dependencias y workflows bajo revisión razonable.
- Revisa permisos de GitHub Actions, configuraciones de despliegue y archivos generados.
- Usa herramientas de análisis de seguridad de manera legal, proporcional y solo sobre sistemas autorizados.
- No pruebes de forma disruptiva, no accedas a cuentas ajenas y no exfiltre datos.

La seguridad es parte del aprendizaje de ingeniería: un hallazgo debe servir para mejorar prácticas sin exponer innecesariamente a estudiantes, colaboradores ni servicios.
