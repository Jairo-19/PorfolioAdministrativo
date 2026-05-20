# Portfolio - Jairo Jimenez Ramos

Portfolio profesional desarrollado con Astro, TypeScript y Tailwind CSS. Presenta mis proyectos, habilidades y experiencia como desarrollador web.

## Caracteristicas

- **Diseno moderno y responsivo** → Se adapta perfectamente a cualquier dispositivo
- **Animaciones suaves** → Efectos de scroll, typewriter y chinchetas con Intersection Observer
- **Efecto Tilt 3D** → Las tarjetas de proyectos se inclinan siguiendo el cursor
- **TypeScript** → Codigo type-safe y mantenible
- **Tailwind CSS** → Estilos optimizados y personalizacion facil
- **Rendimiento** → Sitio estatico ultra rapido con Astro

## Estructura del Proyecto

```
Portfolio/
├── src/
│   ├── assets/
│   │   └── styles/              # Archivos CSS de animaciones
│   │       ├── animacionesInicio.css
│   │       ├── animacionesSobreMi.css
│   │       ├── animacionesScroll.css
│   │       └── global.css
│   ├── components/              # Componentes Astro
│   │   ├── header.astro
│   │   ├── inicio.astro
│   │   ├── sobreMi.astro
│   │   ├── proyectos.astro
│   │   └── contacto.astro
│   ├── layouts/
│   │   └── Layout.astro         # Layout principal
│   └── pages/
│       └── index.astro          # Pagina principal
├── public/                       # Imagenes y assets estaticos
├── package.json
├── tsconfig.json
├── astro.config.mjs
└── tailwind.config.mjs
```

## Tecnologias

- **Astro** - Framework SSG moderno
- **TypeScript** - Tipado estatico
- **Tailwind CSS** - Utilidades CSS
- **Vite** - Bundler rapido
- **Intersection Observer API** - Animaciones con scroll

## Secciones

1. **Inicio** → Presentacion con efecto typewriter
2. **Sobre mi** → Informacion personal, formacion, habilidades y experiencia
3. **Proyectos** → Tarjetas interactivas con efecto Tilt 3D
4. **Contacto** → Enlaces a redes sociales y datos de contacto

## Comandos

```bash
# Instalar dependencias
npm install

# Ejecutar en desarrollo
npm run dev

# Construir para produccion
npm run build

# Vista previa de la build
npm run preview
```

## Proyectos Destacados

- **SurpriseBurger** → App de hamburgueseria (Laravel, PHP, Tailwind)
- **PuraSonrisa** → Web clinica dental con automatizacion n8n (Laravel, PHP, Tailwind)
- **PelisMax** → Catalogo de peliculas con API (HTML, TypeScript, Vite, Express)

## Contacto

- **Email** → ramosj06jairo@gmail.com
- **Telefono** → 722408527
- **GitHub** → https://github.com/Jairo-19
- **LinkedIn** → https://www.linkedin.com/in/jairo-jimenez-ramos-728463258/

## Licencia

MIT
