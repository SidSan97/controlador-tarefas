# PROJETO TODO

<p> 
Este projeto é uma aplicação de lista de tarefas (To-Do List) construída em Laravel no Backend e Blade no front usando Ajax para as requisições. API segue o modelo RESTful e as funcionalidades do sistema segue um padrão CRUD para as <i>tasks</i> e <i>categorias</i>. Além disso, é possivel mover tasks de um card pra outro seguindo o reodernamento, no estilo Trello.
</p>

<h3> Tecnologias: </h3>
<ul>
  <li> Laravel 12 </li>
  <li> Bootstrap </li>
  <li> Blade </li>
  <li> JQuery </li>
  <li> Ajax </li>
  <li> Bootstrap Icons </li>
  <li> SweetAlert2 </li>
</ul>

<h3> Instalação e execução: </h3>
<ul>
  <li> cd controlador-tarefas </li>
  <li> composer install</li>
  <li> cp .env.example .env </li>
  <li> ATUALIZE O  <i>.env</i> COM SUAS CREDENCIAIS DO BANCO DE DADOS </li>
  <li> php artisan key:generate </li>
  <li> php artisan vendor:publish --tag=sanctum-config </li>
  <li> php artisan migrate </li>
  <li> npm install </li>
  <li> composer dev </li>
</ul>
