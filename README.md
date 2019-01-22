# Tutorial penggunaan GIT

Pada langkah awal sebelum membuat repositori konfigurasikan username dan email anda yang sudah didaftarkan pada server GIT
## Langkah pertama
Konfigurasikan username anda, ditulis didalam tanda dua petik.
![1 username](https://user-images.githubusercontent.com/45659535/51545239-1fdbc380-1e94-11e9-8924-d4d2cb93eaf4.PNG)

## Langkah kedua
Konfigurasikan email
![2 email](https://user-images.githubusercontent.com/45659535/51546099-00de3100-1e96-11e9-842f-c7a5c354c2e8.PNG)

## Langkah ketiga
Buatlah repository local  yang akan menjadi tempat menyimpan repositori aktif pada penyimpanan lokal anda
![3 tempat menyimpan](https://user-images.githubusercontent.com/45659535/51546114-0b002f80-1e96-11e9-8559-b9cb447019d1.PNG)

## Langkah keempat
Buatlah folder direktori yang akan ada di dalam tempat penyimpanan repositori aktif anda
![4 folder penyimpanan](https://user-images.githubusercontent.com/45659535/51546272-6500f500-1e96-11e9-90b2-5eae1fc84467.PNG)

## Langkah kelima
Masuk ke folder direktori yang ada di dalam tempat penyimpanan diatas
![5 masuk ke direktori](https://user-images.githubusercontent.com/45659535/51546277-6af6d600-1e96-11e9-9d57-4e20d1156828.PNG)

## Langkah keenam
Buat lagi folder direktori, contoh : latihan1
![6 masuk folder latihan1](https://user-images.githubusercontent.com/45659535/51546298-764a0180-1e96-11e9-9756-d578496d19e2.PNG)

## Langkah ketujuh
Masuk ke folder direktori diatas
![masuk ke direktori latihan1](https://user-images.githubusercontent.com/45659535/51546323-8530b400-1e96-11e9-842a-fe1c41d56845.PNG)

## Langkah kedelapan
Inisialisasi repository local. Pada direktori ini semua perubahan pada working directory akan disimpan
![8 inisialisasi folder latihan1](https://user-images.githubusercontent.com/45659535/51546337-8a8dfe80-1e96-11e9-8ebb-d04eb95decce.PNG)

## Langkah kesembilan
Menambahkan file baru pada folder direktori, disini kita akan coba buat satu file bernama README.md
![9 membuat file readme](https://user-images.githubusercontent.com/45659535/51546345-8f52b280-1e96-11e9-8cf9-040df59bf41d.PNG)

## Langkah kesepuluh
Menambahkan file yang baru dibuat diatas gunakan perintah **git add** dan menyimpan keterangan perubahan menggunakan
**git commit -m "komentar commit**.
![10 menambahkan commit](https://user-images.githubusercontent.com/45659535/51546357-937ed000-1e96-11e9-934e-62819aefbe2f.PNG)

## Langkah kesebelas
**Membuat repositori online (server)**
server repositori yang kita gunakan adalah *http://github.com*, anda juga harus sudah memiliki akun. kemudian klik tombol start a new project atau dari menu (**icon +**) klik **New Repository**
isi nama repository, cth : Latihan1
lalu klik tombol **Create Repository**
![11 membuat repositori online](https://user-images.githubusercontent.com/45659535/51546367-9aa5de00-1e96-11e9-9f72-e3204b3f33e9.PNG)

## Langkah kedua belas
Remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat di akses oleh banyak user, kita menggunakan perintah **git remote add origin [URL]**
![12 remote repo online](https://user-images.githubusercontent.com/45659535/51546382-a09bbf00-1e96-11e9-83b5-60e8a0268b9c.PNG)

## Langkah ketiga belas
Kirim perubahan pada repository local ke server menggunakan perintah **git push**, perintah ini akan meminta memasukkan username dan password pada akun *github.com*
![13 push perubahan ke server](https://user-images.githubusercontent.com/45659535/51546405-a5607300-1e96-11e9-8bfc-b1cbf4c7d95b.PNG)

## Langkah keempat belas
Melihat hasilnya pada server masuklah ke laman *github.com* lalu arahkan ke repositori yang sudah kita buat maka akan tampil perubahan yang sudah kita buat diatas
![hasil pada server](https://user-images.githubusercontent.com/45659535/51546417-aabdbd80-1e96-11e9-8bc0-6796dd7e679a.PNG)

## Langkah kelima belas
Clone Repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktori sesuai dengan nama repositorinya (working repository) kita menggunakan perintah **git clone [URL]**
![15 cloning](https://user-images.githubusercontent.com/45659535/51546425-aee9db00-1e96-11e9-8de5-53a907c5040c.PNG)
