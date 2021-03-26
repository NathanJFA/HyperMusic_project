<!DOCTYPE html>
<html lang="pt-br">
  <head>
  	 <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    
    <title>HyperMusic</title>
   
    <!--Estilo customizado-->
    <link rel="stylesheet" type="text/css" href="css/estilo.css">

  <!--Html5Shiv-->
    <!--[if lt IE 9]>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js"></script>
   <![endif]-->

   <!--Normalize-->
   <link rel="stylesheet" type="text/css" href="css/normalize.css">

   <!--icones-->
   <link rel="stylesheet" type="text/css" href="fontawesome/css/all.css">
  </head>
<body>
	 <header><!--Ínicio cabeçalho-->
	 	
	   <nav class="navbar navbar-expand-md porra navbar-dark">
	 	 <div class="container"><!--ínicio container-->

	 	 <a href="#" class="navbar-brand"><img src="img/logo.png" width="171px"></a>
	 	 <button class="navbar-toggler" data-toggle="collapse" data-target="#music">
	 	    <i class="fas fa-align-justify"></i>
	     </button>
	     <div class="collapse navbar-collapse" id="music"> <!--links items-->
	      <ul class="navbar-nav ml-auto">
	 	  <li class="nav-item">
	 	  <a href="#" class="nav-link">Music</a></li>
	 	  <li class="nav-item"><a href="#" class="nav-link">Lançamentos</a></li>
	 	  </ul>
	 		</div><!--Fim links items-->
	 		</div><!--fim container-->
	    </nav>
	 </header><!--Fim cabeçalho-->

	<!---->

	<section id="home" class="caxote">
	<div class="container">
		<div class="row">
		  <div class="col-md-12 text-center">
		  	<div class="carousel slide text-light" data-ride="carousel" id="next" style="padding-top: 150px">
		  		<div class="carousel-inner">
		  		<div class="carousel-item active">
		  			<h1 class="display-4">Novos Lançamentos</h1>
		  			<p class="lead">A melhor plantaforma de música para dowloand.</p>
		  		</div>
		  		<div class="carousel-item">
		  			<h1 class="display-4">Dowland gratís</h1>
		  			<p class="lead">Só aqui na Hyper Music.</p>
		  		</div>
		  		<div class="carousel-item">
		  			<h1 class="display-4">Patrocíono</h1>
		  			<p class="lead">Adflity</p>
		  		</div>		
		  		</div>
		  		<!--Button-->
		  		<a href="#next" class="carousel-control-prev" data-slide="prev">
		  		   <span class="carousel-control-prev-icon"></span>
		  		</a>
		  		<a href="#next" class="carousel-control-next" data-slide="next">
		  			<span class="carousel-control-next-icon"></span>
		  		</a>
		  	</div>
		  </div>
		</div>
	</div>
	</section>

	<!--section-->
	<section id="album1" class="caxote">
	<div class="container">
	   <div class="row">
	   	<div class="col-md-6 col-sm-6">
	   		<img src="https://source.unsplash.com/random/452x218" class="img-fluid">
	   	</div>
	   	<div class="col-md-6 col-sm-6">
	   		<ol class="list-group aff">
	   			<a class="list-group-item bg-dark text-light" href="#"><span class="badge badge-danger">1</span> manga laiga</a>
	   			<a class="list-group-item" href="#"><span class="badge badge-danger">2</span> cachorrinha</a>
	   			<a class="list-group-item" href="#"><span class="badge badge-danger">3</span> formiga</a>
	   			<a class="list-group-item" href="#"><span class="badge badge-danger">4</span> adflity</a>
	   		</ol>
	   		
	   	</div>
	   </div>
	</div>
	</section>

	<footer>
		<div class="container">
			<div class="row">
			<div class="col-md-2 float-left">
				<img src="img/logo.png" width="171px">
			</div>
			<div class="col-md-8 text-center" >
				 <h6 style="font-family: adf; font-size: 35px;">&copy; 2021 Hyper Music</h6>
			</div>
			<div class="col-md-2">
				<div class=" float-right">
				<i class="fab fa-facebook-square mr-2" style="font-size: 38px;"></i>
				<i class="fab fa-instagram mr-2" style="font-size: 38px;"></i>
				<i class="fab fa-twitter-square" style="font-size: 38px;"></i>
			</div>
			</div>
			</div>		
		</div>
		
	</footer>



    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: jQuery and Bootstrap Bundle (includes Popper) -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="js/bootstrap.bundle.min.js"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.min.js" integrity="sha384-+YQ4JLhjyBLPDQt//I+STsc9iw4uQqACwlvpslubQzn4u2UU2UFM80nGisd026JF" crossorigin="anonymous"></script>
    -->
</body>

</html>
