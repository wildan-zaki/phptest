# phptest

###STRUKTUR DATA TEST###
~~~~
<?php$num = array(2, 1, 6, 9, 9, 4, 3);
$max = $num[0];
$smax = 0;
for($i=1; $i<count($num); $i++){
	if($num[$i]>$max){
		$smax = $max;
		$max = $num[$i];
		
	}else if ($num[$i] > $smax && 
			  $num[$i] != $max){ 
            $smax = $num[$i];
	}
}
echo $smax;
~~~~



###Knowledge & Experience Questions###

1. 	Tantangan terbesar adalah ketika melanjutkan pekerjaan orang lain. saya harus melakukan tracing untuk memastikan code yang dibut tetap clean code
2.  -menggunakan variabel yang jelas dan tidak ambigu;
	-menghapus code yang tidak dipakai
	-menggunakan fungsi yang reuseable
3.  -memungkinkan untuk para developer bekerja bersama-sama dalam satu file
	-kode dapat dikembalikan ke kode lama yang tersimpan
	-sebelum di push di branch utama, kode dapat di review terlebih dahulu
4. Saya menggunakan MVC dalam pekerjaan saya sebelumnya. Ketika terjadi perubahan pada suatu projek maka tidak semua code yang terpengaruh. MVC juga dapat memudahkan pekerjaan saya untuk menghindari duplikasi code, karena MVC memisahkan antara data dan logik dari tampilan.
5. Iya saya Bersedia ditempatkan di Malang.
