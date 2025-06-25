# SmartAgenda – Diseño UI/UX + Desarrollo
Prototipo funcional de una app de recordatorios - Mayo del 2025

## Rol en el Proyecto
Asumí el rol de Scrum Master y líder de diseño:
- Definí las funcionalidades y estructura general de la aplicación.
- Organicé el flujo de trabajo del equipo, tareas y pantallas.
- Diseñé la interfaz completa en Figma, enfocándome en usabilidad y navegación clara.
- Apoyé la integración de APIs para notificaciones push utilizando Expo.

## Objetivo del Proyecto
Crear una aplicación de recordatorios centrada en el usuario, con notificaciones proactivas y una experiencia intuitiva, funcional incluso sin conexión a internet.

## Tecnologías y Herramientas
- Figma para prototipado visual y diseño de interfaz.
- React Native + Expo como framework de desarrollo.
- JavaScript (ES6+) como lenguaje base.
- SQLite (expo-sqlite) para base de datos local.
- Expo Notifications para notificaciones push locales.
- React Context API para manejo de estado global.
- Git y GitHub para control de versiones y colaboración.

## Arquitectura del Sistema
Implementación con arquitectura MVVM en capas:
- View: Pantallas funcionales desarrolladas en React Native.
- ViewModel: Manejo de lógica, validaciones y estado.
- Model/Repository: Comunicación con la base de datos local (SQLite).

Toda la lógica y persistencia se ejecuta directamente en el dispositivo (Edge Computing), lo que garantiza funcionalidad sin conexión y privacidad del usuario.

## Funcionalidades Clave
- Crear, editar y eliminar recordatorios.
- Vista de tareas por día, calendario mensual y próximas/pasadas.
- Notificaciones automáticas programadas sin conexión.
- Persistencia de datos local.
- Marcado de tareas como completadas.

## Vista Previa
![SmartAgenda Preview](./assets/smartagenda-preview)

![SmartAgenda Gif](./assets/smartagenda-gif)

[Ver prototipo en Figma](https://www.figma.com/design/7ktaxUxNghY21Nnnf6xgNa/SmartAgenda?m=auto&t=JrgXVk75v9MmxhXI-6)

[Ver proyecto expandido](./smartagenda/README.md) <!-- Ajusta esta ruta si lo necesitas -->

## Aprendizajes clave
- Aprendí a trabajar con React Native y comprender su ciclo de vida y componentes.
- Apliqué metodologías ágiles como Scrum, desde la planificación hasta los sprints.
- Me familiaricé con la creación de prototipos y wireframes usando Figma.
- Mejoré mis habilidades organizativas al liderar el diseño y definir pantallas y flujos funcionales.
