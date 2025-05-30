# Vancouver Camp Radar

**Find the perfect summer camp for your child in Vancouver — powered by Laravel and GPT.**

This is a lightweight Laravel 11-based MVP that helps parents discover local summer camps tailored to their child’s age, interests, location, and budget.

---

## Features

- Simple form for child age, location, interest, and budget
- GPT-powered camp recommendations via OpenAI
- Built with Laravel 11, Vite, and Tailwind CSS
- PostgreSQL via Railway integration
- Modular GPT integration via Laravel service class

---

## Tech Stack

- **Backend:** Laravel 11 (PHP 8.2+)
- **Frontend:** Blade, Tailwind CSS, Vite
- **AI:** OpenAI GPT-4 (via API)
- **Database:** PostgreSQL (Railway or local)
- **Hosting:** Railway (auto-deploy via GitHub)
- **Dev Tools:** Composer, NPM, Laravel Sail, GitHub Codespaces

---

## 🧑‍💻 Local Development

### 1. Clone & Install

```bash
git clone https://github.com/cranch6699/vancouver-camp-radar.git
cd vancouver-camp-radar
composer install
npm install
cp .env.example .env
php artisan key:generate