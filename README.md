# 🎬 Movie Ticket Booking System

A modern and responsive **Movie Ticket Booking System frontend** built with **React, TypeScript, Vite, Tailwind CSS, and shadcn/ui**.

The application provides a user-friendly interface for browsing movies, viewing movie details, selecting shows, and going through the movie ticket booking workflow. The project is designed to be connected with a backend/database service such as **Supabase** for authentication and data management.

---

## 🚀 Features

* 🎬 Browse available movies
* 🔎 Search and explore movies
* 📽️ View movie details
* 🎟️ Select movie shows
* 💺 Interactive seat selection
* 🧾 Booking and checkout interface
* 👤 User authentication support
* 📱 Fully responsive design
* 🌙 Dark mode support
* 🔔 Toast notifications
* ⚡ Fast and optimized Vite development environment
* 🧩 Reusable UI components
* 🔐 Supabase integration
* 📊 React Query for server-state management

---

## 🛠️ Tech Stack

### Frontend

* **React 18**
* **TypeScript**
* **Vite**
* **React Router DOM**

### UI & Styling

* **Tailwind CSS**
* **shadcn/ui**
* **Radix UI**
* **Lucide React**
* **Tailwind CSS Animate**

### Backend / Services

* **Supabase**

  * Authentication
  * Database
  * Backend services

### Forms & Validation

* **React Hook Form**
* **Zod**
* **@hookform/resolvers**

### State & Data Management

* **TanStack React Query**

## The project's package configuration includes React, React Router, Supabase, React Query, React Hook Form, Zod, Tailwind CSS, and several Radix UI components.

## 📂 Project Structure

```text
movie-ticket-booking/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── ui/
│   │   └── ...
│   │
│   ├── pages/
│   │   └── ...
│   │
│   ├── hooks/
│   │
│   ├── lib/
│   │
│   ├── main.tsx
│   └── ...
│
├── .env
├── components.json
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.js
├── tailwind.config.ts
├── tsconfig.json
├── vite.config.ts
└── README.md
```

The project uses the `@/*` alias to reference files inside the `src` directory.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone <YOUR_REPOSITORY_URL>
```

### 2. Navigate to the project

```bash
cd movie-ticket-booking
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the root directory:

```env
VITE_SUPABASE_PROJECT_ID=your_project_id
VITE_SUPABASE_PUBLISHABLE_KEY=your_publishable_key
VITE_SUPABASE_URL=your_supabase_url
```

> Never commit your `.env` file or private credentials to GitHub.

Your current project is configured to use Supabase environment variables.

### 5. Start the development server

```bash
npm run dev
```

The Vite configuration runs the development server on port **8080**.

Open:

```text
http://localhost:8080
```

---

## 📜 Available Scripts

| Command             | Description              |
| ------------------- | ------------------------ |
| `npm run dev`       | Start development server |
| `npm run build`     | Create production build  |
| `npm run build:dev` | Create development build |
| `npm run lint`      | Run ESLint               |
| `npm run preview`   | Preview production build |

These scripts are defined in the project's `package.json`.

---

## 🎨 UI & Styling

The project uses **Tailwind CSS** with **shadcn/ui** and Radix UI components for building the interface.

Tailwind is configured with:

* Responsive breakpoints
* Dark mode
* Poppins font
* Custom colors
* Custom animations
* Reusable design tokens
* Glow and shimmer effects

---

## 🔐 Supabase Configuration

The frontend uses the Supabase JavaScript client:

```text
@supabase/supabase-js
```

The project includes Supabase support in its dependencies.

Supabase can be used for:

* User authentication
* Movie data
* Theatre/show information
* Seat availability
* Bookings
* User profiles
* Booking history

---

## 🔄 Booking Flow

```text
Home
  ↓
Browse Movies
  ↓
Select Movie
  ↓
View Movie Details
  ↓
Select Theatre / Show
  ↓
Select Seats
  ↓
Review Booking
  ↓
Payment / Confirmation
  ↓
Booking Confirmation
```

---

## 📱 Responsive Design

The application is designed to work across:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📱 Tablet

Tailwind CSS responsive breakpoints are configured from `sm` through `2xl`.

---

## 🧪 Code Quality

ESLint is configured for:

* JavaScript/TypeScript
* React Hooks
* React Refresh
* TypeScript ESLint

Run linting with:

```bash
npm run lint
```

---

## 🚀 Production Build

Create the production build:

```bash
npm run build
```

Then preview it locally:

```bash
npm run preview
```

The project uses Vite's production build system.

---

## 🔮 Future Improvements

* 💳 Online payment gateway integration
* 🎫 Digital ticket generation
* 📧 Email booking confirmation
* 📱 QR code ticket
* 🏢 Multiple theatre management
* ⭐ Movie ratings and reviews
* ❤️ Wishlist / favorite movies
* 🔔 Booking reminders
* 📊 Admin dashboard
* 🎞️ Movie API integration
* 🗺️ Theatre location support

---

## 👨‍💻 Author

**Omm Abinash Barik**

B.Tech — Computer Science & Engineering (AI & ML)

---

## ⭐ Support

If you like this project, consider giving the repository a ⭐ on GitHub.

---

### 📌 Project Status

**Frontend:** 🚧 In Development

**Backend:** 🔌 Supabase Integration

**Deployment:** Ready for production deployment after environment configuration.
