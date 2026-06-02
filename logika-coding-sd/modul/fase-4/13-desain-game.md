# Modul 13 — Desain Game Sederhana

```
Fase      : Fase 4 — Proyek & Scratch Hero
Modul     : 13 dari 16
Durasi    : 3 pertemuan (60–90 menit tiap pertemuan)
Prasyarat : Modul 01–12 (Fase 1, 2, dan 3 selesai)
```

---

## 🎯 Tujuan Belajar

- [ ] Membuat Game Design Document (GDD) sederhana sebelum mulai coding
- [ ] Menggambar wireframe tampilan game di atas kertas
- [ ] Membangun prototype game yang bisa dimainkan di Scratch
- [ ] Menggunakan semua konsep yang sudah dipelajari: variabel, loop, if-else, list, fungsi
- [ ] Melakukan playtesting dan memperbaiki game berdasarkan feedback

---

## 🌍 Konsep dalam Kehidupan Nyata

### Game Tidak Dibuat Secara Asal-Asalan

Tahukah kamu bahwa game profesional seperti Mobile Legends, Minecraft, atau FIFA tidak langsung dibuat begitu saja? Sebelum satu baris kode pun ditulis, tim game designer menghabiskan berminggu-minggu atau berbulan-bulan untuk **merencanakan** gamenya.

Mereka membuat dokumen yang disebut **Game Design Document (GDD)** — semacam "blueprint" atau rancangan bangunan untuk game.

### Mengapa Perlu Merencanakan Dulu?

Bayangkan kamu ingin membangun rumah LEGO yang keren. Kamu langsung mulai menyusun kepingan tanpa rencana... dan 30 menit kemudian rumahnya miring, pintunya tidak muat, dan warnanya tidak cocok.

Dibanding kalau kamu gambar dulu di kertas seperti apa rumahnya, berapa lantainya, di mana pintunya — lalu baru mulai menyusun. Hasilnya jauh lebih bagus dan lebih cepat!

Prinsip yang sama berlaku untuk membuat game di Scratch.

---

## 📚 Materi Inti

### Komponen Sebuah Game

Semua game (sesederhana apapun) punya komponen-komponen ini:

| Komponen | Penjelasan | Contoh |
|----------|-----------|--------|
| **Pemain** | Siapa yang dikontrol pengguna? | Kucing, pesawat, bola |
| **Tujuan** | Apa yang harus dicapai? | Kumpulkan 10 koin, sampai garis finish |
| **Rintangan** | Apa yang menghalangi pemain? | Musuh, lubang, batas waktu |
| **Skor** | Bagaimana kemajuan diukur? | Poin, nyawa, waktu tersisa |
| **Kondisi Menang** | Kapan game dimenangkan? | Skor > 100, selesaikan semua level |
| **Kondisi Kalah** | Kapan game berakhir/gagal? | Nyawa = 0, waktu habis |

---

### Game Design Document (GDD) Sederhana

GDD tidak harus panjang dan rumit. Untuk game Scratch, cukup menjawab pertanyaan-pertanyaan ini:

```
=== GAME DESIGN DOCUMENT ===

Nama Game     : ______________________________
Dibuat oleh   : ______________________________
Tanggal       : ______________________________

KONSEP (1 kalimat):
_________________________________________________

PEMAIN:
Sprite apa yang digunakan?   ___________________
Digerakkan bagaimana?        ___________________
Kecepatan gerak              ___________________

TUJUAN GAME:
_________________________________________________

KONDISI MENANG:
_________________________________________________

KONDISI KALAH:
_________________________________________________

RINTANGAN/TANTANGAN:
_________________________________________________

SISTEM SKOR:
Skor awal           : _______
Bertambah ketika    : _______  (+ berapa?)
Berkurang ketika    : _______  (- berapa?)

VARIABEL YANG DIBUTUHKAN:
- ________________
- ________________
- ________________

SPRITE YANG DIBUTUHKAN:
- ________________ (fungsi: _______________)
- ________________ (fungsi: _______________)
- ________________ (fungsi: _______________)

BACKDROP:
_________________________________________________
```

---

### Proses Membuat Game: Design → Build → Test → Improve

```
[DESIGN]              [BUILD]             [TEST]           [IMPROVE]
Tulis GDD     →   Buat prototype   →   Main sendiri  →   Perbaiki
Gambar wireframe   Mulai dari fitur      Minta teman       Tambah fitur
                   paling penting        mencoba           Perbaiki bug
                                         Catat masalah
                   ← ← ← ← ← ← ← ← ← ← ← ← ← ← ← ←
                           (Ulangi terus!)
```

