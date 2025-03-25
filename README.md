# Sitio Web de Peluquería con Astro 5 y Tailwind CSS v4

Un sitio web moderno y elegante para un salón de peluquería, desarrollado con las últimas tecnologías web para ofrecer una experiencia de usuario fluida y atractiva.

![Peluquería Astro](https://github.com/Aosiika/peluqeria-astro/assets/preview.png)

## 🚀 Tecnologías Utilizadas

- **[Astro 5](https://astro.build/)**: Framework web que ofrece rendimiento excepcional con "zero-JS por defecto"
- **[Tailwind CSS v4](https://tailwindcss.com/)**: La última versión del popular framework CSS utility-first
- **JavaScript**: Para funcionalidades dinámicas y efectos interactivos

## ✨ Características

- Diseño moderno con paleta de colores en tonos de fucsia
- Interfaz responsiva que se adapta a todos los dispositivos
- Efectos visuales sutiles para mejorar la experiencia de usuario
- Secciones bien definidas para servicios, equipo y reserva de citas
- Transiciones suaves entre secciones

## 📂 Estructura del Proyecto

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── [imágenes y recursos]
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   ├── About.astro
│   │   ├── Equipo.astro
│   │   ├── Contacto.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
└── package.json
```

## 🧞 Comandos

| Comando                   | Acción                                              |
| :------------------------ | :-------------------------------------------------- |
| `npm install`             | Instala las dependencias                            |
| `npm run dev`             | Inicia el servidor de desarrollo en `localhost:4321`|
| `npm run build`           | Construye el sitio para producción en `./dist/`     |
| `npm run preview`         | Vista previa de la build antes de desplegar         |

## 🔧 Configuración Especial

Este proyecto utiliza Tailwind CSS v4, que requiere una configuración específica:

- Usa `@tailwindcss/vite` como plugin de Vite en `astro.config.mjs`
- Implementa una simple importación `@import 'tailwindcss';` en `global.css`
- No utiliza `@astrojs/tailwind` ya que es incompatible con Tailwind CSS v4

## 👥 Autor

Desarrollado por [Aosiika](https://github.com/Aosiika)
