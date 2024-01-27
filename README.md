UAS - PEMROGRAMAN WEB
Apriandi syafiq f
i.2210098
ilmu komputer- eksekutif

1. 


<h1>
  link jwt : eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1bml2ZXJzaXRhcyI6IkRqdWFuZGEiLCJwcm9kaSI6IklsbXUgS29tcHV0ZXIiLCJpYXQiOjE2NzQyNzAwMDB9.Yr3mvqeWO9wVYkKaBAv6dzQHDCvnfN3wqazpe_j97-g
</h1>

2. <p>
  Aspek                              Arsitektur Monolitik                          Arsitektur Mikroservis
  Struktur Aplikasi                terdiri dari satu aplikasi tunggal              terdiri dari serangkaian layanan indenpenden mikriservis

  Skalabilitas                     Skalabilitas vertikal menambah daya pada       Skalabilitas horizontal menambah intance dari mikroservis
                                  intance perubahan membutuhkan deploy
                    

  Pengembangan dan                 perubahan membutuhkan deploy utuh              Memungkinkan perubahan dari deploy per mikroservis secara terpisah
  pemeliharaan

  tergantung antar                komponen saling terkait dan berbagi            setiap mikroservis indenpenden dapat dikembangkan secara terpisah
  komponen                        kode secara langsung

  Teknologi dalam                 biasanya menggunakan satu bahasa              setiap mikroservis dapat menggunakan bahasa pemrograman berbeda 
  bahasa pemrograman              pemrograman

  Pengelolaan data                database tunggal atau beberapa                database sendiri atau menggunakan penyimpanan data terdistribusi
                                   database terpusat

</p>


3.  <span>
    Middlewate
    Perangkat lunak yang bertindak sebagai perantara di antara aplikasi-aplikasi yang berbeda atau diantara lapisan-lapisan berbeda dalam satu aplikasi

Keuntungan dari penerapan middleware meliputi:
1. integritas sistem
   memungkinkan integrasi sistem yang berbeda, bahkan jika mereka menggunakan teknologi atau platform yang berbeda

2. kominikasi antar aplikasi
   Middleware memfasilitasi komunikasi antara aplikasi yang berjalan di lingkungan distribusi.

3. Skalabilitas
   Middleware dapat membantu dalam mencapai skalabilitas dengan memungkinkan penambahan atau pengurangan komponen-komponen sistem secara efisien.

   </span>


4.
 <head>
 Unit testing adalah salah satu jenis pengujian perangkat lunak yang dilakukan pada tingkat unit individu, seperti fungsi atau metode, untuk memastikan bahwa setiap unit tersebut berfungsi dengan benar.

 White Box Testing (Pengujian Kotak Putih):

Melibatkan pemeriksaan kode sumber dan struktur internal dari program.
Menguji jalur kode yang berbeda untuk memastikan bahwa setiap instruksi dieksekusi dengan benar.
Memastikan bahwa semua cabang kondisional tercakup.
Black Box Testing (Pengujian Kotak Hitam):

Tidak memperhatikan struktur internal kode sumber.
Menguji fungsionalitas dan respons dari unit tanpa mengetahui implementasinya.
Fokus pada input dan output yang benar.
Gray Box Testing (Pengujian Kotak Abu-abu):

Menggabungkan elemen dari pengujian kotak putih dan kotak hitam.
Pemeriksaan sebagian dari struktur internal kode sumber dan fungsionalitas eksternal.
Manual Testing (Pengujian Manual):

Dilakukan oleh manusia tanpa bantuan alat otomatis.
Memeriksa fungsionalitas, keamanan, kinerja, dan aspek-aspek lainnya secara manual.
Automated Testing (Pengujian Otomatis):

Menggunakan alat otomatis untuk menjalankan skrip pengujian.
Cepat dan efisien untuk pengujian yang berulang.
Memudahkan pengujian pada skala besar.
Mutation Testing (Pengujian Mutasi):

Mengubah sedikit kode sumber untuk menciptakan "mutan" atau variasi dari kode asli.
Mengujikan seberapa baik skrip pengujian dapat mendeteksi perubahan ini.
Menilai kualitas skrip pengujian.
Test-Driven Development (TDD):

