# Invitación Real Mis XV Años — Solange Eluney Mercado Alegría 👑✨

Invitación web interactiva de Alta Costura Digital (Single Page Application) desarrollada con estándares de diseño Awwwards, estética **"Royal Enchanted Night"**, pantalla de inicio con emblema **"XV"** y barra de carga de 3 segundos, efectos de partículas doradas en movimiento a 60fps, minimapa interactivo de Google Maps embebido, emotivas palabras de agradecimiento de la quinceañera y confirmación de asistencia inteligente por WhatsApp al número **917007554**.

---

## 🎵 ¿Cómo Poner un Tema Musical Personalizado (Canción MP3)?

El reproductor ya está 100% preparado para reproducir la canción que elijas:

1. **Guarda tu archivo MP3:**
   - Descarga o copia tu canción favorita (por ejemplo, el vals de los 15 años o una balada romántica) y cópiala en esta misma carpeta:
     `d:\MIS IMÁGENES\MIS DOCUMENTOS\invitación sol\`
   - Nómbrala simplemente: **`musica.mp3`** (o el nombre que prefieras).

2. **Si usas otro nombre o un enlace de internet:**
   - Abre [index.html](file:///d:/MIS%20IM%C3%81GENES/MIS%20DOCUMENTOS/invitaci%C3%B3n%20sol/index.html) y busca la línea:
     ```javascript
     const CUSTOM_AUDIO_URL = "musica.mp3";
     ```
   - Escribe el nombre de tu archivo (ej: `"mi_cancion.mp3"`) o una URL directa.

> [!NOTE]
> **Respaldo Automático Inteligente:** Si no colocas ningún archivo o el MP3 aún no está listo, la invitación reproducirá automáticamente una melodía etérea de arpa celestial sin fallos ni errores.

---

## 🎨 ¿Cómo Cambiar el Tema Visual (Colores de la Fiesta)?

Si la temática de la fiesta utiliza otros tonos (como Oro Rosa, Esmeralda, Lavanda / Lila o Azul Zafiro), puedes cambiar los colores en [index.html](file:///d:/MIS%20IM%C3%81GENES/MIS%20DOCUMENTOS/invitaci%C3%B3n%20sol/index.html) en dos lugares sencillos:

### 1. Variables de Color en CSS (`:root` al inicio de `<style>`):
```css
:root {
  --gold-primary: #D4AF37; /* Color principal de acento */
  --gold-glow: rgba(212, 175, 55, 0.4);
  --midnight-bg: #070B14; /* Color de fondo oscuro */
}
```

### 2. Paleta en Tailwind (`tailwind.config`):
```javascript
colors: {
  midnight: {
    950: '#04060A', // Fondo más oscuro
    800: '#0B0F19', // Fondo de tarjetas
  },
  royal: {
    gold: '#D4AF37', // Tono dorado de títulos y botones
    goldLight: '#F3E5AB',
    rose: '#F4C2C2', // Tono secundario
  }
}
```

---

## 🚀 Cómo Abrir y Probar la Invitación

- **Directamente en tu navegador:** Haz doble clic sobre el archivo [index.html](file:///d:/MIS%20IM%C3%81GENES/MIS%20DOCUMENTOS/invitaci%C3%B3n%20sol/index.html).
- **Servidor local activo:** Puedes abrirlo en [http://localhost:5173/](http://localhost:5173/).

---

## 🌐 Cómo Publicarla en Internet para compartir por WhatsApp

Para que los invitados la abran desde su celular a través de un enlace de WhatsApp:

- **Netlify Drop:** Arrastra la carpeta a [app.netlify.com/drop](https://app.netlify.com/drop).
- **Vercel:** Sube el proyecto con `vercel` o conecta tu repositorio de GitHub.
- **GitHub Pages:** Sube `index.html` a un repositorio público y activa GitHub Pages en *Settings > Pages*.
