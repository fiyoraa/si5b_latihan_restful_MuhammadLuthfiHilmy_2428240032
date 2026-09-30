# Latihan RESTful API Express.js - Data Mahasiswa

Latihan menggunakan **Node.js** dan **Express.js** untuk melakukan operasi CRUD (Create, Read, Update, Delete) pada data mahasiswa.

## Tech Stack
* **Node.js**
* **Express.js**
* **Nodemon** (Development)

## Endpoint API
* `GET /mahasiswa` — Mengambil semua data mahasiswa
* `GET /mahasiswa/:id` — Mengambil data mahasiswa berdasarkan ID
* `POST /mahasiswa` — Menambahkan data mahasiswa baru
* `PUT /mahasiswa/:id` — Memperbarui data mahasiswa berdasarkan ID
* `DELETE /mahasiswa/:id` — Menghapus data mahasiswa berdasarkan ID

## Cara Menjalankan
1. **Clone repositori & masuk ke direktori:**
   ```bash
   git clone <URL_REPOSITORY>
   cd restful-api-app
   ```
2. **Install dependensi:**
   ```bash
   npm install
   ```
3. **Jalankan server:**
   ```bash
   npm run dev
   ```
   *Server akan berjalan di `http://localhost:3000`*
