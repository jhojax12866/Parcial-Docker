# 🚀 Proyecto Final - Orquestación de Servicios con Docker Compose

### Presentado por:
👨‍💻 Johan Fernando Burbano Calpa  
👨‍💻 Cristian Camilo Vallejos

---

## 🎯 Objetivo

Simulamos un entorno empresarial completo, desplegando **8 servicios interconectados** con **Docker Compose**, incluyendo servicios de base de datos, CMS, backend personalizado, administración, pruebas de correo y proxy inverso.

---

## 🧱 Servicios Implementados

| Servicio        | Descripción                                           |
|-----------------|-------------------------------------------------------|
| 🐬 MySQL        | Base de datos relacional principal                    |
| 🛠️ phpMyAdmin  | Administración web para MySQL                         |
| 🌐 WordPress    | CMS conectado a MySQL                                 |
| 🚀 Node.js API  | API propia conectada a MySQL y capaz de enviar correos |
| ✉️ Mailhog      | Servicio para pruebas de envío de correo              |
| 🧭 Nginx        | Reverse Proxy para WordPress y nuestra API            |
| 🍃 MongoDB      | Base de datos NoSQL independiente                     |
| 🧑‍💼 AdminMongo | Panel administrativo para MongoDB                     |

---

## 📁 Estructura de Proyecto
docker-compose-taller/
├── backend/
│ ├── Dockerfile # Imagen personalizada de la API
│ └── index.js # API con rutas GET y funcionalidades CRUD
├── nginx/
│ └── default.conf # Configuración de rutas para Nginx
└── docker-compose.yml # Orquestación de todos los servicios

---

## 🔄 Funcionalidades Extra

✅ Envío de correos desde la API hacia Mailhog  
✅ Operaciones **CRUD** desde el backend a MySQL  
✅ Uso de MongoDB como almacenamiento de **logs**  

---

## 🌐 Accesos Locales

| Servicio         | URL                                                  |
|------------------|------------------------------------------------------|
| WordPress        | [http://localhost:8080](http://localhost:8080)       |
| phpMyAdmin       | [http://localhost:8081](http://localhost:8081)       |
| Node.js API      | [http://localhost/api](http://localhost/api)         |
| Mailhog          | [http://localhost:8025](http://localhost:8025)       |
| AdminMongo       | [http://localhost:8082](http://localhost:8082)       |

---

## 🛠️ Tecnologías Utilizadas

- Docker & Docker Compose 🐳  
- Node.js + Express ⚙️  
- MySQL + phpMyAdmin 💾  
- WordPress 📄  
- Nginx 🌐  
- MongoDB + AdminMongo 🍃  
- Mailhog ✉️

---

## 🧠 Conclusión

Este proyecto demuestra la potencia de **Docker Compose** para simular infraestructuras empresariales modernas, integrando múltiples servicios en contenedores de manera ágil, segura y funcional.

---

📅 **Fecha de entrega:** Junio 2025  
🏫 **Asignatura:** Sistemas Distribuidos  
👨‍🏫 **Docente:** *Nicolas Jurado*

