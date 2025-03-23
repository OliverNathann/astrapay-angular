# Astrapay Angular Frontend

Aplikasi frontend Angular untuk proyek **Astrapay**. Proyek ini dikembangkan menggunakan **Angular** dan berfungsi sebagai antarmuka pengguna untuk backend yang menangani data.

---

## 📥 Clone Repository

Untuk mulai menggunakan proyek ini, lakukan **clone repository** ke dalam komputer Anda menggunakan perintah berikut:

```sh
git clone -b master https://github.com/OliverNathann/astrapay-angular.git
cd astrapay-angular
```

---

## 🚀 Instalasi

### **1️⃣ Pastikan Node.js Terinstal**
Pastikan Anda telah menginstal **Node.js** versi terbaru atau kompatibel dengan Angular. Cek versi dengan:

```sh
node -v
```

Jika belum terinstal, silakan download dan install Node.js dari [Node.js Official Website](https://nodejs.org/).

### **2️⃣ Install Angular CLI**
Jika belum memiliki **Angular CLI**, install dengan perintah berikut:

```sh
npm install -g @angular/cli
```

Untuk memastikan Angular CLI sudah terinstal dengan benar:

```sh
ng version
```

### **3️⃣ Install Dependencies**
Setelah memastikan semua alat yang diperlukan sudah tersedia, jalankan perintah berikut untuk menginstal semua dependencies yang dibutuhkan proyek ini:

```sh
npm install
```

---

## 🚀 Menjalankan Aplikasi

Untuk menjalankan aplikasi dalam mode **development**, gunakan perintah berikut:

```sh
ng serve
```

Aplikasi akan berjalan di **`http://localhost:4200/`** secara default.  
Jika ingin menggunakan port lain, jalankan:

```sh
ng serve --port=4300
```

---

## 🔧 Konfigurasi API

Jika frontend ini membutuhkan koneksi ke backend, pastikan **URL API** sudah dikonfigurasi dengan benar di dalam file **`environment.ts`**:

- **Lokasi:** `src/environments/environment.ts`
- **Contoh Konfigurasi API:**
  ```typescript
  export const environment = {
    production: false,
    apiUrl: 'http://localhost:8000/api' // Ubah sesuai backend
  };
  ```

Pastikan backend **Spring Boot** berjalan di **port yang sesuai** agar komunikasi antara frontend dan backend tidak mengalami masalah.

---

## 📦 Dependencies yang Digunakan

Berikut adalah beberapa dependencies utama yang digunakan dalam proyek ini:

### **📌 Dependencies Utama**
| Package               | Deskripsi |
|-----------------------|--------------------------------------------------|
| `@angular/core`       | Framework utama Angular |
| `@angular/router`     | Routing untuk navigasi antar halaman |
| `@angular/common`     | Modul dasar Angular |
| `rxjs`               | Reactive Extensions Library untuk Angular |
| `zone.js`            | Patch untuk tracking async operations |

### **📌 Dependencies Tambahan**
| Package               | Deskripsi |
|-----------------------|--------------------------------------------------|
| `bootstrap`           | Framework UI untuk styling |
| `ngx-toastr`         | Notifikasi pop-up di aplikasi |
| `@angular/forms`     | Modul untuk form handling |
| `@angular/http`      | HTTP client untuk komunikasi dengan backend |

Anda dapat melihat daftar lengkap dependencies dengan:

```sh
npm list --depth=0
```

---

## 🛠 Fitur yang Tersedia

✅ Menampilkan daftar catatan  
✅ Menambahkan catatan baru  
✅ Menghapus catatan  
✅ Integrasi dengan backend menggunakan **HttpClient**  
✅ Navigasi antar halaman dengan **Angular Router**  

---

## 📌 Struktur Folder

Berikut adalah struktur folder utama dalam proyek ini:

```
/astrapay-angular
│── src/
│   │── app/
│   │   │── components/       # Folder komponen Angular
│   │   │   │── notes-list/   # Komponen daftar catatan
│   │   │   │── note-form/    # Komponen formulir catatan
│   │   │── services/         # Service untuk komunikasi API
│   │   │── app.module.ts     # Modul utama Angular
│   │   │── app-routing.module.ts # Routing aplikasi
│   │── assets/               # Gambar, ikon, dll.
│   │── environments/         # Konfigurasi lingkungan (dev/prod)
│── angular.json              # Konfigurasi proyek Angular
│── package.json              # Daftar dependencies dan skrip
│── README.md                 # Dokumentasi proyek
```

---


## 📞 Kontak dan Bantuan

Jika Anda mengalami masalah atau memiliki pertanyaan, silakan hubungi:

- **GitHub:** [OliverNathann](https://github.com/OliverNathann)
- **Email:** example@email.com
- **Diskusi & Isu:** [GitHub Issues](https://github.com/OliverNathann/astrapay-angular/issues)

---

## 🎉 Terima Kasih! 🎉

Terima kasih telah menggunakan **Astrapay Angular Frontend**! Jika proyek ini bermanfaat, jangan lupa untuk memberikan **⭐ Star** di repository ini. 🚀

---

