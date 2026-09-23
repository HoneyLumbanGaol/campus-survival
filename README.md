# 🎒 Campus Survival

> **Misi bertahan hidup di kampus** — Bisakah kamu menaklukkan 7 hari tanpa tumbang?

Campus Survival adalah game simulasi manajemen waktu berbasis web yang menempatkan pemain sebagai mahasiswa baru yang harus menyeimbangkan kuliah, tugas, istirahat, makan, dan organisasi selama satu minggu penuh.

---

## 🎮 Tentang Game

Semester baru membawa tantangan baru! Kamu harus mengatur waktumu dengan bijak setiap harinya. Kuliah, tugas, makan, tidur, dan organisasi — semuanya ingin jatah waktumu!

Setiap hari terdiri dari **3 slot waktu** (Pagi, Siang, Sore) yang bisa kamu isi dengan satu kegiatan masing-masing. Pilih kegiatanmu dengan cermat agar semua status tetap terjaga hingga akhir minggu.

---

## 📊 Status Mahasiswa

Pantau 4 indikator berikut selama bermain:

| Indikator | Ikon | Keterangan |
|-----------|------|------------|
| **Energi** | ⚡ | Tingkat stamina tubuhmu |
| **Akademik** | 📈 | Nilai dan pemahaman materi |
| **Waktu Luang** | 🎈 | Kesehatan mental dan waktu pribadi |
| **Kenyang** | 🍱 | Kondisi perut dan asupan makan |

---

## 🗓️ Kegiatan yang Bisa Dipilih

Setiap slot waktu, pilih satu dari 6 kegiatan berikut:

| Kegiatan | Ikon | Efek Utama | Deskripsi |
|----------|------|------------|-----------|
| **Kuliah** | 🏫 | + Akademik | Hadiri kelas dan catat kehadiranmu |
| **Kerjakan Tugas** | 📝 | + Akademik | Kejar deadline sebelum terlambat |
| **Belajar Mandiri** | 📚 | + Akademik | Review materi untuk memperkuat pemahaman |
| **Istirahat** | 😴 | + Energi | Recharge baterai tubuh agar tidak burnout |
| **Makan Bergizi** | 🍜 | + Kenyang | Isi tenaga agar otak siap berpikir |
| **Organisasi** | 🎤 | + Relasi | Temui teman dan bangun pengalaman kampus |

---

## 📅 Jadwal 7 Hari

| Hari | Tema |
|------|------|
| Senin | Start yang cerah |
| Selasa | Tugas mulai berdatangan |
| Rabu | Pertengahan minggu |
| Kamis | Tetap fokus, ya! |
| Jumat | Finish line terlihat |
| Sabtu | Waktu untuk berkembang |
| Minggu | Hari terakhir yang santai |

---

## 🏆 Hasil Akhir

Setelah 7 hari, kamu akan mendapatkan salah satu dari tiga predikat:

| Predikat | Kondisi |
|----------|---------|
| 🏆 **Campus Legend** | Akademik ≥ 90, Energi ≥ 60%, Waktu Luang ≥ 40%, Kenyang ≥ 50% |
| 🌟 **Survivor Seimbang** | Akademik ≥ 75, Energi ≥ 45%, Waktu Luang ≥ 35%, Kenyang ≥ 40% |
| 🌱 **Masih Bertumbuh** | Belum memenuhi syarat di atas |

---

## ⚠️ Peringatan Harian

Di akhir setiap hari, game memberikan feedback:

- **⚠️ Hari yang Berat** — muncul jika Energi < 25%. Segera istirahat!
- **🍽️ Perut Protes** — muncul jika Kenyang < 25%. Jangan lupa makan!
- **✅ Jadwal Selesai** — kamu berhasil melewati hari dengan cukup seimbang.

---

## 🗂️ Struktur File

```
campus-survival/
├── index.html   # Struktur halaman utama dan UI game
├── style.css    # Desain visual, animasi, dan responsivitas
└── script.js    # Logika game, data kegiatan, dan mekanisme permainan
```

---

## 🚀 Cara Menjalankan

Tidak perlu instalasi atau server khusus. Cukup buka langsung di browser:

```
Buka file index.html di browser favoritmu
```

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** — Struktur dan markup halaman
- **CSS3** — Styling, animasi, dan desain responsif
- **Vanilla JavaScript** — Logika permainan tanpa framework tambahan
- **Google Fonts** — Tipografi menggunakan font *Baloo 2* dan *Nunito*

---

## 🎨 Desain & Fitur UI

- Latar belakang gradien berwarna biru-hijau yang cerah dan segar
- Elemen dekoratif animasi: awan ☁️ mengambang, bintang ✦ berkedip, maskot mahasiswa 🧑‍💻 memantul
- Bar status dengan transisi halus untuk setiap indikator
- Tampilan jadwal harian dengan timeline Pagi / Siang / Sore
- Grid kegiatan yang interaktif dengan efek hover
- Modal hasil akhir dengan animasi fade-in
- Desain responsif untuk layar mobile hingga desktop

---

> *"IPK penting, tapi kamu juga penting 💛"*
