# EAS KPPL E

Nama  : Muhammad Irsyad Habibi

NRP  : 50255221150

Kelas  : KPPL E

- __Dalam Pengembangan Perangkat Lunak ada fase Analisis dan Desain.__
  
   - __Terangkan aktivitas yang dilakukan dalam fase Analisis dan Desain__
     
     Dalam fase analisis, fokus utamanya adalah menganalisis kebutuhan. Kebutuhan software secara umum dibagi menjadi 2, yaitu kebutuhan fungsional dan kebutuhan non fungsional. Jika perangkat lunak yang akan dibuat adalah Hotel Reservation System, maka kebutuhan fungsionalnya adalah customer dapat melakukan transaksi dengan memesan kamar secara online, dan admin hotel dapat mengetahui riwayat pesanan dari customer dan kamar mana yang masih kosong.
     Dalam fase desain, secara umum terbagi menjadi 2, yaitu desain UI dan desain database. Contoh desain UI pada aplikasi Hotel Reservation System sederhana adalah sebagai berikut.
     ![Screenshot (119)](https://github.com/user-attachments/assets/df04dc2f-1e24-4a57-a66c-b56da7a2cae0)
     
     Desain database berarti menganalisis entitas dalam sistem, atribut yang dimilikinya, dan relasi antar entitas. Sebagai contoh, dalam Hotel Reservation System, terdapat beberapa entitas, yaitu Customer, Admin Hotel, Kamar Hotel, dan Transaksi. Dalam entitas kamar hotel, terdapat beberapa atribut, seperti nomor kamar, jenis bed (single, duo), dan harga kamar.
   - __Apa Output dari aktivitas tersebut untuk mendukung pengembangan perangkat lunak.__
     
     Output dari fase analisis dan desain adalah untuk mendapatkan gambaran yang jelas dari requirement software dan desain sebelum lanjut ke tahap implementasi.

- __Dalam model Waterfall, setiap tahap memiliki fungsi spesifik. Jelaskan lima tahap utama dalam model ini, serta sebutkan kelebihan dan kekurangan dari model tersebut dalam konteks proyek besar yang memiliki persyaratan tetap.__
  
  Terdapat lima tahap utama dalam mengembangkan software menggunakan metode waterfall, yaitu:
  - Requirement Analysis
    Pada tahap ini, pengembang harus mengetahui kebutuhan pengguna terhadap perangkat lunak. Informasi tersebut umumnya diperoleh melalui survei, wawancara, dan diskusi. Selanjutnya, informasi itu dianalisis dan diolah, sehingga pengembang memperoleh berbagai data yang cukup lengkap terkait detail kebutuhan pengguna terhadap perangkat lunak yang nantinya akan dikembangkan. Selain kebutuhan pengguna, perlu dipersiapkan juga kebutuhan pengembang dalam proses pengembangan perangkat lunak, dapat berupa software pendukung yang dapat digunakan untuk membantu pengembang.
  - Design
    Secara umum, tahap tersebut meliputi kepentingan desain teknis seperti lapisan data, bahasa pemrograman, layanan, dan sebagainya. Spesifikasi desain umumnya akan dibuat untuk menguraikan logika bisnis yang nantinya akan diimplementasikan secara teknis. Hal tersebut bertujuan untuk memberikan gambaran menyeluruh mengenai sesuatu yang harus dikerjakan dan tampilan dari suatu sistem yang diinginkan, sehingga membantu keperluan hardware (perangkat keras) dan sistem supaya lebih spesifik, serta mendefinisikan arsitektur sistem yang akan disusun secara menyeluruh.
  - Implementasi
    Tahap implementasi adalah tahap pemrograman (coding). Pembuatan perangkat lunak nantinya akan dibagi menjadi modul-modul kecil yang akan dikombinasikan pada tahap berikutnya. Pada fase ini juga dilaksanakan pemeriksaan mengenai fungsionalitas modul yang telah dibuat, sudahkah memenuhi kriteria yang diharapkan atau belum.
  - Testing
    Pada tahap ini akan dilaksanakan penggabungan berbagai modul yang telah dibuat sebelumnya dan mengintegrasikannya dalam suatu sistem secara keseluruhan. Setelah proses integrasi selesai, nantinya akan dilaksanakan pemeriksaan dan pengujian sistem secara menyeluruh untuk mengidentifikasi kemungkinan adanya kesalahan dan kegagalan dalam perangkat lunak. Jika dirasa sudah layak, maka perangkat lunak akan dirilis.
  - Maintenance
    Pada tahap ini, perangkat lunak sudah dirilis dan sudah dioperasikan oleh penggunanya. Meskipun perangkat lunak sudah dirilis, perlu dilakukan juga pemeliharaan berupa perbaikan implementasi unit sistem, perbaikan bug, dan peningkatan sistem sesuai dengan kebutuhan.

    Kelebihan dari metode waterfall adalah alur kerja(workflow) yang sudah terurut dan jelas, dan cocok untuk proses pengembangan perangkat lunak berskala kecil dan menengah karena cukup hemat biaya (tidak ada pengetesan oleh klien dalam proses pengembangan), dan metode ini cukup mudah dipahami sebagai dasar dalam proses pengembangan perangkat lunak.
    Kekurangan dari metode waterfall adalah kurangnya fleksibilitas karena setiap tahapan pengembangan harus dilakukan secara berurutan. Selain itu, waktu pengembangan dapat berlangsung relatif lama, sebagai contoh tim pengembang tidak dapat memulai proses implementasi sebelum mendapatkan desain UI dan database dari tim desain.
    
- __Jelaskan perbedaan antara architectural design dan detailed design. Mengapa kedua jenis desain tersebut diperlukan dalam proses pengembangan perangkat lunak?__
  
  Architectural Design merupakan gambaran umum dari struktur sistem. Ini mencakup bagaimana komponen utama saling berhubungan, bagaimana data mengalir di antara komponen, dan bagaimana interaksi antar subsistem. Tujuannya adalah untuk mengidentifikasi struktur perangkat lunak, teknologi yang akan digunakan, dan pola arsitektur (misalnya, client-server, peer to peer).

  Detailed Design merupakan rincian teknis dari setiap komponen yang diidentifikasi dalam architectural design, bertujuan untuk mendefinisikan bagaimana setiap komponen sistem akan diimplementasikan secara spesifik. Hasilnya dapat berupa pseudocode, diagram kelas, dan spesifikasi API.

  Kedua Jenis Desain ini diperlukan dalam proses pengembangan perangkat lunak dengan tujuan untuk mempermudah pengelolaan tentang kompleksitas sistem, memastikan konsistensi dan kesesuaian, efisiensi dalam kolaborasi tim, meningkatkan skalabilitas dan kualitas, serta mempermudah proses dokumentasi dan pemeliharaan. Dengan memadukan kedua jenis desain ini, proses pengembangan perangkat lunak dapat lebih terstruktur dan efisien.
  
- __Sebuah perusahaan membutuhkan sistem e-commerce untuk menjual produk digital seperti foto, video, desain poster, ebook. Saat ini transaksi dihandle dengan WhatsApp. Namun seiring dengan perkembangan bisnis tools tersebut tidak mampu menangani lonjakan transaksi. Buatkan sistem / aplikasi yang mampu menangani lonjakan transaksi pada musim tertentu. Jelaskan pendekatan rekayasa perangkat lunak yang akan Anda gunakan untuk merancang, membangun, dan menguji sistem tersebut agar memenuhi kebutuhan klien.__
  
  Untuk merancang dan membangun sistem e-commerce yang mampu menangani lonjakan transaksi pada musim tertentu, digunakan pendekatan pengembangan perangkat lunak yang berfokus pada skalabilitas dan performa. Pendekatan ini menggunakan metode waterfall yang mencakup beberapa tahap utama, yaitu analisis kebutuhan, desain, implementasi, pengujian, dan pemeliharaan.

  - Analisis Kebutuhan
    - Pengumpulan Kebutuhan:
      - Wawancara dengan klien untuk memahami alur bisnis dan fitur yang diinginkan, seperti katalog produk, sistem pembayaran, pengelolaan pelanggan, dan laporan penjualan.
      - Identifikasi kebutuhan non-fungsional seperti skalabilitas, keamanan, dan waktu respons yang cepat selama puncak transaksi.
    - Dokumentasi Kebutuhan:
      - Menghasilkan dokumen spesifikasi kebutuhan perangkat lunak (SRS) yang mencakup kebutuhan fungsional (fitur) dan non-fungsional (kinerja, keamanan).

  - Desain Sistem
    - Architectural Design
     - Pendekatan Arsitektur:
       - Microservices: Sistem dipecah menjadi layanan kecil seperti katalog, pembayaran, pengguna, dan pengelolaan produk. Ini memungkinkan layanan untuk diskalakan secara independen.
       - Cloud Deployment: Gunakan cloud seperti AWS atau Google Cloud untuk memastikan skalabilitas.
       - Database yang Scalable: Gunakan database relasional untuk transaksi untuk caching atau data yang tidak terstruktur.
       - Load Balancing: Gunakan load balancer untuk mendistribusikan lalu lintas data dalam jaringan supaya beban kerja setiap server tersebar secara merata.

    - Detailed Design
      - Desain Antarmuka Pengguna: Mockup atau wireframe untuk antarmuka pengguna.
      - API Specification: Desain API REST/GraphQL untuk komunikasi antar layanan.
      - Diagram Kelas dan Diagram Aktivitas: Untuk mendokumentasikan logika komponen individual.


  - Implementasi
    - Penggunaan CI/CD: Otomatisasi integrasi dan pengujian untuk mempercepat siklus pengembangan.
    - Penerapan Keamanan:
      - Proteksi data dengan enkripsi (HTTPS, TLS).
      - Pengelolaan autentikasi pengguna.

  - Pengujian
    Pengujian Fungsional: Verifikasi semua fitur sesuai dengan spesifikasi, seperti pencarian produk, checkout, dan pembayaran.
    Pengujian Non-Fungsional:
     - Load Testing: Pastikan sistem dapat menangani lonjakan transaksi selama musim puncak.
     - Stress Testing: Simulasikan beban ekstrim untuk mengidentifikasi batas maksimum.
     - Security Testing: Uji kerentanan terhadap serangan siber.
   Pengujian Pengguna: lakukan pengujian dengan end user untuk memastikan pengalaman pengguna sesuai harapan.

   - Pemeliharaan
     - Iterasi berkala untuk menambahkan fitur baru berdasarkan feedback dari user.
     - Penyesuaian sistem jika terjadi perubahan kebutuhan bisnis.
