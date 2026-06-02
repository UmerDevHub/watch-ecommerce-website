# ⌚ Watchify Store

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Railway](https://img.shields.io/badge/Deployed-Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Status](https://img.shields.io/badge/Status-Live-2ea44f?style=flat-square)

> A full-stack watch ecommerce platform with a customer storefront and a dedicated admin panel — built with Laravel and deployed on Railway.

🔗 **[Live Demo → watchifystore-production.up.railway.app](https://watchifystore-production.up.railway.app/home)**

---

## ✨ Features

### 🛍️ Customer Side
- Browse watch catalogue with product listings
- Product detail pages
- Add to cart and checkout flow
- User registration and login

### 🔧 Admin Panel
- Add, edit, and delete products (with validation)
- Manage orders and inventory
- Dashboard overview

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Laravel (PHP) |
| Frontend | Blade Templates, Bootstrap |
| Database | MySQL |
| Auth | Laravel Session Auth |
| Deployment | Railway + Nixpacks |

---

## 🚀 Run Locally

```bash
# Clone the repo
git clone https://github.com/UmerDevHub/watch-ecommerce-website.git
cd watch-ecommerce-website

# Install dependencies
composer install
npm install

# Setup environment
cp .env.example .env
php artisan key:generate

# Configure your DB in .env, then run migrations
php artisan migrate

# Start the server
php artisan serve
```

App runs at: `http://localhost:8000`

---

## 📂 Project Structure

```
watch-ecommerce-website/
├── app/            ← Models, Controllers, Middleware
├── resources/      ← Blade views (customer + admin)
├── routes/         ← web.php route definitions
├── database/       ← Migrations and seeders
├── public/         ← Assets (CSS, JS, images)
└── config/         ← App configuration
```

---

## 🔧 Planned Improvements

- [ ] Payment gateway integration
- [ ] Product search and filtering
- [ ] Order tracking for customers
- [ ] Responsive mobile layout
