# JOBSHEET-02-WEB-LANJUT

## NAMA : Hanief Mochsin

## ABSEN : 15

## KELAS : TI-2F

-pengerjaan laporan jobsheet web lanjut lewat github

### Praktikum Pertama

![alt text](image.png)

-"Route::get('/hello')" untuk menampilkan string hello ke browser dalam bentuk URL bagian akhir.

![alt text](<gambar/Screenshot 2024-02-24 024255.png>)

-Kode tersebut mendefinisikan sebuah route yang mengembalikan string World ketika user mengunjungi URL /world dengan method GET sama seperti URL /hello sebelumnya.

![alt text](<gambar/Screenshot 2024-02-24 034111.png>)

-route URL "/" untuk menampilkan string "Selamat Datang".

![alt text](image-1.png)

-route URL "/About" untuk menampilkan string "NIM dan Nama saya".

### Praktikum Selanjutnya

![alt text](image-2.png)

-route URL {nama} sebagai parameter function ($name) lalu akan di return di dalam function nya dengan memanggil parameter.

![alt text](image-3.png)

-URL localhost/PWL_2024/public/user/ menghasilkan 404 not found karena tidak sesuai dengan pendefinisian pada route yang mengharuskan menggunakan parameter nama atau string.

![alt text](image-4.png)

-URL menggunakan route yang sudah didefinisikan dalam kode untuk menampilkan string yang berisi nilai dari parameter postId dan commentId.

![alt text](image-5.png)

-route URL {name?} dengan memberikan tanda tanyan pada kode tersebut mengartikan bahwa URL name nya menjadi bersifat opsional. parameter function ($name=null) apabila URL name nya dikosong akan di printkan sesuai isi dari function dengan isi parameter name tetap null atau kosong.

![alt text](image-6.png)

-selanjutnya hanya mengubah parameter yang tadinya default nya null sekarang di isi 'John'. jadi, apabila URL name tidak di isi atau kosong maka akan diprintkan sesuai dengan default parameter yang telah diubah tadi.

### Praktikum Selanjutnya

![alt text](image-7.png)

-URL /hello memanggil WelcomeController dengan class hello lalu print value class hello.

![alt text](image-12.png)

-membuat controller

![alt text](image-8.png)

-pengubahan route agar terhubung dengan controller

![alt text](image-9.png)

-Home controller

![alt text](image-10.png)

-about controller

![alt text](image-11.png)

-article controller

### Praktikum Selanjutnya

![alt text](image-13.png)

-generate photocontroller

![alt text](image-14.png)

-route list

![alt text](image-15.png)

-update controller

![alt text](image-16.png)

-hasil run dari view hello dari route dengan URL /greeting. jadi, dari view kita bsia membuat kode template untuk di inisiasi di route dengan URL tertentu dan value fungsi sesuai ketentuan

![alt text](image-17.png)

-hasil nya sama seperti sebelumnya, akan tetapi bedanya berada di function nya yang dipindahkan ke welcomecontroller jadi route hanya menginisiasi dari welcome controller untuk di print

![alt text](image-18.png)

-menambahkan occupation pada view, tidak jauh beda dengan sebelumnya hanya saja menambahkan satu variabel untuk diteruskan ke view

##TUGAS PRAKTIKUM POS

-home:
![alt text](image-19.png)

-kategory :

-1.babykid:

![alt text](image-20.png)

-2.foodbeverage:

![alt text](image-21.png)

-3.homecare:

![alt text](image-22.png)

-4.beautyhealth:

![alt text](image-23.png)

-halaman user:

![alt text](image-24.png)

-halaman penjualan:

![alt text](image-25.png)
