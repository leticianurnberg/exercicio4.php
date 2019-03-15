<?php

print "Qual o valor da sua mercadoria?";
$merca = fgets (STDIN);

print "Qual a sua porcentagem de desconto?";
$desc = (int) fgets (STDIN);

$desconto = $merca*$desc/100;
$total = $merca-$desconto;

print "O valor de desconto da sua mercadoria será de R$ $desconto,00 e o valor total será de R$ $total,00";
