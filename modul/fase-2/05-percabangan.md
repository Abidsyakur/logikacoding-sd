# Modul 05 — Percabangan (If-Else)

```
Fase      : Fase 2 — Struktur & Kontrol
Modul     : 05 dari 16
Durasi    : 2–3 pertemuan (60–90 menit tiap pertemuan)
Prasyarat : Modul 01–04 (Fase 1 selesai)
```

---

## 🎯 Tujuan Belajar

- [ ] Menjelaskan konsep percabangan dengan kata-kata sendiri
- [ ] Membedakan kapan menggunakan `if`, `if-else`, dan `if-else if`
- [ ] Membuat program Scratch yang bereaksi berbeda sesuai kondisi
- [ ] Mengenali dan menghindari kesalahan logika dalam percabangan
- [ ] Menggambar flowchart percabangan sebelum mengimplementasikannya

---

## 🌍 Konsep dalam Kehidupan Nyata

### Kamu Sudah Pakai If-Else Setiap Hari!

Tanpa sadar, otak kamu terus-menerus menjalankan "if-else":

> **Jika** lapar → makan  
> **Jika tidak** → lanjutkan aktivitas

> **Jika** ada PR → kerjakan PR dulu  
> **Jika tidak** → bebas main

> **Jika** HP baterai < 20% → charge segera  
> **Jika tidak** → lanjutkan pakai

Semua pengambilan keputusan di kehidupan nyata adalah if-else!

### If-Else dalam Game yang Kamu Mainkan

Semua game menggunakan if-else secara ekstensif:

```
Jika (nyawa pemain = 0):
    → tampilkan layar Game Over

Jika (pemain menyentuh koin):
    → skor + 10
    → sembunyikan koin
    → putar suara "ding"

Jika (pemain menyentuh musuh):
    → nyawa - 1
    → putar suara "auh"
    → jika nyawa = 0:
        → Game Over
```

Tanpa if-else, game tidak bisa "bereaksi" terhadap apa yang dilakukan pemain!

---

## 📚 Materi Inti

### If — "Jika"

Bentuk paling sederhana. Hanya melakukan sesuatu **jika** kondisi terpenuhi. Jika kondisi tidak terpenuhi, tidak terjadi apa-apa.

```
JIKA (kondisi benar):
    lakukan ini
```

**Contoh:**
```
JIKA (nilai >= 70):
    tampilkan "Selamat, kamu lulus!"
```
Jika nilai di bawah 70, program diam saja — tidak tampilkan apa-apa.

---

### If-Else — "Jika... Kalau Tidak..."

Ketika ada dua kemungkinan hasil yang perlu ditangani.

```
JIKA (kondisi benar):
    lakukan A
KALAU TIDAK:
    lakukan B
```

**Contoh:**
```
JIKA (nilai >= 70):
    tampilkan "Selamat, kamu lulus!"
KALAU TIDAK:
    tampilkan "Semangat, belajar lebih giat!"
```

---

### If-Else If-Else — Banyak Kemungkinan

Ketika ada lebih dari dua kemungkinan hasil.

```
JIKA (kondisi A):
    lakukan X
KALAU JIKA (kondisi B):
    lakukan Y
KALAU JIKA (kondisi C):
    lakukan Z
KALAU TIDAK:
    lakukan default
```

**Contoh:**
```
JIKA (nilai >= 90):
    tampilkan "Nilai A — Sempurna!"
KALAU JIKA (nilai >= 80):
    tampilkan "Nilai B — Bagus sekali!"
KALAU JIKA (nilai >= 70):
    tampilkan "Nilai C — Cukup baik!"
KALAU TIDAK:
    tampilkan "Nilai D — Perlu belajar lebih giat"
```

---

### Nested If — Percabangan di dalam Percabangan

Kadang kita perlu memeriksa kondisi di dalam kondisi.

```
JIKA (punya uang):
    JIKA (lapar):
        beli makanan
    KALAU TIDAK:
        simpan uang
KALAU TIDAK:
    tidak bisa beli apa-apa
```

> ⚠️ **Perhatian:** Nested if bisa membingungkan jika terlalu dalam. Programmer profesional biasanya mencoba membatasi nested if maksimal 2-3 level.

---

### Kondisi yang Benar vs Salah

Ingat dari Modul 04 tentang Boolean? Kondisi dalam if-else selalu bernilai TRUE atau FALSE.

| Kondisi | Nilai |
|---------|-------|
| `5 > 3` | TRUE |
| `10 = 20` | FALSE |
| `"kucing" = "kucing"` | TRUE |
| `nilai >= 70` (nilai=65) | FALSE |

---

### Flowchart If-Else

```
          ↓
  ◇ Kondisi? ◇
  ↙ YA       TIDAK ↘
[Aksi A]       [Aksi B]
  ↘              ↙
       ↓
   (lanjut)
```

