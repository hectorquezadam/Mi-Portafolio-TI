# 🎮 Club V.J. - Catálogo Digital de Videojuegos
**Proyecto Final del Módulo: Desarrollo Web con Django**

Este proyecto es un MVP (Producto Mínimo Viable) diseñado para el "Club V.J.", un local de videojuegos retro y modernos. La aplicación permite gestionar un catálogo dinámico para que los clientes consulten la disponibilidad y detalles de los títulos.

---

## 🛠️ Tecnologías y Herramientas
- **Lenguaje:** ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
- **Framework:** ![Django](https://img.shields.io/badge/-Django-092E20?style=flat&logo=django&logoColor=white)
- **Frontend:** ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
- **Base de Datos:** ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4479A1?style=flat&logo=postgresql&logoColor=white) / SQLite
- **Editor:** ![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)

---

## 🌟 Funcionalidades Clave
1. **Catálogo Dinámico:** Visualización de juegos con filtros por plataforma y género.
2. **Lógica VIP:** El sistema identifica automáticamente lanzamientos del año actual y los etiqueta como **"EXCLUSIVO VIP"**, restringiendo el acceso detallado a usuarios con privilegios.
3. **Panel Administrativo:** Gestión completa de títulos, plataformas y perfiles de usuario.
4. **Diseño Responsivo:** Interfaz adaptada para móviles y escritorio usando Bootstrap 5.

---

## 🗄️ Estructura de Datos
El proyecto utiliza un modelo relacional que conecta:
- **Videojuego:** Título, descripción, año e imagen.
- **Plataforma:** (FK) Relación con consolas como PS5, Xbox, Switch.
- **Género:** (FK) Clasificación por categorías.
- **UserProfile:** Extensión del usuario de Django para gestionar el estado VIP.

---

## 🚀 Instalación y Ejecución
1. Clonar el repositorio.
2. Crear un entorno virtual: `python -m venv venv`.
3. Instalar dependencias: `pip install django`.
4. Ejecutar migraciones: `python manage.py migrate`.
5. Iniciar servidor: `python manage.py runserver`.
