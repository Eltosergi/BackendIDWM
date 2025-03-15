# Guía de Commits con Gitmoji

Esta guía tiene como objetivo establecer un patrón de commits utilizando **Gitmoji** para mejorar la organización, claridad y seguimiento del historial de cambios en tu proyecto.

## ¿Qué es Gitmoji?

**Gitmoji** es un conjunto de emojis que se utiliza en los mensajes de commit para representar visualmente el tipo de cambio realizado en el código. Usar Gitmoji en los commits ayuda a mejorar la comprensión de los cambios y facilita la colaboración en equipos.

## Emoji y su Significado

A continuación se presentan los emojis y su significado, siguiendo las convenciones de los **Conventional Commits**:

- 🎉 `init`: Commit para la inicialización del proyecto o la creación de un nuevo repositorio.
- ✨ `feat`: Añadir una nueva funcionalidad o característica al proyecto.
- 🐛 `fix`: Corregir un error o bug en el código.
- 📝 `docs`: Cambios relacionados con la documentación, como actualización de README o comentarios.
- 🎨 `style`: Mejoras en la estética del código (formato, espaciado, etc.) sin modificar la lógica.
- 🔥 `refactor`: Refactorización de código sin cambiar su comportamiento.
- 🚀 `perf`: Optimización del rendimiento del código o de la aplicación.
- ✅ `test`: Agregar o modificar pruebas unitarias.
- 🛠️ `chore`: Cambios menores o tareas de mantenimiento, como actualizaciones de dependencias o configuraciones.
- ⬇️ `downgrade`: Comits que indican una regresión o retroceso en alguna funcionalidad.
- 🚧 `wip`: Trabajo en progreso, para cuando el commit no está completamente terminado.

## Ejemplos de Commits con Gitmoji

A continuación, se muestran ejemplos de cómo debería lucir un mensaje de commit usando Gitmoji:

- 🎉 `init: Crear estructura básica del proyecto`
- ✨ `feat: Añadir autenticación de usuario`
- 🐛 `fix: Corregir error en el cálculo de descuentos`
- 📝 `docs: Actualizar la documentación de la API`
- 🎨 `style: Ajustar márgenes en el formulario de login`
- 🔥 `refactor: Eliminar código redundante en la función de pagos`
- 🚀 `perf: Mejorar tiempos de respuesta de la API`
- ✅ `test: Agregar pruebas para la validación de formularios`
- 🛠️ `chore: Actualizar versión de dependencias`
- ⬇️ `downgrade: Revertir funcionalidad de login por problemas de compatibilidad`
- 🚧 `wip: Implementar nueva función de búsqueda (en progreso)`

## Patrones de Commit

Cada commit debe seguir este formato:

```bash
<emoji> <tipo>: <Descripción breve del cambio>


```bash
git commit -m "✨ feat: Añadir soporte para inicio de sesión con Google"
git commit -m "🐛 fix: Corregir bug en la validación de formulario"
git commit -m "📝 docs: Actualizar README con nuevos ejemplos"
