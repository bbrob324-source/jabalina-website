<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jabalina Barrio Antiguo</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:#111;
    color:white;
}

header{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.75)),
    url('https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?q=80&w=1974&auto=format&fit=crop');
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
}

.hero h1{
    font-size:5rem;
    margin-bottom:15px;
    letter-spacing:3px;
}

.hero p{
    max-width:750px;
    margin:auto;
    font-size:1.2rem;
    line-height:1.8;
}

.btn{
    display:inline-block;
    margin-top:30px;
    padding:15px 35px;
    background:#d4a373;
    color:white;
    text-decoration:none;
    border-radius:40px;
    font-weight:600;
    transition:.3s;
}

.btn:hover{
    background:#b87c45;
    transform:scale(1.05);
}

section{
    padding:90px 10%;
}

.title{
    text-align:center;
    margin-bottom:60px;
}

.title h2{
    font-size:3rem;
    color:#d4a373;
    margin-bottom:15px;
}

.title p{
    color:#bbb;
}

.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:50px;
    align-items:center;
}

.about img{
    width:100%;
    border-radius:25px;
}

.about-text p{
    line-height:2;
    color:#ddd;
    margin-bottom:20px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1b1b1b;
    border-radius:20px;
    overflow:hidden;
    transition:.4s;
}

.card:hover{
    transform:translateY(-10px);
}

.card img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card-content{
    padding:25px;
}

.card-content h3{
    color:#d4a373;
    margin-bottom:10px;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    height:320px;
    object-fit:cover;
    border-radius:20px;
}

.info{
    background:#191919;
    border-radius:30px;
    padding:50px;
    text-align:center;
}

.info p{
    margin:12px 0;
    color:#ddd;
}

footer{
    text-align:center;
    padding:30px;
    color:#888;
    background:black;
}

@media(max-width:900px){

    .hero h1{
        font-size:3rem;
    }

    .about{
        grid-template-columns:1fr;
    }

}

</style>
</head>
<body>

<header>
    <div class="hero">
        <h1>JABALINA</h1>
        <p>
            Cocina norestense contemporánea en el corazón de Barrio Antiguo.
            Un lugar elegante, relajado y lleno de sabor donde la carne,
            la mixología y el ambiente crean una experiencia inolvidable.
        </p>

        <a href="#menu" class="btn">Ver Especialidades</a>
    </div>
</header>

<section>

    <div class="title">
        <h2>Sobre el Restaurante</h2>
        <p>Tradición norteña con alma contemporánea</p>
    </div>

    <div class="about">

        <img src="https://images.unsplash.com/photo-1552566626-52f8b828add9?q=80&w=1974&auto=format&fit=crop">

        <div class="about-text">
            <p>
                Jabalina Barrio Antiguo es uno de los restaurantes más populares
                de Monterrey, reconocido por su ambiente moderno, excelente
                mixología y cocina norteña de autor.
            </p>

            <p>
                Destacan platillos como los tacos de arrachera,
                el chicharrón mixto y cortes premium preparados a la parrilla.
            </p>

            <p>
                El restaurante ha sido mencionado en la Guía Michelin
                gracias a su propuesta gastronómica y experiencia culinaria.
            </p>

        </div>

    </div>

</section>

<section id="menu">

    <div class="title">
        <h2>Especialidades</h2>
        <p>Los favoritos del restaurante</p>
    </div>

    <div class="cards">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1600891964092-4316c288032e?q=80&w=1974&auto=format&fit=crop">
            <div class="card-content">
                <h3>Tacos de Arrachera</h3>
                <p>
                    Tortillas de harina con queso crujiente,
                    arrachera y guacamole fresco.
                </p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1544025162-d76694265947?q=80&w=1974&auto=format&fit=crop">
            <div class="card-content">
                <h3>Rib Eye</h3>
                <p>
                    Cortes premium preparados al carbón
                    con sabor auténtico del norte.
                </p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1514362545857-3bc16c4c7d1b?q=80&w=1974&auto=format&fit=crop">
            <div class="card-content">
                <h3>Mixología</h3>
                <p>
                    Cócteles artesanales ideales para disfrutar
                    la terraza y el ambiente nocturno.
                </p>
            </div>
        </div>

    </div>

</section>

<section>

    <div class="title">
        <h2>Galería</h2>
        <p>Inspirado en el ambiente real del restaurante</p>
    </div>

    <div class="gallery">

        <img src="https://images.unsplash.com/photo-1559339352-11d035aa65de?q=80&w=1974&auto=format&fit=crop">

        <img src="https://images.unsplash.com/photo-1514933651103-005eec06c04b?q=80&w=1974&auto=format&fit=crop">

        <img src="https://images.unsplash.com/photo-1552566626-52f8b828add9?q=80&w=1974&auto=format&fit=crop">

    </div>

</section>

<section>

    <div class="info">

        <h2 style="margin-bottom:20px;color:#d4a373;">
            Información
        </h2>

        <p>📍 Padre Mier 859, Barrio Antiguo, Monterrey, Nuevo León</p>

        <p>📞 +52 81 2572 2060</p>

        <p>🕒 Domingo a miércoles: 9am - 11pm</p>

        <p>🕒 Jueves a sábado: hasta las 2am</p>

        <p>🍽 Cocina Mexicana / Norteña Contemporánea</p>

        <a href="https://www.opentable.com/r/jabalina-barrio-antiguo-monterrey?lang=es"
           target="_blank"
           class="btn">
            Reservar Mesa
        </a>

    </div>

</section>

<footer>

    © 2026 Jabalina Barrio Antiguo | Sitio conceptual inspirado en el restaurante.

</footer>

</body>
</html>
