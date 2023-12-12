## 1.1 Latar Belakang
selamat datang di web anteiku residensies disini kami menyediakan rumah rumah mewah di komplek anteiku residencies tentu saja pemandangan indah di komplek kami tidak kalah dengan yg lain nya di komplek kami kami menyediakan rumah mewah bertype macam macam kami juga menyediakan taman hiburan untuk anak anak, resto, gym, dan toserba. dengan komplek yg luas dan indah tentu saja tidak akan membuat kita bosan. dengan ini kami membantu anda mendapatkan rumah impian.

## 1.2. Deksripsi Teknologi Informasi

Pada pembuatan aplikasi kali ini saya menggunakan beberapa teknologi informasi diantaranya :
1. untuk database saya menggunakan mongodb kenapa saya menggunakan karana mongodb adalah Basis data NoSQL yang berfokus pada penyimpanan dokumen JSON-style. Cocok untuk pengembangan aplikasi skala besar dan fleksibel. mongodb juga berbasis dokumen kalau mysql berbasis tabel
2. untuk framework saya menggunakan express js sebagai backend
3. untuk library saya menggunakan React.js, Mantine, React Query sebagai front-end
  * react js Fungsi: Library JavaScript untuk membangun antarmuka pengguna (UI) yang bersifat deklaratif dan efisien. Dikembangkan oleh Facebook, React memungkinkan pengembang untuk membuat UI yang dinamis dan mudah dikelola
  *mantine Fungsi: Library desain komponen untuk React. Mantine menyediakan sejumlah komponen siap pakai dan gaya bawaan, mempercepat pengembangan UI dan memastikan konsistensi desain
  *react query Fungsi: Library untuk mengelola state data di aplikasi React. React Query membantu Anda mengelola data asinkron, caching, dan menyediakan alat untuk membuat pengembangan aplikasi dengan data dinamis menjadi lebih efisien.
4. untuk autentikasi email pasword dll saya menggunakan Auth0
5. dan saya menggunakan object relational mapping (ORM) yaitu menggunakan prisma agar mudah berinteraksi dengan data base.
## 1.3. Branding

- nama produk anteiku residencies
- tagline : "wujudkan rumah idaman mu, surga ku adalah rumah ku"
- campaign :Eksklusifnya Hunian Mewah di anteiku residencies Temukan Rumah Impian Anda!
-target user :
  *Profesional Sukses
  *Pasangan Muda Profesional
  *Pensiunan Aktif
  *Investor Properti
  *Ekspatriat dan Profesional Asing
  *Kolektor Properti Mewah
  *Pembeli yang Menilai Keamanan
-user experience theme:
  *Desain Minimalis dan Bersih
  *Palet Warna Elegan
  *Tata Letak Responsif
  *Visualisasi Properti yang Menggoda
  *Fasilitas Interaktif
  *Pengalaman Pendaftaran yang Mulus
  *Informasi yang Jelas dan Rinci
  *Sistem Pemilihan Bahasa dan Mata Uang


## 2. User Story

sebagai  |        saya ingin bisa          |                   sehingga                                    | prioritas
---------|---------------------------------|---------------------------------------------------------------|---
pengguna | bisa memilih lokasi residens    | bisa menyesuaikan dgn barang yg ingin di beli                 | ⭐⭐⭐⭐⭐
pengguna | melihat denah komplek           | bisa menyesuaikan apabila ada bahan yg tidak ingin di sertakan| ⭐⭐⭐⭐⭐
pengguna | melihat type rumah & rumahnya   | bisa lebih meyakinkan membeli di web saya                     | ⭐⭐⭐⭐⭐
pengguna | melihat fasilitas rumah         | bisa mendapatkan hidangan yg berkualitas                      | ⭐⭐⭐⭐⭐
pengguna | melihat fasilitas di komplek    | bisa melihat hidangan dan penambah selera                     | ⭐⭐⭐⭐⭐
pengguna | melihat rumah mana saja yg kosong atau tidak| bisa mengantarkan pesanan dgn cepat dan tepat                 | ⭐⭐⭐⭐⭐
pengguna | memboking rumah yg akan di review | bisa memasukan apa saja yg ingin dibeli                       | ⭐⭐⭐⭐
pengguna | membatalkan boking              | bisa mengganti dengan produk yg lain                          | ⭐⭐⭐
pengguna | memngatur pertemuan                  | bisa sampai kepada saya                                       | ⭐⭐⭐⭐
pengguna | meng inbox penanggung jawab rumah | bisa memberikan kepercayaan kpd org yng akan membeli produk   | ⭐⭐⭐⭐⭐
pengguna | mamasukan rumahnya yg akan di jual |                                                             |⭐⭐⭐⭐⭐
pengguna | bisa login dgn email             |                                                                | ⭐⭐⭐⭐⭐  
pengguna | melihat lokasi rumah            |                                                                | ⭐⭐⭐⭐⭐  
pengguna | mengatur tanggal pertemuan             |                                                          |  ⭐⭐⭐⭐⭐ 
pengguna | mencari jenis rumah              |                                                                | ⭐⭐⭐⭐⭐  
pengguna | bisa melihat harga             |                                                                |   ⭐⭐⭐⭐⭐
pengguna | melihat fasilitas keamanan             |                                                                |   ⭐⭐⭐⭐⭐
pengguna | melihat event             |                                                                |   ⭐⭐⭐⭐⭐
pengguna | melihat updatean            |                                                                |   ⭐⭐⭐⭐⭐





## 3. Struktur Data

Cara membuat aneka macam bentuk grafik menggunakan mermaid.js bisa lihat di [https://mermaid.js.org/syntax/entityRelationshipDiagram.html](https://mermaid.js.org/syntax/entityRelationshipDiagram.html) 

graph TD
  subgraph Frontend
    ReactJS --> Mantine
    ReactJS --> ReactQuery
  end

  subgraph Backend
    NodeJS --> ExpressJS
    ExpressJS --> Prisma
    NodeJS --> MongoDB
    ExpressJS --> Auth0
  end


## 4. Arsitektur Sistem

Masih pake mermaid.js juga bisa lihat flowchart di [https://mermaid.js.org/syntax/flowchart.html](https://mermaid.js.org/syntax/flowchart.html)

## 5. Teknologi, Library, dan Framework

bla bla bla

## 6. Desain User Experience dan User Interface

Bisa load image 
![Contoh](https://fastly.picsum.photos/id/318/536/354.jpg?hmac=Ixy-wle80nudIR_cmnF1iY2y6rMUH7_9sk-BP1fTpM8)

## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini
