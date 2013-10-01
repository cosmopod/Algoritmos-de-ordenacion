<?php

/* Algoritmo de ordenación conocido como Método de la burbuja.
Aquí presenta una formulación algo distinta a la que podemos encontrar
habitualmente en PHP con dos bucles 'for' anidados.
*/

class Burbuja{


public function ordenaArray($array){

	$numElemArray = count($array);
	$isOrder = true;
	while($isOrder){
	$isOrder = false;
		for($i = 1; $i < $numElemArray; $i++){
			if($array[$i] < $array[$i - 1]){
				$aux = $array[$i];
				$array[$i] = $array[$i - 1];
				$array[$i - 1] = $aux;	
				$isOrder = true;
			}
		}
		
	}	
	return $array;	
}

}

?>
