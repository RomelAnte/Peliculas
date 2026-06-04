# 🎬 Películas - Gestor de Películas

Una aplicación web moderna para gestionar tu colección personal de películas con autenticación segura y una interfaz intuitiva.

## ✨ Características

- 🔐 **Autenticación segura** con Firebase
- 🔑 **Inicio de sesión con Google**
- 📝 **CRUD completo** de películas (Crear, Leer, Actualizar, Eliminar)
- 🎨 **Interfaz responsive** con Bootstrap
- 💾 **Almacenamiento en la nube** con Firebase
- 🌙 **Diseño moderno y limpio**

## 🛠️ Tecnologías Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Frameworks**: Bootstrap 5.3.3
- **Backend**: Firebase (Autenticación y Base de Datos)
- **Servidor de desarrollo**: Lite Server

## 📋 Requisitos Previos

- Node.js (versión 14 o superior)
- npm (normalmente incluido con Node.js)
- Una cuenta de Google (para autenticación)

## 🚀 Instalación

1. **Clonar el repositorio**

   ```bash
   git clone https://github.com/tuusuario/Peliculas.git
   cd Peliculas
   ```

2. **Instalar dependencias**

   ```bash
   npm install
   ```

3. **Iniciar el servidor de desarrollo**

   ```bash
   npm run dev
   ```

4. **Abrir en el navegador**
   ```
   http://localhost:3000
   ```

## 📖 Uso

1. Inicia sesión con tu cuenta de Google
2. En la página principal, verás todas tus películas registradas
3. Usa el botón "Nuevo registro" para añadir una película
4. Completa los campos: título, director, género y más
5. Edita o elimina películas según sea necesario

## 📁 Estructura del Proyecto

```
Peliculas/
├── index.html              # Página de login
├── gestionarPeliculas.html # Página principal de gestión
├── package.json            # Dependencias del proyecto
├── style/
│   └── style.css          # Estilos personalizados
├── README.md              # Este archivo
└── mailmap.txt            # Configuración de autores
```

## 🔧 Scripts Disponibles

```bash
npm run dev    # Inicia el servidor de desarrollo
npm run run    # Alias para npm run dev
```

## 🔐 Configuración de Firebase

El proyecto usa Firebase para autenticación y almacenamiento. Las credenciales están configuradas en `index.html` y debes reemplazarlas con las tuyas propias:

```javascript
const firebaseConfig = {
  apiKey: "TU_API_KEY",
  authDomain: "tu-proyecto.firebaseapp.com",
  projectId: "tu-proyecto",
  storageBucket: "tu-proyecto.appspot.com",
  messagingSenderId: "tu-id",
};
```

## 📝 Notas

- Asegúrate de tener las claves de Firebase correctas configuradas
- La aplicación requiere una conexión a Internet para funcionar
- Se recomienda usar HTTPS en producción

## 📄 Licencia

Este proyecto está disponible bajo la licencia MIT.

---

**Disfruta gestionando tu colección de películas! 🎥**
