# Panduan Kontribusi

Terima kasih sudah mau berkontribusi ke Awesome AI Indonesia. Daftar ini dijaga kualitasnya secara manual, jadi ada beberapa aturan sederhana.

## Cara menambahkan entri

1. Fork repo ini.
2. Tambahkan entri di bagian yang paling sesuai, dalam format ini:

   ```markdown
   - [Nama Proyek](https://tautan-resmi) — Deskripsi satu baris, jelas, tanpa kata-kata promosi.
   ```

3. Jaga urutan alfabetis di dalam tiap bagian (berdasarkan nama).
4. Kirim pull request. Tulis satu-dua kalimat kenapa entri itu layak masuk daftar.

## Aturan entri

- **Relevan dengan AI di Indonesia.** Model, dataset, komunitas, kursus, tools, perusahaan, atau riset yang berkaitan langsung dengan ekosistem AI Indonesia.
- **Tautan harus hidup.** Cek dulu sebelum mengirim. Tautan mati akan ditolak.
- **Deskripsi jujur dan singkat.** Satu baris. Jangan menulis klaim yang tidak bisa dibuktikan ("terbaik", "nomor satu", "paling cepat") kecuali ada sumbernya.
- **Bukan iklan.** Entri komersial boleh masuk hanya kalau produknya nyata dan berguna untuk komunitas (misalnya platform atau API yang dipakai banyak orang). Tautan afiliasi dan referral tidak diterima.
- **Bahasa Indonesia.** Deskripsi ditulis dalam Bahasa Indonesia. Nama proyek tetap seperti aslinya.

## Memperbaiki daftar

Menemukan tautan mati, deskripsi yang salah, atau entri yang sudah tidak relevan? Kirim pull request perbaikan — itu kontribusi yang sama berharganya dengan menambah entri baru.

## Memeriksa tautan

Sebelum mengirim pull request, jalankan pemeriksa tautan bawaan repo:

```bash
python3 scripts/check-links.py
```

Script ini memeriksa semua tautan di `README.md` dan melaporkan yang tidak bisa diakses.

## Kode etik

Bersikap sopan dan saling menghormati. Diskusi yang sehat dipersilakan; spam dan promosi terselubung tidak.
