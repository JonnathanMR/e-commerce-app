# Plaza Libre

Prototipo de aplicación móvil/web desarrollado con Ionic y Angular. El proyecto contiene una pantalla principal y vistas de mensajes, con navegación hacia el detalle de cada conversación.

## Tecnologías

- Angular 17
- Ionic 7
- Capacitor 5
- TypeScript

## Rutas principales

- `/home`: pantalla principal.
- `/message/:id`: detalle de un mensaje.

## Requisitos

- Node.js LTS y npm.

## Ejecutar localmente

```bash
npm install
npm start
```

## Comandos

```bash
npm run build
npm test
npm run lint
```

## Estructura

```text
src/app/
├── home/           # Pantalla principal
├── message/        # Funcionalidad de mensajes
├── view-message/   # Vista de detalle
├── services/       # Servicios de la aplicación
└── app-routing.module.ts
```

## Desarrollo

El repositorio está preparado para ejecución web y para empaquetarse con Capacitor. Antes de integrar datos reales, define la capa de servicios, manejo de errores y configuración segura de cualquier API externa.
