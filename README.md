# Juego-de-azar
<meta charset="UTF-8">
<h1> JUEGO DE AZAR </h1>
<script>
  function saltoLinea()  {
    document.write("<br>");
    document.write("<br>");
    document.write("<br>");
    }
  function imprimir(frase) {
  
    document.write(frase);
    saltoLinea();
  }
  var NumeroPensado = Math.round(Math.random()*10);
  var numeroIngrasado = parseInt(prompt("Ingrese un numero del 1 al 10"));
 
  if (NumeroPensado == numeroIngrasado); {
    imprimir("Usted acertó");
  }
 if (NumeroPensado != numeroIngrasado); {
      
        imprimir("Usted erró, el número pensado era " + NumeroPensado);
     }
    
 
</script>
