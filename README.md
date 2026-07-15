# MediLEO Landing

Landing page del proyecto MediLEO, una solución IoT orientada a ayudar a los hogares de la Costa Caribe Colombiana a entender, monitorear y reducir su consumo eléctrico en tiempo real.

## Descripción del proyecto

Este proyecto corresponde a la interfaz web de presentación de MediLEO, donde se expone:

- el problema del alto costo de la energía en la región,
- la propuesta de monitoreo inteligente con hardware IoT,
- el flujo del sistema desde el medidor hasta la app,
- el impacto esperado en ahorro y decisiones energéticas,
- y el equipo detrás del proyecto.

La landing está construida con Astro y Tailwind CSS.

## Tecnologías usadas

- Astro 6
- Tailwind CSS 4
- Vite con integración de Tailwind

## Requisitos previos

- Node.js 22.12.0 o superior
- npm

## Dependencias necesarias

Estas son las dependencias declaradas en el proyecto para que funcione correctamente después de clonar el repositorio:

```json
{
  "dependencies": {
    "@tailwindcss/vite": "^4.3.1",
    "astro": "^6.4.7",
    "tailwindcss": "^4.3.1"
  }
}
```

## Instalación y ejecución

Desde la raíz del proyecto:

```bash
git clone <url-del-repositorio>
cd Landing-MediLeo
npm install
npm run dev
```

Luego abre la URL que indique Astro en tu navegador, normalmente:

```text
http://localhost:4321/
```

## Comandos útiles

```bash
npm install      # instala las dependencias del proyecto
npm run dev      # inicia el servidor de desarrollo
npm run build    # genera la versión lista para producción en dist/
npm run preview  # previsualiza el build localmente
npm run astro    # ejecuta comandos de Astro
```

## Estructura del proyecto

```text
/
├── public/
├── src/
│   ├── components/
│   │   ├── Hero.astro
│   │   ├── Problem.astro
│   │   ├── Solution.astro
│   │   ├── HowItWorks.astro
│   │   ├── Impact.astro
│   │   └── Team.astro
│   ├── layouts/
│   ├── pages/
│   └── styles/
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Notas

Si luego de clonar el proyecto aparecen errores de dependencias, asegúrate de ejecutar:

```bash
npm install
```

y de tener una versión compatible de Node.js instalada.
