# Mi Comida Favorita

Una aplicación móvil desarrollada con **React Native** y **Firebase**, diseñada para gestionar perfiles de usuarios con autenticación y almacenamiento de datos personales.

---

## Funcionalidades
- Registro de usuarios con validación de email y contraseñas seguras.
- Inicio de sesión con manejo de errores y estado de carga.
- Gestión de perfiles personales almacenados en Firestore.
- Persistencia de sesión con Firebase Authentication.
- Indicadores de carga durante operaciones críticas.
- Manejo de errores con mensajes claros y retroalimentación visual.

---

## Requisitos previos
Antes de iniciar, asegúrate de tener las siguientes herramientas instaladas:
- **Node.js** (versión 14 o superior)
- **npm** o **yarn**
- **Expo CLI**
- Un emulador de Android/iOS o un dispositivo físico
- Cuenta activa en [Firebase Console](https://console.firebase.google.com/)

---

## Instalación y configuración
### 1. Clonar el repositorio
```bash
git clone https://github.com/latioskev/mi-comida-favorita.git
cd mi-comida-favorita
```
### 2. Instalar dependencias
-  npm install
-  npm install @react-navigation/native @react-navigation/native-stack
-  npm install firebase
-  npm install react-native-elements
-  npm install expo-constants
-  npm install react-native-safe-area-contex
### 3. Configurar Firebase
- Ir a Firebase Console (
 https://console.firebase.google.com/)
- Crear nuevo proyecto "MiComidaFavorita"
- Habilitar Authentication (Email/Password)
- Crear Cloud Firestore
- Registrar la aplicación web
- Copiar configuración de Firebase
### 3. Iniciar el proyecto
- npx expo start
