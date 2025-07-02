
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Portfólio - Rebeca L</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Olá, meu nome é Rebeca L</h1>
    <p class="subtitulo">Apaixonada por dados e inovação</p>

    <div class="descricao">
      <p>Sou apaixonada por dados.</p>
    </div>

    <div class="contato">
      <a href="https://www.linkedin.com/in/rebecalsousa/" target="_blank" class="btn">LinkedIn</a>
    </div>

    <div class="footer">
      <p>© 2025 Rebeca L - Todos os direitos reservados</p>
    </div>
  </div>
</body>
</html>

body {
  margin: 0;
  padding: 0;
  font-family: 'Arial', sans-serif;
  background: linear-gradient(135deg, #1e3c72, #2a5298);
  color: #fff;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.container {
  background: rgba(255, 255, 255, 0.1);
  padding: 40px;
  border-radius: 20px;
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
  max-width: 600px;
  width: 90%;
}

.subtitulo {
  font-size: 1.2em;
  margin-top: -10px;
  color: #fca311;
}

.descricao {
  margin: 20px 0;
  font-size: 1em;
}

.btn {
  display: inline-block;
  padding: 12px 30px;
  margin-top: 20px;
  background-color: #fca311;
  color: #000;
  text-decoration: none;
  font-weight: bold;
  border-radius: 25px;
  transition: background 0.3s ease;
}

.btn:hover {
  background-color: #ffb703;
}

.footer {
  margin-top: 40px;
  font-size: 0.8em;
  color: #ccc;
}





