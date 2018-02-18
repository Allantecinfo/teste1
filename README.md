<!DOCTYPE html>
<html>
<head>
	<title>Exemplo Formulários</title>
</head>
	<form>
		Nome:<br> <input type="text" autofocus="autofocus" placeholder="Seu nome" required="required"><br>
		Idade:<br> <input type="number" required="required" min="18" max="100"><br>

	Seu Site:<br> <input type="url" placeholder="ex: http://www.site.com.br" required="required"><br>

E-mail:<br> <input type="email" required="required"><br>

Data de Nascimento:<br> <input type="date" required="required"><br>

Buscar por:<br> <input type="search" required="required"><br>

Cor:<br> <input type="color" required="required"><br>

Placa de Carro:<br> <input type="text" placeholder="OLP-0000" pattern="[A-Za-z]{3}-[0-9]{4}" maxlength="8" required="required"><br>

CEP:<br> <input type="text" placeholder="92000-000" pattern="[0-9]{5}-[0-9]{3}" maxlength="9" required="required"><br>

	<input type="submit" value="Cadastrar">
	</form>

</html>
