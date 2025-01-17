# Identifikasi Akun Paling Berpengaruh dalam Penyebaran Informasi COVID-19 Menggunakan Social Network Analysis

## Deskripsi
Pada penelitian ini, ingin diketahui apakah penyebaran informasi COVID-19 di Indonesia sudah efektif dan siapa saja orang yang berpengaruh dalam menyebarkan informasi tersebut. Untuk penelitian ini, akan digunakan pendekatan Social Network Analysis dengan dataset diambil dari Twitter.

## Progres
### 24 Maret 2020
Progress:
Baru dapat idenya. Hal yang perlu dilakukan adalah untuk mengambil data twitter untuk penelitian ini dan membuat network untuk mengetahui siapa user paling berpengaruh di Twitter dalam hal COVID-19.

Hal yang perlu dilakukan besok:
- Membaca mengenai Social Network Analysis For Startuo
- Membaca minimal 5 paper yang berkaitan dengan Social Network Analysis
- Mulai mengambil data dari Twitter

### 25 Maret 2020
Progress:
Data udah discraping, tapi kabar buruknya tidak bisa mengambil ribuan tweet per hari. Hanya beberapa kali momen dapat mengambil ribuan tweet. Sehingga, perlu dilakukan metode lain yang bisa mengambil data tweet. Buruknya, tidak bisa divisualisasikan menggunakan geospasial dan mengambil asosiasi tweet dengan laju pertumbuhan per hari.

Hal yang perlu dilakukan berikutnya:
- Melakukan Pra-Proses terhadap data tweet
- Melakukan eksplorasi n-gram, wordcloud, SNA, dll.
- Melakukan pemodelan topik menggunakan LDA untuk mengetahui topik apa yang sering dibahas terkait virus corona.

Tambahan:
Mungkin bakal mengubah limit dari scraping menjadi 1000 tweet per hari. Kalau berhasil, kemungkinan bisa dibuat pemodelan topik dan asosiasi.

Note:
Nanti aja. Belajar UTS dulu! 

## Referensi
### Paper
- [Implementasi Social Network Analysis pada Penyebaran Country Branding “Wonderful Indonesia”](https://www.researchgate.net/publication/321169993_Implementasi_Social_Network_Analysis_pada_Penyebaran_Country_Branding_Wonderful_Indonesia)
- [A social network analysis of Twitter: Mapping the digital humanities community](https://www.tandfonline.com/doi/pdf/10.1080/23311983.2016.1171458?needAccess=true)
- [Twitter tsunami early warning network: a social network analysis of Twitter information flows](https://ro.uow.edu.au/cgi/viewcontent.cgi?referer=https://scholar.google.com/&httpsredir=1&article=1141&context=eispapers)

### Books
- [Network Science](http://networksciencebook.com/) 
- Social Network Analysis For Startup

### Videos
- [Social Network Analysis - From Graph Theory to Applications - Dima Goldenberg - PyCon Israel 2019](https://www.youtube.com/watch?v=px7ff2_Jeqw)

### Lain-lain
- https://github.com/briatte/awesome-network-analysis