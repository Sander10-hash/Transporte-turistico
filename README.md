<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Viajes El Salvador - Transporte Turístico Premium</title>
    <meta name="description" content="Transporte turístico seguro y cómodo en El Salvador. Recorre volcanes, playas, pueblos y ruinas mayas con guías expertos.">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root{
            --color-primario:#005f73;
            --color-secundario:#0a9396;
            --color-acento:#ee9b00;
            --color-fondo:#f8f9fa;
        }
        body{font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: var(--color-fondo);}
        .navbar-brand{font-weight:700; font-size:1.4rem;}
        .btn-cta{background-color: var(--color-acento); border:none;}
        .hero{background: url('https://images.unsplash.com/photo-1583083527882-4bee9aba2eea?auto=format&fit=crop&w=1350&q=80') center/cover; height:70vh; position:relative;}
        .hero-overlay{position:absolute; inset:0; background:rgba(0,0,0,.55);}
        .hero-content{z-index:2;}
        .card-hover:hover{transform:translateY(-5px); transition:.3s;}
        footer{background-color: var(--color-primario);}
    </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark" style="background-color: var(--color-primario);">
  <div class="container">
    <a class="navbar-brand" href="#"><i class="fa-solid fa-bus me-2"></i>Viajes El Salvador</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#servicios">Servicios</a></li>
        <li class="nav-item"><a class="nav-link" href="#rutas">Rutas</a></li>
        <li class="nav-item"><a class="nav-link" href="#galeria">Galería</a></li>
        <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero -->
<section class="hero d-flex align-items-center text-white">
  <div class="hero-overlay"></div>
  <div class="container hero-content text-center">
    <h1 class="display-4 fw-bold">Descubre El Salvador con Estilo y Seguridad</h1>
    <p class="lead mb-4">Transporte turístico premium. Recorre volcanes, playas, pueblos y ruinas mayas con guías expertos.</p>
    <a href="#contacto" class="btn btn-cta btn-lg px-4 py-2">Reserva tu Viaje</a>
  </div>
</section>

<!-- Servicios -->
<section id="servicios" class="py-5">
  <div class="container">
    <h2 class="text-center mb-5">Nuestros Servicios</h2>
    <div class="row g-4">
      <div class="col-md-6 col-lg-3">
        <div class="card h-100 card-hover">
          <div class="card-body text-center">
            <i class="fa-solid fa-route fa-3x mb-3" style="color:var(--color-secundario);"></i>
            <h5 class="card-title">Tours Privados</h5>
            <p class="card-text">Itinerarios personalizados según tus intereses y tiempo disponible.</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-3">
        <div class="card h-100 card-hover">
          <div class="card-body text-center">
            <i class="fa-solid fa-shuttle-van fa-3x mb-3" style="color:var(--color-secundario);"></i>
            <h5 class="card-title">Traslados Aeropuerto</h5>
            <p class="card-text">Recogida y traslado seguro desde y hacia el Aeropuerto Internacional.</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-3">
        <div class="card h-100 card-hover">
          <div class="card-body text-center">
            <i class="fa-solid fa-users fa-3x mb-3" style="color:var(--color-secundario);"></i>
            <h5 class="card-title">Grupos Corporativos</h5>
            <p class="card-text">Transporte especializado para convenciones, eventos y visitas técnicas.</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-3">
        <div class="card h-100 card-hover">
          <div class="card-body text-center">
            <i class="fa-solid fa-mountain-sun fa-3x mb-3" style="color:var(--color-secundario);"></i>
            <h5 class="card-title">Aventura y Naturaleza</h5>
            <p class="card-text">Excursiones a volcanes, lagos, cascadas y parques nacionales.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Rutas destacadas -->
