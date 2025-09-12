# multi_theme_portfolio
properties/variables), Bootstrap 5, and JavaScript.  Key features: • Multiple color themes (Light, Dark, Accent) that users can switch dynamically. • Responsive design that works on desktop, tablet, and mobile devices. • Clean, semantic HTML and modular CSS for easy maintenance. • Contact form demo with local JavaScript handling. 
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Multi-Theme Portfolio - Mohanad_Habeeb</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="assets/css/bootstrap.min.css">
    <link rel="stylesheet" href="/assets/css/style.css">
</head>

<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-transparent py-3">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">Mohanad_Habeeb</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navMenu">
                <ul class="navbar-nav ms-auto align-items-lg-center">
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                    <li class="nav-item d-flex align-items-center ms-3">
                        <div class="btn-group" role="group" aria-label="Theme switcher">
                            <button id="theme-light" class="btn btn-sm btn-outline-primary">Light</button>
                            <button id="theme-dark" class="btn btn-sm btn-outline-primary">Dark</button>
                            <button id="theme-accent" class="btn btn-sm btn-outline-primary">Accent</button>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero -->
    <header class="py-5 text-center">
        <div class="container">
            <h1 class="display-5 fw-bold">Hi, I'm <span class="text-primary"> Mohanad_Habeeb</span></h1>
            <p class="lead">Front-End Developer • Bootstrap • CSS Variables • JavaScript</p>
            <a href="#projects" class="btn btn-primary mt-3">See Projects</a>
        </div>
    </header>

    <!-- About -->
    <section id="about" class="py-5">
        <div class="container">
            <div class="row align-items-center g-4">
                <div class="col-md-4 text-center">
                    <div class="avatar shadow-sm mb-3"></div>
                    <h4>Mohanad_Habeeb</h4>
                    <p class="text-muted">Front-End Developer</p>
                </div>
                <div class="col-md-8">
                    <h3>About Me</h3>
                    <p>I build responsive and accessible websites using HTML, CSS, JavaScript and Bootstrap. I like to
                        create theme-ready projects using CSS custom properties so clients can easily update branding.
                    </p>
                    <ul>
                        <li>Responsive design (mobile-first)</li>
                        <li>Themeable UI using CSS variables</li>
                        <li>Vanilla JavaScript and React basics</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="py-5 bg-section">
        <div class="container">
            <h3 class="mb-4">Projects</h3>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card h-100 project-card">
                        <div class="card-body">
                            <h5 class="card-title">Multi-Theme Portfolio</h5>
                            <p class="card-text">Portfolio with Light/Dark/Accent themes via CSS variables.</p>
                            <a href="#" class="btn btn-outline-primary btn-sm" target="_blank">View Demo</a>
                            <a href="#" class="btn btn-outline-secondary btn-sm ms-2" target="_blank">Source</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100 project-card">
                        <div class="card-body">
                            <h5 class="card-title">To-Do App</h5>
                            <p class="card-text">Vanilla JS To-Do with Local Storage and responsive UI.</p>
                            <a href="#" class="btn btn-outline-primary btn-sm" target="_blank">View Demo</a>
                            <a href="#" class="btn btn-outline-secondary btn-sm ms-2" target="_blank">Source</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="py-5">
        <div class="container">
            <h3>Contact</h3>
            <form id="contact-form" class="row g-3">
                <div class="col-md-6">
                    <input type="text" id="name" class="form-control" placeholder="Your name" required>
                </div>
                <div class="col-md-6">
                    <input type="email" id="email" class="form-control" placeholder="Email" required>
                </div>
                <div class="col-12">
                    <textarea id="message" class="form-control" rows="4" placeholder="Message"></textarea>
                </div>
                <div class="col-12">
                    <button type="submit" class="btn btn-primary">Send Message</button>
                    <span id="contact-result" class="ms-3 text-success"></span>
                </div>
            </form>
        </div>
    </section>

    <footer class="py-4 text-center">
        <small class="text-muted">© Your Name • Front-End Developer</small>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="assets/js/bootstrap.bundle.min.js"></script>
    <script src="/assets/js/script.js"></script>
</body>

</html>
