# Carta-Caue
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Uma Mensagem Para Você</title>
<style>
body {
font-family: Arial, sans-serif;
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
background-color: #ffe6e6;
}
.container {
text-align: center;
background: white;
padding: 20px;
border-radius: 10px;
box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
max-width: 400px;
}
#message {
display: none;
margin-top: 20px;
font-size: 18px;
color: #d63384;
}
input {
padding: 8px;
margin-top: 10px;
width: 100%;
text-align: center;
}
button {
margin-top: 10px;
padding: 8px 15px;
background: #d63384;
color: white;
border: none;
border-radius: 5px;
cursor: pointer;
}
button:hover {
background: #b82c6d;
}
</style>
</head>
<body>
<div class="container">
<h2>Digite a senha para ver a mensagem</h2>
<input type="text" id="password" placeholder="DD/MM/AAAA">
<button onclick="checkPassword()">Entrar</button>
<p id="message">Feliz aniversário! Só queria dizer que, independente de tudo, desejo que você tenha um dia incrível. Você sempre será especial pra mim. ❤️</p>
</div>

<script>
function checkPassword() {
var input = document.getElementById("password").value;
if (input === "16/03/2024") {
document.getElementById("message").style.display = "block";
} else {
alert("Senha incorreta. Tente novamente!");
}
}
</script>
</body>
</html>
