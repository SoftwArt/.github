# SoftwArt

> 🇨🇴 [Español](#español) · 🌐 [English](#english)

---

## English

**SoftwArt** is a web and mobile management system built for **Arte Café**, a framing and marquetry shop in Laureles, Medellín, Colombia.

Developed as a capstone project for the **Technology in Software Analysis and Development** program at SENA, Regional Antioquia.

### The problem it solves

Arte Café operated with physical records, paper receipts and verbal payment agreements. Customers had to visit the shop in person to schedule appointments or check on their orders. SoftwArt replaces that entirely with a centralized digital system deployed in production.

### Key features

- Appointment scheduling with real-time availability — including guest booking, no account required
- Sales with flexible installment plans · order tracking · payment management
- Self-service client portal: book and track appointments, follow service status
- Role-based admin panel (Admin / Employee / Client) with granular permissions
- Android companion app for staff — live consultation + push notifications (FCM)

### System

🌐 **[softwart.online](https://softwart.online)**

### Repositories

| Repo | Stack |
|---|---|
| [softwart-backend](https://github.com/SoftwArt/softwart-backend) | Node.js · Express · TypeScript · TypeORM · PostgreSQL |
| [softwart-frontend](https://github.com/SoftwArt/softwart-frontend) | React · TypeScript · Vite · Tailwind · shadcn/ui |
| [softwart-mobile](https://github.com/SoftwArt/softwart-mobile) | Flutter · Dart · Clean Architecture · Provider |
| [softwart-docs](https://github.com/SoftwArt/softwart-docs) | Technical and academic documentation |

### Infrastructure

| Service | Role |
|---|---|
| Render | Backend hosting |
| Vercel | Frontend hosting + CDN |
| Supabase | PostgreSQL 15 (managed) |
| Cloudinary | Image storage and delivery |
| Namecheap | Domain (`softwart.online`) |
| Resend | Mail service |
| Firebase | Push notifications (FCM) for the mobile app |

### Built by

**Sergio E. León V.** — [@selvcebo](https://github.com/selvcebo)
SENA · Technology in Software Analysis and Development · Medellín, Colombia

---

## Español

**SoftwArt** es un sistema de gestión web y móvil desarrollado para **Arte Café**, una marquetería PYME ubicada en Laureles, Medellín, Colombia.

Desarrollado como proyecto de grado de la **Tecnología en Análisis y Desarrollo de Software** del SENA, Regional Antioquia.

### El problema que resuelve

Arte Café manejaba su operación con agendas físicas, recibos en papel y acuerdos verbales de pago. Los clientes debían ir presencialmente para agendar citas o ver el avance de su pedido. SoftwArt reemplaza ese flujo con un sistema centralizado desplegado en producción.

### Funcionalidades clave

- Agendamiento de citas con disponibilidad en tiempo real — incluye agendamiento de invitados, sin necesidad de cuenta
- Ventas con planes de abono flexibles · seguimiento de pedidos · gestión de pagos
- Portal de autoservicio para clientes: agendar y consultar citas, seguir el estado del servicio
- Panel admin basado en roles (Admin / Empleado / Cliente) con permisos granulares
- App Android complementaria para el personal — consulta en vivo + notificaciones push (FCM)

### Sistema

🌐 **[softwart.online](https://softwart.online)**

### Repositorios

| Repo | Stack |
|---|---|
| [softwart-backend](https://github.com/SoftwArt/softwart-backend) | Node.js · Express · TypeScript · TypeORM · PostgreSQL |
| [softwart-frontend](https://github.com/SoftwArt/softwart-frontend) | React · TypeScript · Vite · Tailwind · shadcn/ui |
| [softwart-mobile](https://github.com/SoftwArt/softwart-mobile) | Flutter · Dart · Clean Architecture · Provider |
| [softwart-docs](https://github.com/SoftwArt/softwart-docs) | Technical and academic documentation |

### Infraestructura

| Servicio | Rol |
|---|---|
| Render | Hosting del backend |
| Vercel | Hosting del frontend + CDN |
| Supabase | PostgreSQL 15 (gestionado) |
| Cloudinary | Almacenamiento y distribución de imágenes |
| Namecheap | Dominio (`softwart.online`) |
| Resend | Servicio de correos |
| Firebase | Notificaciones push (FCM) para la app móvil |

### Desarrollado por

**Sergio E. León V.** — [@selvcebo](https://github.com/selvcebo)
SENA · Tecnología en Análisis y Desarrollo de Software · Medellín, Colombia