> 💡 **Tips:** Selalu gambar flowchart dulu sebelum buka Scratch! Ini memastikan logika percabanganmu sudah benar sebelum mulai coding.

---

## 🎮 Aktivitas Fisik

### Aktivitas 1: Manusia If-Else 🤖

**Cara main:**
1. Satu anak jadi "komputer" — berdiri di depan
2. Pengajar membisikkan sebuah kondisi (misal: "saat ini hari Senin")
3. Anak lain bergiliran memberi instruksi if-else
4. Si "komputer" harus menjalankan instruksi sesuai kondisi yang dibisikkan

**Contoh instruksi:**
> "Jika hari ini Senin, angkat tangan kanan. Jika tidak, angkat tangan kiri."

---

### Aktivitas 2: Kartu Kondisi 🃏

**Bahan:** Kartu-kartu berisi kondisi (bisa tulis di kertas)

**Cara main:**
1. Setiap anak dapat 1 kartu kondisi (misal: "nilai = 85", "nilai = 60", "nilai = 95")
2. Pengajar membacakan aturan if-else-if:
   - Nilai ≥ 90 → tepuk tangan 3x
   - Nilai ≥ 70 → tepuk tangan 1x
   - Nilai < 70 → senyum dan bilang "semangat!"
3. Setiap anak melakukan aksi sesuai kondisi di kartunya

**Tujuan:** Merasakan secara fisik bagaimana percabangan bekerja!

---

## 💻 Task Scratch

### Task 1 — WAJIB: Penjaga Gerbang 🚪

**Cerita:** Kamu adalah penjaga gerbang sebuah wahana bermain. Anak yang tingginya 140 cm ke atas boleh masuk, yang di bawah itu tidak boleh.

**Flowchart:**
```
[MULAI]
   ↓
[Tanya: "Berapa tinggimu (cm)?"]
   ↓
◇ tinggi >= 140? ◇
  ↙ YA            TIDAK ↘
[Ucapkan          [Ucapkan
"Silakan masuk!"] "Maaf, belum boleh masuk."]
       ↓                 ↓
       └────────────────┘
              ↓
          [SELESAI]
```

**Blok Scratch:**
```scratch
[ketika bendera hijau diklik]
[tanyakan "Berapa tinggimu dalam cm?" dan tunggu]
[jika <(jawaban) >= (140)> maka]
    [ucapkan "Silakan masuk! Selamat bersenang-senang! 🎉" selama 3 detik]
[lain]
    [ucapkan "Maaf, tinggi minimum 140cm. Coba lagi tahun depan ya!" selama 3 detik]
```

**Langkah pengerjaan:**
```
1. Pilih sprite "Giga" atau sprite apapun yang cocok jadi penjaga
2. Ganti backdrop menjadi sesuatu yang cocok (misal: taman bermain)
3. Susun blok sesuai diagram di atas
4. Dari Kontrol: ambil [jika <> maka ... lain]
5. Dari Operator: masukkan [(jawaban) >= (140)]
6. Uji dengan beberapa nilai: 130, 140, 150, 200
```

> 💡 **Tips:** Operator `>=` berarti "lebih dari ATAU sama dengan". Gabungkan blok `>` dengan blok `=` menggunakan... tunggu dulu, di Scratch ada blok `>=` secara langsung!

---

### Task 2 — WAJIB: Kalkulator Nilai Rapor

**Yang dibuat:** Program yang mengubah nilai angka menjadi nilai huruf.

```
90–100  → A (Luar biasa!)
80–89   → B (Bagus sekali!)
70–79   → C (Cukup baik!)
60–69   → D (Perlu ditingkatkan)
0–59    → E (Ayo semangat belajar!)
```

**Tantangan:** Ini membutuhkan **nested if** atau **if-else if**. Di Scratch, caranya dengan **menaruh blok if-else di dalam blok if-else lain!**

**Struktur blok:**
```scratch
[ketika bendera hijau diklik]
[tanyakan "Masukkan nilaimu (0-100):" dan tunggu]

[jika <(jawaban) >= 90> maka]
    [ucapkan "Nilai A — Luar biasa!" selama 3 detik]
[lain]
    [jika <(jawaban) >= 80> maka]
        [ucapkan "Nilai B — Bagus sekali!" selama 3 detik]
    [lain]
        [jika <(jawaban) >= 70> maka]
            [ucapkan "Nilai C — Cukup baik!" selama 3 detik]
        [lain]
            [jika <(jawaban) >= 60> maka]
                [ucapkan "Nilai D — Perlu ditingkatkan" selama 3 detik]
            [lain]
                [ucapkan "Nilai E — Ayo semangat belajar!" selama 3 detik]
```

**Uji dengan nilai:** 95, 85, 75, 65, 45

---

### Task 3 — EKSPLORASI: Sprite Bereaksi terhadap Keyboard

**Yang dibuat:** Sprite yang berbeda-beda reaksinya tergantung tombol yang ditekan.

