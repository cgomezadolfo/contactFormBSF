# Formulario de Garantía de Germinación de Semillas 🌱

Un formulario moderno de 4 pasos desarrollado con Astro para gestionar solicitudes de garantía de germinación de semillas con una interfaz intuitiva.

## ✨ Características

- **Formulario de 4 pasos interactivo**:
  1. **Selección de país con banderas** - Interfaz visual intuitiva con banderas
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

- **Paleta de colores**: 
  - Primario: `#2d5a2d` (Verde oscuro)
  - Secundario: `#7fb069` (Verde medio)
  - Acento: `#a7c957` (Verde claro)
  - Éxito: `#6a994e` (Verde éxito)
  - Error: `#e76f51` (Naranja/rojo)
  - Fondo: `#f8fffe` (Blanco verdoso)
- **Tipografía**: Inter font para mejor legibilidad
- **Iconos**: Emojis temáticos para mejor UX
- **Animaciones**: Transiciones suaves y microinteracciones
- **Gradientes**: Efectos visuales modernos con tonos verdes

## 📝 Funcionalidades del Formulario

### Paso 1: País y Términos
- **Selección visual de país** con banderas interactivas de 5 países principales:
  - �� Chile
  - 🇺🇾 Uruguay  
  - 🇦🇷 Argentina
  - 🇧🇷 Brasil
  - 🇪� Europa
- Términos y condiciones de garantía
- Política de privacidad
- Validación en tiempo real para habilitar botón "Continuar"

### Paso 2: Datos y Variedad
- Información de contacto completa
- Selección de variedad de semilla (10 opciones disponibles):
  - All Star Usa Automix
  - Dealer Deal XXL Automix
  - Dream Team Feminized Mix
  - Psycho XXL Automix
  - Red Line Automix
  - Gorila Familia
  - Old School Fem Mix
  - Tutti Fruty Automix
  - Fast and Furious Mix
  - High Voltage Fem Mix
- Cantidades disponibles (x2, x4, x7, x8, x12, x16)
- Fechas de compra y siembra
- Descripción del problema
- Información adicional sobre conservación y técnicas de germinación

### Paso 3: Documentación
- Carga de imagen de condiciones de temperatura y humedad
- Carga de imagen del proceso de germinación
- Carga de imagen del código QR del envase
- Carga de imagen de boleta o comprobante de compra
- Previsualización y validación de archivos (máximo 5MB por imagen)

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

Para soporte o preguntas sobre el formulario de garantía, contactanos:


---

Desarrollado con ❤️ para BSF Seeds usando Astro

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

# Formulario de Garantía de Germinación BSF - Integración con Google Forms/Sheets

Este proyecto es un formulario multipaso desarrollado en Astro para la gestión de garantías de germinación de semillas. Aquí aprenderás cómo conectar este formulario con **Google Forms** para que todas las respuestas se almacenen automáticamente en una hoja de cálculo de **Google Sheets**.

---

## ¿Por qué Google Forms/Sheets?

- **Google Forms** permite recibir respuestas vía HTTP POST y las almacena automáticamente en una hoja de cálculo de **Google Sheets**.
- Es una solución gratuita, robusta y sin necesidad de backend propio.
- Permite visualizar, filtrar y exportar respuestas fácilmente.

---

## Pasos para la integración

### 1. Crear el Google Form

