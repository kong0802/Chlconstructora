<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>CHL Constructora | Mano de obra para Suiza</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Fuente moderna -->
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">

<style>
* {margin:0; padding:0; box-sizing:border-box;}
body {font-family:'Montserrat', sans-serif; background:#f9fafb; color:#111827;}

/* Header con logo */
header {
    background: linear-gradient(90deg, #0d47a1, #1976d2);
    color:white;
    text-align:center;
    padding:40px 20px;
    position:relative;
}
header img.logo {
    max-height:80px;
    display:block;
    margin:0 auto 15px auto;
}

/* Header textos */
header h1 {font-size:2.5em; margin-bottom:10px;}
header p {font-size:1.2em;}

/* Navegación */
nav {
    position:sticky;
    top:0;
    background:#0d47a1;
    padding:15px 0;
    text-align:center;
    z-index:1000;
}
nav a {color:white; margin:0 20px; text-decoration:none; font-weight:600;}
nav a:hover {text-decoration:underline;}

/* Main */
main {max-width:1100px; margin:40px auto; padding:0 20px;}
section {margin-bottom:60px;}
section h2 {font-size:2em; color:#0d47a1; margin-bottom:20px; text-align:center;}

/* Tarjetas de servicios */
.services {display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:20px; margin-top:30px;}
.card {background:white; border-radius:10px; padding:20px; box-shadow:0 4px 6px rgba(0,0,0,0.1); text-align:center; transition:transform 0.3s;}
.card:hover {transform:translateY(-5px);}
.card h3 {color:#0d47a1; margin-bottom:15px;}
.card p {line-height:1.5;}

/* Proyectos */
.projects {display:grid; grid-template-columns:repeat(auto-fit,minmax(280px,1fr)); gap:20px; margin-top:30px;}
.project {background:white; border-radius:10px; overflow:hidden; box-shadow:0 4px 6px rgba(0,0,0,0.1);}
.project img {width:100%; display:block;}
.project-description {padding:15px;}
.project-description h4 {color:#0d47a1; margin-bottom:10px;}

/* WhatsApp flotante */
.whatsapp-float {
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25d366;
    color:white;
    font-weight:600;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    box-shadow:0 4px 6px rgba(0,0,0,0.2);
    z-index:1000;
}
.whatsapp-float:hover {background:#1ebe57;}

/* Footer */
footer {background:#0d47a1; color:white; text-align:center; padding:20px;}

/* Responsive */
@media(max-width:600px){header h1{font-size:2em;} nav a{display:block; margin:10px 0;}}
</style>
</head>
<body>

<header>
    <!-- Logo aquí -->
    <img src="logo.png" alt="CHL Constructora Logo" class="logo">
    <h1>CHL Constructora</h1>
    <p>Tramitación de mano de obra española para Suiza</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#servicios">Servicios</a>
    <a href="#proyectos">Proyectos</a>
    <a href="#contacto">Contacto</a>
</nav>

<main>

<section id="inicio">
    <h2>Quiénes somos</h2>
    <p style="text-align:center; max-width:800px; margin:auto;">
        En <strong>CHL Constructora</strong> conectamos mano de obra española cualificada con empresas en Suiza,
        gestionando contratos, permisos y todo el proceso legal para que tus trabajadores puedan incorporarse sin problemas.
    </p>
</section>

<section id="servicios">
    <h2>Servicios</h2>
    <div class="services">
        <div class="card">
            <h3>Contratos laborales</h3>
            <p>Gestionamos contratos legales para trabajadores españoles que quieran trabajar en Suiza.</p>
        </div>
        <div class="card">
            <h3>Permisos de trabajo</h3>
            <p>Nos encargamos de toda la documentación y permisos necesarios para operar legalmente.</p>
        </div>
        <div class="card">
            <h3>Selección de personal</h3>
            <p>Seleccionamos mano de obra cualificada según las necesidades de las empresas suizas.</p>
        </div>
        <div class="card">
            <h3>Asesoría completa</h3>
            <p>Ofrecemos acompañamiento legal y laboral durante todo el proceso de incorporación.</p>
        </div>
    </div>
</section>

<section id="proyectos">
    <h2>Proyectos destacados</h2>
    <div class="projects">
        <div class="project">
            <img src="https://via.placeholder.com/400x250" alt="Proyecto 1">
            <div class="project-description">
                <h4>Proyecto Residencial</h4>
                <p>Construcción y gestión de personal para un complejo residencial en Suiza.</p>
            </div>
        </div>
        <div class="project">
            <img src="https://via.placeholder.com/400x250" alt="Proyecto 2">
            <div class="project-description">
                <h4>Obra Comercial</h4>
                <p>Selección de mano de obra para la construcción de un centro comercial.</p>
            </div>
        </div>
        <div class="project">
            <img src="https://via.placeholder.com/400x250" alt="Proyecto 3">
            <div class="project-description">
                <h4>Remodelación</h4>
                <p>Tramitamos todo el personal para remodelaciones industriales en Suiza.</p>
            </div>
        </div>
    </div>
</section>

<section id="contacto">
    <h2>Contacto</h2>
    <p style="text-align:center;">📞 Teléfono / WhatsApp: +41 76 740 15 41</p>
    <p style="text-align:center;">📧 Email: contacto@chlconstructora.com</p>
    <p style="text-align:center;">🌍 España – Suiza</p>
</section>

</main>

<a href="https://wa.me/41767401541" class="whatsapp-float" target="_blank">WhatsApp</a>

<footer>
    <p>© 2026 - CHL Constructora | Todos los derechos reservados</p>
</footer>

</body>
</html>
