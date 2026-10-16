<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Educação</title>
  <style>
    

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.25rem 5%;
  background-color: #ffffff;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

header nav ul {
  display: flex;
  gap: 2rem;
  list-style: none;
}

header nav a {
  text-decoration: none;
  color: #333333;
  font-family: sans-serif;
  font-weight: 500;
  font-size: 1rem;
  transition: color 0.3s ease;
}

header nav a:hover {
  color: #0076df;
}

.caixa {
    list-style: none;
    padding: 0;
    margin-top: 20px;
    margin-bottom: 20px;
    width: 300px;
    height: 150px;
    margin-left: 500px;
}
ul li {
    background-color: #F4F0EA;
    color: #331F19;
    padding: 10px;
    margin: 5px 0;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

h2 {
  text-align: center;
  margin: 5px;
}

button {
  background-color: #0076df;
  color: #F4F0EA;
  border: 0cap;
  border-radius: 3px;
  height: 30px;
  width: 90px;
  margin-left: 90px;
  cursor: pointer;
}

p {
  margin-top: 15px;
  margin-bottom: 20px;
  font-family: Arial, Helvetica, sans-serif;
  margin-left: 4px;
}

  </style>
</head>
<body>
  <header>
    <h1>Fluxo de Saber</h1>
    <nav>
      <ul>
      <li><a href="index.html">Início</a></li>
      <li><a href="#sobre">Sobre</a></li>
      <li><a href="#avaliar">avaliar</a></li>
      </ul>
    </nav>
  </header>
  <ul class="caixa">
    <li class="aprender">
      <h2>Quimica</h2>
      <p>Vem conhecer os principais conecimentos sobre quimica</p>
      <a href="hf.html">
      <button>começar</button>
      </a>
    </li>
    <li class="aprender">
      <h2>Biologia</h2>
      <p>Vem conhecer os principais conecimentos sobre biologia</p>
      <button>começar</button>
    </li>
  </ul>
</body>
</html>