```scratch
[ketika bendera hijau diklik]
[selamanya]
    [jika <tombol [kanan] ditekan?> maka]
        [gerak 10 langkah]
        [ucapkan "Jalan kanan!"]
    [jika <tombol [kiri] ditekan?> maka]
        [gerak -10 langkah]
        [ucapkan "Jalan kiri!"]
    [jika <tombol [spasi] ditekan?> maka]
        [ucapkan "Lompat!" selama 0.5 detik]
        [ubah y sebesar 50]
        [tunggu 0.3 detik]
        [ubah y sebesar -50]
```

---

### Task 4 — BONUS: Game "Tebak Angkaku"

Buat game di mana:
1. Komputer "menyembunyikan" angka acak 1–10 (simpan ke variabel)
2. Pengguna menebak angkanya
3. Program memberitahu: "Terlalu besar!", "Terlalu kecil!", atau "Benar!"
4. Pengguna punya 3 kesempatan menebak

**Tantangan:** Bagaimana cara membatasi hanya 3 tebakan? (Petunjuk: gunakan variabel penghitung!)

---

## 🧠 Soal Latihan

### Pilihan Ganda

**1.** Kapan kita perlu menggunakan `if-else` dibanding hanya `if`?

a) Selalu — if-else lebih bagus dari if  
b) Ketika ada dua kemungkinan hasil yang berbeda  
c) Ketika kondisinya lebih dari satu  
d) Ketika nilai variabel berubah  

**2.** Perhatikan kode ini:
```
jika (nilai = 100):
    ucapkan "Sempurna!"
lain:
    ucapkan "Bagus!"
```
Jika nilai = 85, apa yang terjadi?

a) Program tidak melakukan apa-apa  
b) Program berkata "Sempurna!"  
c) Program berkata "Bagus!"  
d) Program error  

**3.** Manakah analogi if-else yang PALING tepat?

a) Kalkulator menghitung 2+2  
b) Lampu yang menyala terus  
c) Persimpangan jalan — belok kiri atau kanan tergantung tujuan  
d) Jam yang terus berputar  

---

### Analisis Kode

**4.** Perhatikan logika berikut dan jawab pertanyaannya:

```
jika (jam >= 6 DAN jam < 12):
    ucapkan "Selamat pagi!"
kalau jika (jam >= 12 DAN jam < 18):
    ucapkan "Selamat siang!"
kalau jika (jam >= 18 DAN jam < 21):
    ucapkan "Selamat sore!"
kalau tidak:
    ucapkan "Selamat malam!"
```

a) Jika jam = 9, apa yang diucapkan?  
b) Jika jam = 15, apa yang diucapkan?  
c) Jika jam = 23, apa yang diucapkan?  
d) Bisakah ada situasi di mana semua kondisi salah? Jelaskan!  

---

### Praktik

**5.** Tuliskan pseudocode (algoritma dalam bahasa Indonesia) untuk program berikut:

Program menanyakan apakah hari ini hari libur. Jika ya, program berkata "Hore, libur! Mau main apa?". Jika tidak, program menanyakan apakah ada PR. Jika ada PR, berkata "Kerjakan PR dulu ya!". Jika tidak ada PR, berkata "Santai deh, tidak ada PR!".

```
MULAI
  Tanyakan: ___________________________________
  JIKA _______________________________________:
      Ucapkan: ________________________________
  KALAU TIDAK:
      Tanyakan: _______________________________
      JIKA ___________________________________:
          Ucapkan: ____________________________
      KALAU TIDAK:
          Ucapkan: ____________________________
SELESAI
```

---

## 📎 Catatan Pengajar

### Kesalahan Umum

**Lupa blok "lain" ketika membutuhkannya:**
> Tanyakan: "Apa yang terjadi kalau kondisinya tidak terpenuhi? Apakah program perlu melakukan sesuatu?" Jika ya, tambahkan `lain`.

**Urutan kondisi yang salah dalam if-else if:**
> Jika anak memeriksa `nilai >= 70` sebelum `nilai >= 90`, maka nilai 95 akan masuk ke kondisi pertama dan tidak pernah mencapai kondisi kedua. Tekankan pentingnya urutan dari yang paling ketat ke paling longgar (atau sebaliknya, tapi konsisten).

**Membandingkan teks menggunakan angka:**
> `(jawaban) = "kucing"` berbeda dengan `(jawaban) = 1`. Pastikan anak paham kapan membandingkan angka dan kapan membandingkan teks.

### Tips Mengajar

- Mulai selalu dengan contoh fisik (kartu, roleplay) sebelum ke Scratch
- Tekankan: **gambar flowchart dulu**, baru koding
- Ketika anak membuat bug di percabangan, tanyakan: "Coba trace satu per satu — kondisi pertama dipenuhi tidak?"

---

## ➡️ Modul Berikutnya

[Modul 06 — Perulangan (Loop)](./06-perulangan.md)

---

*Fase 2 · Modul 05 dari 16 · Logika Coding SD*
