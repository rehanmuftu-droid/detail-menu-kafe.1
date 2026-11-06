# Detail Menu Kafe — Tugas Praktik Pertemuan 5

Aplikasi Flutter untuk mengubah halaman Detail Menu Kafe menjadi interaktif dengan tiga jenis state.

## Fitur
- Favorit: ikon hati berubah warna dan bentuk ketika ditekan.
- Jumlah pesanan: tombol tambah dan kurang; jumlah minimum adalah 1.
- Total harga: dihitung dari `hargaSatuan * jumlahPesanan` dan diperbarui otomatis.
- Catatan pesanan: teks disimpan melalui `onChanged` dan ditampilkan sebagai pratinjau langsung.
- Tombol Pesan menampilkan ringkasan total melalui SnackBar.

## Menjalankan proyek
1. Pastikan Flutter SDK dan Android Studio atau VS Code sudah terpasang.
2. Ekstrak folder proyek.
3. Buka folder `detail_menu_kafe` di VS Code.
4. Jalankan perintah:
   ```bash
   flutter pub get
   flutter run
   ```

## Bagian utama
Seluruh implementasi berada di `lib/main.dart`.

Harga satuan contoh ditetapkan sebesar Rp25.000 per porsi dan dapat diubah pada variabel `hargaSatuan` di kelas `_DetailMenuPageState`.