> 🌟 **Fun Fact:** Proses ini disebut **iterasi** atau **agile development** — cara kerja yang dipakai oleh hampir semua studio game dan perusahaan teknologi di dunia!

---

### Strategi Membangun: Mulai dari yang Terkecil!

Kesalahan yang sering dilakukan programmer pemula: ingin langsung membuat game yang sempurna dan lengkap di awal.

**Cara yang benar:** Mulai dari **versi paling sederhana yang masih bisa dimainkan**, lalu tambahkan fitur satu per satu.

```
Versi 0.1 — "Bisa jalan"
└── Sprite bergerak ke kiri dan kanan

Versi 0.2 — "Ada tujuan"  
└── + Ada item yang bisa dikumpulkan, skor bertambah

Versi 0.3 — "Ada bahaya"
└── + Ada musuh/rintangan, nyawa berkurang

Versi 0.4 — "Ada awal dan akhir"
└── + Layar mulai, kondisi menang/kalah

Versi 1.0 — "Siap dimainkan"
└── + Suara, animasi, polish
```

---

## 🎮 Aktivitas Fisik

### Aktivitas 1: Analisis Game Favoritmu 🎮

Pilih salah satu game yang sering kamu mainkan (boleh mobile, console, atau PC). Jawab pertanyaan-pertanyaan berikut:

```
Nama game     : ______________________________

Pemain        : ______________________________
Tujuan game   : ______________________________
Rintangan     : ______________________________
Kondisi menang: ______________________________
Kondisi kalah : ______________________________
Cara skor     : ______________________________

Komponen favoritmu: ________________________
Mengapa?       : ______________________________
```

Diskusikan bersama — game yang "terasa menyenangkan" biasanya punya desain yang sangat dipikirkan!

---

### Aktivitas 2: Wireframe di Kertas ✏️

Sebelum membuat game di Scratch, gambar dulu tampilannya di kertas!

**Buat 3 sketsa:**
1. **Layar Judul** — tampilan awal sebelum game dimulai
2. **Layar Game** — tampilan saat game sedang berjalan (di mana sprite, di mana skor, dll.)
3. **Layar Game Over / Menang** — tampilan akhir game

> 💡 **Tips:** Sketsa tidak harus bagus dan rapi. Yang penting membantu kamu membayangkan tampilan akhir gamenya!

---

## 💻 Task Scratch

### Task 1 — WAJIB: Lengkapi GDD

Sebelum membuka Scratch, lengkapi Game Design Document berikut:

**Pilih salah satu tema game:**
- 🐱 Kucing menangkap ikan
- 🚀 Pesawat menghindari asteroid  
- 🏃 Karakter berlari mengumpulkan koin
- 🐍 Ular yang memanjang (Snake)
- Atau ide kreatifmu sendiri!

Isi GDD lengkap di kertas sebelum lanjut ke task berikutnya.

---

### Task 2 — WAJIB: Bangun Versi 0.1 — Sprite yang Bisa Bergerak

**Tujuan:** Buat sprite yang bisa dikendalikan pemain. Ini adalah fondasi dari hampir semua game!

**Opsi A — Gerak 4 arah (WASD atau panah):**
```scratch
[ketika bendera hijau diklik]
[selamanya]
    [jika <tombol [atas] ditekan?> maka]
        [ubah y sebesar 5]
    [jika <tombol [bawah] ditekan?> maka]
        [ubah y sebesar -5]
    [jika <tombol [kanan] ditekan?> maka]
        [ubah x sebesar 5]
    [jika <tombol [kiri] ditekan?> maka]
        [ubah x sebesar -5]
```

**Opsi B — Gerak kiri-kanan + lompat:**
```scratch
[ketika bendera hijau diklik]
[set kecepatan_y ke 0]
[selamanya]
    [jika <tombol [kanan] ditekan?> maka]
        [ubah x sebesar 5]
    [jika <tombol [kiri] ditekan?> maka]
        [ubah x sebesar -5]
    [jika <tombol [spasi] ditekan?> DAN <y posisi < -100>> maka]
        [set kecepatan_y ke 10]
    [ubah y sebesar (kecepatan_y)]
    [ubah kecepatan_y sebesar -1]     ← gravitasi!
    [jika <y posisi < -150> maka]
        [set y ke -150]
        [set kecepatan_y ke 0]
```

---

### Task 3 — WAJIB: Bangun Versi 0.2 — Tambahkan Tujuan

