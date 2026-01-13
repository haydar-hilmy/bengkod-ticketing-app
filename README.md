# 🎟️ Laravel 12 – Ticketing System (Non-Payment)

Sistem Ticketing Konser Berbasis Web (Non-Payment) adalah aplikasi simulasi pemesanan tiket konser yang dibangun menggunakan **Laravel 12**.  
Aplikasi ini dirancang untuk memahami dan mengimplementasikan alur bisnis ticketing, pengelolaan data konser, serta penerapan arsitektur **MVC (Model–View–Controller)**.

Pada sistem ini, pengguna dapat memesan tiket tanpa melalui proses pembayaran. Setiap pemesanan akan langsung tercatat dalam riwayat pembelian.

---

## 📌 Fitur Utama

### 👤 User
- Melihat daftar konser yang tersedia
- Melihat detail konser
- Memesan tiket konser
- Melihat riwayat pemesanan

### 🛠️ Admin
- Mengelola data konser (CRUD)
- Mengelola kategori konser
- Melihat daftar pemesanan tiket

---

## 🧱 Teknologi yang Digunakan

- **Laravel 12**
- **PHP 8+**
- **MySQL / MariaDB**
- **Blade Template Engine**
- **Bootstrap / Tailwind CSS** (opsional)
- **XAMPP / Laragon** (untuk development)

---

## 📂 Struktur Proyek (MVC)

Proyek ini menggunakan struktur standar Laravel:

- **Model**  
  Untuk mengelola data seperti `Concert`, `Category`, dan `Order`

- **View**  
  Menggunakan Blade untuk menampilkan UI ke pengguna

- **Controller**  
  Mengatur alur logika bisnis antara Model dan View

---

## ⚙️ Cara Instalasi

1. Clone repository:
```bash
git clone https://github.com/username/laravel-ticketing.git
cd laravel-ticketing
````

2. Install dependency:

```bash
composer install
```

3. Copy file environment:

```bash
cp .env.example .env
```

4. Generate app key:

```bash
php artisan key:generate
```

5. Atur koneksi database di file `.env`

6. Jalankan migrasi:

```bash
php artisan migrate
```

7. Jalankan server:

```bash
php artisan serve
```

Akses aplikasi di:

```
http://localhost:8000
```

---

## 🧪 Data Dummy (Opsional)

Jika tersedia seeder:

```bash
php artisan db:seed
```

---

## 🎯 Tujuan Proyek

Proyek ini dibuat untuk:

* Mempelajari alur sistem ticketing konser
* Memahami konsep CRUD
* Menerapkan arsitektur MVC di Laravel
* Mengelola relasi data antar tabel

---

## 📜 Lisensi

Proyek ini bersifat edukatif dan bebas digunakan untuk pembelajaran.

---