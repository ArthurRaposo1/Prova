# Prova

//QUESTAO 1//

var result = someFun({ someProperty: 'interview'}, function(value){
    
    console.log('This pointing to ' + value);

});

console.log('Result is', result);

function someFun(teste, teste2){
   
    teste2(teste.someProperty);
    return 1;
}

//QUESTÃO 2

var someFn = function(numero) 
    {
        var somar = numero;

        return function (incremento) 
    {
        somar += increment;

        return somar;
    }
    }

    var counter  = someFN(1)

    console.log("First call", counter(3))
    console.log("second call", counter(1))
    console.log("Third call", counter(5))



//QUESTAO 4//

var a  = 5
var b = 10

if(a == 5){
  let a = 4
  var b = 1
  console.log(a)
  console.log(b)
}
console.log(a)
console.log(b)
//RESPOSTA: 4,1,5,1


//QUESTAO 5//
function num(numero)
{
  for(var i = 1; i <= 10; ++i)
  {
    console.log(i * numero)
    
  }
}
num(2)
*/
