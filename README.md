# Lab5web

Nama : dean pratama saputra

NIM  : 312210114

Kelas : TI.22.A1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Instruksi Praktikum|[Click Here](#instruksi-praktikum)|
|2|Langkah-langkah Praktikum|[Click Here](#langkah-langkah-praktikum)|
|3|Pertanyaan dan Tugas|[Click Here](#pertanyaan-dan-tugas)|

## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama Lab5Web
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
4. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org


## Langkah-langkah Praktikum
> - Persiapan membuat dokumen HTML dengan nama file `lab5_javascript.html` seperti berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
<script>
    document.write("Hello World");
    console.log("Hello World");
</script>
</body>
</html>
```

<img width="960" alt="lab 5 alert" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/f98da699-46b9-4a77-9150-9381cb593e78">



**1. Javascript Dasar**
> - Pemakaian `Alert` sebagai property window
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>alert box</title>
</head>
<body>
    <script language = "javascript" >
    <!-- 
    window.alert("ini merupakan pesan untuk anda");
    //-->
    </script>
</body>
</html>
```

<img width="960" alt="lab 5 alert" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/63f1a9ef-88ed-416d-8a02-55176135f6de">



> - Pemakaian `Method` dalam objek
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>skrip javascript</title>
</head>
<body>
percobaan memakai javascript:<br>
    <script language = "javascript" >
    <!-- 
    document.write("selamat mencoba javascript<br>");
    document.write("semoga sukses!");
    //-->
    </script>
</body>
</html>
```

<img width="960" alt="lab 5 web javascript" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/f3e9a7cc-ec8a-49d3-8faf-1095fde10209">



> - Pemakaian `Prompt`
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>pemasukan data</title>
</head>
<body>
    <script language = "javascript" >
    <!-- 
    var nama = prompt("siapa nama anda?","masukkan nama anda");
    document.write("hai, " + nama);
    //-->
    </script>
</body>
</html>
```



<img width="960" alt="lab 5 web prompt" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/7cd946fa-86a2-4d06-9c69-d5cde0528279">



> - Pembuatan `Fungsi` dan cara pemanggilannya
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>contoh program javascript</title>
    <script language="javascript">
    function pesan(){
        alert ("memanggil javascript lewat body onload")
    }
    </script>
</head>
<body onload=pesan()>
</body>
</html>
```
<img width="960" alt="lab 5 fungsi html" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/c60786a6-14b6-420e-b76a-ab16adb9f12d">




**2. Dasar Pemrograman di Javascript**
> - Operasi dasar `aritmatika`
```
<html>
<head>
    <title>contoh program javascript</title>

    <script language="javascript">
    function test (val1,val2)
    {
        document.write("<br>"+"perkalian : val1*val2 "+"<br>")
        document.write(val1*val2)
        document.write("<br>"+"pembagian : val1/val2 "+"<br>")
        document.write(val1/val2)
        document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
        document.write(val1+val2)
        document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
        document.write(val1-val2)<img width="960" alt="lab 5 fungsi html" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/02d23b29-aa91-40ed-8424-e5c9981c3b30">

        document.write("<br>"+"modulus : val1%val2 "+"<br>")
        document.write(val1%val2)
    }
    </script>
</head>
<body>
    <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
    </body>
    </html>
```

<img width="960" alt="lab 5 web konsep dasar aritmatika" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/164c60be-8dfc-4660-bef3-6d0dd898adb3">




> - Seleksi kondisi `(if..else)`
```
<html>
<head>
    <title>contoh if-else</title>
</head>
<body>
    <script language = "javascript">
    <!--
      var nilai = prompt("nilai (0-100): ", 0);
      var hasil = "";
      if (nilai >= 60)
      hasil = "lulus";
      else 
      hasil = "tidak lulus";
      document.write("hasil:" + hasil);   
    //-->
    </script>
</body>
</html>
```

<img width="960" alt="lab 5 web seleksi kondisi" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/7b1f36a2-6e13-40d4-b0ac-cee70a4a8578">



> - Penggunaan operator `switch` untuk seleksi kondisi
```
<html>
<head>
    <title>contoh program javascript</title>

<script language="javascript">
function test ()
{
    val1=window.prompt("input nilai (1-5):")
    switch (val1)
    {
        case "1" :
            document.write("bilangan satu")
            break
        case "2" :
            document.write("bilangan dua")
            break
        case "3" :
            document.write("bilangan tiga")
            break
        case "4" :
            document.write("bilangan empat")
            break
        case "5" :
            document.write("bilangan lima")
            break
        default :
            document.write("bilangan lainnya")
    }
}
</script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```


<img width="960" alt="lab 5 web switech" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/4a5f0837-bdda-446a-9dda-f7c895d1ee67">




**3. Pembuatan Form**
> - Form `Input`
```
<html>
<head>
    <script language="javascript">
    function test () {
        var val1=document.kirim.T1.value
        if (val1%2==0)
            document.kirim.T2.value="bilangan genap"
        else
            document.kirim.T2.value="bilangan ganjil"
    }
    </script>
</head>
<body>
    <form method="POST" name="kirim">
        <p>BIL <input type="text" name="T1" size="20">
        MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </form>
</body>
</html>
```
<img width="960" alt="lab 5 forminput" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/f9d53d2f-d518-40d6-bcc3-d1feb704be3f">





> - Form `Button`
```
<html>
<head>
    <title>objek document</title>
</head>
<body>
    <script language = "javascript">
    <!--
    function ubahWarnaLB(warna) {
        document.bgColor = warna;
    }    
    function ubahWarnaLD(warna) {
        document.fgColor = warna;
    }
    //-->
    </script>

    <h1>tes</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLLOW')">
        <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
    </form>
    <script language = "javascript">
    <!--
    document.write("Dimodifikasi terakhir pada " +
    document.lastModified);
    //-->
    </script>
</body>
</html>
```


<img width="960" alt="lab 5 formbotton html" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/6f78cb88-3047-480f-8ebf-ad27dc26eeb0">



**4. HTML DOM**
> - Pilihan menggunakan `checkbox` dengan perhitungan otomatis
```
<!--
File: daftar_menu.html
-->
<html>
<head>
    <title>Daftar Menu</title>
    <script>
        function hitung(ele) {
            var total = document.getElementById('total').value;
                total = (total ? parseInt(total) : 0);
            var harga = 0;

            if (ele.checked) {
                harga = ele.value
                total += parseInt(harga);
            } else {
                harga = ele.value;
                if (total > 0)
                    total -= parseInt(harga);
            }
            document.getElementById('total').value = total;
        }
    </script>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" /> Ayam Goreng Rp. 5.000</label><br />
    <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" /> Tempe Goreng Rp. 5.00</label><br />
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" /> Telur Dadar Rp. 2.500</label><br />
    <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
</body>
</html>
```
<img width="960" alt="lab 5 checkbox" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/a9e5d6e9-6002-40e0-80f2-a43ada194339">






## Pertanyaan dan Tugas
**1. Buat script untuk melakukan `validasi` pada isian form**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulir Validasi</title>

    <!-- my styles css -->
    <link rel="stylesheet" href="style.css">
    <script>
        function validateForm() {
            // Dapatkan referensi ke elemen-elemen formulir
            var nama = document.forms["myForm"]["nama"].value;
            var email = document.forms["myForm"]["email"].value;

            // Lakukan validasi
            if (nama == "") {
                alert("Nama wajib diisi");
                return false;
            }

            if (email == "") {
                alert("Email wajib diisi");
                return false;
            }

            // Validasi apakah email sesuai dengan format yang benar
            var emailPattern = /^[a-zA-Z0-9._-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,4}$/;

            if (!emailPattern.test(email)) {
                alert("Email tidak valid. Harap masukkan alamat email yang benar.");
                return false;
            }
        }
    </script>
</head>
<body>
    <h1>Formulir Validasi</h1>
    <div class="container">
        <form name="myForm" onsubmit="return validateForm()" method="post">
            <div class="input-group">
                <label for="nama"><img src="user (3).svg" class="label-img"></label>
                <input type="text" id="nama" name="nama" placeholder="Nama" class="input">
            </div>
            
            <div class="input-group">
                <label for="email"><img src="mail.svg" class="label-img"></label>
                <input type="text" id="email" name="email" placeholder="Email" class="input">
            </div>
            
    
            <input type="submit" value="Submit" class="btn">
        </form>
    </div>
    
</body>
</html>
```


<img width="960" alt="lab 5 validasi" src="https://github.com/deanpratamasaputraa/Lab-5-web/assets/120002341/2fe4ee8e-d975-48a5-8f91-983dba68476c">




## Finish, Terima Kasih
