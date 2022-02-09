{% extends "layout.html" %}
{% block body %}
 
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Python Flask App</title>

   
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" rel="stylesheet">
 
    <link href="https://getbootstrap.com/docs/3.3/examples/jumbotron-narrow/jumbotron-narrow.css" rel="stylesheet">

   
  </head>

  <body bgcolor="yellow" id="top">
	<style> body {background-color:white;} </style>

    <div class="container">
      <div class="header">
	    <h1><center><font CLASS="blue" face="geneva">Olá, seja bem vindo!</font></center></h1>
        <h1><center>Eu sou</center></h1>
		<h1><center>{{name}}</center></h1>
		<h3><small><center>| ENGENHEIRO DE DADOS | ANALISTA DE DADOS | CLOUD ENGINEER |</center></small></h3>
      </div>

      <div>
        <h1>Acompanhe Meu Portfólio de Projetos</h1>
        <p class="lead"></p>
      </div>

      <div class="row marketing">
        <div class="col-lg-6">
          <h4>Projeto 1</h4>
          <p>Análise e Exploração de Dados com Python.</p>

          <h4>Projeto 2</h4>
          <p>Engenharia de Dados com Hadoop e Spark.</p>		  
        </div>
		
        <div class="col-lg-6">
          <h4>Projeto 3</h4>
          <p>Migração de Dados Para Nuvem.</p>
		  
          <h4>Projeto 3</h4>
          <p>Integração de Dados com a Apache NIFI.</p>		  
        </div>		
      </div>

	  
      <footer class="footer">
        <p>&copy; Cleber Zumba</p>
      </footer>

    </div>
  </body>
</html>
{% endblock %}
