# PHP_aulas_udemy
anotações sobre PHP 

"echo" serve para imprimir um elemento na tela.

Para usar um arquivo PHP dentro de outro 

include = apresenta o erro e continua rodando 
require = apresenta o erro e para
once = serve para incluir somente uma vez


 CRIANDO VARS 
 
 
GETTYPE = serve para mostra o tipo da  var

"$nome = valor" assim se cria uma var  em PHp 

O PHP sabe diferenciar uma var com letra maiuscula

exemplo 
"myname"  "myName"
"my_name" "myname"

-------------------------------------

O &  (E comercial) serve para fazer uma referencia no mesmo ponto de memoria 
-------------------------------------

Condicionais If else 

exemplo= $number1 = 70;
         $number2 = 50;
         $isAdmin = false;
         
$resultado = $number1 > $number2 && $isAdmin;

echo ($resultado) ? 'é verdadeiro' : 'não é verdadeiro';

exemplo 2= 

if($number1>$number2){
   echo 'é maior';
}else{
   echo 'não é maior';
}


normalmente se usa if para saber o verdadeiro ou falso e switch para verificar um valor passando entre parentes "cases" analisando 

echo strlen serve para cortar o numero de caracteres que tem em uma var 
-----------------------------------------------------------------------
         arrays
         
array_push (var, valor) // para adicionar um valor no array
array_unshift()var, valor) // para adicionar um valor na var em primeiro sem substituir 


------------------------------------------------------------------------

Transformando Arrays em objeto

$person = ['name' => "valor", "age" => 49]

$change = (object) $person;
-------------------------------------------------------------------------