<section id="rutas" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-4">Rutas Destacadas</h2>
    <div class="row g-4">
      <div class="col-md-6 col-lg-4">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1604999333679-b86d54738315?auto=format&fit=crop&w=800&q=60" class="card-img-top" alt="Ruta de las Flores">
          <div class="card-body">
            <h5 class="card-title">Ruta de las Flores</h5>
            <p class="card-text">Pasea por Juayúa, Ataco y Apaneca. Café, arte callejero y gastronomía.</p>
            <span class="badge bg-success">1 día</span>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1507035895480-2b3156c31fc8?auto=format&fit=crop&w=800&q=60" class="card-img-top" alt="Suchitoto">
          <div class="card-body">
            <h5 class="card-title">Suchitoto & Lago Suchitlán</h5>
            <p class="card-text">Encanto colonial, artesanías y paseo en bote por la isla de las aves.</p>
            <span class="badge bg-success">1 día</span>
          </div>
        </div>
      </div>
      <div class="col-md-6 col-lg-4">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1599571234909-29ed5d1321d6?auto=format&fit=crop&w=800&q=60" class="card-img-top" alt="Playa El Tunco">
          <div class="card-body">
            <h5 class="card-title">Playa El Tunco & Surf</h5>
            <p class="card-text">Relájate en la playa más famosa del país y aprende a surfear.</p>
            <span class="badge bg-success">Medio día</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Galería -->
<section id="galeria" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Galería</h2>
    <div class="row g-3">
      <div class="col-6 col-md-4 col-lg-2"><img src="https://source.unsplash.com/400x300?san-salvador" class="img-fluid rounded" alt="San Salvador"></div>
      <div class="col-6 col-md-4 col-lg-2"><img src="https://source.unsplash.com/400x300?el-salvador-volcano" class="img-fluid rounded" alt="Volcán"></div>
      <div class="col-6 col-md-4 col-lg-2"><img src="https://source.unsplash.com/400x300?el-salvador-beach" class="img-fluid rounded" alt="Playa"></div>
      <div class="col-6 col-md-4 col-lg-2"><img src="https://source.unsplash.com/400x300?el-salvador-food" class="img-fluid rounded" alt="Comida"></div>
      <div class="col-6 col-md-4 col-lg-2"><img src="https://source.unsplash.com/400x300?el-salvador-colonial" class="img-fluid rounded" alt="Colonial"></div>
      <div class="col-6 col-md-4 col-lg-2"><img src="https://source.unsplash.com/400x300?el-salvador-ruins" class="img-fluid rounded" alt="Ruinas"></div>
    </div>
  </div>
</section>

<!-- Contacto -->
<section id="contacto" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-4">Contáctanos</h2>
    <div class="row justify-content-center">
      <div class="col-lg-8">
        <form action="https://formspree.io/f/YOUR-ID" method="POST">
          <div class="row g-3 mb-3">
            <div class="col-md-6">
              <label class="form-label">Nombre</label>
              <input type="text" class="form-control" name="nombre" required>
            </div>
            <div class="col-md-6">
              <label class="form-label">Correo electrónico</label>
              <input type="email" class="form-control" name="email" required>
            </div>
          </div>
          <div class="mb-3">
            <label class="form-label">Mensaje / Fecha tentativa</label>
            <textarea class="form-control" rows="4" name="mensaje" required></textarea>
          </div>
          <button type="submit" class="btn btn-cta w-100 py-2">Enviar Solicitud</button>
        </form>
        <div class="text-center mt-4">
          <p><i class="fa-brands fa-whatsapp"></i> WhatsApp: <a href="https://wa.me/50312345678">+503 1234 5678</a></p>
          <p><i class="fa-solid fa-envelope"></i> Email: <a href="mailto:info@viajessv.com">info@viajessv.com</a></p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Footer -->
<footer class="text-white py-4">
  <div class="container text-center">
    <p class="mb-1">&copy; 2025 Viajes El Salvador. Todos los derechos reservados.</p>
    <div>
      <a href="#" class="text-white me-3"><i class="fa-brands fa-facebook-f"></i></a>
      <a href="#" class="text-white me-3"><i class="fa-brands fa-instagram"></i></a>
      <a href="#" class="text-white"><i class="fa-brands fa-tiktok"></i></a>
    </div>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
