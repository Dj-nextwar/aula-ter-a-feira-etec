<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Atividade Bootstrap</title>
 <!-- tentiva git djalma -->
<!-- Bootstrap 5 -->
<link href="jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css
</head>
<body>
 
<div class="container mt-4">
 
<h1 class="text-center mb-4">Exemplos de Componentes Bootstrap 5</h1>
 
<!-- 1. Tabela -->
<h2>Tabela</h2>
<table class="table table-striped">
<thead>
<tr>
<th>Nome</th>
<th>Curso</th>
</tr>
</thead>
<tbody>
<tr>
<td>Djalma</td>
<td>ADS</td>
</tr>
<tr>
<td>fulana</td>
<td>SI</td>
</tr>
</tbody>
</table>
 
<!-- 2. Dropdown -->
<h2>Dropdown</h2>
<div class="dropdown mb-4">
<button class="btn btn-primary dropdown-toggle" type="button" data-bs-toggle="dropdown">
Escolha uma opção
</button>
<ul class="dropdown-menu">
<li>#Opção 1</a></li>
<li>#Opção 2</a></li>
<li>#Opção 3</a></li>
</ul>
</div>
 
<!-- 3. Navbar -->
<h2>Navbar</h2>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark mb-4">
<div class="container-fluid">
#Meu Site</a>
</div>
</nav>
 
<!-- 4. Carousel -->
<h2>Carousel</h2>
<div id="demo" class="carousel slide mb-4" data-bs-ride="carousel">
<div class="carousel-inner">
<div class="carousel-item active">
<img src="csum.photos/800/300?1
</div>
<div class="carousel-item">
<img src="https://picsum.photos/800 </div>
<div class="carousel-item">
<img src="https://picsum.photos/800/300 </div>
</div>
</div>
 
<!-- 5. Modal -->
<h2>Modal</h2>
<button type="button" class="btn btn-success" data-bs-toggle="modal" data-bs-target="#meuModal">
Abrir Modal
</button>
 
<div class="modal fade" id="meuModal">
<div class="modal-dialog">
<div class="modal-content">
 
<div class="modal-header">
<h4 class="modal-title">Exemplo de Modal</h4>
<button type="button" class="btn-close" data-bs-dismiss="modal"></button>
</div>
 
<div class="modal-body">
Esta é uma janela modal criada com Bootstrap 5.
</div>
 
</div>
</div>
</div>
 
</div>
 
https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.jsscript>
 
</body>
</html>