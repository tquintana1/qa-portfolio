# QA Portfolio — Thiago De La Quintana

## Contenido del repositorio

### 📁 Colección Postman · JSONPlaceholder API
Colección de pruebas funcionales sobre la API REST pública JSONPlaceholder.

- 8 requests organizados (GET, POST, PUT, PATCH, DELETE)
- Variables de entorno configuradas para múltiples ambientes
- 21 tests automáticos con pm.test() — todos en verde

| Método | Endpoint | Tests |
|---|---|---|
| GET | /users | Status 200, array de 10 usuarios |
| GET | /users/{id} | Status 200, campos id y email |
| GET | /users/999 | Status 404, body vacío |
| GET | /posts?userId=1 | Status 200, filtro correcto |
| POST | /posts | Status 201, id asignado |
| PUT | /posts/1 | Status 200, datos actualizados |
| PATCH | /posts/1 | Status 200, campo modificado |
| DELETE | /posts/1 | Status 200, body vacío |

---

### 📁 gestion-datos · Matriz de Dependencias
Documentación de pre-requisitos de prueba para un sistema e-commerce.

- 10 casos de prueba con ID (TC-001 a TC-010)
- Datos necesarios clasificados por tipo (estático, dinámico, sintético)
- Ambientes y dependencias mapeadas por caso

---

## Tecnologías
Postman · REST APIs · JavaScript (pm.test) · Variables de entorno · CRUD completo · SQL · Gestión de datos de prueba
