# Metal Cooper - Sitio Web

Este proyecto es un sitio web desarrollado con Astro y Tailwind CSS para Metal Cooper, una empresa especializada en la distribución, adquisición y exportación de metales no ferrosos reciclados.

## Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

- [Node.js](https://nodejs.org/) (versión 16 o superior)
- npm (viene incluido con Node.js)

## Instrucciones de Instalación

Sigue estos pasos para configurar el proyecto en tu entorno local:

1. **Clonar el repositorio**

   ```bash
   git clone <url-del-repositorio>
   cd site_cooper
   ```

2. **Instalar dependencias**

   ```bash
   npm install
   ```

## Comandos Disponibles

El proyecto incluye los siguientes comandos que puedes ejecutar:

- **Iniciar servidor de desarrollo**

   ```bash
   npm run dev
   ```

   Este comando inicia un servidor de desarrollo local en `http://localhost:4321`. El sitio se recargará automáticamente cuando realices cambios en los archivos.

- **Construir para producción**

   ```bash
   npm run build
   ```

   Este comando genera una versión optimizada del sitio en el directorio `dist/`.

- **Vista previa de la versión de producción**

   ```bash
   npm run preview
   ```

   Este comando te permite ver localmente la versión construida para producción.

## Estructura del Proyecto

El proyecto sigue la estructura estándar de Astro:

```
site_cooper/
├── public/          # Archivos estáticos (imágenes, fuentes, etc.)
├── src/
│   ├── components/  # Componentes reutilizables
│   │   ├── about/   # Componentes para la sección "Nosotros"
│   │   └── solutions/ # Componentes para la sección "Soluciones"
│   ├── layouts/     # Plantillas de diseño
│   └── pages/       # Páginas del sitio
└── package.json     # Dependencias y scripts
```

## Tecnologías Utilizadas

- [Astro](https://astro.build/) - Framework web para construir sitios rápidos
- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS utilitario

## Contacto

Para más información o soporte, contacta al equipo de desarrollo.

---

© 2024 Metal Cooper. Todos los derechos reservados.
