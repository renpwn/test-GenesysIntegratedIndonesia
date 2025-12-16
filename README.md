Berikut **README.md versi siap pakai** (bisa langsung **copy–paste** ke GitHub **atau** kamu simpan sebagai file `README.md`).
Isinya sudah disesuaikan dengan hasil analisa project di dalam ZIP yang kamu upload.

---

```markdown
# Genesys Integrated Indonesia – Technical Test

Project ini merupakan **technical test** berbasis **Laravel** yang dikembangkan untuk kebutuhan **Genesys Integrated Indonesia**.  
Aplikasi ini menggunakan **Laravel Breeze**, **Tailwind CSS**, dan **Vite** sebagai stack utama.

---

## 📦 Tech Stack

- **Backend**: Laravel 10+
- **Frontend**: Blade + Tailwind CSS
- **Auth Scaffolding**: Laravel Breeze
- **Build Tool**: Vite
- **Database**: MySQL / MariaDB
- **Package Manager**:
  - PHP: Composer
  - JS: NPM

---

## 📁 Struktur Folder Utama

```

test-GenesysIntegratedIndonesia-main/
├── Coding/
│   ├── app/                # Core application logic
│   ├── bootstrap/          # Laravel bootstrap files
│   ├── config/             # Application configuration
│   ├── database/
│   │   ├── migrations/     # Database migrations
│   │   └── seeders/        # Database seeders
│   ├── public/             # Public assets
│   ├── resources/
│   │   ├── views/          # Blade templates
│   │   └── css/js          # Tailwind & JS resources
│   ├── routes/             # Web & API routes
│   ├── storage/            # Logs & cache
│   ├── tests/              # Feature & unit tests
│   ├── .env.example
│   ├── composer.json
│   ├── package.json
│   └── vite.config.js

````

---

## ⚙️ Instalasi & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/username/test-GenesysIntegratedIndonesia.git
cd test-GenesysIntegratedIndonesia/Coding
````

### 2️⃣ Install Dependency Backend

```bash
composer install
```

### 3️⃣ Install Dependency Frontend

```bash
npm install
```

### 4️⃣ Konfigurasi Environment

```bash
cp .env.example .env
php artisan key:generate
```

Sesuaikan konfigurasi database di file `.env`:

```env
DB_DATABASE=your_db_name
DB_USERNAME=your_db_user
DB_PASSWORD=your_db_password
```

### 5️⃣ Migrasi Database

```bash
php artisan migrate
```

Jika tersedia seeder:

```bash
php artisan db:seed
```

---

## ▶️ Menjalankan Aplikasi

### Jalankan Laravel Server

```bash
php artisan serve
```

### Jalankan Vite (Frontend)

```bash
npm run dev
```

Akses aplikasi melalui:

```
http://127.0.0.1:8000
```

---

## 🔐 Autentikasi

Project ini menggunakan **Laravel Breeze**, sehingga sudah tersedia fitur:

* Login
* Register
* Logout
* Reset Password
* Email Verification

Semua controller auth dapat ditemukan di:

```
app/Http/Controllers/Auth
```

---

## 🧪 Testing

```bash
php artisan test
```

---

## 📝 Catatan Teknis

* Menggunakan standar struktur Laravel
* Siap dikembangkan untuk CRUD, ERP module, atau REST API
* Frontend sudah mendukung **Tailwind CSS**
* Konfigurasi Vite sudah terintegrasi

---

## 📄 License

Project ini dibuat **khusus untuk keperluan technical test**.
Tidak diperuntukkan untuk penggunaan komersial tanpa izin.

---

## 👨‍💻 Author

**Technical Test – Genesys Integrated Indonesia**
Built with ❤️ using Laravel

```

---

### ✅ Opsi Selanjutnya
Kalau kamu mau, aku bisa:
- 🔹 Sesuaikan README untuk **ERP / Inventory System**
- 🔹 Tambahkan **API Documentation**
- 🔹 Buat **README versi HR / Non-Teknis**
- 🔹 Review kualitas kode & best practice Laravel
- 🔹 Tambahkan **badge GitHub (Laravel, PHP, License, dll)**

Tinggal bilang mau fokus ke arah mana 👍
```
