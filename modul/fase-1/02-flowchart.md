# Modul 02 — Flowchart & Diagram Alir

```
Fase      : Fase 1 — Fondasi Berpikir
Modul     : 02 dari 16
Durasi    : 2 pertemuan (60–90 menit tiap pertemuan)
Prasyarat : Modul 01 — Apa itu Algoritma?
```

---

## 🎯 Tujuan Belajar

- [ ] Mengenali dan menggambar 4 simbol flowchart utama dengan benar
- [ ] Membaca flowchart yang sudah ada dan menjelaskan alurnya
- [ ] Mengubah algoritma yang ditulis dalam teks menjadi flowchart
- [ ] Membuat flowchart dengan percabangan sederhana (ya/tidak)
- [ ] Mengimplementasikan flowchart sederhana ke dalam proyek Scratch

---

## 🌍 Konsep dalam Kehidupan Nyata

### Kamu Sudah Sering Membaca Flowchart!

Pernahkah kamu melihat bagan seperti ini di majalah atau media sosial?

```
Apakah hari ini hujan?
        |
       YA → Bawa payung → Keluar rumah
        |
      TIDAK → Cek apakah panas?
                    |
                   YA → Pakai topi
                    |
                 TIDAK → Langsung keluar
```

Itu adalah flowchart! Diagram yang menunjukkan alur pengambilan keputusan secara visual.

### Mengapa Flowchart Itu Penting?

Bayangkan kamu harus menjelaskan cara kerja lift kepada teman yang belum pernah melihat lift. Mana yang lebih mudah dipahami?

**Cara A (teks):**
"Masuk lift, tekan tombol lantai tujuan, jika sudah sampai lantai yang dituju maka keluar, jika belum maka tunggu lift bergerak, kemudian ketika sudah sampai keluar dari lift."

**Cara B (flowchart):**
```
[MULAI]
   ↓
[Masuk lift]
   ↓
[Tekan nomor lantai]
   ↓
[Tunggu lift bergerak]
   ↓
Sudah sampai? → TIDAK → kembali ke "Tunggu"
      ↓
     YA
      ↓
[Keluar dari lift]
   ↓
[SELESAI]
```

Flowchart jauh lebih mudah dibaca dan dipahami!

---

## 📚 Materi Inti

### Simbol-Simbol Flowchart

Ada 4 simbol utama yang perlu kamu hafal:

| Simbol | Nama | Fungsi | Contoh |
|--------|------|--------|--------|
| ⬭ (Oval) | Terminator | Menandai awal atau akhir | "MULAI", "SELESAI" |
| ▭ (Kotak) | Proses | Menunjukkan aksi atau langkah | "Rebus air", "Tambahkan garam" |
| ◇ (Belah ketupat) | Keputusan | Pertanyaan ya/tidak | "Apakah sudah matang?" |
| → (Panah) | Alur | Menunjukkan arah urutan | Menghubungkan antar simbol |

> 💡 **Tips menghafal:** **O**val = **O**pen/tutup (awal/akhir). Kotak = aksi (seperti kotak ajaib yang melakukan sesuatu). Belah ketupat = dibelah dua (ya atau tidak).

### Aturan Menggambar Flowchart

1. **Selalu mulai dari atas, alir ke bawah**
2. **Setiap flowchart hanya boleh punya 1 titik MULAI dan minimal 1 titik SELESAI**
3. **Dari belah ketupat (keputusan), selalu keluar 2 panah: YA dan TIDAK**
4. **Panah tidak boleh "menggantung" — semua harus terhubung ke simbol lain**
5. **Gunakan label yang jelas di setiap panah dari belah ketupat**

### Contoh Flowchart Lengkap: Menyeberang Jalan

```
         [MULAI]
            ↓
   [Berdiri di tepi jalan]
            ↓
   [Lihat kiri dan kanan]
            ↓
     ◇ Jalan kosong? ◇
      ↙ YA          TIDAK ↘
[Seberangi jalan]    [Tunggu]
      ↓                  ↑
      └──────────────────┘
                         ↓
                   ◇ Sudah sampai? ◇
                    ↙ YA
               [SELESAI]
```

