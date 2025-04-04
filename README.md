# 🎬 Movie QR Code App

This is a full-stack web application that generates a QR code linking to a page displaying 10 random movies. The QR code regenerates every 10 seconds with a new set of movies. Built with **NestJS**, **PostgreSQL**, and **React**.

---

## 🚀 Features

- ⏱️ Generates a QR code every 10 seconds
- 🎥 Displays 10 random movies per QR code scan
- 🖼️ Shows movie titles and images
- 🌐 Deployed backend (NestJS + PostgreSQL) and frontend (React) on Render
- 📦 Seed movie data from a local JSON file

---

## 🛠️ Tech Stack

**Backend:**
- [NestJS](https://nestjs.com/)
- [TypeORM](https://typeorm.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Render](https://render.com/) (for deployment)

**Frontend:**
- [React](https://reactjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Axios](https://axios-http.com/)

---


---

## 🧪 Local Development

### 🧰 Backend

```bash
cd movies-qrcode-api
npm install

Create a .env file
DATABASE_URL=postgres://user:password@localhost:5432/movies_db

Run the backend
npm start

Seed the database
ts-node src/database/seeder.ts
```

### 💻 Frontend
```bash
cd movies-qrcode-client
npm install
npm start
```
