# PR16m18
JayJay Bootcamp Pekerjaan rumah 16 | Module 18
Tugas khusus Gradle dan add libraries
  Kriteria:
1. Tugas Gradle sederhana untuk menerima parameter CLI dan mencetaknya dengan pesan ucapan.
2. Proyek skrip Gradle harus dibuat di repositori yang berbeda dan dorong ke GitHub.
  Detail:
- Proyek Gradle baru  ada atas perintah "gradle init --type java-library" dengan struktur direktori dan file nama "build.gradle" awal.
- Gradle menjalankan tugas dengan menjalankan perintah berikut: "./gradlew greetingTask -Pname=YourName"
- File menambahkan pustaka menggunakan fitur manajemen dependensi bawaan Gradle.
- Melakukan tambahkan kode dependencies  ke file "build.gradle"
- Proyek telah didorong ke GitHub dengan membuat repositori "PR1618"
- Dokumentasi pengerjaan https://docs.google.com/spreadsheets/d/1QxEHJ_e1e3lqSnD0GBWfq7_6bhcucOFk/edit?usp=sharing&ouid=102679944825117484129&rtpof=true&sd=true
- Sebagaian kode tersebut langkah-langkah untuk membuat proyek Java dengan menggunakan Gradle, menambahkan tugas Gradle khusus untuk menyapa pengguna, menambahkan dependensi ke proyek, dan mengunggah proyek ke repositori GitHub. Berikut adalah penjelasan dari setiap langkah:

1. `gradle init --type java-library`
Ini adalah perintah yang digunakan untuk menginisialisasi proyek Gradle dengan jenis proyek `java-library`. Ini akan membuat struktur proyek dasar yang cocok untuk pengembangan perpustakaan Java.

2. Tugas Gradle `greetingTask()`
Ini adalah definisi dari sebuah task Gradle bernama `greetingTask`. Task ini memiliki aksi `doLast` yang mencetak pesan sapaan kepada pengguna. Pesan sapaan akan mencetak nama yang diterima sebagai properti atau menggunakan nilai default 'Gradle User' jika nama tidak disediakan.

3. `./gradlew greetingTask -Pname=YourName`
Ini adalah cara untuk menjalankan task Gradle yang baru saja dibuat. Anda dapat menjalankannya dari terminal dengan menggunakan `./gradlew` (atau `gradlew.bat` di Windows), diikuti dengan nama task (`greetingTask`) dan mungkin properti tambahan (`-Pname=YourName`).

4. Konfigurasi Dependensi
Ini adalah bagian dari file `build.gradle` yang menentukan dependensi proyek. Dependensi yang didefinisikan di sini adalah `com.google.guava:guava:29.0-jre` dan `junit:junit:4.13`. Ini berarti proyek akan menggunakan pustaka Guava versi 29.0-jre dan JUnit versi 4.13.

5. Inisialisasi dan Unggah ke GitHub
Langkah-langkah ini menjelaskan cara menginisialisasi repositori Git lokal, menambahkan semua perubahan ke dalamnya, membuat commit, menambahkan remote repository GitHub, dan mengunggah perubahan ke GitHub.
