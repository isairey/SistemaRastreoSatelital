# 🚗📡 Sistema de Rastreo Satelital de Vehículos

Plataforma web desarrollada para el monitoreo y gestión de vehículos en tiempo real mediante tecnologías de geolocalización, permitiendo visualizar rutas, posiciones y actividad de unidades desde cualquier lugar.

---

## 📌 Descripción

El **Sistema de Rastreo Satelital de Vehículos** es una solución orientada al seguimiento de flotas utilizando datos de ubicación obtenidos por GPS.

El sistema permite visualizar la posición de los vehículos en tiempo real, almacenar rutas históricas y gestionar información relevante para optimizar la operación y seguridad.

---

## 🚀 Características

- 📍 Monitoreo en tiempo real de vehículos  
- 🗺️ Visualización de ubicaciones en mapa  
- 📊 Historial de rutas recorridas  
- 🚨 Alertas y notificaciones  
- 🔐 Gestión de usuarios  
- 🧾 Registro de eventos  
- ⚡ Procesamiento eficiente de datos  

---

## 🛠️ Tecnologías utilizadas

### Backend
- **PHP** → Lógica del servidor  
- **PostgreSQL** → Base de datos  

### Base de datos avanzada
- **PL/pgSQL** → Procedimientos almacenados y lógica interna  

### Frontend
- **HTML5**
- **CSS3**
- **JavaScript**

### Integraciones (opcional)
- **Google Maps API / Leaflet** → Visualización de mapas  

---

## 📂 Estructura del proyecto

```
rastreo-vehiculos/
│
├── 📁 app/
│ ├── controllers/
│ ├── models/
│
├── 📁 public/
│ ├── css/
│ ├── js/
│ ├── index.php
│
├── 📁 database/
│ ├── schema.sql
│ ├── procedures.sql
│
├── 📁 views/
├── config.php
└── README.md
```

---

## ⚙️ Requisitos

- PHP 7.4 o superior  
- PostgreSQL  
- Servidor web (Apache / Nginx)  
- Extensión PDO para PostgreSQL  

---

## 🔧 Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/isairey/SistemaRastreoSatelital.git
```
Acceder al proyecto:
```
cd SistemaRastreoSatelital
```
Configurar la base de datos:
```
Crear base de datos en PostgreSQL
```
Ejecutar scripts:
```
\i database/schema.sql
\i database/procedures.sql
Configurar conexión en config.php
```
Levantar servidor:
```
php -S localhost:8000
```
---

## ▶️ Uso

- Iniciar sesión en el sistema
- Registrar vehículos
- Visualizar ubicaciones en tiempo real
- Consultar rutas históricas
- Gestionar alertas

---

## 💡 Funcionamiento

El sistema recibe datos de ubicación desde dispositivos GPS instalados en los vehículos, los cuales son:

-📡 Enviados al servidor
-💾 Almacenados en PostgreSQL
-⚙️ Procesados mediante funciones en PL/pgSQL
-🗺️ Visualizados en la interfaz web

---

## 🎨 Interfaz

Panel de control intuitivo
Mapa interactivo
Visualización en tiempo real
Diseño adaptable

---

## 📈 Mejoras futuras

-📱 Aplicación móvil
-🔔 Notificaciones en tiempo real
-📊 Dashboard con analítica avanzada
-☁️ Despliegue en la nube
-🤖 Predicción de rutas

---

## ⚠️ Nota

Este sistema puede integrarse con hardware GPS real o funcionar con datos simulados para pruebas.

---

## 👨‍💻 Autor

Desarrollado por **Isai Reyes Peña**
