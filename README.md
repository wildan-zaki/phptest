# phptest

#STRUKTUR DATA TEST
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
