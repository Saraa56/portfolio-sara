# Portafolio Sara
 
Sitio web personal para mostrar mi trabajo como desarrolladora, construido con **Astro**. Incluye Inicio, Sobre mí (experiencia, formación y stack), Proyectos, Certificados y Contacto con mis datos reales.
 
## Tecnologías
 
- **Astro 7** — generación de sitio estático con arquitectura basada en componentes (`.astro`)
- **Tailwind CSS v4** — estilos vía `@theme` en `src/styles/global.css` (sin `tailwind.config.ts`)
- **TypeScript** (configuración estricta de Astro)
- **Node.js** ≥ 22

## Estructura actual
 
```
src/
├── styles/global.css               # tokens de color y tipografía (@theme)
├── layouts/Layout.astro            # layout base (head, fuentes, Header + Footer)
├── components/
│   ├── Header.astro                # navegación (Inicio, Sobre mí, Proyectos, Certificados, Contacto)
│   ├── Footer.astro                # pie con enlaces sociales
│   ├── TerminalCard.astro          # tarjeta estilo terminal del hero
│   └── ProjectCard.astro           # tarjeta reutilizable de proyecto
└── pages/
    ├── index.astro                 # inicio
    ├── about.astro                 # sobre mí, experiencia, formación y stack
    ├── projects.astro              # proyectos
    ├── certificates.astro          # certificados
    └── contact.astro               # contacto
```
 
## Cómo correrlo en local
 
```bash
npm install
npm run dev
```
 
Abre [localhost:4321](http://localhost:4321) para verlo.
 
##  Por qué Astro
 
Hice este proyecto con Astro para entender de primera mano la diferencia entre la generación estática y los frameworks orientados al cliente: cómo Astro renderiza el HTML en tiempo de build y envía JavaScript mínimo al navegador, en lugar de cargar todo el sitio del lado del cliente. De paso, aprendí a estructurar un sitio en componentes reutilizables (`Layout`, `Header`) y a organizar un proyecto frontend desde cero.
 
## 🚧 Próximos pasos
- [ ] Actualizar el proyecto "E-commerce con Hostinger" cuando esté listo
