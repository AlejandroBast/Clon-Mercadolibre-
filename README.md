# Clon Mercadolibre - Frontend

> Proyecto de clon de MercadoLibre construido con Vite + React + TypeScript y TailwindCSS.

## Resumen

Este repositorio contiene la interfaz frontend del clon de MercadoLibre creado como ejercicio. Usa Vite para el bundling, React + TypeScript para la UI y TailwindCSS junto con componentes basados en Radix/`shadcn`.

## Requisitos

- Node.js (v18+ recomendado) o `bun` / `pnpm` según preferencia.
- Git

## Instalación

Instala las dependencias con tu gestor preferido:

`npm install`

o

`pnpm install`

o

`bun install`

## Scripts disponibles

- **Dev:** `npm run dev` — Ejecuta el servidor de desarrollo (Vite).
- **Build:** `npm run build` — Genera la versión de producción.
- **Build (dev mode):** `npm run build:dev` — Genera el build en modo `development`.
- **Preview:** `npm run preview` — Previsualiza el build localmente.
- **Lint:** `npm run lint` — Ejecuta ESLint sobre el proyecto.
- **Test:** `npm run test` — Ejecuta pruebas con Vitest.
- **Test (watch):** `npm run test:watch` — Corre Vitest en modo watch.

Ejemplo para arrancar en desarrollo:

`npm run dev`

## Estructura del proyecto (resumen)

- `src/` : Código fuente principal.
  - `assets/components/` : Componentes reutilizables (Navbar, HeroBanner, Footer, etc.).
  - `pages/` : Rutas/páginas (ej. `Index.tsx`, `NotFound.tsx`).
  - `lib/` : Utilidades (ej. `utils.ts`).
  - `hooks/` : Hooks personalizados.
  - `test/` : Pruebas y setup para Vitest.

Archivos principales:

- `index.html` — Entrada HTML.
- `vite.config.ts` — Configuración de Vite.
- `tailwind.config.ts` — Configuración de Tailwind.

## Tecnologías principales

- Vite
- React (18)
- TypeScript
- TailwindCSS
- Radix UI + componentes `shadcn` (en `assets/components/ui`)
- React Router DOM
- Vitest (tests)

## Notas de desarrollo

- Si usas `bun`, los scripts pueden ejecutarse con `bun run <script>`.
- Para agregar nuevas dependencias, preferible usar el mismo gestor que usó el equipo (ej. `npm i <pkg>`).
- Mantén los estilos con las clases de Tailwind y reutiliza los componentes en `assets/components/ui`.

## Consejos para producción

- Ajusta variables de entorno si agregas APIs o keys.
- Asegúrate de revisar el tamaño del bundle y lazy-load donde sea necesario.

## Ejecutar pruebas

`npm run test`

Para ejecutar en modo interactivo/watch:

`npm run test:watch`

## Linting

`npm run lint`

## Contribuir

1. Crea una rama con un nombre descriptivo: `git checkout -b feat/nombre-funcionalidad`.
2. Haz commits claros y atómicos.
3. Abre un pull request y pide revisión.

## Contacto

Si tienes dudas sobre la estructura o quieres orientación, abre un issue o contacta al autor del repositorio.

---

Archivo creado automáticamente: `README.md`.
