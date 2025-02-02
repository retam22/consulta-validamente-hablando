<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Consulta Válidamente Hablando</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f3f4f6;
        }
        .navbar {
            background-color: #4a90e2;
        }
        .navbar-brand, .nav-link {
            color: white !important;
        }
        .hero-section {
            background: url('https://source.unsplash.com/1600x900/?therapy,mental-health') center/cover no-repeat;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            flex-direction: column;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .btn-primary {
            background-color: #4a90e2;
            border: none;
        }
        .btn-primary:hover {
            background-color: #357ABD;
        }
        .blog-card {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            background: white;
            margin-bottom: 20px;
        }
        .blog-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .blog-card .content {
            padding: 15px;
        }
        .logo {
            width: 100px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg">
        <div class="container">
            <a class="navbar-brand" href="#">Consulta Válidamente Hablando</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Inicio</a></li>
                    <li class="nav-item"><a class="nav-link" href="#registro">Registro</a></li>
                    <li class="nav-item"><a class="nav-link" href="#blog">Blog</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero-section">
        <img src="C:\Users\victo\Downloads\logo.png" alt="Logo Consulta Válidamente Hablando" class="logo">
        <h1>Consulta Válidamente Hablando</h1>
    </div>

    <!-- Formulario de Registro -->
    <div class="container text-center" id="registro">
        <h2 class="mb-4">Formulario de Registro</h2>
        <p>Por favor, completa el siguiente formulario para evaluar tu caso y contactarte.</p>
        <a href="https://forms.gle/tu-formulario" class="btn btn-primary btn-lg mt-3">Ir al Formulario</a>
    </div>

    <!-- Blog Section -->
    <div class="container" id="blog">
        <h2 class="mb-4 text-center">Blog de Psicología</h2>
        <div class="row">
            <div class="col-md-6">
                <div class="blog-card">
                    <img src="https://source.unsplash.com/600x400/?mindfulness" alt="Mindfulness">
                    <div class="content">
                        <h5>Cómo el Mindfulness puede mejorar tu vida</h5>
                        <p>El mindfulness te ayuda a reducir el estrés y aumentar tu bienestar emocional...</p>
                        <a href="#" class="btn btn-primary btn-sm">Leer más</a>
                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div class="blog-card">
                    <img src="https://source.unsplash.com/600x400/?mental-health" alt="Salud Mental">
                    <div class="content">
                        <h5>Importancia de la Salud Mental</h5>
                        <p>Cuidar tu salud mental es tan importante como cuidar tu salud física...</p>
                        <a href="#" class="btn btn-primary btn-sm">Leer más</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
