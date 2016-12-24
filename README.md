# alo-mundo
Apenas outro repositorio.
Alteração de arquivo para fazer commit depois no arquivo master.

Aqui pode entrar códigos do prograga

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Herança</title>
</head>
<body>
<h1>### Demonstrando HERANÇA ###</h1>
<pre>
	<?php
		require_once 'Pessoa.php';
		require_once 'Aluno.php';
		require_once 'Professor.php';
		require_once 'Funcionario.php';

		$p1 = new Pessoa();
		$p2 = new Aluno();
		$p3 = new Professor();
		$p4 = new Funcionario();

		$p2->setNome("Marcelo");
		$p2->setIdade(42);
		$p2->setSexo("M");
		$p2->setMatr(2117235);
		$p2->setCurso("Sistemas da informação");

		//$p2->cancelarMatr();

		print_r($p2);
	?>
</pre>
	
</body>
</html>
