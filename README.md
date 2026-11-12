<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>KARAK VPN</title>

<style>

* {

  box-sizing: border-box;

}

body {

  margin: 0;

  font-family: Arial, sans-serif;

  background: #100b20;

  color: white;

  text-align: center;

}

header {

  padding: 30px;

  color: #b69aff;

  font-size: 30px;

  font-weight: bold;

}

.card {

  margin: 30px 20px;

  padding: 30px 20px;

  background: #211638;

  border-radius: 25px;

}

.status {

  color: #b69aff;

  margin: 20px;

}

button {

  background: #853cff;

  color: white;

  border: none;

  padding: 20px 45px;

  border-radius: 50px;

  font-size: 20px;

  font-weight: bold;

  margin: 20px;

}

select {

  background: #35234f;

  color: white;

  padding: 15px;

  border-radius: 12px;

  border: none;

  width: 85%;

  font-size: 16px;

}

footer {

  color: #aaa;

  margin-top: 60px;

}

</style>

</head>

<body>

<header>💜 KARAK VPN</header>

<div class="card">

<h2>Secure Your Connection</h2>

<p class="status" id="status">● DISCONNECTED</p>

<button onclick="connectVPN()" id="connect">

CONNECT

</button>

<h3>Select Server</h3>

<select id="server">

<option>Singapore</option>

<option>Japan</option>

<option>United States</option>

<option>Thailand</option>

</select>

</div>

<footer>

KARAK VPN © 2026

</footer>

<script>

function connectVPN() {

  alert("VPN connection engine is not installed yet.");

}

</script>

</body>

</html>
