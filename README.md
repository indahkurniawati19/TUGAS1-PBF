# TUGAS1-PBF Indah Kurniawati S-220102085

## Apa itu CodeIgniter?
CodeIgniter adalah salah satu FreamWork yang ada di PHP yang bersifat Open Source yang menggunakan Metode MVC (Model,Viwe,Controler). Framwork (softwear freamwork) adalah sudatu kerangka kerja yang berisi aturan” sesuai dengan bahasanya, dan ada fungsi” yang reuseability atau di gunakan berulang”
#### **Mengapa Perlu Menggunakan CodeIgniter**
1.	Small footprint = Ci adalah  freamwork yang ukuran nya kecil 
2.	Perfomance yang baik
3.	Hampir ”zero configuration” = hanya dengan menginstall saja sudah siap di gunakan tidak banyak melakukan konfigurasi
4.	Tidak harus menggunakan command line
5.	Tidak harus mengikuti aturan coding yang ketat 
6.	Tidak harus menggunakan tempalte engine
7.	Dokumentasi yang jelas
8.	Menggunakan mvc
## Installation
#### Syarat Menginstall CodeIgniter
Diperlukan PHP minimal versi 7.4 atau lebih baru.
#### **Installation Composer**
   1.Cek apakah ada composer atau tidak dengan perintah :
```shell
$ composer -v
```
<img width="620" alt="Screenshot 2024-03-18 101440" src="https://github.com/indahkurniawati19/TUGAS1-PBF/assets/134476013/0f2fa79c-8580-42cc-aba9-e2f97d499dfe">

2. Buka folder root yang akan digunakan untuk menyimpan Folder CodeIgniter, lalu buka CMD lalu ketik
    <img width="311" alt="Screenshot 2024-03-18 095234" src="https://github.com/indahkurniawati19/TUGAS1-PBF/assets/134476013/8343a220-8d85-4c85-8fda-5227b7a06f77">
    
    atau bisa klik kanan lalu buka folder tersebut lewat Terminal. dan Ketikkan :
```shell
$ composer create-project codeigniter4/appstarter nama-project
```
perintah di atas memerlukan koneksi internet pada saat install, maka dari itu cepat atau lambat nya proses install di pengaruih dengan koneksi internet

3. Jalankan server
```shell
$ cd nama-root
$ php spark serve
```

#### **Installation Manual**
1. Install Manual CodeIgniter4 melalui web resminya, dan hasil downloadnya berbentuk zip 
[CodeIgniter 4.](https://www.codeigniter.com/download)
2. Lalu Ekstrak folder CodeIgniter yang sudah di download ke direktori root web server pada penyimpanan, Jika menggunakan laragon maka exctract pada C:\laragon\www
4. Jalankan server dengan masuk ke dalam root project yang terdapat folder CI → code editor (Visual Studio Code) → Terminal atau masuk ke Command Prompt → ketik :
```shell
$ cd nama-root
$ php spark serve
```
5. Perintah diatas akan menjalankan Codeigniter 4 di port 8080. Proses running ini akan terus berjalan sampai jika ingin memberhentikan maka menekan tombol CTRL+C 
Untuk melihat hasilnya, silahkan buka browser dan arahkan ke http://localhost:8080/.
