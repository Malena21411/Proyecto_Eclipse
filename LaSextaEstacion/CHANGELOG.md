# Changelog — Proyecto Eclipse

Registro de los cambios importantes realizados durante el desarrollo del proyecto progresivo de modding.

## [0.1.0] — Beta 0.1

Primera beta funcional de Proyecto Eclipse.

### Historia

- Creada la historia inicial de Proyecto Eclipse.
- Establecida la desaparición de una antigua estación ferroviaria como misterio principal.
- Incorporada una progresión narrativa durante los primeros cuatro días de una nueva partida.
- Establecida la secuencia narrativa:
  - Día 1: inicio normal de Stardew Valley.
  - Día 2: carta inicial, Lewis y Abigail.
  - Día 3: Informe 001, Lewis y Sebastián.
  - Día 4: Informe 002 y fotografía de la estación.

### Correos

- Añadida carta inicial anónima.
- Añadido Informe 001.
- Añadido Informe 002.
- Añadido correo con fotografía de la estación.
- Integrados los documentos dentro del sistema de correo del juego.
- Configurado el envío de los informes mediante `Data/TriggerActions`.

### Diálogos

- Modificado el diálogo de introducción de Lewis.
- Modificado el diálogo de introducción de Abigail.
- Añadidos diálogos de Sebastián relacionados con Proyecto Eclipse.
- Añadidas advertencias y pistas relacionadas con la estación.
- Añadidas conversaciones relacionadas con los informes descubiertos.

### Recursos gráficos

- Añadida fotografía personalizada de la estación.
- Integrado el recurso gráfico dentro del sistema de correo del juego.

### Organización

- Separados los correos y diálogos en archivos JSON independientes.
- Organizado el proyecto mediante archivos `Include` en `content.json`.
- Creada una estructura de carpetas para datos y recursos.
- Creada documentación del proyecto mediante `README.md` y `CHANGELOG.md`.

### Pruebas

- Comprobada la carga del mod mediante SMAPI.
- Comprobada la detección del Content Pack.
- Comprobado el funcionamiento de los diálogos.
- Comprobado el envío de la carta inicial.
- Comprobado el envío del Informe 001.
- Comprobado el envío del Informe 002.
- Comprobada la recepción y visualización de la fotografía.
- Comprobada la progresión narrativa hasta el final de la Beta 0.1.

## [0.0.1] — Desarrollo inicial

Primera etapa de desarrollo y configuración del proyecto.

### Preparación

- Creado el proyecto Proyecto Eclipse.
- Configurado Stardew Valley para utilizar SMAPI.
- Instalado Content Patcher.
- Creada la estructura inicial de carpetas.
- Creado `manifest.json`.
- Creado `content.json`.

### Primeras pruebas

- Comprobada la carga inicial del Content Pack.
- Realizadas pruebas iniciales con cartas.
- Realizadas pruebas iniciales con diálogos.
- Investigadas diferentes formas de implementar eventos narrativos.
- Realizadas pruebas de detección y activación mediante `Data/TriggerActions`.

### Cambios de diseño

- Se investigó la posibilidad de modificar directamente eventos originales del juego.
- Se descartó la modificación directa del evento original del museo.
- Se simplificó la propuesta para crear una Beta funcional y alcanzable.
- Se estableció el sistema de cartas y diálogos como base de la primera versión.
- Se definió una progresión narrativa distribuida durante los primeros días de una nueva partida.

## Próximamente

Posibles contenidos para futuras versiones:

- Continuación de la historia.
- Nuevos documentos.
- Nuevas pistas.
- Nuevos eventos narrativos.
- Ampliación del misterio de la estación perdida.
- Desarrollo de la historia de la villa relacionada con la estación.

Estos contenidos no forman parte de la Beta 0.1, son solo una posibilidad.