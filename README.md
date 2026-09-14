Menampilkan lokasi Anda sekarang
# pwd

Membuat folder latihan_terminal
# mkdir latihan_terminal

Masuk ke folder latihan_terminal
# cd latihan_terminal

melihat isi folder latihan_terminal
# ls

Membuat folder dokumen
# mkdir dokumen

Membuat folder cadangan
# mkdir cadangan

Menampilkan isi folder secara rinci
# ls -l

Masuk ke folder dokumen
# cd dokumen

Membuat file catatan.txt
# touch catatan.txt

Membuat file profil.txt
# touch profil.txt

Mengisi file catatan.txt dengan sebuah catatan
# echo "Ini adalah catatan pertama saya di terminal" > catatan.txt

Menampilkan isi file tersebut
# cat catatan.txt

Menambahkan teks pertama ke file profil.txt
# echo "Nama saya adalah pengguna terminal" > profil.txt

Menambahkan teks kedua ke file profil.txt
# echo "Saya sedang belajar 50 perintah dasar" >> profil.txt

Menampilkan isi file profil.txt
# cat profil.txt

Melihat file yang telah dibuat di dalam folder
# ls

Memindahkan file profil copy.txt ke folder cadangan
# mv profil_copy.txt cadangan/

Melihat isi folder cadangan
# ls cadangan/

Mengganti nama file catatan.txt ke folder dokumen
# mv catatan.txt jurnal.txt

Melihat isi file yang terdapat difolder saat ini
# ls

Menyalin file jurnal.txt ke folder dokumen
# cp jurnal.txt dokumen/

Masuk ke folder dokumen
# cd dokumen

Melihat isi yang ada dalam folder dokumen
# ls

menampilkan baris kesatu dari file jurnal.txt
# head -n 1 jurnal.txt

menampilkan baris kedua dari file jurnal.txt
# tail -n 1 jurnal.txt

Digunakan untuk melihat kembali ke folder sebelumnya
# cd . .

Digunakan untuk mencari kata "belajar" dalam file profil.txt
# grep "belajar" profil.txt

Mencari file jurnal.txt pada folder saat ini
# find . -name "jurnal.txt"

Menampilkan kalender
# cal

Menampilkan nama pengguna 
# whoami

Menampilkan informasi sistem secara lengkap
# uname -a

Melihat ukuran folder secara keseluruhan
# du -sh

Melihat informasi penggunaan ruang penyimpanan
# df -h

Menampilkan seluruh isi folder, termasuk file tersembunyi, beserta informasi detailnya
# ls -la

Mengubah hak akses file profil.txt
# chmod 777 profil.txt

Menampilkan informasi file profil.txt secara rinci
# ls -l profil.txt

Membuat arsip dari folder dokumen dan cadangan 
# -cvf arsip_data. tar dokumen/ cadangan/ dokumen/ 

Melihat file dan folder yang terdapat pada folder saat ini
# ls

Menguji jaringan koneksi sebanyak 3 kali
# ping -c 3 8.8.8.8

Menampilkan riwayat perintah yang telah di jalankan 
# history

Membersihkan tampilan layar
# clear

Menghapus file jurnal .txt
# rm jurnal.txt

Menghapus folder cadangan beserta isinya
# rm -r cadangan

Perintah ls
# ls

Menampilkan proses yang sedang berjalan pada sistem
# ps

menampilkan informasi penggunaan memori
# free

Menampilkan informasi waktu sistem telah aktif dan bebas sistem
# uptime

Menampilkan alias atau perintah singkat yang telah dibuat
# alias

menampilkan pesan bahwa seluruh latihan telah selesai
# echo "Selamat! saya berhasil menyelesaikan 50 perintah command line!"
# df -h

