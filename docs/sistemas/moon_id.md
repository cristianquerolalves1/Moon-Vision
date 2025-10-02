[![Moon ID](imagenes/sistemas/moon_id.png)](docs/sistemas/moon_id.md)
# Moon ID

**Moon ID** es el sistema de identificación de usuarios de **Moon Studio**, que permite gestionar registros, permisos y autenticación dentro del ecosistema del servidor y la web interactiva. Es la base sobre la que funcionan la mayoría de sistemas internos y sirve para mantener un control seguro y organizado de los jugadores.

---

## 📌 Objetivo

El objetivo de Moon ID es:

- Proporcionar un **identificador único** para cada jugador.  
- Gestionar **permisos y roles** dentro del servidor.  
- Facilitar la integración con otros sistemas: Moon Missions, Whitelist, Moon Map, Paneles de usuario.  
- Garantizar **seguridad y trazabilidad** de acciones dentro del ecosistema.

---

## 🛠️ Funcionalidades principales

| Funcionalidad | Descripción |
|---------------|------------|
| Registro de usuarios | Cada jugador recibe un ID único al registrarse. |
| Autenticación | Inicio de sesión seguro mediante credenciales propias o integraciones con Discord / OAuth. |
| Roles y permisos | Gestión de acceso a zonas, misiones y herramientas según el rol del jugador. |
| Integración con sistemas | Conecta con Moon Missions, Moon Map y paneles de usuario para mostrar datos personalizados. |
| Seguridad | Almacenamiento seguro de datos y registro de acciones importantes dentro del servidor. |

---

## 🗂️ Estructura interna

Moon ID se organiza en módulos:

1. **Usuarios**: Datos básicos, perfil y estadísticas.  
2. **Roles y permisos**: Control de acceso y jerarquías.  
3. **Autenticación**: Login, logout y verificación.  
4. **Integraciones**: Conexión con otros sistemas internos (missions, whitelist, dashboards).  
5. **Auditoría**: Registro de actividades y cambios importantes.
