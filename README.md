# task-manager
Pratikum Jobsheet 3
Aplikasi Manajemen Tugas dengan MongoDB dan Node.js
Ini adalah aplikasi sederhana Manajemen Tugas yang dibangun menggunakan Node.js dan MongoDB. Aplikasi ini memungkinkan Anda melakukan operasi CRUD (Create, Read, Update, Delete) pada data pengguna dan tugas menggunakan MongoDB sebagai basis data.

Prasyarat
Sebelum menjalankan aplikasi, pastikan Anda telah menginstal hal-hal berikut:

Node.js
MongoDB Community Server
Memulai
Klon repositori:
git clone https://github.com/username/repo.git
cd task-manager
Pasang dependensi:

bash
Copy code
npm install
Buat file konfigurasi bernama .env di root proyek dan berikan URL koneksi MongoDB. Contoh:
MONGODB_URI=mongodb://localhost:27017/task-manager
Ganti URL dengan string koneksi MongoDB Anda.

Jalankan aplikasi:
npm start
Aplikasi akan mulai, dan Anda dapat mengaksesnya di http://localhost:3000.

Penggunaan
Aplikasi Manajemen Tugas menyediakan endpoint untuk mengelola pengguna dan tugas. Anda dapat melakukan operasi CRUD menggunakan alat seperti Postman atau curl.

Endpoint Pengguna
Buat Pengguna: POST /users
Baca Pengguna: GET /users
Baca Pengguna berdasarkan ID: GET /users/:id
Perbarui Pengguna berdasarkan ID: PATCH /users/:id
Hapus Pengguna berdasarkan ID: DELETE /users/:id
Endpoint Tugas
Buat Tugas: POST /tasks
Baca Tugas: GET /tasks
Baca Tugas berdasarkan ID: GET /tasks/:id
Perbarui Tugas berdasarkan ID: PATCH /tasks/:id
Hapus Tugas berdasarkan ID: DELETE /tasks/:id
