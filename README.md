# Astro Rey Flores 🌸

Un hermoso sitio web para una florería, diseñado con HTML, CSS y JavaScript. Este proyecto incluye configuración automática para GitHub Pages.

## 🌐 Demo en vivo

Puedes ver el sitio en funcionamiento en: [https://ulisescm.github.io/astro-rey-flores](https://ulisescm.github.io/astro-rey-flores)

## 🚀 Cómo usar este proyecto

### Prerrequisitos

Antes de comenzar, necesitas tener instalado:

1. **Git** - Sistema de control de versiones
2. **Una cuenta en GitHub** - Para hospedar tu repositorio
3. **Un editor de código** (recomendado: VS Code)

### 🔗 Enlaces importantes

- **Git:** [https://git-scm.com/](https://git-scm.com/)
- **GitHub:** [https://github.com/](https://github.com/) (crear cuenta gratuita)
- **VS Code:** [https://code.visualstudio.com/](https://code.visualstudio.com/)
- **Formspree:** [https://formspree.io/](https://formspree.io/) (para formularios de contacto)
- **Homebrew (macOS):** [https://brew.sh/](https://brew.sh/)

### 📦 Instalación de Git

#### Windows

1. Ve a [git-scm.com/download/win](https://git-scm.com/download/win)
2. Haz clic en "Download for Windows" (descarga automática)
3. Ejecuta el archivo `Git-x.x.x-64-bit.exe` descargado
4. Sigue las instrucciones del instalador (puedes usar las opciones por defecto)
5. Verifica la instalación abriendo CMD o PowerShell y ejecutando:
   ```bash
   git --version
   ```

#### macOS

**Opción 1: Usando Homebrew (recomendado)**

1. Instala Homebrew desde [brew.sh](https://brew.sh/)
2. Ejecuta en Terminal:
   ```bash
   brew install git
   ```

**Opción 2: Descarga directa**

1. Ve a [git-scm.com/download/mac](https://git-scm.com/download/mac)
2. Descarga el instalador para macOS
3. Ejecuta el archivo `.dmg` descargado

#### Linux (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install git
```

### 🆔 Crear cuenta en GitHub

1. Ve a [github.com](https://github.com/)
2. Haz clic en **"Sign up"** (Registrarse)
3. Completa el formulario con:
   - Tu nombre de usuario (será parte de la URL de tu sitio)
   - Tu email
   - Una contraseña segura
4. Verifica tu email
5. ¡Listo! Ya puedes crear repositorios

### 💻 Instalar VS Code (Editor recomendado)

#### Todas las plataformas

1. Ve a [code.visualstudio.com](https://code.visualstudio.com/)
2. Haz clic en **"Download"** (se detecta automáticamente tu sistema operativo)
3. Ejecuta el instalador descargado
4. **Extensiones útiles** (instalar desde VS Code):
   - Live Server (para preview local)
   - Prettier (formateo de código)
   - Auto Rename Tag (HTML)
   - GitLens (mejor integración con Git)

### 🔄 Clonar y personalizar el proyecto

1. **Fork este repositorio**

   - Ve a [https://github.com/UlisesCm/astro-rey-flores](https://github.com/UlisesCm/astro-rey-flores)
   - Haz clic en "Fork" en la esquina superior derecha
   - Esto creará una copia en tu cuenta de GitHub

2. **Clona tu fork**

   ```bash
   git clone https://github.com/TU-USUARIO/astro-rey-flores.git
   cd astro-rey-flores
   ```

3. **Personaliza el contenido**

   - Edita `index.html` con tu información
   - Reemplaza las imágenes en la carpeta `assets/`
   - Personaliza los textos, colores y contenido según tus necesidades

4. **Configura el formulario de contacto**
   - Ve a [formspree.io](https://formspree.io/) y crea una cuenta gratuita
   - Haz clic en **"Get Started"** y luego **"Sign Up"**
   - Una vez dentro, clic en **"+ New Form"**
   - Dale un nombre a tu formulario (ej: "Contacto Florería")
   - Copia la URL que se genera (algo como `https://formspree.io/f/xabcdefg`)
   - En `index.html`, busca `https://formspree.io/f/xxxxxxxx` y reemplázalo con tu URL

### 🚀 Desplegar en GitHub Pages

1. **Sube tus cambios**

   ```bash
   git add .
   git commit -m "Personalizar sitio web"
   git push origin main
   ```

2. **Activa GitHub Pages**

   - Ve a tu repositorio en GitHub
   - Clic en **Settings** (Configuración)
   - En el menú lateral, busca **Pages**
   - En **Source**, selecciona **"GitHub Actions"**
   - ¡Listo! En unos minutos tu sitio estará en línea

3. **Tu sitio estará disponible en:**
   ```
   https://TU-USUARIO.github.io/astro-rey-flores
   ```

### 🎨 Estructura del proyecto

```
astro-rey-flores/
│
├── index.html          # Página principal
├── assets/            # Imágenes y recursos
│   ├── logo.png
│   ├── portada.jpg
│   ├── ramos.jpeg
│   ├── eventos.jpeg
│   └── ...
├── .github/
│   └── workflows/
│       └── deploy.yml # Configuración automática de GitHub Pages
└── README.md          # Este archivo
```

### 🛠️ Comandos útiles de Git

```bash
# Ver el estado de tus archivos
git status

# Agregar cambios
git add .

# Hacer commit
git commit -m "Descripción de los cambios"

# Subir cambios
git push

# Ver historial
git log --oneline

# Crear una nueva rama
git checkout -b nueva-funcionalidad

# Cambiar de rama
git checkout main
```

### 📝 Personalización

Para personalizar completamente el sitio:

1. **Cambiar información de contacto:**

   - Edita las secciones con tu información en `index.html`
   - Actualiza números de teléfono, direcciones, etc.

2. **Reemplazar imágenes:**

   - Coloca tus imágenes en la carpeta `assets/`
   - Mantén los mismos nombres o actualiza las referencias en `index.html`

3. **Modificar estilos:**

   - Los estilos CSS están dentro de `<style>` en `index.html`
   - Puedes cambiar colores, fuentes, y diseño

4. **Agregar nuevas secciones:**
   - Edita el HTML para agregar más contenido
   - Mantén la estructura responsive existente

### 🆘 Solución de problemas

**El sitio no se actualiza:**

- Verifica que hayas hecho `git push`
- Ve a la pestaña "Actions" en GitHub para ver el estado del despliegue
- Los cambios pueden tardar 1-5 minutos en aparecer

**Error en GitHub Pages:**

- Asegúrate de que el repositorio sea público
- Verifica que GitHub Pages esté habilitado en Settings > Pages

**Formulario de contacto no funciona:**

- Verifica que hayas configurado correctamente Formspree
- Asegúrate de haber reemplazado la URL en el código

### 📞 Soporte

Si tienes problemas o preguntas:

1. Revisa la [documentación de GitHub Pages](https://docs.github.com/es/pages)
2. Consulta la [documentación de Git](https://git-scm.com/doc)
3. Busca en [Stack Overflow](https://stackoverflow.com/) para problemas específicos
4. Soporte personalizado Navori Technologies: +52 452 376 8281

## � Enlaces de referencia rápida

### Descargas y cuentas

- **Git para Windows:** [git-scm.com/download/win](https://git-scm.com/download/win)
- **Git para macOS:** [git-scm.com/download/mac](https://git-scm.com/download/mac)
- **Crear cuenta GitHub:** [github.com/signup](https://github.com/signup)
- **VS Code:** [code.visualstudio.com/download](https://code.visualstudio.com/download)
- **Formspree (formularios):** [formspree.io/register](https://formspree.io/register)

### Documentación

- **Documentación Git:** [git-scm.com/doc](https://git-scm.com/doc)
- **GitHub Pages:** [docs.github.com/pages](https://docs.github.com/pages)
- **Markdown Guide:** [markdownguide.org](https://www.markdownguide.org/)

### Herramientas útiles

- **Homebrew (macOS):** [brew.sh](https://brew.sh/)
- **Generador de .gitignore:** [gitignore.io](https://www.toptal.com/developers/gitignore)
- **Verificar nombres disponibles:** [namechk.com](https://namechk.com/)

## �📄 Licencia

Este proyecto está bajo la Licencia MIT. Siéntete libre de usarlo y modificarlo para tus propios proyectos.

---

**¡Disfruta creando tu hermoso sitio web de florería! 🌺**
