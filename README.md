# Aplikasi Pertambahan Dua Angka

## Deskripsi Program
Aplikasi ini memungkinkan pengguna untuk:
- Memasukkan dua angka.
- Menampilkan hasil penjumlahan kedua angka saat tombol **Tambah** diklik.
- Menghapus nilai input dan mengarahkan fokus ke input pertama saat tombol **Hapus** diklik.
- Menutup aplikasi saat tombol **Keluar** diklik.

## Logika Program
1. **Penjumlahan**:
   - Menjumlahkan dua angka yang dimasukkan pengguna.
2. **Validasi Input**:
   - Memastikan input berupa angka.
   - Menampilkan pesan error dengan `JOptionPane` jika input tidak valid.
3. **Pengelolaan Event**:
   - `ActionListener` untuk menangani tombol **Tambah**, **Hapus**, dan **Keluar**.
   - `KeyAdapter` untuk membatasi input pada kolom hanya angka.
   - `FocusListener` untuk membersihkan input otomatis saat mendapat fokus.
