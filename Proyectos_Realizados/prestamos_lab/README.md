# 💻 Sistema de Préstamos de Notebooks
Aplicación para el control de inventario tecnológico en laboratorios institucionales.

### 🛠️ Tecnologías Aplicadas
- **Seguridad:** Control de acceso basado en Grupos y Permisos de Django.
- **UX/UI:** Mensajes de retroalimentación (Django Messages) y formularios estilizados.

### 🔒 Funciones Especiales
- **Reporte Interno:** Vista restringida únicamente para usuarios del grupo "Encargados".
- **Contador de Visitas:** Implementación de manejo de Sesiones para estad# 💻 Préstamos Lab - Control de Inventario
**Ejercicio de Aplicación: Seguridad y Sesiones**

Sistema desarrollado para el control de préstamo de notebooks institucionales, garantizando que solo personal autorizado acceda a información sensible.

---

## 🛠️ Tecnologías y Herramientas
- **Backend:** ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/-Django-092E20?style=flat&logo=django&logoColor=white)
- **Seguridad:** Control de acceso por Grupos y Permisos.
- **Frontend:** ![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)

---

## 🌟 Funcionalidades Clave
- **Gestión de Sesiones:** Contador de visitas dinámico para estadísticas de uso.
- **Reporte Interno:** Vista protegida mediante el decorador `permission_required` para el grupo de "Encargados".
- **Mensajería:** Retroalimentación al usuario mediante el framework de mensajes de Django.ísticas de uso.