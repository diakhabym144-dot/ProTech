 <!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<meta name="description" content="ProTech - Técnico informático a domicilio en Montornès del Vallès y alrededores. Reparación de PCs, WiFi, redes, cableado, móviles y más.">

<title>ProTech | Técnico Informático a Domicilio</title>

<style>

:root {
    --blue: #1457e8;
    --dark: #111827;
    --light: #f6f8fc;
    --muted: #64748b;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    color: var(--dark);
    background: white;
    line-height: 1.6;
}

/* HEADER */

header {
    position: sticky;
    top: 0;
    z-index: 10;
    background: rgba(255,255,255,.96);
    border-bottom: 1px solid #e8edf5;
}

.nav {
    max-width: 1100px;
    margin: auto;
    padding: 12px 22px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.nav img {
    width: 130px;
    height: auto;
}

.nav a {
    color: var(--dark);
    text-decoration: none;
    margin-left: 22px;
    font-weight: 600;
    font-size: 14px;
}

.btn {
    display: inline-block;
    background: var(--blue);
    color: white !important;
    padding: 12px 18px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: 700;
    box-shadow: 0 8px 20px rgba(20,87,232,.18);
}

/* HERO */

.hero {
    background: linear-gradient(135deg,#f7f9ff,#fff);
    padding: 80px 22px;
}

.hero-inner {
    max-width: 1100px;
    margin: auto;
    display: grid;
    grid-template-columns: 1.15fr .85fr;
    gap: 50px;
    align-items: center;
}

.badge {
    display: inline-block;
    background: #eaf0ff;
    color: var(--blue);
    padding: 7px 12px;
    border-radius: 99px;
    font-size: 13px;
    font-weight: 700;
    margin-bottom: 18px;
}

h1 {
    font-size: clamp(38px,6vw,68px);
    line-height: 1.03;
    letter-spacing: -2px;
    margin-bottom: 20px;
}

h1 span {
    color: var(--blue);
}

.hero p {
    font-size: 19px;
    color: var(--muted);
    max-width: 650px;
    margin-bottom: 28px;
}

.hero-logo {
    display: flex;
    justify-content: center;
}

.hero-logo img {
    width: min(380px,80vw);
    filter: drop-shadow(0 20px 30px rgba(15,23,42,.08));
}

/* SECCIONES */

section {
    padding: 75px 22px;
}

.container {
    max-width: 1100px;
    margin: auto;
}

.title {
    text-align: center;
    margin-bottom: 42px;
}

.title h2 {
    font-size: 34px;
    margin-bottom: 8px;
}

.title p {
    color: var(--muted);
}

/* SERVICIOS */

.grid {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 18px;
}

.card {
    border: 1px solid #e8edf5;
    border-radius: 16px;
    padding: 24px;
    background: white;
    transition: .2s;
}

.card:hover {
    transform: translateY(-4px);
    box-shadow: 0 14px 35px rgba(15,23,42,.08);
}

.icon {
    font-size: 28px;
    margin-bottom: 12px;
}

.card h3 {
    font-size: 18px;
    margin-bottom: 7px;
}

.card p {
    color: var(--muted);
    font-size: 14px;
}

/* FONDO */

.alt {
    background: var(--light);
}

/* PASOS */

.steps {
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 20px;
}

.step {
    padding: 25px;
    background: white;
    border-radius: 16px;
}

.num {
    color: var(--blue);
    font-size: 14px;
    font-weight: 800;
}

/* CONTACTO */

.contact {
    background: #101827;
    color: white;
}

.contact .title p {
    color: #b9c4d6;
}

.contact-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
}

.contact-card {
    background: #182235;
    border: 1px solid #26334a;
    border-radius: 16px;
    padding: 28px;
}

.contact-card a {
    color: white;
    text-decoration: none;
}

.contact-card .btn {
    margin-top: 18px;
}

.whatsapp {
    background: #20c66a;
    color: white !important;
}

/* FOOTER */

footer {
    padding: 24px 22px;
    text-align: center;
    color: #718096;
    font-size: 13px;
}

/* MÓVIL */

@media(max-width:760px) {

    .nav div:last-child {
        display: none;
    }

    .hero {
        padding: 55px 20px;
    }

    .hero-inner {
        grid-template-columns: 1fr;
        text-align: center;
    }

    .hero p {
        margin-left: auto;
        margin-right: auto;
    }

    .grid,
    .steps,
    .contact-grid {
        grid-template-columns: 1fr;
    }

    .hero-logo {
        order: -1;
    }

    .hero-logo img {
        width: 250px;
    }

    section {
        padding: 55px 20px;
    }
}

</style>
</head>

<body>

<!-- HEADER -->

<header>

<nav class="nav">

<a href="#inicio">
<img src="logo.png" alt="ProTech">
</a>

<div>

<a href="#servicios">Servicios</a>

<a href="#como">Cómo trabajamos</a>

<a href="#contacto">Contacto</a>

</div>

</nav>

</header>


<main>

<!-- INICIO -->

<section class="hero" id="inicio">

<div class="hero-inner">

<div>

<div class="badge">
🛠️ Servicio técnico a domicilio
</div>

<h1>
Soluciones informáticas
<span>sin complicaciones.</span>
</h1>

<p>
ProTech ofrece asistencia informática a domicilio en Montornès del Vallès y alrededores. PCs, WiFi, redes, cableado, móviles, instalaciones y mucho más.
</p>

<a
class="btn"
href="https://wa.me/34645465230?text=Hola%20ProTech%2C%20quiero%20consultar%20un%20servicio."
target="_blank">

💬 Contactar por WhatsApp

</a>

</div>


<div class="hero-logo">

<img src="logo.png" alt="Logo ProTech">

</div>

</div>

</section>


<!-- SERVICIOS -->

<section id="servicios">

<div class="container">

<div class="title">

<h2>¿En qué puedo ayudarte?</h2>

<p>
Servicios informáticos para particulares y pequeños negocios.
</p>

</div>


<div class="grid">


<div class="card">

<div class="icon">🖥️</div>

<h3>PCs y portátiles</h3>

<p>
Diagnóstico, reparación, mantenimiento, montaje y actualización de componentes.
</p>

</div>


<div class="card">

<div class="icon">🌐</div>

<h3>WiFi y redes</h3>

<p>
Configuración de routers, repetidores, problemas de conexión y mejora de cobertura.
</p>

</div>


<div class="card">

<div class="icon">🔌</div>

<h3>Cableado de red</h3>

<p>
Instalación, organización y configuración de conexiones de red en casa o negocio.
</p>

</div>


<div class="card">

<div class="icon">🚀</div>

<h3>Optimización</h3>

<p>
Puesta a punto, limpieza de software, mejora del rendimiento y configuración.
</p>

</div>


<div class="card">

<div class="icon">🦠</div>

<h3>Virus y malware</h3>

<p>
Detección, limpieza y configuración de medidas básicas de seguridad.
</p>

</div>


<div class="card">

<div class="icon">💾</div>

<h3>Datos y copias</h3>

<p>
Transferencia de fotos, vídeos y archivos, copias de seguridad y restauraciones.
</p>

</div>


<div class="card">

<div class="icon">📱</div>

<h3>Móviles</h3>

<p>
Configuración, transferencia de datos, restauración y puesta a punto.
</p>

</div>


<div class="card">

<div class="icon">🪟</div>

<h3>Windows</h3>

<p>
Instalación, configuración y solución de problemas del sistema operativo.
</p>

</div>


<div class="card">

<div class="icon">🖨️</div>

<h3>Periféricos</h3>

<p>
Instalación y configuración de impresoras, accesorios y dispositivos.
</p>

</div>


</div>

</div>

</section>


<!-- CÓMO TRABAJAMOS -->

<section class="alt" id="como">

<div class="container">

<div class="title">

<h2>Así de fácil</h2>

<p>
Un servicio claro y directo.
</p>

</div>


<div class="steps">


<div class="step">

<div class="num">
01 · CONTACTA
</div>

<h3>
Cuéntame el problema
</h3>

<p>
Explícame qué necesitas por WhatsApp o teléfono.
</p>

</div>


<div class="step">

<div class="num">
02 · DIAGNÓSTICO
</div>

<h3>
Reviso el equipo
</h3>

<p>
Analizo el problema y te informo del trabajo necesario y su precio.
</p>

</div>


<div class="step">

<div class="num">
03 · SOLUCIÓN
</div>

<h3>
Lo dejamos funcionando
</h3>

<p>
Realizo el servicio con cuidado y te explico lo realizado.
</p>

</div>


</div>

</div>

</section>


<!-- CONTACTO -->

<section class="contact" id="contacto">

<div class="container">

<div class="title">

<h2>
Contacta con ProTech
</h2>

<p>
¿Tienes un problema informático? Hablemos.
</p>

</div>


<div class="contact-grid">


<div class="contact-card">

<h3>
📞 Teléfono
</h3>

<p>

<a href="tel:+34645465230">
645 46 52 30
</a>

</p>

<a
class="btn"
href="tel:+34645465230">

Llamar ahora

</a>

</div>


<div class="contact-card">

<h3>
💬 WhatsApp
</h3>

<p>
También puedes escribirme directamente por WhatsApp.
</p>

<a
class="btn whatsapp"
href="https://wa.me/34645465230?text=Hola%20ProTech%2C%20quiero%20consultar%20un%20servicio."
target="_blank">

Abrir WhatsApp

</a>

</div>


</div>

</div>

</section>

</main>


<!-- FOOTER -->

<footer>

© 2026 ProTech · Técnico Informático a Domicilio · Montornès del Vallès y alrededores

</footer>


</body>
</html>
