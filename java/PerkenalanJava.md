# Sejarah Singkat Java

Java secara resmi diperkenalkan oleh SUN Microsystems pada dunia pada tanggal 23 Mei 1995. Sedangkan sejarah pembangunan java sendiri sudah dimulai sejak tahun 1991. Saat itu tim “ Stealth Project “ mengadakan pertemuan (brainstorming) untuk menciptakan suatu system software yang mampu berjalan pada alat-alat elektronik (small devices)

James Gosling berkonsultasi pada ide permbuatan bahasa pemograman. Pada Juni 1991 , munculah bahasa interpreter “Oak” yang menjadi cikal bakal dari Java. Kemudian secara resmi pada tahun 1995 Java diperkenalkan bersama browser HotJava, Java pun merambah ke dunia Web-apps.

Kenyataan ini mungkin agak sedikit berbeda dengan ide pembuatan java pada awalnya. Internet ternyata membantu membuat Java terkenal seperti sekarang ini. Memang harus diakui karena semakin berkembangnya Internet, maka focus pemrograman saat ini mengarah ke pemrograman Internet itu sendiri.

Saat ini Java dibagi menjadi 3 framework atau teknologi yaitu J2SE untuk pemograman aplikasi berbasis console dan desktop, kemudian J2EE berskala enterprise seperti aplikasi web-base (JSP dan Sevplet), komponen (EJB), web service dan lain-lain. Kemudian framework yang terakhir adalah J2ME untuk pemograman small device seperti handphone dan PDA.

# Komponen-komponen Dalam Java

1. **JDK *(Java Development Kit)*** adalah sebuah software yang biasa digunakan untuk membuat
   aplikasi Java. Salah satu fungsi JDK yaitu untuk melakukan compiling baris kode yang telah kita tulis untuk dijalankan. Adapun fungsi lain JDK selain compiler diantaranya :

    - Interpreter / loader
    - Archiver
    - Documentation generator
    - DLL

2. **JRE *(Java Runtime Environment)*** adalah sebuah software yang digunakan untuk menjalankan
   aplikasi berbasis Java. Dengan JRE kalian bisa menjalankan aplikasi berbasis Java tetapi tidak bisa membuat aplikasi berbasis Java.

3. **JAVA SE *(Standar Edition)*** adalah software dari Java yang sudah termasuk JDK dan JRE. Jadi
   Java SE sudah termasuk JDK dan JRE. Jika ingin menggunakan dan membuat aplikasi berbasis Java bisa install langsung Java SE karena didalamnya sudah termasuk JDK dan JRE.

4. **JVM *(Java Virtual Machine)*** dalah machine abstract dengan spesifikasi tertentu yang
   menyediakan lingkungan untuk runtime untuk menjalankan bytecode dari Java (Apliksi yang dibuat dengan java). JVM tersedia untuk banyak platform hardwre maupun software. Bytecode Java (aplikasi Java) yang dikomplilasi oleh JDK bukan merupakan bytecode native yang langusung dapat dimengeri oleh OS, untuk itu JVM hadir sebagai *jubir* yang akan menjembantani antara OS dengan bytecode java.
    JVM melakukan tugas-tugas utama sbb:
    - Membuka kode (Loads code)
    - Verifikasi kode
    - Mengeksekusi kode
    - Menyediakan runtime environment

# Siklus Hidup Java

![Java Lifecycle](https://grassroothoper.files.wordpress.com/2015/01/kedudukan-java.jpg)

``` Kesimpulan : Untuk mengembangkan aplikasi menggunakan Java kita membutuhkan JDK yang akan mengkompilasi kode yang kita buat, sedangkan untuk menjalan aplikasi dari java kita hanya membutuhkan JRE saja. Antara JDK, JRE dan JVM ketiganya mempunyai konfigurasi berbeda untuk setiap OS dan membuat Java menjadi Bahasa pemograman yang dapat berjalan di banyak OS. ```


Situs yang dibangun menggunakan Teknologi Java
- Gmail
- LinkedIn
- BCA
- Bank Mandiri
- BCA Life Insurance

