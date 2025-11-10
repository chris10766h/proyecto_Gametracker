# 🎮 GameTracker 2

**GameTracker 2** es una aplicación web desarrollada para gestionar tu biblioteca de videojuegos.  
Permite registrar, editar y visualizar información detallada sobre tus juegos, reseñas personales, horas jugadas y estadísticas globales.  
Su interfaz combina un diseño moderno con funcionalidades prácticas para el seguimiento de progreso y análisis de tus hábitos de juego.

---

## 🚀 Características Principales

- 📚 **Biblioteca de Juegos** — Agrega, edita y elimina tus juegos fácilmente.  
- ⭐ **Sistema de Reseñas** — Registra puntuaciones, horas jugadas y opiniones.  
- 📊 **Dashboard de Estadísticas** — Visualiza métricas globales y distribuciones por género y plataforma.  
- 🌙 **Modo Oscuro / Claro** — Cambia el tema según tu preferencia.  
- 📄 **Exportar a PDF** — Descarga tu biblioteca o tus reseñas como archivo PDF.  
- 🔍 **Filtros Avanzados** — Busca por título, plataforma, género, estado o año de lanzamiento.  

---

## 🧱 Tecnologías Utilizadas

**Frontend**
- React.js  
- Axios  
- HTML5 / CSS3  
- jsPDF + html2canvas (para exportar a PDF)

**Backend**
- Node.js  
- Express.js  
- MongoDB + Mongoose  

---

## ⚙️ Instalación y Ejecución

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/chris10766h/proyecto_Gametracker.git
2️⃣ Instalar dependencias
Instala las dependencias tanto del backend como del frontend:

bash
Copiar código
# En la carpeta raíz o backend
npm install

# Luego entra al frontend
cd frontend
npm install
3️⃣ Ejecutar el backend
bash
Copiar código
npm run dev
4️⃣ Ejecutar el frontend
Abre otra terminal:

bash
Copiar código
cd frontend
npm start
📊 Estructura del Proyecto
graphql
Copiar código
proyecto_Gametracker/
│
├── backend/                 # API REST con Express y MongoDB
│   ├── models/              # Modelos de datos (Juegos, Reseñas)
│   ├── routes/              # Rutas de la API
│   └── server.js            # Servidor principal
│
├── frontend/                # Interfaz de usuario en React
│   ├── src/
│   │   ├── components/      # Componentes reutilizables
│   │   ├── pages/           # Vistas principales
│   │   └── App.jsx          # Punto de entrada principal
│
└── README.md                # Documentación del proyecto
🧠 Funcionalidades Avanzadas
Dashboard Interactivo con progreso y porcentajes.

Formulario Integrado en reseñas y biblioteca.

Subida de imágenes con drag & drop para portadas de juegos.

Filtros dinámicos y responsivos en tiempo real.

👤 Desarrollado por
Cristian Acosta
Proyecto académico universitario — 2025
📍 Colombia

🧩 Licencia
Este proyecto fue creado con fines educativos.