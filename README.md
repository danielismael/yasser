<h2 align="left">Sobre o projeto</h2>

<p align="left">Rest API para criar usuário e autenticação de login com JWT</p>

<h5 align="left">COMO RODAR O PROJETO BAIXADO</h5>

<p align="left">Instalar todas as dependencias indicada pelo package.json<br>🪶 npm install<br><br>Rodar o projeto<br>🪶 npm start<br><br>Rodar o projeto usando o nodemon <br>🪶 nodemon index.js</p>

<h5 align="left">ROTAS</h5>

<p align="left"><span style="display: block; padding: 5px 8px; background-color: #F13030">POST |</span>  Login com retorno de token<br><br>http://localhost:3000/admin/users/login<br><br>{ <br> "MAIL": "", <br> "PASSWORD": ""<br>}</p>

<p align="left"><span style="display: block; padding: 5px 8px; background-color: #F13030">GET |</span> Buscar usuários<br><br>http://localhost:3000/admin/users/<br><br>{<br>"id"<br>}</p>

<p align="left"><span style="display: block; padding: 5px 8px; background-color: #F13030">POST |</span> Cadastrar usuário<br><br>http://localhost:3000/admin/users/<br><br>{<br> "NAME", <br> "MAIL": "", <br>  "PASSWORD": ""<br>}</p>

<p align="left"><span style="display: block; padding: 5px 8px; background-color: #F13030">PUT |</span> Alterar usuário<br><br>http://localhost:3000/admin/users/<br><br>{<br> "ID", <br> "NAME", <br> "MAIL": "", <br>  "PASSWORD": ""<br>}</p>

<p align="left"><span style="display: block; padding: 5px 8px; background-color: #F13030">DELETE |</span> Deletar usuário usuário<br><br>http://localhost:3000/admin/users/<br><br>{<br>"id"<br>}</p>

<h2 align="left">Techs</h2>

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" width="52" alt="nodejs logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="40" width="52" alt="express logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" height="40" width="52" alt="mysql logo"  />
  <img src="https://jwt.io/img/logo.svg" height="40" width="52" alt="mysql logo"  />
</div>
