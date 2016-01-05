<!DOCTYPE.html>
<html lang="pt-BR">
	<head>		
		<title>Instituto Harmonia Arapoanga</title>
		<meta charset="utf-8">
		
		
		<!--css da pagina-->		
		<link rel="stylesheet" type="text/css" href="css/HARMONIA.css" media="all">	
		<script src="_JS/jquery.js"> </script>
		<script src="_JS/_JS.js"> </script>
	
	
	</head>
		
	<body>
	<!--pelicula mobile-->
		<div id="pelicula"></div>
		<header id="topo">
			<div class="container">
				<div class="logo"> 
					<img src="img/brinc.png" style="width: 50px; height: 30px;" alt="Nome da Empresa">
				</div> <!-- fim .logo -->
				
				<?php include_once "_MENU/_MENU.php" ?>

				
				
				<div class="menuMobile">
					<img src="img/menuMobile.png" alt="">
				</div> <!-- fim #menuMobile -->
			</div> <!-- fim .container -->
		</header> <!-- fim #topo -->
		<div id="bt-menu-mobile">
			<img src="img/menuMobile.png" alt="menu mobile"/>
		</div>

		<!--MENUMOBILE -->
		<?php include_once "_MENU/_MENUMOBILE.php" ?>


		<div id="banner"></div> <!-- fim #banner -->

		<div id="comentario">
			<p> 
				<blink><h2>Turmas Abertas</h2></bilnk>

				" O instituto de música Arapoanga oferece aulas de instrumentos, canto e ritimos variados,para que nossos alunos aprendam os fundamentos teóricos e práticos da música clássica a popular, com aulas regulares. Turmas abertas! O instituto se localiza na Quadra 5 conjunto D Apartamento 01e02 Arapoanga Planaltina-DF<br> e-mail: harmoniaarapoangas@gmail.com<br> Fone(61)3012-4209.<img src="img/whats.png" style="widht:60px; height: 60px;" alt="whats"/> (61)9249-5809  "
			</p>

			<h1> Instituto de música Harmonia Arapoanga agradece a preferência</h1>
		</div> <!-- fim #comentario -->

		<div id="artigos">
			<article>
				<figure> 
					<img src="img/flauta1.png" alt="Artigo 01">
				</figure>

				<h1> Aulas de flauta-doce </h1>

				<p class="autor"> por <span> Harmonia Arapoanga </span> </p>

				<p class="descricao">
					As aulas de flauta-doce ...
				</p>
			</article> <!-- fim article -->

			<article>
				<figure> 
					<img src="img/cantos2.png" alt="Artigo 01">
				</figure>

				<h1> Aulas de canto </h1>

				<p class="autor"> por <span> Harmonia Arapoanga </span> </p>

				<p class="descricao">
					As aulas de canto...
				</p>
			</article> <!-- fim article -->

			<article>
				<figure> 
					<img src="img/teclado1.png" alt="Artigo 01">
				</figure>

				<h1> Título do Artigo </h1>

				<p class="autor"> por <span> Harmonia Arapoanga </span> </p>

				<p class="descricao">
					As aulas de teclado...
				</p>
			</article> <!-- fim article -->

		</div> <!-- fim #artigos -->


		<table>
			<caption> Tabela de Preços </caption>

			<thead>
				<tr> 
					<th> Aulas </th>
					<th> Descrição com valor </th>
				</tr>
			</thead>

			<tbody> 
				<tr> 
					<td> Aulas de canto </td>
					<td> As aulas de canto proporciona e custa o valor simbólico de  R$80,00...  </td>
				</tr>

				<tr> 
					<td> Aulas de flauta </td>
					<td> As aulas de flauta proporciona e custa o valor simbolico de R$80,00... </td>
				</tr>

				<tr> 
					<td> Aulas de violão</td>
					<td> As aulas de violão proporciona e custa o valor simbolico de R$80,00... </td>
				</tr>

				<tr> 
					<td> Aulas de guitarra </td>
					<td> As aulas de guitarra proporciona e custa o valor simbolico de R$80,00... </td>
				</tr>

				<tr> 
					<td> Aulas de contrabaixo </td>
					<td> As aulas de contrabsixo proporciona e custa o valor simbolico de R$80,00... </td>
				</tr>

				<tr> 
					<td> Aulas de bateria </td>
					<td> As aulas de bateria proporciona e custa o valor simbolico de R$80,00... </td>
				</tr>

				
			</tbody>

			<tfoot> 
				<tr> 
					<td colspan="2"> 
						O Instituto se localiza na Quadra 5 conjunto D Apartamento 01e02 Arapoangas Planaltina-DF
					</td>
				</tr>
			</tfoot>
		</table> <!-- fim table -->

		<?php include_once "_RODAPE/_RODAPE.php" ?>

	</body>
</html>
