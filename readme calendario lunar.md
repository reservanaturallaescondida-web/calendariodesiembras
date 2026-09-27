# 🌱 Calendario Lunar de Siembras

Aplicación web progresiva (PWA) para gestionar siembras, podas y abonos siguiendo las fases lunares. Diseñada especialmente para **Pacho, Cundinamarca**, pero adaptable a cualquier ubicación.

![Versión](https://img.shields.io/badge/versión-3.0-green)
![Estado](https://img.shields.io/badge/estado-activo-brightgreen)
![Licencia](https://img.shields.io/badge/licencia-MIT-blue)

---

## 📱 ¿Qué hace esta app?

Es una herramienta completa para agricultores, huerteros y aficionados a la siembra que permite:

- 🌙 **Consultar la fase lunar del día** con recomendaciones específicas
- 🌱 **Registrar y editar cultivos** con cálculo automático de fecha de cosecha
- 📅 **Ver el calendario lunar mensual** con colores por fase
- ✂️ **Programar podas** con recordatorios
- 🧪 **Consultar guía de abonos orgánicos** (recetas completas)
- 💧 **Recibir sugerencias de riego** según el tipo de cultivo
- 📍 **Elegir la ubicación** para ajustar clima y consejos
- 🌡️ **Ver el clima en vivo** de tu zona
- 💾 **Exportar e importar backups** de todos los datos
- 📤 **Compartir por WhatsApp** el estado del huerto
- 🖨️ **Exportar a PDF** el calendario
- 🔔 **Recibir notificaciones diarias** con recordatorios

---

## 🎨 Características principales

### 🌙 Fases Lunares
| Fase | Color | Qué hacer | Qué sembrar |
|------|-------|-----------|-------------|
| 🌑 Nueva | Negro | Labrar, compostar | ❌ NO sembrar |
| 🌒 Creciente | Verde | Trasplantar, entutorar | 🌿 Hojas y 🍅 frutos |
| 🌕 Llena | Plateado | Cosechar, podar | ❌ NO sembrar |
| 🌘 Menguante | Morado | Podar, abonar | 🥕 Raíces y bulbos |

### 🗂️ Categorías de cultivos
- 🥬 Hortaliza
- 🫘 Legumbre
- 🍎 Fruta
- 🥔 Tubérculo
- 🥕 Raíz
- 🌽 Cereal
- 🌿 Aromática
- 🧅 Bulbo
- 🍅 Hortaliza de fruto
- 🌱 Otro

### 🧪 Guía de abonos incluida
- 🟦 **Caldo Bordelés** — Fungicida preventivo
- 🟫 **Bocashi** — Abono fermentado completo
- 🪱 **Humus de Lombriz** — Abono sólido premium
- 🍵 **Té de Compost** — Abono líquido microbiano
- 🌿 **Extracto de Ortiga** — Fertilizante foliar
- 🧪 **Biol** — Biofertilizante foliar

Cada receta incluye: ingredientes, preparación, aplicación y precauciones.

---

## 🚀 Instalación

### Opción 1: Usar directamente (más rápido)
1. Descarga el archivo `index.html`
2. Ábrelo en cualquier navegador moderno (Chrome, Safari, Firefox, Edge)
3. **¡Listo!** La app funciona sin internet (los datos se guardan localmente)

### Opción 2: Instalar como app en el celular

**Android (Chrome):**
1. Abre la URL de la app en Chrome
2. Toca el menú **⋮** → **Instalar app** o **Agregar a pantalla de inicio**
3. Confirma el nombre y listo

**iPhone (Safari):**
1. Abre la URL en Safari
2. Toca el botón **Compartir** 📤
3. Desliza y toca **Agregar a pantalla de inicio**
4. Confirma y listo

### Opción 3: Publicar en GitHub Pages (recomendado para compartir)

1. Crea una cuenta en [github.com](https://github.com)
2. Crea un repositorio **público** llamado `calendario-lunar`
3. Sube el archivo `index.html`
4. Ve a **Settings → Pages**
5. En **Source** elige: `Deploy from a branch`
6. En **Branch** elige: `main` y carpeta `/ (root)`
7. Clic en **Save**
8. Espera 1-2 minutos
9. Tu app estará en: `https://TU-USUARIO.github.io/calendario-lunar/`

### Opción 4: Publicar en Netlify (alternativa rápida)

1. Ve a [app.netlify.com/drop](https://app.netlify.com/drop)
2. Arrastra el archivo `index.html` a la zona de carga
3. En segundos tendrás una URL tipo `https://nombre-random.netlify.app`
4. Puedes personalizar el nombre desde el panel

---

## 📖 Cómo usar la app

### 🏡 Primera vez que la abres
1. Verás el **selector de ubicación** — elige tu zona (Pacho Centro, Pacho Rural, La Palma, San Cayetano u otra)
2. Toca **Confirmar ubicación**
3. La app cargará el clima real y los consejos de tu zona

### ➕ Agregar un cultivo
1. Toca **+ Agregar nuevo cultivo** (en Inicio o Cultivos)
2. Completa:
   - Nombre (ej: "Lechuga")
   - Categoría (se autodetecta, pero puedes cambiarla)
   - Emoji
   - Ubicación (ej: "Parcela A", "Invernadero")
   - Fecha de siembra
3. La app calcula **automáticamente la fecha de cosecha** según el ciclo del cultivo
4. Guarda

### ✏️ Editar un cultivo
1. Toca el botón ✏️ en cualquier cultivo
2. Puedes cambiar:
   - Nombre, categoría, emoji, ubicación
   - Fecha de siembra (la cosecha se recalcula)
   - Estado (En crecimiento, En floración, etc.)
   - Progreso con un slider
3. Guarda

### 📤 Compartir
- Toca el ícono **📤** arriba a la derecha
- Se abre WhatsApp con un mensaje formateado que incluye:
  - Fecha y fase lunar
  - Tareas pendientes
  - Cultivos activos con progreso
  - Tip del día

### 🖨️ Exportar a PDF
- Toca el ícono **🖨️**
- Se abre el diálogo de impresión → elige "Guardar como PDF"

### 🔔 Activar notificaciones
- Toca el ícono **🔔**
- Acepta el permiso
- Recibirás un recordatorio diario a las **7:00 AM**

---

## 💾 Sistema de Backup

**⚠️ IMPORTANTE:** Los datos se guardan **localmente en el navegador de cada dispositivo**. No se sincronizan automáticamente entre celulares o computadoras.

### 📤 Exportar backup
1. Ve a la pestaña **📊 Stats**
2. Baja hasta **💾 Backup de datos**
3. Toca **📤 Exportar**
4. Se descarga un archivo `.json` con todos tus datos
5. **Guárdalo en un lugar seguro** (Google Drive, WhatsApp a ti mismo, correo)

**Nombre del archivo:** `calendario-lunar-backup-2026-09-26-14-30-45.json`

### 📥 Importar backup
1. Ve a **📊 Stats → 💾 Backup de datos**
2. Toca **📥 Importar**
3. Dos opciones:
   - **📁 Cargar archivo**: selecciona el `.json` desde tu teléfono
   - **📋 Pegar**: pega el texto del backup directamente
4. Confirma → todos tus datos se restauran

### 📅 Recomendaciones de backup
- **Cada domingo**: exporta un backup nuevo
- **Antes de cambiar de teléfono**: exporta primero
- **Guarda 2 copias**: una en WhatsApp, otra en Drive
- **No borres los backups viejos** hasta tener el siguiente

---

## 🌐 Compatibilidad

| Navegador | Android | iPhone | PC |
|-----------|---------|--------|-----|
| Chrome | ✅ | ✅ | ✅ |
| Safari | — | ✅ | ✅ |
| Firefox | ✅ | ✅ | ✅ |
| Edge | ✅ | — | ✅ |
| Samsung Internet | ✅ | — | — |

**Requisitos:**
- Conexión a internet (solo para clima y notificaciones)
- JavaScript habilitado
- Navegador actualizado (2023+)

---

## 🛠️ Tecnologías usadas

- **HTML5** — Estructura semántica
- **CSS3** — Diseño responsive con variables CSS, grid y flexbox
- **JavaScript (Vanilla)** — Sin frameworks, puro JS moderno
- **localStorage** — Persistencia de datos
- **Open-Meteo API** — Clima en vivo (gratuita, sin API key)
- **Web Notifications API** — Recordatorios nativos
- **Blob API** — Exportación de backups
- **PWA** — Instalable en el celular

---

## 📁 Estructura del proyecto
