# QA Portfolio — Thiago De La Quintana

## Colección Postman · JSONPlaceholder API

Colección de pruebas funcionales sobre la API REST pública JSONPlaceholder,
construida como parte de mi formación en Testing QA.

### ¿Qué incluye?
- 5 requests organizados en colección (GET, POST)
- Variables de entorno configuradas para múltiples ambientes
- 12 tests automáticos con pm.test() — todos en verde

### Endpoints testeados
| Método | Endpoint | Tests |
|---|---|---|
| GET | /users | Status 200, array de 10 usuarios |
| GET | /users/{id} | Status 200, campos id y email |
| GET | /users/999 | Status 404, body vacío |
| GET | /posts?userId=1 | Status 200, filtro correcto |
| POST | /posts | Status 201, id asignado |

### Tecnologías
Postman · REST APIs · JavaScript (pm.test) · Variables de entorno
