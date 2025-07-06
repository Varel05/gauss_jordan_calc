---

# Penyelesaian Sistem Persamaan Linear 3x3 dengan Eliminasi Gauss-Jordan

---

## Deskripsi Proyek

Proyek ini adalah sebuah aplikasi web sederhana yang dirancang untuk menyelesaikan sistem persamaan linear dengan tiga variabel (\$x, y, z\$) menggunakan **metode eliminasi Gauss-Jordan**. Pengguna dapat memasukkan koefisien dari tiga persamaan, dan aplikasi akan menghitung serta menampilkan nilai \$x, y,\$ dan \$z\$ jika solusi unik ditemukan.

---

## Teknologi yang Digunakan

- **HTML5**: Untuk struktur dasar halaman web.
- **CSS3**: Untuk gaya visual dan tata letak antarmuka pengguna.
- **JavaScript (ES6+)**: Untuk logika inti metode eliminasi Gauss-Jordan dan interaksi antarmuka pengguna (DOM manipulation).

---

## Fitur

- **Input Koefisien Interaktif**: Antarmuka pengguna yang ramah memungkinkan pengguna untuk dengan mudah memasukkan koefisien untuk tiga persamaan linear.
- **Penyelesaian Gauss-Jordan Otomatis**: Secara otomatis menerapkan algoritma eliminasi Gauss-Jordan untuk menemukan solusi sistem.
- **Tampilan Hasil Jelas**: Menampilkan nilai \$x, y,\$ dan \$z\$ yang dihitung dengan presisi empat angka desimal.
- **Penanganan Kasus Khusus**: Memberikan umpan balik jika sistem tidak memiliki solusi unik (misalnya, solusi tak terbatas atau tidak ada solusi).
- **Validasi Input Dasar**: Memberikan pesan kesalahan jika input yang dimasukkan bukan angka yang valid.

---

## Instruksi Penyiapan

Proyek ini adalah aplikasi *client-side* murni, yang berarti Anda tidak memerlukan server web atau instalasi tambahan apa pun.

1. **Kloning Repositori (Opsional)**: Jika ini adalah repositori Git, Anda bisa mengkloningnya:
   ```bash
   git clone https://github.com/Varel05/gauss_jordan_calc.git
   cd gauss_jordan_calc
   ```
2. **Unduh File (Alternatif)**: Jika tidak menggunakan Git, cukup unduh file `gauss_jordan.html` ke komputer Anda.
3. **Buka di Browser**: Buka file `gauss_jordan.html` langsung di browser web favorit Anda (seperti Google Chrome, Mozilla Firefox, Microsoft Edge, atau Safari). Anda bisa melakukannya dengan:
   - Mengklik dua kali file tersebut di penjelajah file Anda.
   - Menyeret file tersebut ke jendela browser yang terbuka.

Aplikasi akan segera berjalan dan siap digunakan.

---

## Penjelasan Dukungan AI (Transformasi dari Rumus ke Kalkulator)

Aplikasi ini dapat dianggap sebagai implementasi "kalkulator" dari **rumus atau algoritma eliminasi Gauss-Jordan**. Alih-alih mengharuskan pengguna untuk secara manual melakukan setiap langkah perhitungan matriks (seperti mencari pivot, normalisasi baris, atau eliminasi baris), yang bisa rumit dan rawan kesalahan, aplikasi ini mengotomatiskan seluruh proses.

**Bagaimana ini mengubahnya menjadi kalkulator:**

1. **Abstraksi Kompleksitas**: Logika kompleks dari operasi baris Gauss-Jordan (`solveGaussJordan` function) dienkapsulasi di balik antarmuka yang sederhana. Pengguna tidak perlu memahami setiap detail perhitungan matriks, cukup masukkan angka.
2. **Input Terstruktur**: UI menyediakan kolom input yang jelas untuk setiap koefisien (\$A\_{ij}\$ dan \$B\_i\$), memandu pengguna dalam memasukkan data yang diperlukan sesuai format sistem persamaan linear.
3. **Hasil Instan**: Setelah input diberikan, aplikasi langsung memprosesnya dan menampilkan solusi akhir. Ini menghilangkan kebutuhan untuk perhitungan manual berulang, seperti layaknya menggunakan kalkulator untuk operasi aritmatika dasar.

Dengan demikian, proyek ini mengambil prosedur matematis yang dikenal (rumus Gauss-Jordan) dan mengubahnya menjadi alat yang interaktif dan mudah digunakan, serupa dengan bagaimana kalkulator mengubah operasi aritmatika dasar menjadi proses *point-and-click* yang efisien.

