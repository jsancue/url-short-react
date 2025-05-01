# 📎 URL Shortener - Frontend (React + Vite)

Este proyecto es la interfaz frontend de un acortador de URLs, desarrollado con **React** y **Vite**. Ofrece una experiencia de usuario moderna e intuitiva para generar, copiar y visualizar URLs cortas.

Repositorio del Backend: [https://github.com/jsancue/url-short-react](https://github.com/jsancue/url-shortener-sb)

## 🚀 Características

- Interfaz rápida y responsiva con Vite + React.
- Creación de URLs cortas integradas con el backend.
- Visualización de estadísticas mediante gráficos.
- Copia de enlaces acortados al portapapeles.
- Feedback visual con notificaciones y animaciones.
- Formulario avanzado para validar y enviar URLs.

## 🛠️ Tecnologías y Librerías

- **React + Vite** (desarrollo rápido y moderno)
- **React Router DOM** (navegación de rutas)
- **MUI / Material UI** (diseño de interfaz)
- **@emotion/react + @emotion/styled** (estilos en JS)
- **React Query** (gestión de datos asíncronos)
- **Axios** (solicitudes HTTP)
- **React Hook Form** (gestión de formularios)
- **Chart.js + react-chartjs-2** (visualización de datos)
- **Day.js** (manipulación de fechas)
- **React Copy to Clipboard** (copiar enlaces)
- **React Hot Toast** (notificaciones)
- **React Loader Spinner** (carga visual)
- **Framer Motion** (animaciones suaves)
- **React Icons** (iconografía)

## 📦 Instalación y ejecución

### Prerrequisitos

- Node.js (v14 o superior)
- npm o yarn

### Clonar el repositorio

```bash
git clone https://github.com/jsancue/url-short-react.git
cd url-short-react
```

### Instalar dependencias

```bash
npm install
# o con yarn
yarn install
```

### Ejecutar en modo desarrollo

```bash
npm run dev
# o con yarn
yarn dev
```

La aplicación estará disponible en: `http://localhost:5173`

## 🧪 Scripts adicionales

- `npm run build`: compila el proyecto para producción
- `npm run preview`: previsualiza la aplicación compilada localmente

## 🗂 Estructura del Proyecto

```
src/
├── api/             # Solicitudes a la API
├── assets/          # Recursos estáticos (imágenes, íconos)
├── components/      # Componentes reutilizables
├── contextApi/      # Contextos de React para gestión global
├── dummyData/       # Datos de prueba / simulación
├── hooks/           # Hooks personalizados
├── utils/           # Funciones auxiliares
├── App.css
├── App.jsx
├── AppRouter.jsx
├── PrivateRoute.jsx
├── index.css
└── main.jsx
```

## 🧑‍💻 Autor

- [jsancue](https://github.com/jsancue)

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.

---

¡Gracias por visitar el proyecto! Si te fue útil, considera dejar una ⭐ en GitHub.
