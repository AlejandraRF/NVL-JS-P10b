# NVL-JS-P10b
Asumiendo que Math.floor((Math.random() * 100) + 1); saca elementos al azar entre 1 y 100, queremos que hagas lo siguiente:  1.  Saca 50 números al azar entre 1 y 100. 2. Almacena los números que salgan impares en un array impares. 3.Almacena los números que salgan pares en un array pares

        var numeros=[];
        var impares=[];
        var pares=[];

        for (var i=0; i<100;i++){

            var num= Math.floor ((Math.random()*100)+1)
            numeros.push(num);
            if(num%2===0){ ---> le digo que si la mitad del número es 0 me saque un número par. 
             pares.push(num);   
            }
            else{
                impares.push(num);---> si no lo es que me saque un número impar. 
            }
        }
        
       
