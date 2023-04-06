#### <?php

#### echo "eae beleza meu chefe";


#### $funcionarios = array(
   #### array("nome" => "paulo", "idade" => 21, "salario" => 1500.00),
  ####  array("nome" => "carlos", "idade" => 19, "salario" => 1100.00),
  ####  array("nome" => "juliana", "idade" => 25, "salario" => 1600.00),
  ####  array("nome" => "larissa", "idade" => 22, "salario" => 1400.00),
#### );





#### $fp = fopen("desafioexcel.xls", "w");

#### foreach ($funcionarios as $funcionario) {
  ####  fputcsv($fp, $funcionario, "\t", '"');
#### }
  ####   fclose($fp);

#### ?> 