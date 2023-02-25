# gjb91.github.io
Tema: Inicios en front end.
Título: tp final.
Descripción: entrega de proyecto final del curso.
index.html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilo.css">
    <title>CV John Doe</title>
</head>
<body>
    <!-- SECCION INICIO -->
    <section class="inicio" id="inicio">
        <div class="contenido-seccion">
            <header>
                <div class="nav-bar" onclick="mostrarOcultarMenu()">
                    <i class="fa-solid fa-bars"></i>
                </div>
                <nav id="nav" class="nav">
                    <a href="#inicio">Inicio</a>
                    <a href="#sobremi">Sobre mí</a>
                    <a href="#habilidades">Habilidades</a>
                    <a href="#resumen">Resumen</a>
                    <a href="#contacto">Contacto</a>
                </nav>
                <div class="logo">
                    M<span class="color">S</span>
                </div>
            </header>
            <div class="info">
                <h1>John Doe 91</h1>
                <h2>Profesional de la salud, Autodidacta</h2>
                <div class="redes">
                    <a href="#"><i class="fa-brands fa-twitter"></i></a>
                    <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                    <a href="#"><i class="fa-brands fa-square-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-youtube"></i></a>
                    <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
                    <a href="#"><i class="fa-brands fa-pinterest-p"></i></a>
                </div>
            </div>
            <div class="foto">
                <img src="http://www.stars-portraits.com/img/portraits/stars/p/per-yngve-ohlin/per-yngve-ohlin-by-ambrasegat[310566].jpg" alt="">
            </div>
        </div>
    </section>

    <!-- SECCION SOBRE MI -->
    <section class="sobremi" id="sobremi">
        <div class="contenido-seccion">
            <h2 class="titulo-seccion">Sobre Mi</h2>
            <h3>Detalles personales</h3>

            <p class="especial">Me dedico al área de diagnóstico por imágenes y quiero expandirme.</p>
            <p>Noen ganger finner du noe du ikke engang visste om og ikke visste at du kunne være interessert i.</p>

            <div class="fila">
                <div class="col">
                    <i class="fa-solid fa-user"></i>
                    <span class="titulo-detalle">Perfil</span>
                    <p>Noen ganger finner du noe du ikke engang visste om og ikke visste at du kunne være interessert i.</p>
                </div>
                <div class="col">
                    <i class="fa-solid fa-location-pin"></i>
                    <span class="titulo-detalle">Ubicación</span>
                    <p>Noen ganger finner du noe du ikke engang visste om og ikke visste at du kunne være interessert i.</p>
                </div>
                <div class="col">
                    <i class="fa-solid fa-flag"></i>
                    <span class="titulo-detalle">Intereses</span>
                    <p>Noen ganger finner du noe du ikke engang visste om og ikke visste at du kunne være interessert i.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- SECCION HABILIDADES -->
    <section class="habilidades" id="habilidades">
        <div class="contenido-seccion">
            <h2 class="titulo-seccion">Mis habilidades</h2>
            <h3>Me especializo en diagnóstico por imágenes.</h3>

            <div class="fila">
                <div class="col">
                    <span>Tomografía</span>
                    <div class="cont-barra">
                        <div class="barra" id="html">
                            
                        </div>
                        <span>98%</span>
                    </div>
                </div>
                <div class="col">
                    <span>Radiología</span>
                    <div class="cont-barra">
                        <div class="barra" id="javascript">
                           
                        </div>
                        <span>100%</span>
                    </div>
                </div>
            </div>
            <div class="fila">
                <div class="col">
                    <span>Densitometría</span>
                    <div class="cont-barra">
                        <div class="barra" id="wordpress">
                            
                           
                        </div>
                        <span>90%</span>
                    </div>
                </div>
                <div class="col">
                    <span>Resonancia magnética</span>
                    <div class="cont-barra">
                        <div class="barra" id="photoshop">
                            
                           
                        </div>
                        <span>20%</span>
                    </div>
                </div>
            </div>
            <div class="fila">
                <div class="col">
                    <span>Reconocimiento de patologías.</span>
                    <div class="cont-barra">
                        <div class="barra" id="php">
                            
                           
                        </div>
                        <span>95%</span>
                    </div>
                </div>
                <div class="col">
                    <span>Ganas de aprender.</span>
                    <div class="cont-barra">
                        <div class="barra" id="ilustrator">
                            
                           
                        </div>
                        <span>100%</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    
    <section class="resumen" id="resumen">
        <div class="contenido-seccion">
            <h2 class="titulo-seccion">Resumen</h2>
            <h3>Mi preparación y experiencia</h3>
            <div class="info">
                <div class="col">
                    <span class="titulo">Educación</span>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>2005 - 2009</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Noen ganger finner du noe du ikke engang visste om og ikke visste at du kunne være interessert i.um.
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <h4>XXXXXXXXX</h4>
                                <p>Universidad de XXXXXXX</p>
                                <span class="promedio">8.5 PG</span>
                            </td>
                        </tr>
                    </table>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>2010 - 2014</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Noen ganger finner du noe du ikke engang visste om og ikke visste at du kunne være interessert i.
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <h4>Estudiante de programación.</h4>
                                <p>Aula online.</p>
                                <span class="promedio">8.9 PG</span>
                            </td>
                        </tr>
                    </table>
                </div>
                <div class="col">
                    <span class="titulo">Experiencia Laboral en mi rubro.</span>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>7 Años</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Noen ganger finner du noe du ikke engang visste om og ikke visste at du kunne være interessert i.
                        </tr>
                        <tr>
                            <td>
                                <h4>XXXXXX</h4>
                                <p>XXXXXX</p>
                               
                            </td>
                        </tr>
                    </table>
                    <table>
                        <tr>
                            <td class="datos">
                                <h3>5 Años</h3>
                            </td>
                            <td rowspan="2" class="descripcion">
                                Noen ganger finner du noe du ikke engang visste om og ikke visste at du kunne være interessert i.
                            </td>
                        </tr>
                        <tr>
                            <td>
                                <h4>JHFGFFFGBLB</h4>
                                <p>Sin experiencia.</p>
                            </td>
                        </tr>
                    </table>
                </div>
            </div>
        </div>
    </section>

    
    <section class="contacto" id="contacto">
        <div class="contenido-seccion">
            <h2 class="titulo-seccion">Contacto</h2>
            <h3>Acceso a mi contacto.</h3>

            <div class="fila">
                <div class="col">
                    <h2>
                        <i class="fa-solid fa-phone"></i> Teléfono
                    </h2>
                    <span class="info-contacto">1234567890</span>
                </div>
                <div class="col">
                    <h2>
                        <i class="fa-solid fa-envelope"></i> Correo
                    </h2>
                    <span class="info-contacto">hola@hola.com.ar</span>
                </div>
                <div class="col">
                    <h2>
                        <i class="fa-solid fa-globe"></i> Página Web
                    </h2>
                    <span class="info-contacto">holajohndoe91.com</span>
                </div>
            </div>
        </div>
    </section>

    <script src="app.js"></script>
