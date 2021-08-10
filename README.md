# Template-wisataku
ini adalah bahan-bahan yang digunakan untuk membuat template wisataku
- download https://github.com/hendikaseptio/template-wisataku/archive/refs/heads/main.zip dan ekstrak file dimana anda membuat project nya
- lalu anda dapat memulainya dengan membuat file index.html sebagai halaman utama

# Membuat tampilan 
untuk membuat tampilan pada halaman web yang anda buat anda bisa ikuti langkah berikut :
- buat folder baru dengan nama css
- buka folder tersebut dan tambahkan file baru dengan nama style.css
- agar style yang anda buat berfungsi gunakan kode berikut pada file index.html
- <link rel="stylesheet" type="text/css" href="css/style.css">
- letakkan kode tersebut didalam element <head></head>

# Menggunakan Bootstrap icon
anda dapat menambahkan beberapa icon dengan menggunakan bootstrap icon dengan cara memasukkan kode berikut :
<link rel="stylesheet" href="vendor/bootstrap-icons/bootstrap-icons.css">
untuk informasi cara penggunaan bootstrap icon anda dapat mengunjungi website officialnya https://icons.getbootstrap.com/

# Menggunakan font 
anda dapat menggunakan font dengan cara mengimport font yang sudah saya sediakan
- buka file style.css anda dan tambahkan style berikut :
@font-face {
	font-family: 'poppins';
	src: url('../font/Poppins-Light.ttf');
}
sekarang anda dapat menggunakan font tersebut dengan cara sebagai berikut :
body {
	font-family: 'poppins';
	margin: 0;
}
