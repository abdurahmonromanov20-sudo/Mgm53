<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mening Publichniy Saytim</title>
    
    <!-- Google Fonts (Poppins) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Font Awesome Ikonkalar -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        .hero-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 100px 0;
        }
        .feature-icon {
            font-size: 2.5rem;
            color: #764ba2;
        }
    </style>
</head>
<body>

    <!-- Navigatsiya paneli (Navbar) -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">MyProject</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="#home">Asosiy</a></li>
                    <li class="nav-item"><a class="nav-link" href="#features">Xizmatlar</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">Biz haqimizda</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Aloqa</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section (Asosiy qism) -->
    <section id="home" class="hero-section text-center text-md-start">
        <div class="container">
            <div class="row align-items-center g-5">
                <div class="col-md-6">
                    <h1 class="display-4 fw-bold mb-3">Zamonaviy Web Sayt platformasiga xush kelibsiz!</h1>
                    <p class="lead mb-4">Bu sayt HTML, CSS va Bootstrap 5 yordamida mutlaqo mobilbop qilib yaratildi. Loyihalaringizni dunyoga ko'rsating.</p>
                    <a href="#features" class="btn btn-light btn-lg px-4 me-2 fw-semibold text-primary">Boshlash</a>
                    <a href="#contact" class="btn btn-outline-light btn-lg px-4">Bog'lanish</a>
                </div>
                <div class="col-md-6 text-center">
                    <img src="https://images.unsplash.com/photo-1531403009284-440f080d1e12?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Hero Image" class="img-fluid rounded-3 shadow-lg">
                </div>
            </div>
        </div>
    </section>

    <!-- Xizmatlar qismi (Features) -->
    <section id="features" class="py-5 bg-light">
        <div class="container text-center py-4">
            <h2 class="fw-bold mb-5">Bizning Afzalliklarimiz</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card h-100 p-4 border-0 shadow-sm">
                        <div class="card-body">
                            <i class="fa-solid fa-laptop-code feature-icon mb-3"></i>
                            <h5 class="card-title fw-bold">Toza Kod</h5>
                            <p class="card-text text-muted">Bootstrap komponentlari asosida yozilgan, tushunarli va oson tahrirlanuvchi kod strukturasi.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100 p-4 border-0 shadow-sm">
                        <div class="card-body">
                            <i class="fa-solid fa-mobile-screen feature-icon mb-3"></i>
                            <h5 class="card-title fw-bold">Responsive Dizayn</h5>
                            <p class="card-text text-muted">Telefon, planshet va kompyuter ekranlariga avtomatik tarzda ajoyib moslashish.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100 p-4 border-0 shadow-sm">
                        <div class="card-body">
                            <i class="fa-solid fa-bolt feature-icon mb-3"></i>
                            <h5 class="card-title fw-bold">Tezkorlik</h5>
                            <p class="card-text text-muted">CDN tarmoqlari orqali ulangan kutubxonalar tufayli sayt juda tez yuklanadi.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Aloqa qismi (Contact Form) -->
    <section id="contact" class="py-5">
        <div class="container py-4" style="max-width: 600px;">
            <h2 class="fw-bold text-center mb-4">Biz bilan bog'laning</h2>
            <form>
                <div class="mb-3">
                    <label class="form-label fw-semibold">Ismingiz</label>
                    <input type="text" class="form-control form-control-lg" placeholder="Eshmat Toshmatov" required>
                </div>
                <div class="mb-3">
                    <label class="form-label fw-semibold">Email manzilingiz</label>
                    <input type="email" class="form-control form-control-lg" placeholder="name@example.com" required>
                </div>
                <div class="mb-3">
                    <label class="form-label fw-semibold">Xabaringiz</label>
                    <textarea class="form-control form-control-lg" rows="4" placeholder="Xabarni shu yerga yozing..." required></textarea>
                </div>
                <button type="submit" class="btn btn-primary btn-lg w-100" style="background-color: #764ba2; border: none;">Yuborish</button>
            </form>
        </div>
    </section>

    <!-- Footer (Sayt oxiri) -->
    <footer class="bg-dark text-white text-center py-4">
        <div class="container">
            <p class="mb-0">&copy; 2026 MyProject. Barcha huquqlar himoyalangan.</p>
        </div>
    </footer>

    <!-- Bootstrap 5 JS va Popper.js -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
