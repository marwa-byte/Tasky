<h1 align="center">Tasky 📝</h1>

<p align="center">A simple Laravel-based task manager built with PostgreSQL</p>

---

### 🚀 Features
- User registration & login
- Add, update, delete tasks
- Due dates & priorities
- Clean TailwindCSS interface

---

### ⚙️ Tech Stack
- Laravel 11
- PostgreSQL
- Tailwind CSS
- PHP 8.2+

---

### 🧪 Setup
```bash
git clone https://github.com/yourusername/tasky.git
cd tasky
composer install
cp .env.example .env
php artisan key:generate
# Set your DB config in .env
php artisan migrate
npm install && npm run dev
