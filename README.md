Simulasi Pendaftaran Mahasiswa

1. Mahasiswa Melakukan Pendaftaran
-Program akan menampilkan daftar mahasiswa yang melakukan pendaftaran secara bersamaan
-Setiap mahasiswa akan mendaftar dalam waktu antara 2 hingga 5 detik secara acak.
2. Menampilkan Mahasiswa yang Berhasil Mendaftar
-Setelah semua proses pendaftaran selesai, program mengambil nama mahasiswa dan menampilkan daftar mahasiswa yang berhasil mendaftar.
3. Menentukan Mahasiswa yang Terlambat Mendaftar
-Program memilih secara acak beberapa mahasiswa yang terlambat mendaftar.
-Jika ada mahasiswa yang terlambat, mereka akan menjalani proses pendaftaran terpisah.
4. Mahasiswa Terlambat Melakukan Pendaftaran
-Mahasiswa yang terlambat mendaftar akan menjalani pendaftaran.
-Waktu pendaftaran dilakukan dalam waktu 2 hingga 5 detik secara acak.
5. Pendaftaran dengan AsyncIO
-Mahasiswa yang terlambat juga disimulasikan menggunakan AsyncIO untuk menunjukkan alternatif konkuren lainnya.
-Setiap mahasiswa akan melakukan pendaftaran secara asinkron, sehingga beberapa mahasiswa dapat mendaftar bersamaan tanpa harus menunggu yang lain selesai.
6. Simulasi dengan MPI
-Program juga mensimulasikan penggunaan MPI4PY, yang sering digunakan dalam komputasi paralel berbasis distribusi.
-Setiap proses MPI mencetak informasi tentang rank (ID) dari proses tersebut.
7. Spawning dan Menghentikan Proses
-Program membuat proses baru yang mewakili mahasiswa tambahan.
-Setelah beberapa detik, proses ini dihentikan secara paksa.
8. Menampilkan Waktu Eksekusi dan Konfirmasi Ulang
-Program menampilkan total waktu eksekusi untuk seluruh proses pendaftaran.
-Pengguna diberikan pilihan untuk mengulang simulasi atau mengakhiri program.
Hasil SS
![GambarSS_UKSister1](https://github.com/user-attachments/assets/cb483199-8d11-40b0-9e6c-cc0f2dbf025d)
![GambarSS_UKSister2](https://github.com/user-attachments/assets/c6ec96cd-8877-4edd-99a7-9b9d3f0c970d)

