# 🧾 Kanri - Audit Service

**Descripción:**  
Microservicio que registra todas las acciones importantes ejecutadas en el sistema por parte del administrador.

## 🚀 Tecnologías utilizadas
- Express.js
- TypeScript
- Prisma ORM
- PostgreSQL
- Zod
- Dotenv

## 🧱 Modelo principal
- `AuditLog`

## 📦 Comandos útiles

```bash
npm install
npx prisma generate
npx prisma migrate dev --name init
npm run dev

⚙️ .env de ejemplo
DATABASE_URL="postgresql://kanri:kanri123@localhost:5432/tu_bd?schema=public"
PORT=3004