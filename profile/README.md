# 🛠️ OficioYa

> Plataforma web diseñada para conectar de forma ágil, segura y confiable a trabajadores de diferentes oficios con clientes que requieren soluciones técnicas y de servicios.

---

## 📌 Visión del Proyecto
**OficioYa** centraliza la oferta y demanda de servicios de oficios (plomería, electricidad, reparaciones, mantenimiento, etc.), facilitando la búsqueda, contacto, cotización y seguimiento de trabajos a través de una experiencia intuitiva tanto para el cliente como para el prestador de servicios.

---

## 🏗️ Arquitectura y Tecnologías

El sistema está concebido bajo una arquitectura desacoplada frontend/backend:

### ⚙️ Backend (`OficioYa-Backend`)
* **Lenguaje:** Java 21
* **Framework:** Spring Boot (Spring Web, Spring Data JPA, Spring Security)
* **Gestor de dependencias:** Apache Maven
* **Arquitectura:** Diseño multicapas (Controllers, Services, Repositories, Domain/DTOs) con buenas prácticas y principios SOLID.
* **Base de datos:** Relacional (PostgreSQL / MySQL)

### 🎨 Frontend (`OficioYa-Frontend`)
* **Librería/Framework:** React
* **Estilos & UI:** Componentes modulares, diseño responsivo y accesible.
* **Consumo de APIs:** Cliente HTTP (Axios / Fetch API) para comunicación con el backend RESTful.

---

## 📂 Repositorios Principales

| Repositorio | Descripción | Tecnologías |
| :--- | :--- | :--- |
| [**OficioYa-Backend**](https://github.com/OficioYa1/OficioYa-Backend) | API RESTful y lógica de negocio central del sistema | Java 21, Spring Boot, Maven |
| [**OficioYa-Frontend**](https://github.com/OficioYa1/OficioYa-Frontend) | Interfaz web interactiva para usuarios y prestadores | React, JavaScript/TypeScript |
| [**.github**](https://github.com/OficioYa1/.github) | Configuración organizacional, discusiones y documentación | Markdown |

---

## 🌿 Flujo de Trabajo y Buenas Prácticas
* **Estrategia de ramas:** Flujo de trabajo basado en GitFlow (`feature/*`, `develop`, `main`).
* **Commits Semánticos:** Prefijos estándar (`feat:`, `fix:`, `chore:`, `refactor:`, `docs:`).
* **Pull Requests:** Todo cambio a ramas principales requiere revisión previa (code review) para garantizar la calidad y coherencia del código.