1. Ve a [Google Forms](https://forms.google.com) y crea un formulario nuevo.
2. Crea los campos del formulario **en el mismo orden y tipo** que los de tu formulario Astro. Ejemplo:
   - País
   - Nombre completo
   - Email
   - Teléfono
   - Dirección
   - Variedad de semilla
   - Cantidad
   - Fecha de compra
   - Fecha de germinación
   - Descripción del problema
   - Tienda donde compraste
   - Comentarios adicionales
   - Variedades del mix que no germinaron
   - Conservación de semillas
   - Técnica de germinación
   - Tipo de fallo
   - Código QR
   - Imágenes adjuntas (puedes pedir links o usar un campo de texto para URLs de imágenes si lo deseas)
3. **Importante:** Cada campo tendrá un "entry ID" único (ejemplo: `entry.123456789`). Lo necesitarás para el siguiente paso.

---

### 2. Obtener el endpoint de Google Forms

1. Haz clic en "Enviar" en la parte superior derecha de Google Forms.
2. Selecciona el icono de enlace (`< >`) para obtener el enlace del formulario.
3. Abre el formulario en una ventana de incógnito.
4. Haz clic derecho en el formulario y selecciona "Inspeccionar" para abrir las herramientas de desarrollador.
5. Rellena el formulario con datos de prueba y haz clic en "Enviar".
6. En la pestaña "Network", busca la solicitud de tipo `formResponse` (normalmente es un POST a una URL como `https://docs.google.com/forms/d/e/XXXXXXXXXXXX/formResponse`).
7. Copia esa URL: **ese es tu endpoint de Google Forms**.

---

### 3. Obtener los "entry IDs" de cada campo

1. En la pestaña "Network", selecciona la solicitud `formResponse`.
2. En el "Payload" verás algo como:
   ```
   entry.123456789=valor1&entry.987654321=valor2
   ```
3. Cada campo de tu formulario tiene un `entry.xxxxxxxx` único. Asócialos con los campos de tu formulario Astro.

---

### 4. Modificar tu formulario Astro para enviar los datos

En tu archivo `index.astro`, modifica la función de envío para hacer un POST a Google Forms:

```javascript
// ...existing code...
function handleFormSubmit(e) {
    e.preventDefault();

    if (!validateStep(4)) {
        alert('Por favor, complete todos los campos requeridos.');
        return;
    }

    const form = document.getElementById('warranty-form');
    const formData = new FormData(form);

    // Mapea los campos de tu formulario Astro a los entry IDs de Google Forms
    const googleFormData = new FormData();
    googleFormData.append('entry.123456789', formData.get('country')); // País
    googleFormData.append('entry.987654321', formData.get('firstName') + ' ' + formData.get('lastName')); // Nombre completo
    // ...agrega todos los campos necesarios...

    fetch('https://docs.google.com/forms/d/e/TU_ID_DE_FORMULARIO/formResponse', {
        method: 'POST',
        mode: 'no-cors',
        body: googleFormData
    }).then(() => {
        showSuccessMessage();
    }).catch(() => {
        alert('Hubo un error al enviar el formulario. Intente nuevamente.');
    });
}
```

**Notas:**
- Reemplaza cada `entry.XXXXXXXX` por el ID real de tu Google Form.
- El método `mode: 'no-cors'` es necesario porque Google Forms no permite CORS, pero igual recibe los datos.
- No podrás obtener una respuesta de éxito/fallo real, pero los datos llegarán a tu Google Sheets.

---

### 5. Consideraciones para archivos/imágenes

Google Forms **no acepta archivos directamente** vía API. Opciones:
- Pide a los usuarios subir imágenes a Google Drive, Dropbox, etc. y pegar el enlace en un campo de texto.
- O usa un backend propio para manejar archivos y solo envía los links a Google Forms.

---

### 6. Ver las respuestas en Google Sheets

1. En Google Forms, haz clic en "Respuestas".
2. Haz clic en el icono de Google Sheets para crear/ver la hoja de respuestas.
3. Todas las respuestas enviadas desde tu formulario Astro aparecerán allí.

---

## Resumen de pasos técnicos

1. Crea el Google Form y obtén los entry IDs.
2. Modifica tu función de envío en Astro para hacer POST a Google Forms.
3. Mapea cada campo de tu formulario Astro al entry ID correspondiente.
4. (Opcional) Ajusta la gestión de imágenes para enviar solo enlaces.
5. Verifica que las respuestas lleguen a Google Sheets.

---

## Recursos útiles


- [Google Forms API Docs (no oficial)](https://github.com/dwyl/learn-to-send-email-via-google-form)

---

¿Dudas? Puedes consultar la documentación oficial de Google Forms o solicitar implementación a Brava Digital.
