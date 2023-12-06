# Guía de Commits del Proyecto

## Introducción

Esta guía tiene como objetivo establecer un estándar claro para los mensajes de commit en nuestro proyecto. Al seguir estas convenciones, facilitamos la colaboración y el mantenimiento del código.

## Convenciones de Commits

### Formato de Commits

```none
<type>(<scope>): <subject>

<body>

<footer>
```

### Tipos de Commits

Los tipos de commits que se pueden utilizar son los siguientes:

- `feat`: Introduce una nueva funcionalidad
- `fix`: Corrige un error
- `docs`: Actualizaciones en la documentación
- `style`: Cambios que no afectan el significado del código (espacios, formato)
- `refactor`: Cambios en el código que no arreglan errores ni añaden funcionalidad
- `test`: Añade o corrige pruebas
- `chore`: Actualizaciones de tareas rutinarias; no cambian la producción de código.
- `build`: Cambios que afectan el sistema de compilación o dependencias externas.
- `ci`: Cambios en los archivos de configuración y scripts de CI.
- `revert`: Revierte un commit anterior

### Alcance de Commits

El alcance de un commit debe ser el nombre del componente o módulo que se está modificando. Si el cambio afecta a varios componentes, se puede utilizar `*` como alcance.

### Mensaje de Commits

El mensaje de un commit debe ser una descripción corta y concisa de los cambios realizados. Debe comenzar con un verbo en infinitivo y no debe terminar con un punto.

### Plantillas de Commits

#### Actualización de Dependencias

```none
chore(dependencies): Update [dependency name] to version [new version]

Reason for change: [Briefly describe the reason for the update, such as security fixes, new features, etc.]
```

#### Creación de un Nuevo Componente

```none
feat(components): Add new component [component name]

Description: [Explain the functionality of the new component and how it is expected to improve the application]
```

#### Corrección de un Error

```none
fix([component/module]): [describe the bug]

Details: [Explain the cause of the bug and how it was solved]
```

#### Actualización de la Documentación

```none
docs([component/module]): [describe the changes]
```

#### Realizar un test

```none
test([tested component]): Add unit test for [describe the functionality or use case]
```

## Buenas Prácticas

- Mantén los mensajes de commit claros y descriptivos.
- Agrupa los cambios relacionados en un único commit.
- Evita commits demasiado grandes que abarquen múltiples aspectos.

---

Este documento debe ser consultado y actualizado por todos los miembros del equipo para garantizar la coherencia en nuestro enfoque de desarrollo.
