# -Human-Resource-Management-System-Sistema-de-Gesti-n-de-Recursos-Humanos
# 🏢 Human Resource Management System | Sistema de Gestión de Recursos Humanos

[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![NestJS](https://img.shields.io/badge/NestJS-10-e0234e?style=for-the-badge&logo=nestjs)](https://nestjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-6-47A248?style=for-the-badge&logo=mongodb)](https://mongodb.com/)
[![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql)](https://graphql.org/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript)](https://typescriptlang.org/)

> **EN**: A modern, full-stack Human Resource Management System built with cutting-edge technologies for efficient employee management.
> 
> **ES**: Un sistema moderno de gestión de recursos humanos full-stack construido con tecnologías de vanguardia para una gestión eficiente de empleados.

---

## 📖 Table of Contents | Tabla de Contenidos

- [🌟 Features | Características](#-features--características)
- [🛠️ Tech Stack | Stack Tecnológico](#️-tech-stack--stack-tecnológico)
- [⚡ Quick Start | Inicio Rápido](#-quick-start--inicio-rápido)
- [📦 Installation | Instalación](#-installation--instalación)
- [🎯 Usage | Uso](#-usage--uso)
- [🏗️ Project Structure | Estructura del Proyecto](#️-project-structure--estructura-del-proyecto)
- [🔧 API Documentation | Documentación de la API](#-api-documentation--documentación-de-la-api)
- [🧪 Testing | Pruebas](#-testing--pruebas)
- [🤝 Contributing | Contribución](#-contributing--contribución)
- [📄 License | Licencia](#-license--licencia)

---

## 🌟 Features | Características

### 🇺🇸 English
- **Employee Management**: Complete CRUD operations for employee records
- **Advanced Search & Filtering**: Real-time search by name, email, or position with department filtering
- **Responsive Design**: Modern UI that works seamlessly on desktop, tablet, and mobile devices
- **Real-time Updates**: Instant data synchronization using GraphQL subscriptions
- **Type Safety**: Full TypeScript implementation for robust development
- **Modern Architecture**: Clean, scalable architecture following best practices

### 🇪🇸 Español
- **Gestión de Empleados**: Operaciones CRUD completas para registros de empleados
- **Búsqueda y Filtrado Avanzado**: Búsqueda en tiempo real por nombre, email o posición con filtrado por departamento
- **Diseño Responsivo**: Interfaz moderna que funciona perfectamente en escritorio, tablet y dispositivos móviles
- **Actualizaciones en Tiempo Real**: Sincronización instantánea de datos usando suscripciones GraphQL
- **Seguridad de Tipos**: Implementación completa de TypeScript para un desarrollo robusto
- **Arquitectura Moderna**: Arquitectura limpia y escalable siguiendo las mejores prácticas

---

## 🛠️ Tech Stack | Stack Tecnológico

### Frontend
- **[Next.js 14](https://nextjs.org/)** - React framework with App Router
- **[TypeScript](https://typescriptlang.org/)** - Type-safe JavaScript
- **[TailwindCSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Apollo Client](https://apollographql.com/client)** - GraphQL client with caching

### Backend
- **[NestJS](https://nestjs.com/)** - Progressive Node.js framework
- **[GraphQL](https://graphql.org/)** - Query language for APIs
- **[Apollo Server](https://apollographql.com/server)** - GraphQL server
- **[MongoDB](https://mongodb.com/)** - NoSQL database
- **[Mongoose](https://mongoosejs.com/)** - MongoDB object modeling

### Development Tools
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Class Validator** - DTO validation
- **Jest** - Testing framework


---

## ⚡ Quick Start | Inicio Rápido

### 🇺🇸 English

```bash
# Clone the repository
git clone https://github.com/Flaticon/Human-Resource-Management-System-Sistema-de-Gesti-n-de-Recursos-Humanos
cd Human-Resource-Management-System-Sistema-de-Gesti-n-de-Recursos-Humanos

# Install and run backend
cd  hrm-backend
npm install
npm run seed      # Populate database with sample data
npm run start:dev # Start backend server

# In a new terminal, install and run frontend
cd ../hrm-frontend
npm install
npm run dev       # Start frontend server
```

### 🇪🇸 Español

```bash
# Clonar el repositorio
git clone https://github.com/yourusername/hrm-system.git
cd hrm-system

# Instalar y ejecutar backend
cd hrm-backend
npm install
npm run seed      # Poblar base de datos con datos de ejemplo
npm run start:dev # Iniciar servidor backend

# En una nueva terminal, instalar y ejecutar frontend
cd ../hrm-frontend
npm install
npm run dev       # Iniciar servidor frontend
```

**🌐 Access the application at | Accede a la aplicación en:** `http://localhost:3000`

---

## 📦 Installation | Instalación

### Prerequisites | Prerrequisitos

- **Node.js** >= 18.0.0
- **MongoDB** >= 6.0.0
- **npm** or **yarn**

### 🇺🇸 Detailed Setup

<details>
<summary>Click to expand detailed installation steps</summary>

#### 1. Database Setup
```bash
# Install MongoDB (macOS)
brew tap mongodb/brew
brew install mongodb-community

# Start MongoDB
brew services start mongodb-community

# Verify MongoDB is running
mongosh
```

#### 2. Backend Setup
```bash
cd hrm-backend

# Install dependencies
npm install

# Environment setup (optional)
cp .env.example .env

# Seed database with sample data
npm run seed

# Start development server
npm run start:dev
```

#### 3. Frontend Setup
```bash
cd hrm-frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

</details>

### 🇪🇸 Configuración Detallada

<details>
<summary>Haz clic para expandir los pasos de instalación detallados</summary>

#### 1. Configuración de Base de Datos
```bash
# Instalar MongoDB (macOS)
brew tap mongodb/brew
brew install mongodb-community

# Iniciar MongoDB
brew services start mongodb-community

# Verificar que MongoDB está funcionando
mongosh
```

#### 2. Configuración del Backend
```bash
cd hrm-backend

# Instalar dependencias
npm install

# Configuración de entorno (opcional)
cp .env.example .env

# Poblar base de datos con datos de ejemplo
npm run seed

# Iniciar servidor de desarrollo
npm run start:dev
```

#### 3. Configuración del Frontend
```bash
cd hrm-frontend

# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev
```

</details>

---

## 🎯 Usage | Uso

### 🇺🇸 English

1. **View Employees**: Browse the complete employee list with search and filter capabilities
2. **Add Employee**: Click "Add Employee" to create new employee records
3. **Employee Details**: Click on any employee row to view detailed information
4. **Delete Employee**: Use the delete button to remove employees from the system
5. **Search & Filter**: Use the search bar and department filter for quick navigation

### 🇪🇸 Español

1. **Ver Empleados**: Navega por la lista completa de empleados con capacidades de búsqueda y filtro
2. **Agregar Empleado**: Haz clic en "Agregar Empleado" para crear nuevos registros de empleados
3. **Detalles del Empleado**: Haz clic en cualquier fila de empleado para ver información detallada
4. **Eliminar Empleado**: Usa el botón eliminar para quitar empleados del sistema
5. **Buscar y Filtrar**: Usa la barra de búsqueda y el filtro de departamento para navegación rápida

---

## 🏗️ Project Structure | Estructura del Proyecto

```
hrm-system/
├── hrm-backend/                 # NestJS Backend
│   ├── src/
│   │   ├── employees/
│   │   │   ├── employee.schema.ts      # MongoDB Schema
│   │   │   ├── employee.types.ts       # GraphQL Types
│   │   │   ├── employees.service.ts    # Business Logic
│   │   │   ├── employees.resolver.ts   # GraphQL Resolver
│   │   │   └── employees.module.ts     # NestJS Module
│   │   ├── app.module.ts
│   │   └── main.ts
│   ├── scripts/
│   │   └── seed.js                     # Database Seeding
│   └── package.json
├── hrm-frontend/               # Next.js Frontend
│   ├── app/
│   │   ├── layout.tsx                  # Root Layout
│   │   ├── page.tsx                    # Home Page
│   │   └── globals.css                 # Global Styles
│   ├── components/
│   │   ├── EmployeeList.tsx            # Employee List Component
│   │   ├── EmployeeForm.tsx            # Employee Form Component
│   │   └── EmployeeModal.tsx           # Modal Component
│   ├── lib/
│   │   ├── apollo.ts                   # Apollo Client Config
│   │   ├── apollo-wrapper.tsx          # Apollo Provider
│   │   └── graphql/
│   │       └── queries.ts              # GraphQL Queries
│   ├── types/
│   │   └── employee.ts                 # TypeScript Types
│   └── package.json
└── README.md
```

---

## 🔧 API Documentation | Documentación de la API

### GraphQL Endpoints

**🌐 GraphQL Playground:** `http://localhost:4000/graphql`

<details>
<summary>📋 Available Operations | Operaciones Disponibles</summary>

#### Queries
```graphql
# Get all employees
query {
  employees {
    id
    firstName
    lastName
    email
    position
    department
    salary
    status
  }
}

# Get employee by ID
query {
  employee(id: "employee_id") {
    id
    firstName
    lastName
    # ... other fields
  }
}

# Get employees by department
query {
  employeesByDepartment(department: "Technology") {
    id
    firstName
    lastName
    position
  }
}
```

#### Mutations
```graphql
# Create new employee
mutation {
  createEmployee(createEmployeeInput: {
    firstName: "John"
    lastName: "Doe"
    email: "john.doe@company.com"
    position: "Software Engineer"
    department: "Technology"
    salary: 75000
    hireDate: "2024-01-15"
  }) {
    id
    firstName
    lastName
  }
}

# Update employee
mutation {
  updateEmployee(
    id: "employee_id"
    updateEmployeeInput: {
      salary: 80000
      position: "Senior Software Engineer"
    }
  ) {
    id
    salary
    position
  }
}

# Delete employee
mutation {
  removeEmployee(id: "employee_id") {
    id
    firstName
    lastName
  }
}
```

</details>

---

## 🧪 Testing | Pruebas

### 🇺🇸 Running Tests

```bash
# Backend tests
cd hrm-backend
npm run test
npm run test:e2e
npm run test:cov

# Frontend tests
cd hrm-frontend
npm run test
npm run test:watch
```

### 🇪🇸 Ejecutar Pruebas

```bash
# Pruebas del backend
cd hrm-backend
npm run test
npm run test:e2e
npm run test:cov

# Pruebas del frontend
cd hrm-frontend
npm run test
npm run test:watch
```

---

## 🤝 Contributing | Contribución

### 🇺🇸 English

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

### 🇪🇸 Español

¡Damos la bienvenida a las contribuciones! Por favor, sigue estos pasos:

1. Haz un fork del repositorio
2. Crea una rama de característica (`git checkout -b feature/caracteristica-increible`)
3. Confirma tus cambios (`git commit -m 'Agregar característica increíble'`)
4. Sube la rama (`git push origin feature/caracteristica-increible`)
5. Abre un Pull Request

Por favor, lee nuestras [Guías de Contribución](CONTRIBUTING.md) para más detalles.

---

## 👨‍💻 Author | Autor

**Your Name | Tu Nombre**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com

---

## 🙏 Acknowledgments | Agradecimientos

- **NestJS Team** for the amazing framework
- **Vercel Team** for Next.js
- **MongoDB Team** for the database solution
- **TailwindCSS Team** for the utility-first CSS framework
- **Apollo GraphQL Team** for the GraphQL implementation

---

## 📈 Roadmap

- [ ] 🔐 Authentication & Authorization
- [ ] 📊 Analytics Dashboard
- [ ] 📄 PDF Report Generation
- [ ] 📧 Email Notifications
- [ ] 🔄 Employee History Tracking
- [ ] 📱 Mobile App (React Native)
- [ ] 🌐 Multi-language Support
- [ ] 🎨 Theme Customization

---

## 📄 License | Licencia

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

---

<div align="center">

### 🌟 If you found this project helpful, please give it a star! | ¡Si este proyecto te fue útil, por favor dale una estrella!

[![GitHub stars](https://img.shields.io/github/stars/yourusername/hrm-system?style=social)](https://github.com/yourusername/hrm-system/stargazers)

**Made with ❤️ by [Your Name] | Hecho con ❤️ por [Tu Nombre]**

</div>