#Pembuatan Form Login dan Registrasi Interaktif
1. Tambahkan validasi yang lebih baik. Misalnya, cek apakah email
 memiliki format yang benar (mengandung ’@’) atau password memiliki panjang
 minimal 6 karakter:
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/6a65dc59-78ae-42c5-9214-3406a1067d2c" />
<img width="677" height="515" alt="image" src="https://github.com/user-attachments/assets/5624ea36-6437-4a06-979d-ceab64222d38" />
-jika password tisak sesuai ketentuan 6 karakter yang telah di tentuak:
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/816af357-1d62-412d-9d50-c5cc6fe9f257" />
2. Tampilkan/Sembunyikan Password: Tambahkan ikon mata pada TextField password yang bisa ditekan untuk menampilkan atau menyembunyikan teks password
-pada bagian register
<img width="1362" height="1340" alt="image" src="https://github.com/user-attachments/assets/7707b0b6-62ce-430c-9546-efbe4079ad7b" />
hasilnya 
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/d968867f-c627-46fd-9baf-114d6d833e80" />
terdapat icon mata pada password bagian ujung kanan dan juga pada bagian passoword dapat menyembunyikan password yang akan kita masukkan
3. Animasi Sederhana: Tambahkan Hero widget pada ikon di halaman login dan registrasi agar ada transisi animasi yang halus
-pada register
<img width="1026" height="708" alt="image" src="https://github.com/user-attachments/assets/7e8da900-8167-4dfc-a329-443e517fb51d" />
-pada login
<img width="974" height="708" alt="image" src="https://github.com/user-attachments/assets/0acbc759-e274-4978-a398-3c8dda108701" />
4. Simpan Sesi Login: Coba gunakan package shared_preferences untuk menyimpan status login. Jadi, saat aplikasi ditutup dan dibuka lagi, pengguna tidak perlu login ulang jika sesinya masih aktif.
-pada login
<img width="1498" height="484" alt="image" src="https://github.com/user-attachments/assets/db72dfd4-a367-406b-aa1e-312d11a9a27f" />
-main.dart
<img width="1616" height="1714" alt="image" src="https://github.com/user-attachments/assets/e85c6281-8dc3-4eb4-87b3-bd72cb49c2e5" />
-Shared Preferences ditambahkan ke pubspec.yaml agar aplikasi bisa menyimpan status login pengguna secara lokal. Tanpa itu, Flutter tidak dapat menemukan dan menggunakan paket tersebut untuk menyimpan data.
<img width="1498" height="1378" alt="image" src="https://github.com/user-attachments/assets/f75e6a79-f013-4993-88b4-7f36810467c4" />
hasilnya:
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9369b6fb-4bb4-4c22-ab75-029e59009f54" />











