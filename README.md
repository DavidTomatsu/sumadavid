# sumadavid
proyecto github
Algoritmo:

1.inicio
2.leer num1,num2
3.calcular
suma num1+num2
4.mostrar resultado suma
5.fin


---------------------------------------------------------------
<html>
  <body>
     <label for="numero1">Numero 1</label>
     <input type="text" id="numero1" onchange="sumar();"><br>

     <label for="numero2">Numero 2</label>
     <input type="text" id="numero2" onchange="sumar();"><br>

     <label for="resultado">Resultado</label>
     <input type="text" id="resultado">
    <scrip>
        // si la respuesta que se espera es sumar
        function sumar(){
            var numero1 = document.getElementById('numero1').value;
            var numero2 = document.getElementById('numero1').value;
            
            if(numero1!=='' && numero2!==''){
                var suma = parseInt(numero1)+parseInt(numero2);
                document.getElementById('resultado').value = suma;
            }
        }
    </scrip>
   </body>
</html>
