# Praktikum 5: JavaScript Dasar dan Manipulasi HTML

**Nama:** Nabila Lutfia Sari  
**NIM:** 312510040  
**Kelas:** TIA25A Mata Kuliah: Pemrograman Web  

---

## Deskripsi Praktikum

Praktikum ini membahas tentang dasar-dasar pemrograman JavaScript, penggunaan variabel, operator, fungsi, percabangan kondisi, manipulasi elemen HTML (DOM), serta penanganan event interaksi form[cite: 1].

---

## Struktur File Repositori

```text
Lab5Web/
├── index.html          # Halaman utama HTML dan form interaktif
├── script.js           # File logika JavaScript eksternal
├── screenshots/        # Folder bukti tangkapan layar (SS)
└── README.md           # Laporan praktikum

```
---

# Laporan Langkah-Langkah Praktikum Pemrograman Web

## 1. Persiapan Awal Folder Kerja

* Membuat folder proyek baru bernama **`Lab5Web`** di komputer.
* Menyiapkan file dasar **`index.html`** dan **`script.js`** di dalam folder tersebut.
* Menghubungkan file JavaScript eksternal menggunakan tag `<script src="script.js"></script>` pada dokumen HTML.

---

## 2. Rincian Latihan Praktikum

### Latihan 1: Menampilkan Output

* Menggunakan `document.getElementById("pesan").textContent` untuk mengubah teks pada elemen HTML secara dinamis.
* Menggunakan `console.log("Hello World")` untuk mencetak teks debug ke dalam Console browser.
* Bukti screenshots:

<img width="335" height="134" alt="Screenshot 2026-10-24 155122" src="https://github.com/user-attachments/assets/10190a13-616a-475e-99ad-3ed1181b2358" />

### Latihan 2: Dialog Alert dan Prompt

* Menerima input data string dinamis dari pengguna menggunakan fungsi `prompt()`.
* Menampilkan pop-up notifikasi sambutan menggunakan fungsi `alert()`.
* Bukti screensots:

<img width="330" height="125" alt="Screenshot 2026-10-24 155320" src="https://github.com/user-attachments/assets/749172b0-9a4e-432a-824f-738285ee046b" />

### Latihan 3: Function dan Operasi Aritmetika

* Membuat fungsi JavaScript berparameter untuk melakukan perhitungan aritmetika dasar: **penjumlahan**, **pengurangan**, **perkalian**, **pembagian**, dan **modulus**.
* Bukti screenshots:
  
<img width="959" height="464" alt="Screenshot 2026-10-24 155923" src="https://github.com/user-attachments/assets/d98bda0f-a9fa-4a90-8951-1361217ed27d" />


### Latihan 4 & 5: Seleksi Kondisi (If-Else & Switch)

* Menerapkan struktur percabangan `if-else` untuk memvalidasi nilai angka mahasiswa (rentang 0-100).
* Menerapkan seleksi kondisi `switch` untuk memilih opsi menu berdasarkan angka 1 sampai 5.
* Bukti screenshots:
  
<img width="959" height="146" alt="Screenshot 2026-10-24 160030" src="https://github.com/user-attachments/assets/df45e630-b152-4931-a6f3-0f38dab20562" />

<img width="335" height="117" alt="Screenshot 2026-10-24 160040" src="https://github.com/user-attachments/assets/ef140ad6-b601-4db7-9ebe-2c280f1a16d9" />

<img width="335" height="139" alt="Screenshot 2026-10-24 160201" src="https://github.com/user-attachments/assets/29681897-c4b1-4abb-a8dd-e6b67787c6dd" />

<img width="329" height="115" alt="Screenshot 2026-10-24 160209" src="https://github.com/user-attachments/assets/25756401-77ec-4406-b49e-337f4a39d63f" />


### Latihan 6: Cek Bilangan Genap atau Ganjil

* Membuat form input angka pada HTML yang dihubungkan dengan fungsi JavaScript untuk mendeteksi apakah suatu bilangan bernilai **genap** atau **ganjil**.
* Bukti screeshost:
  
<img width="324" height="176" alt="Screenshot 2026-10-24 160520" src="https://github.com/user-attachments/assets/33b1a824-75e4-48fe-a9b4-02708adc02d6" />


### Latihan 7: Mengubah Warna Background

* Membuat tombol interaktif dengan atribut `onclick` yang memanggil fungsi berparameter untuk mengubah warna latar belakang halaman web secara dinamis.
* Bukti screenshots:
  
<img width="323" height="263" alt="Screenshot 2026-10-24 160658" src="https://github.com/user-attachments/assets/2daa29d0-bf42-4820-bf64-989c54ab0250" />


### Latihan 8: Manipulasi DOM Checkbox Menu Makanan

* Menggunakan `document.querySelectorAll(".menu")` untuk mendeteksi status centang pada elemen checkbox.
* Menghitung total harga makanan secara otomatis setiap kali pilihan menu dicentang.
* Bukti screenshots:
  
<img width="323" height="263" alt="Screenshot 2026-10-24 160658 - Copy" src="https://github.com/user-attachments/assets/eef4b8a1-648f-41f7-87da-db942a3d43c8" />


### Mini Project: Kalkulator Nilai Mahasiswa

* Membuat aplikasi form kalkulator nilai yang mengkalkulasikan komponen nilai: **Tugas (30%)**, **UTS (30%)**, dan **UAS (40%)**.
* Menampilkan nilai akhir, konversi huruf predikat (**A-E**), serta status kelulusan secara otomatis ke halaman web.
* Bukti screenshots:
  
<img width="224" height="416" alt="Screenshot 2026-10-24 162001" src="https://github.com/user-attachments/assets/e5cdd807-1b68-4dcc-aab6-effdf3bc0f01" />

---

## 3. Daftar Bukti Tangkapan Layar (Screenshot)

Berikut adalah tabel referensi untuk melampirkan bukti tangkapan layar (SS) dari setiap bagian praktikum:

| Bagian Praktikum | Bukti Tangkapan Layar (SS) |
| --- | --- |
| **Latihan 1 - 3** (Output & Console) | `[ ________________________ ]` |
| **Latihan 4 - 5** (Percabangan) | `[ ________________________ ]` |
| **Latihan 6** (Genap / Ganjil) | `[ ________________________ ]` |
| **Latihan 7** (Ubah Warna) | `[ ________________________ ]` |
| **Latihan 8** (Checkbox Menu) | `[ ________________________ ]` |
| **Mini Project** (Kalkulator Nilai) | `[ ________________________ ]` |
