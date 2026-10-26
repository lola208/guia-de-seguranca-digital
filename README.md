<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Internet Segura Para Todos</title>
 
<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
}
 
body{
font-family: 'Arial', sans-serif;
background:#eef4ff;
color:#333;
}
 
header{
background:linear-gradient(135deg,#004aad,#0077ff);
color:white;
text-align:center;
padding:60px 20px;
}
 
header h1{
font-size:3rem;
}
 
header p{
margin-top:10px;
font-size:1.1rem;
}
 
main{
max-width:1100px;
margin:auto;
padding:30px;
}
 
.card{
background:white;
margin-bottom:25px;
padding:25px;
border-radius:15px;
box-shadow:0 4px 15px rgba(0,0,0,0.1);
}
 
.card h2{
color:#004aad;
margin-bottom:15px;
}
 
ul{
margin-left:25px;
}
 
li{
margin:10px 0;
}
 
.alerta{
background:#ffe5e5;
border-left:6px solid red;
padding:15px;
border-radius:8px;
margin-top:15px;
}
 
.dica{
background:#e8fff1;
border-left:6px solid green;
padding:15px;
border-radius:8px;
margin-top:15px;
}
 
button{
padding:12px 20px;
background:#004aad;
color:white;
border:none;
border-radius:8px;
cursor:pointer;
margin-top:15px;
}
 
#mensagem{
margin-top:15px;
font-weight:bold;
}
 
footer{
background:#003580;
color:white;
text-align:center;
padding:20px;
margin-top:30px;
}
</style>
</head>
 
<body>
 
<header>
<h1>🔒 Internet Segura Para Todos</h1>
<p>Aprenda a reconhecer ameaças digitais e proteger seus dados.</p>
</header>
 
<main>
 
<section class="card">
<h2>Por que a segurança digital é importante?</h2>
 
<p>
Atualmente realizamos diversas atividades pela internet, como estudar,
trabalhar, acessar bancos e conversar com amigos. Por isso, conhecer
os riscos digitais é fundamental para evitar golpes e proteger
informações pessoais.
</p>
</section>
 
<section class="card">
<h2>⚠️ Sinais de possíveis golpes</h2>
 
<ul>
<li>Links desconhecidos recebidos por mensagens.</li>
<li>Pedidos urgentes para clicar imediatamente.</li>
<li>Solicitação de senhas ou códigos de segurança.</li>
<li>Promoções com benefícios exagerados.</li>
<li>Erros de português e aparência suspeita.</li>
</ul>
 
<div class="alerta">
Nunca informe senhas ou dados bancários por mensagens,
e-mails ou redes sociais.
</div>
</section>
 
<section class="card">
<h2>✅ Como se proteger</h2>
 
<ul>
<li>Verifique o endereço dos sites.</li>
<li>Utilize senhas fortes.</li>
<li>Ative a autenticação em dois fatores.</li>
<li>Mantenha aplicativos atualizados.</li>
<li>Desconfie de ofertas muito vantajosas.</li>
</ul>
 
<div class="dica">
Pequenos cuidados podem evitar grandes problemas de segurança.
</div>
</section>
 
<section class="card">
<h2>Teste seu conhecimento</h2>
 
<p>
Você recebeu uma mensagem prometendo um prêmio e pedindo seus dados pessoais. O que deve fazer?
</p>
 
<button onclick="resposta()">
Ver Resposta
</button>
 
<div id="mensagem"></div>
 
</section>
 
</main>
 
<footer>
<p>Projeto desenvolvido para conscientização sobre segurança digital e prevenção de golpes virtuais.</p>
</footer>
 
<script>
function resposta(){
document.getElementById("mensagem").innerHTML =
"✅ A atitude correta é NÃO fornecer dados pessoais, verificar a origem da mensagem e desconfiar de ofertas suspeitas.";
}
</script>
 
</body>
</html>