</body>
</html>

CSS
@import url('https://fonts.googleapis.com/css2?family=Titillium+Web:wght@200;300;400;600;700&family=Yellowtail&display=swap');
*{
    font-family: "Titillium Web";
    margin: 0;
    padding: 0;
}
html{
    scroll-behavior: smooth;
}

/* SECCION INICIO */
.inicio{
    background: linear-gradient(rgba(0,0,0,.3), rgba(0,0,0,.3)),
    url("img/fondo.jpg");
    background-size: cover;
    background-position: center center;
    color: #fff;
}
.inicio .contenido-seccion{
    max-width: 1000px;
    margin: auto;
    text-align: center;
    padding: 0 10px;
}
.inicio .contenido-seccion header{
    padding: 30px;
}
/* menu lateral */
.inicio .contenido-seccion header nav{
    position: fixed;
    margin-left: 60px;
    background-color: cornflowerblue;
    padding: 15px;
    border-radius: 10px;
    text-align: left;
    z-index: 99;
    display: none;
}
.inicio .contenido-seccion header nav a{
    display: block;
    color: #df3f3f;
    text-decoration: none;
    margin-bottom: 10px;
    font-weight: bold;
}
/* ****** */
.inicio .contenido-seccion header .logo{
    font-weight: bold;
    font-size: 2.5rem;
    font-family: "Yellowtail";
    text-shadow: 0 0 35px #830b0b;
}
.inicio .contenido-seccion header .logo .color{
    color: #940253;
    font-family: "Yellowtail";
}
.inicio .contenido-seccion header .nav-bar{
    position: fixed;
    background-color: #c0470e;
    font-size: 20px;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    line-height: 50px;
    cursor: pointer;
    transition: .3s;
}
.inicio .contenido-seccion header .nav-bar:hover{
    box-shadow: 0 0 35px #f74040;
}
.inicio .contenido-seccion .info{
    padding-bottom: 130px;
}
.inicio .contenido-seccion .info h1{
    font-size: 3rem;
    letter-spacing: 5px;
}
.inicio .contenido-seccion .info h2{
    font-weight: normal;
    font-size: 20px;
    margin-top: -10px;
    letter-spacing: 2px;
}
.inicio .contenido-seccion .info .redes{
    margin: 20px 0;
}
.inicio .contenido-seccion .info .redes a{
    display: inline-block;
    text-decoration: none;
    background-color: #000;
    color: #b6aa09;
    border: 1px solid #cc4813;
    border-radius: 50%;
    width: 40px;
    height: 40px;
    line-height: 40px;
    margin: 0 5px;
    transition: .3s;
}
.inicio .contenido-seccion .info .redes a:hover{
    color: #fff;
    background-color: #ac0000;
    box-shadow: 0 0 20px #fff;
}
.inicio .contenido-seccion .foto{
    position: relative;
}
.inicio .contenido-seccion .foto img{
    max-width: 200px;
    border-radius: 50%;
    border: 5px solid #9e3911;
    position: absolute;
    left: 50%;
    top: -100px;
    transform: translateX(-50%);
}
/* estilos generales */
.titulo-seccion{
    font-family: "Yellowtail";
    font-size: 1.5rem;
}
/* SECCION SOBRE MI */
.sobremi{
    background-color: #751616;
    padding: 140px 0 100px 0;
    text-align: center;
}
.sobremi .contenido-seccion{
    max-width: 1000px;
    margin: auto;
    padding: 0 10px;
}
.sobremi .contenido-seccion h3{
    text-transform: uppercase;
    font-size: 30px;
}
.sobremi .contenido-seccion .especial{
    color: #913206;
    font-weight: bold;
    margin-top: 15px;
}
.sobremi .contenido-seccion p{
    max-width: 700px;
    margin: auto;
    color: #666;
}
.sobremi .contenido-seccion .fila{
    display: flex;
    margin-top: 30px;
    justify-content: space-between;
}
.sobremi .contenido-seccion .fila .col{
    width: 30%;
}
.sobremi .contenido-seccion .fila .col i{
    color: #029433;
    display: inline-block;
    width: 40px;
    height: 40px;
    border: 2px solid #527e18;
    line-height: 40px;
    border-radius: 50%;
}
.sobremi .contenido-seccion .fila .col span{
    display: block;
    font-weight: bold;
    margin: 8px 0;
}
/* SECCION HABILIDADES */
.habilidades{
    padding: 80px 0 100px 0;
    text-align: center;
    background: linear-gradient(rgba(0,0,0,.3), rgba(0,0,0,.3)),
    url("img/habilidades.jpg");
    background-size: cover;
    background-attachment: fixed;
    background-position: center center;
    color: #fff;
}
.habilidades .contenido-seccion{
    max-width: 1000px;
    margin: auto;
    padding: 0 10px;
}
.habilidades .contenido-seccion h3{
    text-transform: uppercase;
    font-size: 30px;
}
.habilidades .contenido-seccion .fila{
    display: flex;
    justify-content: space-between;
    margin-top: 30px;
}
.habilidades .contenido-seccion .fila .col{
    width: 47%;
    text-align: left;
}
.habilidades .contenido-seccion .fila .col .cont-barra{
    display: flex;
    align-items: center;
}
.habilidades .contenido-seccion .barra{
    display: flex;
    border: 1px solid #d41818;
    padding: 2px;
    border-radius: 3px;
    margin-right: 10px;
}
.habilidades .contenido-seccion .barra .e{
    background-color: #363636;
    width: 20px;
    height: 30px;
    margin-right: 2px;
}
/* SECCION RESUMEN */
.resumen{
    background-color: #34a730;
    padding: 140px 0 100px 0;
    text-align: center;
}
.resumen .contenido-seccion{
    max-width: 1000px;
    margin: auto;
    padding: 0 10px;
}
.resumen .contenido-seccion h3{
    text-transform: uppercase;
    font-size: 30px;
}
.resumen .contenido-seccion .info{
    text-align: left;
    display: flex;
    justify-content: space-between;
    margin-top: 30px;
}
.resumen .contenido-seccion .info .col{
    width: 45%;
}
.resumen .contenido-seccion .info .col .titulo{
    display: inline-block;
    color: #940253;
    font-weight: bold;
    border: 2px solid #940253;
    padding: 10px;

}
.resumen .contenido-seccion .info .col table{
    margin-top: 30px;
    border-collapse: collapse;
}
.resumen .contenido-seccion .info .col table .datos{
    width: 40%;
    border-bottom: 1px solid #bab9b9;
}
.resumen .contenido-seccion .info .col table h4{
    margin-top: 10px;
}
.resumen .contenido-seccion .info .col table h3{
    font-size: 20px;
    margin-bottom: 5px;
}
.resumen .contenido-seccion .info .col table p{
    font-size: 14px;
}
.resumen .contenido-seccion .info .col table .promedio{
    display: block;
    color: #a38b1d;
    margin-top: 10px;
    font-weight: bold;
}
.resumen .contenido-seccion .info .col table .descripcion{
    border-left: 1px solid #bab9b9;
    padding-left: 20px;
}
/* SECCION CONTACTO */
.contacto{
    background-color: #611c1c;
    padding: 140px 0 100px 0;
    color: #706f6f;
    text-align: center;
}
.contacto .contenido-seccion{
    max-width: 1000px;
    margin: auto;
    padding: 0 10px;
}
.contacto .contenido-seccion h3{
    text-transform: uppercase;
    font-size: 30px;
}
.contacto .contenido-seccion .fila{
    display: flex;
    justify-content: space-around;
}
.contacto .contenido-seccion .fila .col{
    margin-top: 50px;
}
.contacto .contenido-seccion .fila .col h2{
    color: #940253;
}
/* SECCION RESPONSIVE */
@media screen and (max-width:800px){
    .habilidades .contenido-seccion .fila{
        display: block;
    }
    .habilidades .contenido-seccion .fila .col{
        width: 100%;
        text-align: center;
    }
    .habilidades .contenido-seccion .fila .col .cont-barra{
        justify-content: center;
    }
    .sobremi .contenido-seccion .fila{
        display: block;
    }
    .sobremi .contenido-seccion .fila .col{
        width: 80%;
        margin: auto;
        margin-top: 20px;
    }
    .resumen .contenido-seccion .info{
        display: block;
    }
    .resumen .contenido-seccion .info .col{
        width: 90%;
        margin: auto;
    }
    .resumen .contenido-seccion .info .col .titulo{
        display: block;
        text-align: center;
    }
    .resumen .contenido-seccion .info .col table{
        margin-top: 10px;
        margin-bottom: 30px;
    }
    .contacto .contenido-seccion .fila{
        display: block;
    }

Javascript
var menu_visible = false;
let menu = document.getElementById("nav");
function mostrarOcultarMenu(){
    if(menu_visible==false){//si esta oculto
        menu.style.display = "block";
        menu_visible = true;
    }
    else{
        menu.style.display = "none";
        menu_visible = false;
    }
}
//oculto el menu una vez que selecciono una opción
let links = document.querySelectorAll("nav a");
for(var x = 0; x <links.length;x++){
    links[x].onclick = function(){
        menu.style.display = "none";
        menu_visible = false;
    }
}

//Creo las barritas de una barra particular identificada por su id
function crearBarra(id_barra){
    for(i=0;i<=16;i++){
        let div = document.createElement("div");
        div.className = "e";
        id_barra.appendChild(div);
    }
}

//selecciono todas las barras generales par aluego manipularlas
let html = document.getElementById("html");
crearBarra(html);
let javascript = document.getElementById("javascript");
crearBarra(javascript);
let wordpress = document.getElementById("wordpress");
crearBarra(wordpress);
let photoshop = document.getElementById("photoshop");
crearBarra(photoshop);
let php = document.getElementById("php");
crearBarra(php);
let ilustrator = document.getElementById("ilustrator");
crearBarra(ilustrator);

//Ahora voy a guardar la cantidad de barritas que se van a ir pintando por cada barar
//para eso utilizo un arreglo, cada posiciòn pertenece a un elemento
//comienzan en -1 porque no tiene ninguna pintada al iniciarse
let contadores = [-1,-1,-1,-1,-1,-1];
//esta variable la voy a utilizar de bandera para saber si ya ejecuto la animación
let entro = false;

//función que aplica las animaciones de la habilidades
function efectoHabilidades(){
    var habilidades = document.getElementById("habilidades");
    var distancia_skills = window.innerHeight - habilidades.getBoundingClientRect().top;
    if(distancia_skills>=300 && entro==false){
        entro = true;
        const intervalHtml = setInterval(function(){
            pintarBarra(html, 16, 0, intervalHtml);
        },100);
        const intervalJavascript = setInterval(function(){
            pintarBarra(javascript, 11, 1, intervalJavascript);
        },100);
        const intervalWordpress = setInterval(function(){
            pintarBarra(wordpress, 11, 2, intervalWordpress);
        },100);
        const intervalPhotoshop = setInterval(function(){
            pintarBarra(photoshop, 15, 3, intervalPhotoshop);
        },100);
        const intervalPhp = setInterval(function(){
            pintarBarra(php, 16, 4, intervalPhp);
        },100);
        const intervalIlustrator = setInterval(function(){
            pintarBarra(ilustrator, 11, 5, intervalIlustrator);
        },100);
    }
}

//lleno una barra particular con la cantidad indicada
function pintarBarra(id_barra, cantidad, indice, interval){
    contadores[indice]++;
    x = contadores[indice];
    if(x < cantidad){
        let elementos = id_barra.getElementsByClassName("e");
        elementos[x].style.backgroundColor = "#940253";
    }else{
        clearInterval(interval)
    }
}

//detecto el scrolling del mouse para aplicar la animación de la barra
window.onscroll = function(){
    efectoHabilidades();
}
