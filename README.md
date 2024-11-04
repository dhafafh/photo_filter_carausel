# Dhafa Firjatullah Hikmal (362358302074)

TUGAS PRAKTIKUM
-
![image](https://github.com/user-attachments/assets/fad64e70-1b76-48f9-a2ec-54bf5fffd8bb)
-

Jelaskan maksud void async pada praktikum 1?
-

Void Async digunakan untuk menunjukan bahwa suatu fungsi bersifat Asinkkron. Yaitu Fungsi tersebut tidak diblokir, Sehingga Program lain dapat terus dijalankan sambil menunggu Asinkkron menjalankan tugasnya
-

Jelaskan fungsi dari anotasi @immutable dan @override ?

Anotasi @immutable dalam bahasa pemrograman Dart digunakan untuk menunjukkan bahwa suatu kelas bersifat immutable, artinya properti atau atribut yang dikandungnya tidak dapat diubah setelah objek dibuat. Penggunaan anotasi ini penting selama pengembangan aplikasi Flutter untuk memastikan bahwa widget atau objek yang dibuat bersifat konstan, sehingga menghindari perubahan status yang tidak disengaja yang dapat menyebabkan kesalahan. Dengan menandai kelas dengan @immutable, pengembang akan diperingatkan oleh pemeriksa kode statis (analyzer) jika ada upaya untuk mengubah properti setelah inisialisasi.

Sementara itu, anotasi @override digunakan untuk menunjukkan bahwa metode atau properti dalam suatu kelas mengesampingkan implementasi metode atau properti dengan nama yang sama dari superclass-nya. Anotasi ini berguna untuk memperjelas bahwa metode tersebut bukanlah definisi baru, melainkan pembaruan dari metode di superclass. Hal ini membantu mencegah kesalahan ketik atau perubahan yang tidak disengaja pada tanda tangan metode, yang dapat menyebabkan kesalahan. Dengan @override, pengembang dapat memastikan bahwa metode yang diterapkan cocok dengan metode superclass dan dapat dipanggil atau dimodifikasi sesuai kebutuhan.
