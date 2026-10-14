# LKPD Interaktif: Usaha Rekayasa Bidang Sistem Teknik

LKPD web responsif untuk mata pelajaran Prakarya kelas XI SMA.

## Fitur
- Identitas peserta didik dan aktivitas isian interaktif
- Materi ringkas, studi kasus, rancangan produk, mini proyek
- Kalkulator biaya produksi, biaya per unit, harga jual, dan laba
- Evaluasi 10 soal dengan skor otomatis dan pembahasan
- Simpan/muat jawaban pada browser yang sama (localStorage)
- Cetak atau simpan ke PDF melalui menu cetak browser
- Dapat dihosting gratis menggunakan GitHub Pages

## Cara hosting di GitHub Pages
1. Unduh dan ekstrak ZIP ini.
2. Masuk ke https://github.com dan buat repository baru, misalnya `lkpd-rekayasa-sistem-teknik`.
3. Unggah file `index.html` ke bagian paling atas (root) repository. File `README.md` boleh ikut diunggah.
4. Buka **Settings → Pages**.
5. Pada **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
7. Tunggu proses publikasi selesai. URL biasanya berbentuk:
   `https://USERNAME.github.io/lkpd-rekayasa-sistem-teknik/`

## Catatan penting
- Ganti identitas sekolah/guru pada file `index.html` bila diperlukan.
- Jawaban tersimpan di browser/perangkat yang digunakan, bukan ke server atau akun guru. Jika siswa membuka LKPD di perangkat lain, jawaban tidak otomatis terkirim kepada guru.
- Untuk mengumpulkan jawaban, minta siswa menggunakan **Cetak / PDF** lalu mengirimkan PDF kepada guru, atau kembangkan versi lanjutan yang terhubung ke Google Sheets/backend.
- File ini tidak membutuhkan instalasi atau library eksternal.
