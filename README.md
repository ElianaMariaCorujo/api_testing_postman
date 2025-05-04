# 🧪 Ejercicios CRUD con Postman

Este proyecto contiene una colección básica de pruebas manuales usando [Postman](https://www.postman.com/) contra la API pública de prueba [JSONPlaceholder](https://jsonplaceholder.typicode.com/). Es ideal para comenzar a familiarizarse con los métodos HTTP básicos: `GET`, `POST`, `PUT` y `DELETE`.

## 📌 Objetivo

Practicar el ciclo CRUD utilizando una API REST gratuita sin necesidad de autentificación ni entorno de desarrollo.

## 🚀 Métodos implementados

### ✅ `GET /posts/1`
Consulta un post específico por ID y devuelve su contenido en formato JSON.

### 🆕 `POST /posts`
Crea un nuevo post simulando el envío de datos en formato JSON:
```json
{
  "title": "Mi primer post desde Postman",
  "body": "Estoy aprendiendo a usar Postman y me encanta.",
  "userId": 123
}
