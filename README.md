# BackendIDWM

### 🚀 Introducción
Bienvenido al backend del taller de **Introducción al Desarrollo Web Móvil (IDWM)**, desarrollado en **ASP.NET Core**. Este proyecto sigue el **patrón Repository y Unit of Work**, y utiliza **ASP.NET Identity** para la gestión de autenticación y usuarios. 

---

## 🛠️ Tecnologías utilizadas
- **Framework:** ASP.NET Core  
- **Patrones de diseño:** Repository Pattern y Unit of Work  
- **Base de datos:** SQLite  
- **ORM:** Entity Framework Core  
- **Autenticación:** ASP.NET Identity  
- **Registro de logs:** Serilog  

---

## 📌 Funcionalidades principales
✅ API REST para la aplicación móvil  
✅ Manejo de autenticación y roles con ASP.NET Identity  
✅ Patrón Repository para una mejor separación de responsabilidades  
✅ Implementación de Unit of Work para un control eficiente de transacciones  
✅ Gestión de usuarios y permisos  
✅ Control de sesiones y seguridad  
✅ Configuración de CORS  
✅ Documentación con Swagger  

---

## 🏗️ Arquitectura del Proyecto
```
📂 Backend-IDWM
 ├── 📂 Controllers
 ├── 📂 Services
 ├── 📂 Repositories
 ├── 📂 Models
 ├── 📂 Data
 ├── 📂 DTOs
 ├── 📂 Interfaces
 ├── 📂 Request
 ├── appsettings.json
 ├── Startup.cs
 ├── Program.cs
```

---

## 🚀 Instalación y configuración
### 1️⃣ Clonar el repositorio
```bash
 git clone https://github.com/Eltosergi/BackendIDWM.git
 cd backend-idwm
```
### 2️⃣ Configurar la base de datos SQLite
- La conexión a SQLite se configura en `appsettings.json`:
```json
"ConnectionStrings": {
  "DefaultConnection": "Data Source=idwm.db;"
}
```
- Asegurar que Entity Framework Core pueda generar automáticamente la base de datos.

### 3️⃣ Aplicar migraciones y actualizar la base de datos
```bash
 dotnet ef migrations add InitialCreate
 dotnet ef database update
```
### 4️⃣ Ejecutar el proyecto
```bash
 dotnet run
```
El backend estará disponible en: `http://localhost:5000`

---

## 📄 Endpoints principales
| Método | Endpoint | Descripción |
|--------|---------|-------------|
| `POST` | `/api/auth/register` | Registro de usuario |
| `POST` | `/api/auth/login` | Inicio de sesión |
| `GET`  | `/api/users` | Obtener lista de usuarios |
| `POST` | `/api/users` | Crear un nuevo usuario |

Para más detalles, consulta la documentación con **Swagger** en `http://localhost:5000/swagger`.

---

## 🔥 Contribuciones
¡Las contribuciones son bienvenidas! Si deseas colaborar:
1. Haz un fork del proyecto.
2. Crea una nueva rama (`git checkout -b feature-nueva`).
3. Realiza tus cambios y haz commit (`git commit -m "Agrega nueva funcionalidad"`).
4. Sube los cambios (`git push origin feature-nueva`).
5. Abre un Pull Request.

---

## 📜 Licencia
Este proyecto se encuentra bajo la licencia **MIT**. ¡Siéntete libre de usarlo y modificarlo! 🚀

---

### 📬 Contacto
Si tienes alguna duda o sugerencia, no dudes en contactar a los mantenedores del proyecto. 😉

---

## 📂 Más información
Para más detalles sobre las solicitudes y respuestas de la API, revisa la carpeta **Request**, donde encontrarás los **requerimientos del backend** y las **tareas asignadas a los estudiantes**.
