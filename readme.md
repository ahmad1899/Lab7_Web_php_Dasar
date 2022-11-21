# LAAAB7_WEB

<h3> Praktikum 2 - Pemrograman  PHP DASAR</h3>
<h3> Mata Kuliah : Pemrograman Web </h3>
<h3> Dosen        : Agung Nugroho,S.Kom.,M.Kom </h3>

<h3> Nama : Achmad Syarifudin </h3>
<h3> Nim  : 312110598 </h3> 
<h3> Kelas : TI.21.B1 </h3>



# Langkah Praktikum
<h1> Menjalankan Web Server </h1>
[instal XAMMP](https://www.apachefriends.org/)
![Lalu Jalankan XAMPP](https://imgur.com/pvkGSAK.png)

<h1> Uji Coba Mengakses Direktory </h1>
![Uji Coba Direktoy](https://imgur.com/h7docba.png)

<h1> Membuat PHP DASAR </h1>
![Membuat php dasar](https://imgur.com/CBknCfw.png)

<h1> Membuat Variable php dasar </h1>
![Membuat variable php dasar](https://imgur.com/JICbQrK.png)


<h1> Membuat Predefine Variable Get </h1>
![Membuat Predefine Variable Get](https://imgur.com/vXwajp9.png)


<h1> Membuat Form Input </h1>
![Membuat Form Input](https://imgur.com/gCEKilu.png)


<h1> Membuat Operator </h1>
![Membuat Operator](https://imgur.com/HA5fpiK.png)
<h1> Index </h1>
![Index](https://imgur.com/dJoTalN.png)


<h1> Membuat kondisi If </h1>

<?php
$nama_hari = date("l");
if ($nama_hari == "Sunday") {
echo "Minggu";
} elseif ($nama_hari == "Monday") {
echo "Senin";
} else {
echo "Selasa";
}
?>

<h1>Kondisi Switch</h1>

<?php
$nama_hari = date("l");
switch ($nama_hari) {
case "Sunday":
echo "Minggu";
break;
case "Monday":
echo "Senin";
break;
case "Tuesday":
echo "Selasa";
break;
default:
echo "Sabtu";
?>

<h1>Pengulangan For</h1>

<?php
echo "Perulangan 1 sampai 10 <br />";
for ($i=1; $i<=10; $i++) {
echo "Perulangan ke: " . $i . '<br />';
}
echo "Perulangan Menurun dari 10 ke 1 <br />";
for ($i=10; $i>=1; $i--) {
echo "Perulangan ke: " . $i . '<br />';
}
?>

<h1>Perulangan While</h2>

<?php
echo "Perulangan 1 sampai 10 <br />";
$i=1;
while ($i<=10) {
echo "Perulangan ke: " . $i . '<br />';
$i++;
}
?>

<h1> Perulangan do while</h1>

<?php
    echo "Perulangan 1 sampai 10 <br />";
    $i=1;
    do {
        echo "Perulangan ke: " . $i . '<br />';
        $i++;
    }
    while ($i<=10);
?>