> 🔁 **Koneksi:** Perhatikan bagian "Tunggu → Lihat lagi" — ini adalah contoh **loop** (perulangan) yang akan kamu pelajari di Modul 06! Kamu sudah melihat konsepnya duluan dalam flowchart.

---

## 🎮 Aktivitas Fisik

### Aktivitas 1: Kartu Flowchart 🃏

**Bahan yang dibutuhkan:**
- Kartu-kartu bertuliskan langkah-langkah (bisa ditulis di kertas kecil)
- Kartu berbentuk oval, kotak, dan belah ketupat (bisa dipotong dari kertas warna)

**Cara main:**
1. Pengajar menyiapkan kartu-kartu berisi langkah-langkah yang diacak
2. Anak menyusun kartu-kartu tersebut menjadi flowchart yang benar
3. Tandai mana yang MULAI, mana yang SELESAI, mana yang KEPUTUSAN

**Skenario yang bisa dipakai:**
- Menyeduh teh/kopi
- Mencuci baju
- Mengirim email

---

### Aktivitas 2: Gambar Flowchart Bersama ✏️

Di kertas besar atau papan tulis, gambar bersama flowchart untuk pertanyaan ini:

**"Apakah aku harus bawa payung hari ini?"**

Mulai dari pertanyaan-pertanyaan ini:
- Apakah cuaca mendung?
- Apakah ada perkiraan hujan?
- Apakah perjalananku jauh?

Tambahkan percabangan dan buat flowchart yang lengkap!

---

## 💻 Task Scratch

### Task 1 — WAJIB: Implementasi Flowchart Sederhana

**Flowchart yang akan diimplementasikan:**

```
[MULAI]
   ↓
[Kucing menyapa: "Halo!"]
   ↓
[Kucing bertanya: "Nama kamu siapa?"]
   ↓
[Ambil jawaban pengguna]
   ↓
[Ucapkan: "Senang bertemu, " + nama + "!"]
   ↓
[SELESAI]
```

**Blok Scratch yang digunakan:**

```scratch
[ketika bendera hijau diklik]
[ucapkan "Halo!" selama 2 detik]
[tanyakan "Nama kamu siapa?" dan tunggu]
[ucapkan (gabungkan "Senang bertemu, " dan (jawaban)) selama 3 detik]
```

**Langkah-langkah di Scratch:**

```
1. Buka Scratch — pilih sprite kucing
2. Dari Kejadian: ambil [ketika bendera hijau diklik]
3. Dari Tampilan: sambungkan [ucapkan "Halo!" selama 2 detik]
4. Dari Sensing: sambungkan [tanyakan "Nama kamu siapa?" dan tunggu]
5. Dari Tampilan: sambungkan [ucapkan () selama 3 detik]
6. Di dalam ucapkan, dari Operator: masukkan [gabungkan () dan ()]
   - Isi bagian kiri: "Senang bertemu, "
   - Isi bagian kanan: blok [jawaban] dari Sensing
7. Klik bendera hijau, ketik namamu, dan lihat hasilnya!
```

> ⚠️ **Perhatian:** Blok `gabungkan` ada di kategori **Operator** (warna hijau tua). Blok `jawaban` ada di kategori **Sensing** (warna hijau muda). Keduanya berbeda!

---

### Task 2 — WAJIB: Flowchart dengan Percabangan

**Yang akan dibuat:** Program yang memberi reaksi berbeda tergantung jawaban pengguna.

**Flowchart:**
```
[MULAI]
   ↓
[Tanya: "Kamu suka kucing atau anjing?"]
   ↓
◇ Jawabannya "kucing"? ◇
  ↙ YA                  TIDAK ↘
[Ucapkan "Meong!"]    [Ucapkan "Guk guk!"]
       ↓                    ↓
       └────────────────────┘
                  ↓
            [SELESAI]
```

**Blok Scratch:**

```scratch
[ketika bendera hijau diklik]
[tanyakan "Kamu suka kucing atau anjing?" dan tunggu]
[jika <(jawaban) = "kucing"> maka]
  [ucapkan "Meong! Kamu tim kucing ya!" selama 3 detik]
[lain]
  [ucapkan "Guk guk! Kamu tim anjing!" selama 3 detik]
```

**Tips penting:**
- Blok `jika...maka...lain` ada di kategori **Kontrol** (kuning)
- Blok perbandingan `() = ()` ada di kategori **Operator** (hijau tua)
- Masukkan blok `jawaban` dari **Sensing** ke dalam blok `()`

