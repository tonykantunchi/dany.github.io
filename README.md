# Ilarri – Plataforma de Acompañamiento Emocional y Psicología Clínica

## Descripción

**Ilarri** es una plataforma web diseñada para ofrecer acompañamiento emocional y servicios de psicología clínica. Su objetivo es proporcionar herramientas para el bienestar emocional, incluyendo **tests interactivos** que evalúan niveles de riesgo o estados emocionales, y almacenan los resultados de manera segura en una base de datos.

La aplicación cuenta con:

- **Frontend** desarrollado en **React**, enfocado en una experiencia intuitiva, accesible y visualmente calming.
- **Backend** desarrollado en **Python con Flask**, encargado de la lógica de negocio y la exposición de una API REST.
- **Base de datos PostgreSQL** para la persistencia segura de resultados.

---

## Funcionalidades Principales

- **Tests interactivos**
  - Chatbot o formulario guiado
  - Cálculo de promedios
  - Clasificación de niveles de riesgo
  - Resultados con colores y mensajes personalizados

- **Almacenamiento de resultados**
  - Registro en base de datos
  - IDs únicos y timestamps

- **Páginas principales**
  - Inicio
  - Sobre Nosotros
  - Servicios
  - Contacto
  - Consentimiento
  - Resultados

- **Protección de rutas**
  - Consentimiento informado obligatorio para secciones sensibles

- **Efectos visuales**
  - Fondos dinámicos con auras y gradientes
  - Animaciones suaves (experiencia calming)

---

## Tecnologías Usadas

### Frontend (React)

- React **v19.1.1**
- React Router
- Framer Motion
- Lucide React
- Tailwind CSS
- Axios
- Librerías adicionales:
  - React Icons
  - Web Vitals

### Backend (Flask)

- Python **3.9+**
- Flask
- SQLAlchemy (ORM)
- Psycopg2
- Pydantic (schemas, estilo FastAPI)
- Flask-CORS
- Dotenv

### Base de Datos

- **PostgreSQL**
- Configuración mediante `DATABASE_URL` en `.env`

### Otras Herramientas

- Venv (Python)
- NPM
- Tailwind CSS + PostCSS + Autoprefixer

---

## Requisitos Previos

### Frontend

- Node.js **v18.x** (recomendado con NVM)
- NPM o Yarn

### Backend

- Python **3.9+**
- Pip
- Venv
- PostgreSQL instalado y en ejecución
- Base de datos creada

---

## Instalación

### 1. Clonar el Repositorio

```bash
git clone https://github.com/tonykantunchi/ILARRI_WEB.git
cd ILARRI_WEB
