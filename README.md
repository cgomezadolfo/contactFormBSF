# Formulario de Garantía de Germinación de Semillas 🌱

Un formulario moderno de 4 pasos desarrollado con Astro para gestionar solicitudes de garantía de germinación de semillas con una interfaz intuitiva y temática de naturaleza.

## ✨ Características

- **Formulario de 4 pasos interactivo**:
  1. **Selección de país con banderas** - Interfaz visual intuitiva con banderas de los 5 países principales (México 🇲🇽, Argentina 🇦🇷, Brasil 🇧🇷, Colombia 🇨🇴, España 🇪🇸)
  2. Datos de contacto y selección de variedad de semillas
  3. Carga de imágenes (temperatura, humedad, germinación, código QR)
  4. Confirmación final y declaración de autenticidad

- **Diseño moderno con temática de naturaleza**
- **Selección visual de países** con banderas interactivas
- **Completamente responsivo** (móvil y escritorio)
- **Validación de formularios en tiempo real**
- **Carga y previsualización de imágenes**
- **Transiciones suaves entre pasos**
- **Interfaz accesible y fácil de usar**
- **Estados de botones inteligentes** (habilitado/deshabilitado según validaciones)

## 🚀 Inicio Rápido

```bash
# Instalar dependencias
npm install

# Ejecutar servidor de desarrollo
npm run dev

# Construir para producción
npm run build

# Previsualizar build de producción
npm run preview
```

## 📁 Estructura del Proyecto

```text
/
├── public/
│   └── favicon.svg
├── src/
│   └── pages/
│       └── index.astro          # Formulario principal
├── .github/
│   └── copilot-instructions.md  # Instrucciones para Copilot
├── astro.config.mjs
├── package.json
└── README.md
```

## 🎨 Características de Diseño

- **Paleta de colores**: Tonos verdes y naturales
- **Tipografía**: Inter font para mejor legibilidad
- **Iconos**: Emojis temáticos para mejor UX
- **Animaciones**: Transiciones suaves y microinteracciones
- **Gradientes**: Efectos visuales modernos

## 📝 Funcionalidades del Formulario

### Paso 1: País y Términos
- **Selección visual de país** con banderas interactivas de 5 países principales:
  - 🇲🇽 México
  - 🇦🇷 Argentina  
  - 🇧🇷 Brasil
  - 🇨🇴 Colombia
  - 🇪🇸 España
- Términos y condiciones de garantía
- Política de privacidad
- Validación en tiempo real para habilitar botón "Continuar"

### Paso 2: Datos y Variedad
- Información de contacto completa
- Selección de variedad de semilla (20+ opciones)
- Cantidades disponibles (x2, x4, x6, x8, x12)
- Fechas de compra y siembra
- Descripción del problema

### Paso 3: Documentación
- Carga de imagen de temperatura
- Carga de imagen de humedad
- Carga de imagen de germinación
- Carga de imagen del código QR
- Previsualización y validación de archivos

### Paso 4: Confirmación
- Resumen de la solicitud
- Declaración de autenticidad
- Advertencia sobre uso de imágenes falsas
- Envío final

## 🛠️ Tecnologías Utilizadas

- **[Astro](https://astro.build/)** - Framework web moderno
- **TypeScript** - Tipado estático
- **CSS3** - Estilos modernos con variables CSS
- **JavaScript ES6+** - Funcionalidad interactiva
- **HTML5** - Marcado semántico

## 🎯 Validaciones Implementadas

- Campos requeridos en cada paso
- Validación de formato de email
- Validación de archivos de imagen (tipo y tamaño)
- Verificación de términos y condiciones
- Límite de tamaño de archivo (5MB)

## 📱 Compatibilidad

- ✅ Chrome/Edge (últimas versiones)
- ✅ Firefox (últimas versiones)  
- ✅ Safari (últimas versiones)
- ✅ Dispositivos móviles iOS/Android
- ✅ Tablets

## 🚀 Deployment

Este proyecto está listo para deploy en cualquier plataforma que soporte sitios estáticos:

- Vercel
- Netlify
- GitHub Pages
- Cloudflare Pages

```bash
npm run build
```

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## � Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 📞 Soporte

Para soporte o preguntas sobre el formulario de garantía, contacta:
- Email: soporte@ejemplo.com
- Teléfono: +1-234-567-8900

---

Desarrollado con ❤️ usando Astro

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
