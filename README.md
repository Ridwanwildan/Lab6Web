# :rocket: Latihan Menggunakan Bootstrap

* Nama          : Hizbullah Ridwan
* NIM           : 312110055
* Kelas         : TI.21.B.1
* Mata Kuliah   : Pemrograman Web

Dalam latihan Bootstrap ini, saya menggunakan [Bootstrap Versi 5.2](https://getbootstrap.com/), [Google Chrome](https://www.google.com/intl/id_id/chrome/) sebagai web browser dan [Visual Studio Code](https://code.visualstudio.com/) sebagai teks editornya.      

Latihan ini adalah latihan slicing design website yang sudah ada ke bootstrap.      
Design nya bisa dilihat disini : [Capture1.PNG](https://github.com/Ridwanwildan/Lab6Web/blob/main/Screenshoots/Capture1.PNG)             

## Install CDN

Pertama adalah menyiapkan folder yang didalamnya berisi `index.html` dan  `style.css`. Kemudian buat html         
dasar seperti ini :            

```bash
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
    <title>Belajar Bootstrap</title>
</head>
<body>
    
</body>
</html>
```         

Disini sudah disiapkan link CDN bootstrap dan juga tambahan CSS eksternal buatan sendiri.         

## Add Header

Selanjutnya adalah menambahkan header. Didalam header ini sudah ditambahkan class yang berasal dari [Bootstrap](https://getbootstrap.com/)                    
dan ada juga class yang dibuat sendiri.          

```bash
<header>
    <h1 class="px-4 py-5 fw-bolder fs-2 font-color-grey">
        Layout Sederhana
    </h1>
</header>
```          

## Add Navbar

Untuk menambahkan navbar versi [Bootstrap](https://getbootstrap.com/) sebenarnya banyak berbagai macam         
pilihan, navbar ini disamakan tampilannya seperti design yang sudah ada sebelumnya. ditambah juga dengan       
CSS eksternal. Seperti ini :              

```bash
<nav class="navbar navbar-expand-lg bg-color-blue">
    <div class="container-fluid">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
                <a class="nav-link active fw-bolder font-color-white px-4" aria-current="page" href="#">Home</a>
                <a class="nav-link fw-bolder font-color-white px-4" href="#">Artikel</a>
                <a class="nav-link fw-bolder font-color-white px-4" href="#">About</a>
                <a class="nav-link fw-bolder font-color-white px-4" href="#">kontak</a>
            </div>
        </div>
    </div>
</nav>
```                   
