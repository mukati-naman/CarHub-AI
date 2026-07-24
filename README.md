# 🚗 CarHub AI

An AI-powered full-stack car marketplace that helps users discover, search, and manage car listings through a fast, modern, and responsive web application.

---

## 📌 Overview

CarHub AI is built with Next.js and provides a complete car marketplace experience. Users can browse vehicles, search using AI, save favorite cars, and administrators can manage listings through a dedicated dashboard.

---

## ✨ Features

- 🔐 Secure user authentication with Clerk
- 🤖 AI-powered car search using Google Gemini
- 🚗 Browse and search car listings
- ❤️ Save favorite cars
- 📱 Fully responsive design
- 📊 Admin dashboard for managing cars
- ➕ Add, edit, and delete car listings
- ☁️ Image upload with Supabase Storage
- ⚡ Fast server-side rendering using Next.js
- 🛡️ Route protection with ArcJet

---

## 🛠️ Tech Stack

### Frontend
- Next.js
- React
- Tailwind CSS
- Shadcn UI

### Backend
- Next.js Server Actions
- Prisma ORM
- PostgreSQL (Supabase)

### Authentication
- Clerk

### AI
- Google Gemini API

### Database & Storage
- Supabase

### Security
- ArcJet

---

## 📂 Project Structure

```
app/
components/
hooks/
lib/
prisma/
public/
actions/
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/mukati-naman/CarHub-AI.git
```

### Install dependencies

```bash
npm install
```

### Configure environment variables

Create a `.env.local` file and add the required environment variables.

```env
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

GEMINI_API_KEY=

ARCJET_KEY=
```

### Run the development server

```bash
npm run dev
```

Open `http://localhost:3000` in your browser.

---

## 📸 Screenshots

Add screenshots of your application here.

- Home Page
- AI Search
- Car Details
- Admin Dashboard
- Favorites

---

## 🔮 Future Improvements

- Car comparison
- Advanced search filters
- AI price prediction
- Test drive booking
- Email notifications
- Payment integration

---

## 👨‍💻 Author

**Naman Mukati**

GitHub: https://github.com/mukati-naman