Pendekatan pengembangan perangkat lunak yang dimulai dengan menulis tes sebelum mengimplementasikan fungsionalitas.
Memastikan bahwa setiap fitur atau fungsi diuji secara otomatis.
Behavior-Driven Development (BDD):

Pendekatan yang memfokuskan pengujian pada tingkat fungsionalitas dan perilaku aplikasi.
Menggunakan bahasa yang lebih terstruktur dan bisa dimengerti oleh orang non-teknis.
  
</head>


5. <body>
  KONTAINERISASI
  sebuah inovasi yang memberdayakan bundling, transportasi, dan menjalankan aplikasi beserta seluruh kondisinya dalam iklim yang tidak terlibat yang disebut "holder".

  DOCKER
  Docker adalah platform perangkat lunak yang memungkinkan pengembang untuk membuat, menguji, dan mendistribusikan aplikasi dalam kontainer. Docker menggunakan       teknologi kontainerisasi untuk mengisolasi aplikasi dan dependensinya dari lingkungan host

  KUBERNETES  
  Kubernetes, atau disingkat sebagai K8s, adalah platform open-source yang digunakan untuk mengelola dan orkestrasi kontainer. Kubernetes membantu dalam otomatisasi tugas-tugas seperti penjadwalan, penyebaran, dan penskalaan aplikasi berbasis kontainer. 
</body>

6.  <div class = CI/CD>
Continuous Integration (CI):
CI melibatkan penggabungan kode dari beberapa pengembang ke repository bersama secara teratur, biasanya beberapa kali sehari. Setiap kali ada perubahan kode, sistem CI akan secara otomatis memicu proses build dan menjalankan serangkaian tes otomatis untuk memastikan bahwa perubahan tersebut tidak merusak fungsionalitas eksisting. Jika terdapat kesalahan, tim pengembangan akan diberi tahu segera untuk memperbaiki masalah tersebut.

Continuous Deployment (CD):
Continuous Deployment melibatkan otomatisasi proses pengiriman dan implementasi perangkat lunak ke lingkungan produksi setelah lulus uji CI. Dengan CD, setiap kali ada perubahan yang lulus uji, perangkat lunak secara otomatis dideploy ke lingkungan produksi tanpa perlu campur tangan manusia. Ini mempercepat waktu rilis dan memastikan bahwa perubahan yang telah diuji secara menyeluruh segera tersedia bagi pengguna akhir.

Beberapa tools yang digunakan untuk CI/CD:

Jenkins:

Jenkins adalah platform CI/CD open-source yang sangat populer.
Mendukung otomatisasi build, uji, dan penerapan perangkat lunak.
Berintegrasi dengan berbagai alat dan lingkungan.
GitLab CI/CD:

GitLab menyediakan fitur CI/CD yang terintegrasi dengan repositori Git.
Memungkinkan definisi langkah-langkah CI/CD dalam file konfigurasi GitLab CI.
Travis CI:

Layanan CI/CD cloud-based yang bekerja dengan proyek-proyek GitHub.
Memungkinkan konfigurasi CI/CD dengan menggunakan file .travis.yml.
CircleCI:

Platform CI/CD cloud-based yang mendukung otomatisasi pengujian dan penerapan.
Mendukung integrasi dengan repositori GitHub dan GitLab.
TeamCity:

Platform CI/CD yang dikembangkan oleh JetBrains.
Memiliki fungsionalitas CI yang kuat dan dapat diintegrasikan dengan berbagai alat.
Bamboo:

Solusi CI/CD dari Atlassian yang terintegrasi dengan produk-produk Atlassian seperti Jira dan Bitbucket.
Spinnaker:

Platform pengiriman perangkat lunak terbuka yang dapat digunakan untuk CD.
Dirancang untuk menyederhanakan dan mempercepat pengiriman aplikasi di berbagai lingkungan.
  
</div>


7. <a href="https://apriandisyafiqfirdaus.github.io/websiteno7.github.io/">website untuk jawaban no 7</a>


    


        


