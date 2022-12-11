# numeros_pares_1_al_100
Creacion de numero pares del 1 al 100

<meta charset="UTF-8">


<h1> imprimir numeros pares del 1 al 100</h1>


<script>
	
	function saltarLinea() {

		document.write("<br>");
		document.write("<br>");
		document.write("<br>");
	}

	function imprimir(frase){

		document.write(frase);
		saltarLinea();
	}

	var par = 1;
	var contador = 2;

	while(par <= 50){

		imprimir(contador);
		par++;
		contador = contador + 2;
	}
	
	imprimir ("FIN");






</script>
