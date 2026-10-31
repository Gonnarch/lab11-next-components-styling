# Laboratorio 11 — Componentes y estilización

Aplicación Next.js con TypeScript, Tailwind CSS y componentes shadcn/ui.

## Ejecutar

Requiere Node.js 20.9 o superior. Ejecutar npm install y npm run dev.

- /styling: Button con CSS Modules; Card y Badge con Tailwind; Input combinado.
- /dashboard: resumen, proyectos, equipo, tareas y configuración.

Los datos viven en memoria de React. Al recargar se restauran los ejemplos. Las operaciones simulan 900 ms de latencia. Los miembros con tareas deben reasignarlas antes de ser eliminados; eliminar proyectos elimina sus tareas y libera sus miembros.

El campo prjectId conserva el nombre indicado en el laboratorio. userId se genera al crear un miembro.

## Comprobaciones

npm run build
npm run lint

## Publicar en Vercel

Importar el repositorio como proyecto Next.js. No requiere variables de entorno ni servicios de pago.
