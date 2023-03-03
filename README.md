# Cadastro_HTML
Formulário de Cadastro

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Formulário Exemplo</title>
  </head>
  <body>
    <h1>Formulário de Cadastro</h1>
    <form>
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome"><br><br>
      
      <label for="idade">Idade:</label>
      <input type="number" id="idade" name="idade"><br><br>
      
      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email"><br><br>
      
      <label for="interesses">Interesses:</label><br>
      <input type="checkbox" id="interesse1" name="interesses" value="Esportes">
      <label for="interesse1">Esportes</label><br>
      <input type="checkbox" id="interesse2" name="interesses" value="Cinema">
      <label for="interesse2">Cinema</label><br>
      <input type="checkbox" id="interesse3" name="interesses" value="Música">
      <label for="interesse3">Música</label><br>
      <input type="checkbox" id="interesse4" name="interesses" value="Gastronomia">
      <label for="interesse4">Gastronomia</label><br>
      <input type="checkbox" id="interesse5" name="interesses" value="Viagens">
      <label for="interesse5">Viagens</label><br><br>
      
      <label for="sexo">Sexo:</label><br>
      <input type="radio" id="masculino" name="sexo" value="masculino">
      <label for="masculino">Masculino</label><br>
      <input type="radio" id="feminino" name="sexo" value="feminino">
      <label for="feminino">Feminino</label><br>
      <input type="radio" id="outro" name="sexo" value="outro">
      <label for="outro">Outro</label><br><br>
      
      <input type="submit" value="Enviar">
      <input type="reset" value="Limpar">
    </form>
  </body>
</html>
