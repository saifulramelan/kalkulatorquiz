<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>Untitled Form</title>
<link rel="stylesheet" type="text/css" href="view.css" media="all">
<script type="text/javascript" src="view.js"></script>

</head>
<body id="main_body" >
	
	<img id="top" src="top.png" alt="">
	<div id="form_container">
	
		<h1><a>KALKULATOR </a></h1>
		<form id="form_32476" class="appnitro"  method="post" action="">
					<div class="form_description">
			<h2>KALKULATOR </h2>
			<p>ini adalah Kalkulator percobaan</p>
		</div>						
			<ul >
			
			<body>
    <form action="hitung.php" method="post">
       
        Masukan Angka Pertama <input type="text"  name="a"><br><br>
        Masukan Angka Kedua <input type="text"  name="b"><br><br>
        Hasil Dari: <br>
        <input type="radio" name="operasi" value="tambah" >Penjumlahan<br>
       <input type="radio" name="operasi" value="kurang" >Pengurangan<br>
       <input type="radio" name="operasi" value="kali" >Perkalian<br>
       <input type="radio" name="operasi" value="bagi" >Pembagian<br><br>
        <input type="submit" name="submit" value="Hitung" >
    </form>
    </body>
	
<?php
$a=$_POST['a'];
$b=$_POST['b'];
$operasi=$_POST['operasi'];

echo "Masukan Angka Pertama = $a <br>";echo "Masukan Angka Kedua = $b <br>";

if($operasi=="tambah"){
    $c=$a+$b;
    echo "Hasil penjumlahan $a + $b = $c";
}else if ($operasi=="kurang"){
    $c=$a-$b;
    echo "Hasil Pengurangan $a - $b = $c";
}else if ($operasi=="kali"){
    $c=$a*$b;
    echo "Hasil Perkalian $a x $b = $c";
}else if ($operasi=="bagi"){
    $c=$a/$b;
    echo "Hasil Pembagian $a / $b = $c";
}else {
    echo "Pilih Operasi Dulu Bro";
}
?> 
		
		<div id="footer">
		
		</div>
	</div>
	<img id="bottom" src="bottom.png" alt="">
	</body>
</html>
