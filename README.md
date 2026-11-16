### Tugas 7

Progress mingguan:
- Membuat tampilan awal portofolio mobile dengan Flutter
- Menambahkan tombol interaktif dengan SnackBar

Refleksi:
1. Widget tree adalah struktur yang terdiri dari widget. Setiap widget dapat memiliki child berupa widget lain. Parent dapat mengatur tampilan child, seperti ukuran dan posisi.
2. MyApp: Menjalankan aplikasi dan menentukan halaman yang ditampilkan
InfoCard: Menampilkan NPM, nama lengkap, dan kelas.
MyHomePage: Berfungsi sebagai halaman utama
ItemCard: Menampilkan tombol di halaman utama
3. MaterialApp adalah widget yang mengatur tampilan aplikasi secara keseluruan. MaterialApp umum digunakan sebagai root widget karena konfigurasinya dapat diwariskan oleh widget-widget lain.
4. StatelessWidget adalah widget yang tidak mengubah data setelah dibuat, sedangkan StatefulWidget adalah widget yang dapat berubah saat aplikasi berjalan. StatefulWidget biasanya menggunakan method setState() untuk mengubah isinya.
5. BuildContext adalah objek yang digunakan untuk menandai lokasi widget di widget tree. BuildContext penting untuk menentukan tema aplikasi dan ukuran widget, serta menampilkan SnackBar.
6. Hot reload adalah fungsi yang memuat ulang aplikasi tanpa harus dijalankan dari awal. Hot restart menjalankan ulang aplikasi, sehingga kecepatannya lebih lambat daripada hot reload. Hot reload tidak cukup ketika inisialisasi ulang aplikasi diperlukan. Misalnya, saat method main() berubah.

AI Declaration:
Saya tidak menggunakan AI untuk mengerjakan tugas mingguan ini. Untuk menyelesaikan tugas ini, saya menggunakan tutorial, petunjuk implementasi tugas, dan dokumentasi Flutter sebagai referensi.