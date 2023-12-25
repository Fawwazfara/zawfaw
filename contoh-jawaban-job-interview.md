## 1.1 Latar Belakang
selamat datang di web anteiku residensies disini kami menyediakan rumah rumah mewah di komplek anteiku residencies tentu saja pemandangan indah di komplek kami tidak kalah dengan yg lain nya di komplek kami kami menyediakan rumah mewah bertype macam macam kami juga menyediakan taman hiburan untuk anak anak, resto, gym, dan toserba. dengan komplek yg luas dan indah tentu saja tidak akan membuat kita bosan. dengan ini kami membantu anda mendapatkan rumah impian.

## 1.2. Deksripsi Teknologi Informasi

MongoDB:

Deskripsi: MongoDB adalah basis data NoSQL yang fleksibel dan dapat diskalakan secara horizontal. Digunakan untuk menyimpan data proyek Anda, termasuk informasi tentang residensi, penghuni, dan detail lainnya.
Express.js:

Deskripsi: Express.js adalah kerangka kerja web untuk Node.js. Digunakan untuk membuat backend aplikasi, menangani rute, dan berkomunikasi dengan basis data MongoDB.
React.js:

Deskripsi: React.js adalah library JavaScript yang digunakan untuk membangun antarmuka pengguna yang responsif dan dinamis. Digunakan dalam proyek Anda untuk membuat frontend aplikasi web Anteiku Residencies.
Node.js:

Deskripsi: Node.js adalah runtime JavaScript yang memungkinkan penggunaan JavaScript di sisi server. Digunakan sebagai backend untuk menangani logika bisnis, rute, dan berkomunikasi dengan MongoDB.
Auth0:

Deskripsi: Auth0 adalah layanan manajemen otentikasi dan otorisasi. Digunakan untuk mengimplementasikan otentikasi pengguna, kontrol akses, dan keamanan di situs web Anda.
Prisma:

Deskripsi: Prisma adalah ORM (Object-Relational Mapping) untuk Node.js dan TypeScript. Mempermudah interaksi dengan MongoDB, menyediakan API deklaratif dan aman.
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
pengguna | bisa memilih lokasi residens    | ada 3 cabang yaitu bandung jakarta jogja                | ⭐⭐⭐⭐
pengguna | melihat denah komplek           | bisa menentukan jalan apabila tidak ingat jalan| ⭐⭐⭐⭐⭐
pengguna | melihat type rumah & rumahnya   | agar bisa memilih tipe yg di idamkan dan di inginkan          | ⭐⭐⭐⭐
pengguna | melihat fasilitas rumah         | bisa melihat ada berapa kamar rouftop dll                     | ⭐⭐⭐⭐⭐
pengguna | melihat fasilitas di komplek    | bisa peri ke gym moll taman dll                   | ⭐⭐⭐⭐⭐
pengguna | melihat rumah mana saja yg kosong atau tidak| bisa tahu kita punya tetangga atau tidak                 | ⭐⭐⭐
pengguna | memboking rumah yg akan di review | rumah yg di cari tidak terjual ke org lain                       | ⭐⭐⭐
pengguna | membatalkan boking              | bisa membatalkan dan memilih type lain                         | ⭐⭐⭐
pengguna | melihat jadwal pertemuan   yg senggang | bisa sampai kepada saya                                       | ⭐⭐⭐
pengguna | meng inbox penanggung jawab rumah | agar bisa menentukan jadwal survey   | ⭐⭐⭐⭐⭐
pengguna | mamasukan rumahnya yg akan di jual | setelah di setujui admin maka bisa di jual                      |⭐⭐⭐
pengguna | bisa login dgn email             | jiga tidak login hanya bisa melihat lihat saja        | ⭐⭐⭐⭐⭐  
pengguna | melihat lokasi rumah            |  bisa menentukan lokasi yg enak                                  | ⭐⭐⭐⭐ 
pengguna | mengatur tanggal pertemuan             |   apabila melebihi maka boking di batalkan              |  ⭐⭐⭐⭐ 
pengguna | memiliki jasa antar makanan atau tumpangan  |  memesan makanan di resto atau driver        | ⭐⭐⭐⭐  
pengguna | bisa melihat harga             |   bisa mempertimbangkan beli atau tidak                |   ⭐⭐⭐
pengguna | memiliki fasilitas keamanan  |  apanila terjadi sesuatu di rumah nyalakan saja bel     |   ⭐⭐⭐⭐⭐⭐
pengguna | melihat event             | melihat event agustusan kurban dll                         |   ⭐⭐⭐⭐⭐
pengguna | melihat updatean            |   melihat apa yg baru di bangun atau semua kejadian di komplel    |   ⭐⭐⭐⭐⭐
pengguna | melihat pengumuman           |   melihat berita berita     |   ⭐⭐⭐⭐⭐





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

Pada pembuatan aplikasi kali ini saya menggunakan beberapa teknologi informasi diantaranya :
1. untuk database saya menggunakan mongodb kenapa saya menggunakan karana mongodb adalah Basis data NoSQL yang berfokus pada penyimpanan dokumen JSON-style. Cocok untuk pengembangan aplikasi skala besar dan fleksibel. mongodb juga berbasis dokumen kalau mysql berbasis tabel
2. untuk framework saya menggunakan express js sebagai backend
3. untuk library saya menggunakan React.js, Mantine, React Query sebagai front-end
 * react js Fungsi: Library JavaScript untuk membangun antarmuka pengguna (UI) yang bersifat deklaratif dan efisien. Dikembangkan oleh Facebook, React memungkinkan pengembang untuk membuat UI yang dinamis dan mudah dikelola
 * mantine Fungsi: Library desain komponen untuk React. Mantine menyediakan sejumlah komponen siap pakai dan gaya bawaan, mempercepat pengembangan UI dan memastikan konsistensi desain
 * react query Fungsi: Library untuk mengelola state data di aplikasi React. React Query membantu Anda mengelola data asinkron, caching, dan menyediakan alat untuk membuat pengembangan aplikasi dengan data dinamis menjadi lebih efisien.
4. untuk autentikasi email pasword dll saya menggunakan Auth0
5. dan saya menggunakan object relational mapping (ORM) yaitu menggunakan prisma agar mudah berinteraksi dengan data base.

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
