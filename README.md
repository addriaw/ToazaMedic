# 🏥 Toaza Medic

Sistema web desarrollado para la gestión y promoción de servicios biomédicos, mantenimiento de equipos médicos y comercialización de dispositivos especializados.

![Next.js](https://img.shields.io/badge/Next.js-16-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Prisma](https://img.shields.io/badge/Prisma-ORM-green)
![SQLite](https://img.shields.io/badge/SQLite-Database-lightgrey)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-38BDF8)

---

## 📋 Descripción

Toaza Medic es una plataforma web moderna desarrollada para empresas del sector biomédico.

El sistema permite:

- Gestión de productos biomédicos.
- Publicación de noticias y artículos.
- Administración de contenido institucional.
- Gestión de suscriptores.
- Panel administrativo seguro.
- Seguimiento de visitas y métricas.
- Catálogo de equipos médicos.
- Integración con WhatsApp para contacto comercial.

---

# 🚀 Características

## Sitio Público

### 🏠 Inicio
- Hero principal con video promocional.
- Información corporativa.
- Accesos rápidos a servicios.
- Catálogo destacado.

### 👨‍⚕️ Quiénes Somos
- Historia de la empresa.
- Equipo profesional.
- Valores institucionales.

### 🎯 Misión y Visión
- Presentación de objetivos empresariales.

### 🔧 Servicios
- Mantenimiento preventivo.
- Mantenimiento correctivo.
- Reparación de equipos médicos.
- Soporte técnico especializado.

### 📦 Catálogo
- Productos organizados por categorías.
- Búsqueda de productos.
- Vista detallada.
- Contacto directo mediante WhatsApp.

### 📰 Noticias
- Publicación de novedades.
- Contenido administrable.

### ✍️ Blog
- Artículos informativos.
- Sistema de contenido dinámico.

### 📧 Suscripción
- Registro de usuarios interesados.
- Gestión desde panel administrativo.

---

# 🔐 Panel Administrativo

Acceso restringido mediante autenticación segura.

## Dashboard

Visualización de:

- Productos registrados.
- Publicaciones.
- Noticias.
- Suscriptores.
- Eventos del sistema.

## Gestión de Productos

Permite:

- Crear productos.
- Editar productos.
- Eliminar productos.
- Gestionar imágenes.
- Administrar categorías.

## Gestión de Noticias

Permite:

- Crear noticias.
- Editar contenido.
- Publicar novedades.

## Gestión de Blog

Permite:

- Crear artículos.
- Administrar publicaciones.
- Actualizar contenido.

## Gestión de Contenido

Administración de:

- Inicio
- Quiénes Somos
- Misión y Visión
- Servicios

## Gestión de Suscriptores

- Visualización de registros.
- Administración de usuarios suscritos.

## Gestión de Usuarios Administradores

Solo disponible para:

```txt
SUPER_ADMIN
```

Permite:

- Crear administradores.
- Activar usuarios.
- Desactivar usuarios.
- Control de roles.

---

# 🛠️ Tecnologías Utilizadas

## Frontend

- Next.js 16
- React 19
- TypeScript
- Tailwind CSS

## Backend

- Next.js App Router
- Server Actions
- Route Handlers

## Base de Datos

- Prisma ORM
- SQLite

## Seguridad

- Cookies HttpOnly
- Hash de contraseñas con bcrypt
- Gestión de sesiones

---

# 📂 Estructura del Proyecto

```txt
src/
│
├── app/
│   ├── (public)/
│   ├── (admin)/
│   ├── api/
│
├── components/
│   ├── admin/
│   ├── Navbar.tsx
│   ├── Footer.tsx
│   ├── MegaFooter.tsx
│
├── lib/
│   ├── prisma.ts
│   ├── adminAuth.ts
│
├── generated/
│
└── prisma/
    └── schema.prisma
```

---

# ⚙️ Instalación

## 1. Clonar repositorio

```bash
git clone https://github.com/usuario/toaza-medic.git
```

## 2. Ingresar al proyecto

```bash
cd toaza-medic
```

## 3. Instalar dependencias

```bash
npm install
```

## 4. Configurar variables de entorno

Crear archivo:

```env
.env
```

Ejemplo:

```env
DATABASE_URL="file:./dev.db"

ADMIN_PASSWORD=toaza123
ADMIN_TOKEN=toaza_admin_token_123

BOOTSTRAP_KEY=crear_un_token_seguro_123
```

## 5. Generar Prisma

```bash
npx prisma generate
```

## 6. Ejecutar migraciones

```bash
npx prisma migrate dev
```

## 7. Iniciar proyecto

```bash
npm run dev
```

---

# 🌐 Accesos

## Sitio Web

```txt
http://localhost:3000
```

## Panel Administrativo

```txt
http://localhost:3000/admin-login
```

---

# 📈 Funcionalidades Futuras

- Dashboard avanzado con BI.
- Integración con Google Analytics.
- Reportes PDF.
- Integración con ERP.
- Integración con CRM.
- Sistema de tickets de soporte.
- Notificaciones en tiempo real.
- Almacenamiento en la nube.

---

# 👨‍💻 Autor

### Adrián Eduardo Alvarado Toaza

Ingeniero en Sistemas de Información

- Desarrollo Web
- Business Intelligence
- Ciencia de Datos
- Ingeniería de Software

---

# 📄 Licencia

Copyright © 2025-2026 Addriaw.

Todos los derechos reservados.
