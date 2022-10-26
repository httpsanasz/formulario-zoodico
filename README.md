# formulario-zoodico

inicio do teste php de formulário

<!DOCTYPE html>

<html lang="en">
  
<head>
  
    <meta charset="UTF-8">
  
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
    <title> Signos Zoodiaco </title>
  
</head>
  
<body> 

<section class="container">
  
    <h1></h1>
  
    <form action="/" class="form" method="POST">
      
    </br><label for="nome"> Qual o seu nome?:</label>
  
    </br><input type="text" id="nome" name="nome">
  
    </br><label for="dia"> Qual o dia você nasceu?:</label>
  
    </br><input type="int" id="dia" name="dia">
    
    </br><label for="mes"> Qual mês você nasceu?:</label>
    
    </br><input type="int" id="mes" name="mes">
    
    </br><label for="ano"> Qual ano você nasceu?:</label>
    
    </br><input type="int" id="ano" name="ano">
    
    </br><button type="submit">enviar</button>
    
    </form>

  </section>

 <php?
 
\\declaraçao de variaveis

$nome = $_POST {nome};

$dia = $_POST {dia};

$mes = $_POST {mes};

$ano = $_POST {ano};

if ($dia = >= 21 && $mes == 1 || $dia = <= 19 && $mes == 2) {
    $signo = 'aquario';
    
} if else ($dia = >= 19 && $mes == 2 || $dia = <= 20 && $mes == 3) {
    $signo = 'peixes';
    
} if else ($dia = >= 21 && $mes == 3 || $dia = <= 20 && $mes == 4) {
    $signo = 'áries';
    
} if else ($dia = >= 21 && $mes == 4 || $dia = <= 20 && $mes == 5) {
    $signo = 'touro';
    
} if else ($dia = >= 21 && $mes == '5' || $dia = <= 20 && $mes == '6') {
    $signo = 'gemeos';
    
} if else ($dia = >= 21 && $mes == '6' || $dia = <= 22 && $mes == '7') {
    $signo = 'cancer';
    
} if else ($dia = >= 23 && $mes == '7' || $dia = <= 22 && $mes == '8') {
    $signo = 'leao';
    
} if else ($dia = >= 23 && $mes == '8' || $dia = <= 22 && $mes == '9') {
    $signo = 'virgem';
    
} if else ($dia = >= 23 && $mes == '9' || $dia = <= 22 && $mes == '10') {
    $signo = 'libra';
    
} if else ($dia = >= 23 && $mes == '10' || $dia = <= 21 && $mes == '11') {
    $signo = 'escorpião';
    
} if else ($dia = >= 22 && $mes == '11' || $dia = <= 21 && $mes == '12') {
    $signo = 'sagitário';
    
} if else ($dia = >= 22 && $mes == '12' || $dia = <= 20 && $mes == '1') {
    $signo = 'capricórnio';
    

"</br> Olá" .$nome "seu signo é" .$signo;

   ?>
   
</body>

</html>
