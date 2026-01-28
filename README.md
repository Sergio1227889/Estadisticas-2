# Dashboard de Estadísticas de Comercios

Aplicación web profesional para análisis integral de estadísticas de comercios por sectores.

## 🚀 Características

- **Dashboard Interactivo**: Visualización en tiempo real de métricas clave
- **6 Sectores Diferentes**: Retail, Gastronomía, Servicios, Salud, Educación, Viajes
- **18 Comercios Monitoreados**: Análisis detallado de cada comercio
- **Gráficos Avanzados**: Barras, líneas, pastel, radar y burbujas
- **Exportación de Datos**: Descarga en CSV, impresión y compartir
- **Diseño Responsivo**: Funciona perfectamente en móviles, tablets y desktop
- **Interfaz Moderna**: Diseño profesional con colores y animaciones

## 📋 Requisitos

- Node.js >= 16.0.0
- npm >= 8.0.0

## 🛠️ Instalación

1. **Clonar o descargar el proyecto**
   ```bash
   cd web-estadisticas
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Iniciar servidor de desarrollo**
   ```bash
   npm run dev
   ```

   La aplicación estará disponible en `http://localhost:3000`

## 📦 Compilación para Producción

```bash
npm run build
```

Esto generará una carpeta `dist/` con los archivos optimizados listos para desplegar.

## 📁 Estructura del Proyecto

```
web-estadisticas/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Footer.jsx
│   │   ├── KPICards.jsx
│   │   ├── TabsSection.jsx
│   │   ├── ExportSection.jsx
│   │   └── tabs/
│   │       ├── OverviewTab.jsx
│   │       ├── SectoresTab.jsx
│   │       ├── ComerciostTab.jsx
│   │       └── AnalisisTab.jsx
│   ├── pages/
│   │   └── Dashboard.jsx
│   ├── styles/
│   │   ├── index.css
│   │   ├── App.css
│   │   ├── Navbar.css
│   │   ├── Footer.css
│   │   ├── Dashboard.css
│   │   ├── KPICards.css
│   │   ├── TabsSection.css
│   │   ├── Charts.css
│   │   ├── SectoresTab.css
│   │   ├── ComerciostTab.css
│   │   └── ExportSection.css
│   ├── data/
│   │   └── comercios.json
│   ├── App.jsx
│   └── main.jsx
├── package.json
├── vite.config.js
├── README.md
└── .gitignore
```

## 🌐 Despliegue

### Opción 1: Vercel (Recomendado)
1. Conecta tu repositorio a Vercel
2. Vercel detectará automáticamente que es un proyecto Vite
3. Haz clic en Deploy

### Opción 2: Netlify
1. Conecta tu repositorio a Netlify
2. Configura el comando de build: `npm run build`
3. Configura el directorio de publicación: `dist`

### Opción 3: Servidor Propio
1. Compila el proyecto: `npm run build`
2. Sube la carpeta `dist/` a tu servidor web
3. Configura tu servidor para servir `index.html` en todas las rutas

## 📊 Datos

Los datos de ejemplo se encuentran en `src/data/comercios.json`. Puedes modificar este archivo para actualizar las estadísticas.

## 🎨 Personalización

### Cambiar Colores
Modifica las variables CSS en `src/styles/index.css`:
```css
:root {
  --primary: #FF6B35;
  --secondary: #004E89;
  --accent: #F7B801;
  /* ... más colores */
}
```

### Agregar Nuevos Sectores
1. Abre `src/data/comercios.json`
2. Agrega un nuevo objeto sector con sus comercios
3. Los gráficos se actualizarán automáticamente

## 🔧 Scripts Disponibles

- `npm run dev` - Inicia el servidor de desarrollo
- `npm run build` - Compila para producción
- `npm run preview` - Vista previa de la compilación
- `npm run lint` - Ejecuta el linter
- `npm run format` - Formatea el código

## 📝 Licencia

MIT

## 👨‍💻 Autor

Dashboard de Estadísticas de Comercios v1.0.0

## 🤝 Soporte

Para reportar problemas o sugerencias, por favor contacta al equipo de desarrollo.
