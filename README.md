

# teste-php
primeiro passo de uma criação em php 
![image](https://user-images.githubusercontent.com/72118415/118348474-ffcae500-b520-11eb-846f-1249457bac42.png)

![image](https://user-images.githubusercontent.com/72118415/118348574-b5963380-b521-11eb-817c-d7087e5b1202.png)



![image](https://user-images.githubusercontent.com/72118415/118348559-a7e0ae00-b521-11eb-8b3c-ba20bd639228.png)



request.php

<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title>GET e POST</title>
</head>
<body>
<form id="form1" name="form1" method="post" action="acao.php">
<br>
 Nome <input name="nome" type="text" id="nome" placeholder = "Digitar
Nome"><br>
Idade<input name="idade" type="text" id="idade" placeholder = "Ex.: 18"><br>
Profissão<input name="profi" type="text" id="profi" placeholder = "Ex:
Professor"><br>
Salário<input name="sal" type="text"id="sal" placeholder = "Ex: 1000"><br>
  
  
  acao.php
  
  <?php
echo "Nome: ".$_POST['nome']."<br>";
echo "Idade: ".$_POST['idade']."<br>";
echo "Profissão: ".$_POST['profi']."<br>";
echo "Salário: R$ ".$_POST['sal']."<br>";


