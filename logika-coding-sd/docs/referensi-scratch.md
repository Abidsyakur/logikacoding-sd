# 🧩 Referensi Blok Scratch

Panduan cepat blok-blok Scratch yang digunakan dalam kurikulum ini, dikelompokkan berdasarkan kategori.

> Buka Scratch di **[scratch.mit.edu](https://scratch.mit.edu)** dan cari blok-blok ini di panel sebelah kiri.

---

## 🟡 Kontrol (Control) — Kuning

Blok-blok untuk mengatur alur dan urutan program.

| Blok | Fungsi | Pertama dipakai |
|------|--------|-----------------|
| `ketika bendera hijau diklik` | Titik mulai program | M01 |
| `ketika sprite ini diklik` | Jalankan kode saat sprite diklik | M05 |
| `tunggu (N) detik` | Jeda program selama N detik | M02 |
| `ulangi (N) kali` | Jalankan blok di dalamnya N kali | M06 |
| `selamanya` | Jalankan blok di dalamnya terus-menerus | M05 |
| `jika <kondisi> maka` | Jalankan blok jika kondisi benar | M05 |
| `jika <kondisi> maka ... lain ...` | Percabangan dengan dua pilihan | M05 |
| `tunggu sampai <kondisi>` | Jeda sampai kondisi terpenuhi | M06 |
| `ulangi sampai <kondisi>` | Loop sampai kondisi terpenuhi | M06 |
| `hentikan semua` | Menghentikan semua skrip | M05 |

---

## 🔵 Gerak (Motion) — Biru

Blok-blok untuk menggerakkan sprite.

| Blok | Fungsi | Pertama dipakai |
|------|--------|-----------------|
| `gerak (N) langkah` | Maju N langkah ke arah yang dihadapi | M01 |
| `pergi ke x: () y: ()` | Pindah ke koordinat tertentu | M02 |
| `meluncur dalam (N) detik ke x: () y: ()` | Gerak halus ke koordinat dalam N detik | M11 |
| `arahkan ke (N) derajat` | Atur arah hadap sprite | M06 |
| `arahkan ke (penunjuk mouse)` | Arahkan sprite ke kursor | M06 |
| `pantulkan jika di tepi` | Balik arah jika menyentuh tepi stage | M06 |
| `ubah x sebesar (N)` | Geser sprite ke kanan/kiri | M12 |
| `ubah y sebesar (N)` | Geser sprite ke atas/bawah | M12 |
| `x posisi` | Nilai koordinat X saat ini | M06 |
| `y posisi` | Nilai koordinat Y saat ini | M06 |

> **Koordinat Scratch:** Titik tengah stage = (0, 0). Kanan = X positif, Kiri = X negatif. Atas = Y positif, Bawah = Y negatif.

---

## 💜 Tampilan (Looks) — Ungu

Blok-blok untuk mengubah tampilan sprite dan stage.

| Blok | Fungsi | Pertama dipakai |
|------|--------|-----------------|
| `ucapkan (teks) selama (N) detik` | Tampilkan balon bicara N detik | M01 |
| `ucapkan (teks)` | Tampilkan balon bicara permanen | M01 |
| `pikirkan (teks) selama (N) detik` | Tampilkan balon pikiran N detik | M03 |
| `ganti kostum ke (nama)` | Ubah tampilan sprite | M02 |
| `kostum berikutnya` | Ganti ke kostum selanjutnya | M06 |
| `ganti backdrop ke (nama)` | Ubah latar belakang stage | M11 |
| `ubah ukuran sebesar (N)` | Tambah/kurangi ukuran sprite | M06 |
| `set ukuran ke (N)%` | Atur ukuran sprite ke persentase tertentu | M06 |
| `tampilkan` | Buat sprite terlihat | M09 |
| `sembunyikan` | Buat sprite tidak terlihat | M09 |

---

## 🟢 Sensing — Hijau Muda

Blok-blok untuk mendeteksi kondisi dan mengambil input.

| Blok | Fungsi | Pertama dipakai |
|------|--------|-----------------|
| `menyentuh (sprite/tepi)?` | Deteksi apakah sprite menyentuh sesuatu | M05 |
| `menyentuh warna (warna)?` | Deteksi apakah sprite menyentuh warna tertentu | M12 |
| `tombol (tombol) ditekan?` | Cek apakah tombol keyboard tertentu ditekan | M05 |
| `mouse ditekan?` | Cek apakah tombol mouse ditekan | M06 |
| `x penunjuk mouse` | Koordinat X kursor saat ini | M06 |
| `y penunjuk mouse` | Koordinat Y kursor saat ini | M06 |
| `tanyakan (pertanyaan) dan tunggu` | Tampilkan pertanyaan dan tunggu jawaban | M03 |
| `jawaban` | Nilai dari jawaban terakhir pengguna | M03 |
| `timer` | Waktu yang sudah berjalan sejak program dimulai (detik) | M08 |
| `atur ulang timer` | Reset timer ke 0 | M08 |

---

## 🟩 Operator — Hijau Tua

Blok-blok untuk operasi matematika dan logika.

| Blok | Fungsi | Pertama dipakai |
|------|--------|-----------------|
| `() + ()` | Penjumlahan | M07 |
| `() - ()` | Pengurangan | M07 |
| `() * ()` | Perkalian | M07 |
| `() / ()` | Pembagian | M07 |
| `bilangan acak antara () dan ()` | Hasilkan angka acak dalam rentang | M08 |
| `() > ()` | Lebih besar dari | M05 |
| `() < ()` | Lebih kecil dari | M05 |
| `() = ()` | Sama dengan | M05 |
| `() dan ()` | Logika AND — keduanya harus benar | M04 |
| `() atau ()` | Logika OR — salah satu cukup benar | M04 |
| `bukan ()` | Logika NOT — membalik nilai boolean | M04 |
| `gabungkan () dan ()` | Menggabungkan dua teks | M08 |
| `huruf ke () dari ()` | Mengambil karakter ke-N dari teks | M09 |
| `panjang ()` | Menghitung panjang teks | M09 |
| `() mengandung ()?` | Cek apakah teks mengandung kata tertentu | M09 |
| `() mod ()` | Sisa bagi (modulo) | M10 |
| `bulatkan ()` | Membulatkan angka desimal | M11 |

---

## 🟠 Variabel (Variables) — Jingga

Blok-blok untuk membuat dan menggunakan variabel dan list.

| Blok | Fungsi | Pertama dipakai |
|------|--------|-----------------|
| `[nama variabel]` | Nilai dari variabel tersebut | M07 |
| `set (variabel) ke (nilai)` | Isi variabel dengan nilai baru | M07 |
| `ubah (variabel) sebesar (N)` | Tambahkan N ke nilai variabel | M07 |
| `tampilkan variabel (variabel)` | Tampilkan nilai variabel di stage | M07 |
| `sembunyikan variabel (variabel)` | Sembunyikan tampilan variabel | M07 |
| `tambahkan (nilai) ke (list)` | Tambah item baru di akhir list | M09 |
| `hapus (index) dari (list)` | Hapus item pada posisi tertentu | M09 |
| `hapus semua dari (list)` | Kosongkan seluruh isi list | M09 |
| `masukkan (nilai) di (index) dari (list)` | Sisipkan item di posisi tertentu | M09 |
| `ganti item (index) dari (list) ke (nilai)` | Ubah nilai item pada posisi tertentu | M09 |
| `item (index) dari (list)` | Ambil nilai item pada posisi tertentu | M09 |
| `panjang (list)` | Jumlah item dalam list | M09 |
| `(list) mengandung (nilai)?` | Cek apakah nilai ada dalam list | M09 |

---

## 🔴 Suara (Sound) — Merah Muda

| Blok | Fungsi | Pertama dipakai |
|------|--------|-----------------|
| `putar suara (nama) sampai selesai` | Putar suara dan tunggu selesai | M13 |
| `putar suara (nama)` | Putar suara tanpa menunggu | M13 |
| `hentikan semua suara` | Hentikan semua suara yang sedang diputar | M13 |
| `ubah volume sebesar (N)` | Tambah/kurangi volume | M13 |
| `set volume ke (N)%` | Atur volume ke persentase tertentu | M13 |

---

## ✏️ Blok Khusus (My Blocks) — Merah

| Blok | Fungsi | Pertama dipakai |
|------|--------|-----------------|
| `definisikan (nama block)` | Membuat custom block baru | M10 |
| `(nama block)` | Memanggil custom block | M10 |

---

## 📐 Koordinat Stage Scratch

```
         Y+
         |
         | (0, 180)
         |
(-240,0) |-----(0,0)------(240,0)  → X
         |
         | (0, -180)
         |
         Y-
```

- **Tengah stage**: x=0, y=0
- **Lebar stage**: 480 piksel (dari -240 sampai 240)
- **Tinggi stage**: 360 piksel (dari -180 sampai 180)

---

*Referensi ini diperbarui seiring modul bertambah. Untuk dokumentasi Scratch yang lebih lengkap, kunjungi [en.scratch-wiki.info](https://en.scratch-wiki.info).*
