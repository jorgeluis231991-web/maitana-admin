# 🎉 Maitana Admin

Sistema de administración completo para **Maitana Eventos y Decoraciones**.

## ✨ Características

- 💰 Gestión de Ventas (Presupuestos, Pedidos, Facturas)
- 👥 Gestión de Empleados
- 📋 Gestión de Clientes
- 📦 Gestión de Inventario/Productos
- 📊 Reportes y Estadísticas
- 🔐 Autenticación segura (JWT)
- 📱 Interfaz responsive

## 🛠️ Stack Tecnológico

**Frontend:**
- React 18+
- Tailwind CSS
- Chart.js (gráficos)
- Axios (HTTP client)

**Backend:**
- Node.js + Express
- PostgreSQL
- JWT Authentication
- Sequelize ORM

## 📁 Estructura del Proyecto

```
maitana-admin/
├── client/               # Frontend (React)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── styles/
│   └── package.json
├── server/               # Backend (Node.js)
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── package.json
├── database/             # Migraciones y seeds
└── .env.example
```

## 🚀 Instalación

### Requisitos previos
- Node.js 16+
- PostgreSQL 12+
- Git

### Backend Setup
```bash
cd server
npm install
cp .env.example .env
# Edita .env con tus credenciales de PostgreSQL
npm run migrate
npm run dev
```

### Frontend Setup
```bash
cd client
npm install
npm run dev
```

### Desarrollo (ambos simultáneamente)
```bash
npm run dev
```

## 📚 Documentación

- [Guía de Configuración](./docs/SETUP.md)
- [API Endpoints](./docs/API.md)
- [Base de Datos](./docs/DATABASE.md)

## 📄 Licencia

MIT - Libre para usar y modificar

---

**Hecho con ❤️ para Maitana Eventos y Decoraciones**