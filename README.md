<?php

print "Qual o valor da sua mercadoria?";
$merca = fgtes (STDIN);

print "Qual a sua porcentagem de desconto?";
$desc = (int) fgets (STDIN);

$desconto = $merca*$desc/100;
$total = $merca-$desconto;

print "O valor de desconto da sua mercadoria será de $desconto, e o valor total será de $total";
