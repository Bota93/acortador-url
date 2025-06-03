# 🔗 Acortador de URLs

Proyecto creado con Next.js, TypeScript, Docker y PostgreSQL para acortar URLs y hacer seguimiento de clics.

---

## 🧰 Tecnologías usadas

- [Next.js](https://nextjs.org/) + React
- [TypeScript](https://www.typescriptlang.org/)
- [Prisma ORM](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Docker + Docker Compose](https://docs.docker.com/compose/)
- [Tailwind CSS](https://tailwindcss.com/) (opcional)

---

## 🚀 Instrucciones para levantar el proyecto (desarrollo)

### 1. Clona el repositorio

```bash
git clone https://github.com/TU_USUARIO/acortador-url.git
cd acortador-url
git checkout desarrollo
```

### 2. Instala dependencias

```bash
npm install
```

### 3. Configura las variables de entorno

Crea un archivo `.env` en la raíz con el siguiente contenido:

```
DATABASE_URL=postgres://postgres:postgres@db:5432/acortador
```

### 4. Levanta los contenedores Docker

```bash
docker-compose up -d
```

Esto iniciará el servidor de PostgreSQL y la app de Next.js.

### 5. Aplica la migración de base de datos

```bash
npx prisma migrate dev --name init
```

### 6. Abre el navegador

Visita: [http://localhost:3000](http://localhost:3000)

---

## 🧱 Estructura inicial del proyecto

- `/pages` → Páginas Next.js
- `/pages/api` → Endpoints backend
- `/prisma/schema.prisma` → Definición de la base de datos
- `docker-compose.yml` → Configuración de Docker

---

## 📌 Estado del desarrollo

✔️ Estructura base  
✔️ Git conectado  
⬜ Endpoints API  
⬜ Redirección por slug  
⬜ Estadísticas de clics

---

## ✍️ Autor

Adrián – Proyecto DAM Freelance