---

### Task 3 — EKSPLORASI: Flowchart Lebih Kompleks

Buat flowchart di kertas terlebih dahulu, lalu implementasikan ke Scratch!

**Ide proyek:** Kuis "Kamu Hewan Apa?"

Program menanyakan 2-3 pertanyaan dan menebak kamu adalah hewan apa.

Contoh pertanyaan:
- "Kamu lebih suka siang atau malam?" → siang/malam
- "Kamu lebih suka panas atau dingin?" → panas/dingin

Berdasarkan kombinasi jawaban, program menyimpulkan hewan yang sesuai.

**Langkah:**
1. Gambar flowchart-nya di kertas dulu!
2. Pastikan semua jalur berakhir di SELESAI
3. Baru implementasikan di Scratch

---

### Task 4 — BONUS: Buat Flowchart dari Proyek Orang Lain

Pilih salah satu proyek Scratch populer di [scratch.mit.edu/explore](https://scratch.mit.edu/explore), buka kode-nya, dan buat flowchart yang menggambarkan cara kerjanya.

Ini adalah latihan membaca kode dan mengubahnya menjadi diagram — skill yang sangat berguna!

---

## 🧠 Soal Latihan

### Pilihan Ganda

**1.** Simbol apa yang digunakan untuk menandai "MULAI" dan "SELESAI" dalam flowchart?

a) Kotak persegi panjang  
b) Belah ketupat  
c) Oval / lonjong  
d) Panah  

**2.** Dari simbol "keputusan" (belah ketupat), berapa panah yang harus keluar?

a) 1 panah  
b) 2 panah (YA dan TIDAK)  
c) 3 panah  
d) Bebas, tidak ada aturan  

**3.** Manakah pernyataan yang BENAR tentang flowchart?

a) Flowchart harus selalu mengarah ke atas  
b) Flowchart boleh punya banyak titik MULAI  
c) Flowchart lebih mudah dipahami daripada algoritma dalam teks  
d) Flowchart hanya digunakan oleh programmer profesional  

---

### Praktik

**4.** Gambar flowchart untuk algoritma berikut:

```
"Cara memutuskan apakah perlu bawa jas hujan:
Cek ramalan cuaca. Jika hujan, bawa jas hujan.
Jika tidak hujan, cek apakah perjalanan jauh.
Jika jauh, tetap bawa untuk jaga-jaga.
Jika dekat, tidak perlu bawa."
```

**5.** Baca flowchart berikut dan tuliskan algoritma-nya dalam bentuk teks:

```
[MULAI] → [Nyalakan HP] → [Cek sinyal?]
YA → [Buka WA] → [Kirim pesan] → [SELESAI]
TIDAK → [Cari area sinyal] → kembali ke [Cek sinyal?]
```

Tuliskan dalam bentuk langkah-langkah:
```
1. _______________________________________________
2. _______________________________________________
3. _______________________________________________
...
```

---

## 📎 Catatan Pengajar

### Kesalahan Umum

**Anak tidak menutup panah dari keputusan:**
Setelah percabangan YA/TIDAK, kedua jalur harus bertemu kembali (atau masing-masing berakhir di SELESAI). Panah yang "menggantung" menandakan logika yang belum selesai.

**Anak menggunakan kotak untuk keputusan:**
Tegaskan: "Apakah..." → selalu belah ketupat. "Lakukan..." → selalu kotak.

**Anak langsung buka Scratch tanpa gambar flowchart:**
Dorong kebiasaan: gambar flowchart dulu di kertas, baru buka Scratch. Ini kebiasaan programmer profesional yang sangat berharga!

### Koneksi ke Dunia Nyata

Tunjukkan kepada anak bahwa flowchart digunakan di banyak bidang:
- Dokter menggunakan flowchart untuk mendiagnosis penyakit
- Kasir supermarket mengikuti flowchart untuk melayani pelanggan
- Pilot mengikuti flowchart untuk prosedur darurat

---

## ➡️ Modul Berikutnya

[Modul 03 — Berpikir Komputasional](./03-berpikir-komputasional.md)

---

*Fase 1 · Modul 02 dari 16 · Logika Coding SD*
