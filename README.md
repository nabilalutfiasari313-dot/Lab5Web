# Praktikum 5: JavaScript Dasar dan Manipulasi HTML

**Nama:** Nabila Lutfia Sari  
**NIM:** 312510040  
**Kelas:** TIA25A 
**Mata Kuliah:** Pemrograman Web  

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

### Eksperimen Mandiri
1. Ubah Latihan 3 agar menerima dua nilai dari prompt dan mengonversinya menjadi number.
Bukti screenshots:
<img width="326" height="178" alt="Screenshot 2026-10-25 144932" src="https://github.com/user-attachments/assets/ac34e169-3590-4299-a51e-89134a86a3b9" />

7. Buat perulangan untuk menampilkan tabel perkalian angka 7 dari 1 sampai 10.
Bukti screenshots:
<img width="152" height="269" alt="Screenshot 2026-10-25 145004" src="https://github.com/user-attachments/assets/f2b8bf0a-b3a6-45a1-bcb3-5614084b3402" />

9. Buat function cekGenap(angka) yang mengembalikan true jika angka genap.
Bukti screenshots:
<img width="206" height="89" alt="Screenshot 2026-10-25 145020" src="https://github.com/user-attachments/assets/9c22477d-aae0-4fba-9824-0c3e9bf6b099" />

11. Tambahkan validasi form agar kolom tidak boleh kosong.
Bukti screenshots:
<img width="206" height="115" alt="Screenshot 2026-10-25 145035" src="https://github.com/user-attachments/assets/cd8fa75d-feb1-4606-8855-1ea7ef0a3bd4" />

13. Ubah Latihan 8 dengan menambah minimal dua pilihan menu dan harga.
Bukti screenshots:
<img width="365" height="219" alt="Screenshot 2026-10-25 164828" src="https://github.com/user-attachments/assets/ff256654-16ed-4811-96c1-b720364811d5" />

15. Gunakan tombol untuk menyembunyikan atau menampilkan elemen HTML.
Bukti screenshots:
<img width="332" height="122" alt="Screenshot 2026-10-25 164835" src="https://github.com/user-attachments/assets/0d7d211a-ff17-4434-8b42-609277d44993" />

<img width="323" height="98" alt="Screenshot 2026-10-25 164842" src="https://github.com/user-attachments/assets/d288eb8c-055c-43c0-927d-c5987d199514" />


### **Pertanyaan dan Tugas**
**1. Jelaskan perbedaan `console.log()`, `alert()`, `prompt()`, dan `textContent`/`innerHTML`?**

Jawaban: 

**`console.log()`**: Digunakan untuk mencetak pesan/debugging ke tab Console di browser agar tidak tampil di halaman utama.

**`alert()`**: Memunculkan kotak dialog pop-up peringatan atau informasi singkat kepada pengguna.

**`prompt()`**: Memunculkan kotak dialog interaktif untuk meminta masukan (input teks) dari pengguna.

**`textContent` / `innerHTML**`: Digunakan untuk mengubah teks atau konten elemen HTML secara dinamis di dalam dokumen web.


**2. Apa perbedaan `let` dan `const`? Berikan contoh.**

Jawaban: 

**`const`**: Digunakan untuk mendeklarasikan variabel yang nilainya tetap dan **tidak dapat ditetapkan ulang**. Contoh: `const nama = "Rani";`

**`let`**: Digunakan untuk mendeklarasikan variabel yang nilainya **bisa diubah (reassigned)** di kemudian hari. Contoh: `let umur = 20;`


**3. Apa perbedaan operator `==` dan `===`?**

Jawaban: 

**`==`**: Membandingkan dua nilai setelah melakukan konversi tipe data otomatis (*type coercion*).

**`===`**: Membandingkan nilai sekaligus **tipe data secara ketat** tanpa konversi otomatis (harus sama persis tipe dan nilainya).


**4. Jelaskan fungsi `if-else` dan `switch`. Kapan masing-masing dapat digunakan?**

Jawaban: 

**`if-else`**: Digunakan untuk menguji kondisi logis yang bercabang atau berupa rentang nilai (benar/salah).


* **`switch`**: Digunakan untuk memilih satu tindakan dari sejumlah nilai spesifik yang sudah pasti (seperti pilihan menu atau opsi angka).


**5. Apa fungsi parameter dan return dalam function?**

Jawaban: 

**Parameter**: Berfungsi sebagai wadah data masukan (*input*) yang diterima di dalam fungsi.

**`return`**: Berfungsi untuk **mengembalikan hasil akhir** pengolahan data dari dalam fungsi agar bisa digunakan di luar fungsi tersebut.


**6. Bagaimana JavaScript memilih elemen HTML menggunakan `document.getElementById()`?**

Jawaban:
JavaScript mencari dan mengambil elemen spesifik dari dokumen HTML berdasarkan nilai atribut **`id`** unik yang dimiliki elemen tersebut, sehingga bisa dimanipulasi isinya.


**7. Buat script untuk memvalidasi form agar nama tidak kosong dan nilai berada pada rentang 0-100.**


* *Contoh kode script validasi:*
```javascript
function validasiInput(nama, nilai) {
    if (!nama || nama.trim() === "") {
        alert("Nama tidak boleh kosong!");
        return false;
    }
    if (isNaN(nilai) || nilai < 0 || nilai > 100) {
        alert("Nilai harus berupa angka di antara 0 sampai 100!");
        return false;
    }
    alert("Validasi berhasil!");
    return true;
}

```
---