Tambahkan **item yang bisa dikumpulkan** (koin, ikan, bintang — sesuai tema).

**Kode untuk sprite item:**
```scratch
[ketika bendera hijau diklik]
[selamanya]
    [jika <menyentuh [Pemain]?> maka]
        [ubah [skor] sebesar 1]
        [pergi ke x: (bilangan acak antara -200 dan 200) y: (bilangan acak antara -150 dan 150)]
        [putar suara [pop] sampai selesai]
```

**Jangan lupa:** Buat variabel `skor` dan tampilkan di layar!

---

### Task 4 — WAJIB: Bangun Versi 0.3 — Kondisi Menang/Kalah

Tambahkan kondisi game berakhir:

```scratch
[ketika bendera hijau diklik]
[set [skor] ke 0]
[set [waktu] ke 30]
[selamanya]
    [tunggu 1 detik]
    [ubah [waktu] sebesar -1]
    [jika <(waktu) = 0> maka]
        [hentikan semua]
        [ucapkan (gabungkan "Game Over! Skor akhir: " dan (skor)) selama 5 detik]
```

---

### Task 5 — EKSPLORASI: Tambahkan Musuh

Buat sprite musuh yang bergerak sendiri dan berbahaya jika disentuh pemain:

```scratch
[ketika bendera hijau diklik]
[selamanya]
    [gerak 3 langkah]
    [pantulkan jika di tepi]
    [jika <menyentuh [Pemain]?> maka]
        [ubah [nyawa] sebesar -1]
        [jika <(nyawa) = 0> maka]
            [hentikan semua]
```

---

### Task 6 — BONUS: Playtesting & Improvement

1. Minta minimal 2 orang (teman/anggota keluarga) mencoba gamenya
2. Amati mereka bermain — jangan bantu, jangan jelaskan
3. Catat di kertas: apa yang membingungkan mereka? Di mana mereka stuck?
4. Perbaiki gamenya berdasarkan observasi

```
=== CATATAN PLAYTESTING ===

Pemain 1  : _______________________
Masalah   : _______________________
Perbaikan : _______________________

Pemain 2  : _______________________
Masalah   : _______________________
Perbaikan : _______________________
```

---

## 🧠 Soal Latihan

**1.** Sebutkan 6 komponen utama sebuah game dan jelaskan masing-masing!

**2.** Mengapa penting membuat GDD sebelum mulai coding game di Scratch?

**3.** Apa yang dimaksud dengan "iterasi" dalam proses pembuatan game?

**4.** Game kamu punya skor yang selalu 0 meskipun karakter sudah menyentuh koin. Apa yang kemungkinan salah?

a) Variabel skor belum dibuat  
b) Kondisi "menyentuh" tidak mendeteksi sprite yang tepat  
c) Blok "ubah skor" tidak terhubung dengan benar  
d) Semua jawaban di atas bisa jadi penyebabnya  

**5.** Kamu ingin membuat game yang sangat kompleks dengan 5 level, 10 jenis musuh, dan sistem senjata. Strategi mana yang lebih baik?

a) Langsung buat semuanya sekaligus agar hemat waktu  
b) Buat dulu versi paling sederhana yang bisa dimainkan, lalu tambahkan fitur satu per satu  
c) Jangan dibuat, terlalu susah  
d) Copy proyek orang lain dan modifikasi  

---

## 📎 Catatan Pengajar

### Poin Kritis di Fase 4

Fase ini adalah **fase paling penting** dalam seluruh kurikulum. Anak tidak lagi mengikuti instruksi langkah demi langkah — mereka mulai membuat keputusan desain sendiri.

**Peran pengajar berubah:** Dari "instruktur" menjadi "mentor." Jangan terlalu banyak memberi jawaban. Alih-alih menjawab "Bagaimana caranya?", tanyakan balik: "Kira-kira blok apa yang kira-kira cocok? Sudah pernah buat sesuatu yang mirip sebelumnya?"

### Tanda-tanda Anak Siap Hero Project

- Bisa menjelaskan logika gamenya dengan lancar
- Bisa menemukan dan memperbaiki bug sendiri (atau setidaknya tahu harus mencari di mana)
- Punya inisiatif menambahkan fitur yang tidak ada di instruksi
- Bisa mengajari teman yang kesulitan

---

## ➡️ Modul Berikutnya

[Modul 14 — Debugging & Problem Solving](./14-debugging.md)

---

*Fase 4 · Modul 13 dari 16 · Logika Coding SD*
