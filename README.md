# Wikipedia Scraping for Company Rankings
![image](https://github.com/user-attachments/assets/6f1d63a5-2af8-4c5a-a3df-4d94d54e807a)
Kelompok 2 project UAS praktikum MDS

---
# 🧩 Overview
Wikipedia, ensiklopedia bebas, tidak hanya menjadi sumber pengetahuan yang kaya, tetapi juga menjadi tempat yang sangat berguna untuk mengakses informasi terkini, termasuk perusahaan-perusahaan dengan peringkat tertinggi berdasarkan pendapatan. Artikel-artikel yang ada di Wikipedia sering kali mencakup data yang mendetail tentang peringkat perusahaan di berbagai sektor industri, dengan informasi yang diperbarui secara berkala, termasuk pendapatan tahunan, laba, dan posisi mereka di pasar global.

Peringkat perusahaan berdasarkan pendapatan ini sering kali muncul dalam artikel-artikel seperti "Daftar perusahaan dengan pendapatan tertinggi" atau "Perusahaan terbesar menurut pendapatan", yang merangkum data dari laporan keuangan publik dan sumber terpercaya lainnya. Dengan akses terbuka yang dimiliki Wikipedia, siapa saja dapat dengan mudah menemukan informasi terbaru mengenai perusahaan-perusahaan terkemuka di dunia tanpa harus mengunjungi banyak situs web atau laporan tahunan.

Namun, untuk mempermudah akses ke informasi ini, sering kali dilakukan scraping data dari artikel-artikel Wikipedia. Teknik ini memungkinkan pengguna untuk secara otomatis mengumpulkan data tentang peringkat perusahaan berdasarkan pendapatan dan menganalisisnya lebih lanjut. Dengan menggunakan scraping, informasi yang terkandung dalam daftar perusahaan yang besar dan terus berkembang ini dapat dikumpulkan dengan cepat dan efisien, sehingga mempermudah riset atau analisis lebih mendalam.

# 🔍  Deskripsi Projek
Projek ini bertujuan untuk mengimplementasikan proses scraping data dari sumber-sumber terbuka, seperti artikel Wikipedia, untuk mengumpulkan informasi yang relevan tentang perusahaan-perusahaan berdasarkan peringkat dan pendapatan. Data yang diperoleh akan diambil secara otomatis melalui teknik scraping yang efisien, memastikan informasi yang terkumpul selalu up-to-date dan akurat.

Setelah data terkumpul, proyek ini akan menghubungkan hasil scraping ke database MongoDB, yang memungkinkan penyimpanan data secara terstruktur dan skalabel. MongoDB dipilih karena kemampuannya untuk menangani volume data yang besar dan fleksibilitas dalam menyimpan berbagai jenis informasi.

Selanjutnya, proyek ini akan melakukan agregasi data menggunakan kemampuan MongoDB untuk mengolah dan menganalisis data secara efektif. Proses agregasi ini memungkinkan untuk menyusun laporan atau statistik yang memberikan wawasan lebih dalam mengenai peringkat perusahaan, pendapatan, dan faktor-faktor lain yang relevan. Dengan pendekatan ini, diharapkan proyek dapat memberikan hasil analisis yang cepat, akurat, dan mudah diakses, serta berguna untuk berbagai aplikasi dalam dunia bisnis dan riset.

# 🛠️ Tahapan Projek
1. Web Scrapping
Langkah awal dilakukan dengan mengambil data dari Wikipedia mengenai daftar perusahaan dengan pendapatan tertinggi (List of largest companies by revenue). Menggunakan R dengan library rvest, data yang diambil pada perusahaan seperti nama, negara asal, industri, dan total revenue 
2. Membuat Koneksi
Setelah data berhasil di-scrape, data disimpan dalam database MongoDB, setelah penyimpanan, koneksi ke R dilakukan menggunakan package mongolite, yang memungkinkan R terhubung langsung ke database MongoDB. Berikut adalah contoh membuat koneksi langsung ke R.
4. Membuat Visualisasi
Setelah data berhasil diambil dari MongoDB ke dalam data frame di R, tahap selanjutnya adalah membuat konsep visualisasi. Visualisasi ini akan membantu menyampaikan insight secara lebih intuitif.
5. Membuat Aggregasi
Selanjutnya data perlu diolah untuk menghasilkan agregasi yang informatif, seperti melihat 10 perusahaan yang memiliki revenue tertinggi, rata-rata pendapatan perusahaan per industri, 10 perusahaan dengan profit paling tinggi dan lain sebagainya.
Agregasi ini dilakukan setelah membuat koneksi di R, sehingga aggregasi ini langsung di R menggunakan dplyr.
6. Membuat Github Readme
Seluruh proses dan hasil dari proyek ini didokumentasikan dalam file README.md di GitHub. README menjelaskan apa tujuan proyek, data apa yang digunakan, serta alur kerja secara keseluruhan. Harapannya dokumentasi kami di Readme dapat membuat pembaca untuk langsung memahami maksud dan cakupan proyek tanpa harus membaca semua baris kode.

# 📊 Dashboard Analisis
![image](https://github.com/user-attachments/assets/cfa05749-0fbf-4d31-a95c-da1c5a2b72e7)
![image](https://github.com/user-attachments/assets/13c03ad4-e7ec-442f-91ae-224514f45f60)
![image](https://github.com/user-attachments/assets/8edbe768-9c5d-4e9d-afed-1ed6cf5c9ebc)
![image](https://github.com/user-attachments/assets/b4fe7f54-e734-4382-8d3c-0f9fa1d9f607)

Jika ingin melihat dashboardnya lebih rinci, anda bisa mengaksesnya melalui link berikut ini:
https://charts.mongodb.com/charts-dbnajih-sdejqvp/public/dashboards/68314d68-f651-4eac-8bd3-1898cdc320e3





 
