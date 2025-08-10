# MadeInIran – Production Line Online Store

**My first freelance project as a full-stack developer.**  
MadeInIran is a **production line ecommerce platform** built with **Laravel** (API backend) and **Nuxt.js** (frontend) to showcase and sell products manufactured in Iran.

🔗 **Frontend Repository:** [madeiniran-onlineStore](https://github.com/fatemesoleymanian/madeiniran-onlineStore)  
🔗 **Backend Repository (this):** [MadeInIran_Api](https://github.com/fatemesoleymanian/OnlineStore_madeInIran_Api)

---

## 📌 Features

### 🛒 Storefront
- Browse products by category, department, or tags
- Search with live suggestions
- Product details with images, states, models, and FAQs
- Blog with categories, tags, and comments
- Customer testimonials
- Campaign forms & newsletters
- Responsive design for desktop & mobile

### 👤 User Features
- Register, login, and password recovery (via SMS using Kavenegar)
- Manage personal account details
- Bookmark products
- Add items to cart and place orders
- View order history

### 🛠 Admin Panel
- Manage products, categories, departments, and product states/models
- Manage blogs, comments, tags, and sliders
- Role & permission management
- Order and transaction management
- Customer management
- Notifications system for admins

### 💳 Payment & Transactions
- Integrated with **Shetabit/Multipay** for handling multiple payment gateways
- Order processing flow with multiple steps
- Transaction verification

---

## 🛠️ Tech Stack

**Backend (API)**
- [Laravel 9](https://laravel.com/) – PHP Framework
- [Laravel Sanctum](https://laravel.com/docs/sanctum) – API authentication
- [Kavenegar](https://kavenegar.com/) – SMS verification
- [Shetabit/Multipay](https://github.com/shetabit/multipay) – Payment gateway integration
- [Spatie Laravel Sitemap](https://github.com/spatie/laravel-sitemap) – SEO sitemap generation
- MySQL – Relational database

**Frontend**
- [Nuxt.js 2](https://nuxtjs.org/) – Vue.js framework
- [Bootstrap 5](https://getbootstrap.com/) – Styling & layout
- [Vue Awesome Swiper](https://github.com/surmon-china/vue-awesome-swiper) – Sliders
- [Nuxt Video Player](https://www.npmjs.com/package/nuxt-video-player) – Video integration
- [Vue Notifications](https://github.com/euvl/vue-notification) – User notifications
- [Vuex Persisted State](https://www.npmjs.com/package/vuex-persistedstate) – Cart & session persistence

---

## 🚀 Getting Started

### 1️⃣ Clone the repositories
**Backend**
```bash
git clone https://github.com/fatemesoleymanian/OnlineStore_madeInIran_Api.git
cd OnlineStore_madeInIran_Api
````

**Frontend**

```bash
git clone https://github.com/fatemesoleymanian/madeiniran-onlineStore.git
cd madeiniran-onlineStore
```

---

### 2️⃣ Backend Setup (Laravel)

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

* Configure `.env` for database, Kavenegar API key, and payment gateways.

---

### 3️⃣ Frontend Setup (Nuxt.js)

```bash
npm install
npm run dev
```

* Update API base URL in `nuxt.config.js` or Axios config.

## 📜 License

This project is licensed under the **MIT License**.

---

**Developed by Fateme Soleymanian**
💻 Full-stack Laravel & Vue/Nuxt developer.

