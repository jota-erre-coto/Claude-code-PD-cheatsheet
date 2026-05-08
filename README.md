# Claude Code para Product Designers — Cheatsheet

Guía rápida e interactiva de comandos para diseñadores de producto usando Claude Code.

**Versión 2026** · Civitatis Design System (Odisea)

---

## 📖 Descripción

Un cheatsheet completo, visualmente refinado y optimizado para Product Designers que utilizan Claude Code. Incluye atajos de entrada, comandos diarios, herramientas de diseño y funcionalidades avanzadas — todo en una interfaz moderna y accesible.

---

## 🖨️ Print & PDF Export

El archivo está optimizado para exportación a PDF sin pérdida de calidad visual:

- Colores preservados con `print-color-adjust: exact`
- Hero y footer mantienen estilos en impresión
- Tablas y cards se adaptan al ancho de página
- Tipografía se renderiza correctamente en PDF

**Exportar a PDF**: Usar Print (Cmd+P / Ctrl+P) → Guardar como PDF

---

## 📋 Estructura

```
Claude-code-PD-cheatsheet/
├── index.html          # Cheatsheet completo
├── README.md           # Este archivo
└── .gitignore          # Configuración de git
```

### Secciones del Cheatsheet

1. **Atajos de Entrada del Prompt**
   - `!` — Modo bash
   - `/` — Comandos
   - `@` — Rutas de archivo
   - `&` — Background
   - `#` — Comentario

2. **Configuración Inicial**
   - `/init`, `/login`, `/logout`
   - `/config`, `/permissions`
   - `/mcp`, `/doctor`, `/help`

3. **Flujo de Trabajo Diario**
   - `/plan`, `/memory`, `/context`
   - `/focus`, `/diff`, `/rewind`
   - `/voice`, `/skills`, `/effort`

4. **Comandos para Diseño**
   - Integración con Figma
   - Auditoría de accesibilidad
   - MCPs útiles (Linear, Notion, Playwright)
   - Prompts listos para copiar

5. **Avanzado**
   - Modos de razonamiento (`think`, `think hard`, `think harder`)
   - Automatización (`/loop`, `/schedule`, `/agents`)
   - Diagnóstico y costos

---

## 🚀 Uso

1. **Abrir en navegador**: Abrir `index.html` en cualquier navegador moderno
2. **Navegar entre tabs**: Hacer click en los botones de navegación (Básicos, Diarios, Diseño, Avanzado)
3. **Copiar comandos**: Hacer hover sobre una card y hacer click en "Copiar"
4. **Buscar en la página**: Usar Cmd+F / Ctrl+F para buscar comandos específicos
5. **Exportar a PDF**: Usar Print (Cmd+P / Ctrl+P) → "Guardar como PDF"

---

## 🔧 Desarrollo

### Modificar el contenido

El archivo es un HTML autónomo. Editar directamente `index.html`:

- **Agregar un comando**: Copiar un `.command-card` y actualizar el contenido
- **Cambiar estilos**: Los tokens CSS están en el `<style>` del head
- **Añadir una sección**: Duplicar una sección y actualizar el id del tab

### Fuentes

- **Montserrat**: Cargada desde Google Fonts (sans-serif para todos los textos)
- **JetBrains Mono**: Cargada desde Google Fonts (monospace para código)

Ambas están optimizadas para web con subsets latinos.

---

## 📄 Licencia

Documento de referencia interno de Civitatis Product Designers Chapter.

---

## 🤝 Contribuciones

Para actualizar el cheatsheet:

1. Crear una rama desde `main`
2. Hacer cambios en `index.html`
3. Pushear y crear un PR
4. El Chapter Lead revisa y mergea

---

**Última actualización**: Mayo 2026  
**Autor**: Civitatis Product Designers Chapter  
**Design System**: Odisea (Civitatis)

---

🚀 **[Claude Code Official Site](https://claude.ai/code)**  
📚 **[Claude Code Docs](https://support.claude.com)**
