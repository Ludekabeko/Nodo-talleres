# Nodo-talleres- WOrkshop 1
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Personal - Lued Beltrán</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- ¡Tu sello personal! -->
    <header>
        <h1>Lued Beltrán</h1>
        <img src="[file:///C:/Users/lued/Desktop/ejemplos/mipagina.html](https://drive.google.com/file/d/1dqVaRsDaPPu4QWDAwdkORQrrGeVPncIS/view?usp=drive_link)" alt="Foto de Lued Beltrán">
        <h2>Quién Soy</h2>
        <p>Soy esposa, madre, hija, hermana, me apasiona la tecnología y trabajo desde casa como emprendedora y aventurera. Amo viajar, conectar con otras personas. Estoy certificada en HR Learnability, Agile Coach, Chief Learning Officer, Formación, Cultura y Liderazgo organizacional, Maestra y aprendiz permanente.</p>
        <h2>¿Qué te mueve en Nodo?</h2>
        <h3>Motivación</h3>
        <p>Qué te impulsa a formar parte de la comunidad Nodo y del desarrollo.</p>
        <h3>Razones</h3>
        <p>Las razones que te llevaron a elegir Nodo.</p>
    </header>
    
    <!-- ¡Aprende sin límites! -->
    <section class="learn">
        <h2>¡Aprende sin límites!</h2>
        <div class="cards-carousel">
            <!-- Cards -->
            <div class="card">
                <h3>Metas</h3>
                <p>Habilidades y conocimientos que deseas adquirir en Nodo.</p>
            </div>
            <div class="card">
                <h3>Lista de deseos</h3>
                <ul>
                    <li>Curso 1</li>
                    <li>Curso 2</li>
                    <li>Taller 1</li>
                    <li>Evento 1</li>
                </ul>
            </div>
        </div>
    </section>
    
    <!-- ¡Tus Hobbies! -->
    <section class="hobbies">
        <h2>¡Tus Hobbies!</h2>
        <div class="hobbies-grid">
            <div class="hobby">
                <img src="hobby1.jpg" alt="Hobby 1">
                <p>Eslogan del hobby 1</p>
            </div>
            <div class="hobby">
                <img src="hobby2.jpg" alt="Hobby 2">
                <p>Eslogan del hobby 2</p>
            </div>
        </div>
    </section>
    
    <!-- ¡Conéctate conmigo! -->
    <footer>
        <h2>¡Conéctate conmigo!</h2>
        <a href="https://github.com/tu-usuario">Mi GitHub</a>
    </footer>
</body>
</html>
CSS
css
Copiar código
/* Reset CSS */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilos generales */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
    margin: 20px;
}

/* Estilos de la cabecera */
header {
    text-align: center;
    margin-bottom: 40px;
}

header img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
}

/* Estilos de la sección Aprender */
.learn {
    margin-bottom: 40px;
}

.cards-carousel {
    display: flex;
    overflow-x: auto;
}

.card {
    background: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    margin: 0 10px;
    flex: 0 0 auto;
    width: 200px;
    border-radius: 10px;
}

.card h3 {
    margin-bottom: 10px;
}

.card ul {
    list-style-type: disc;
    margin-left: 20px;
}

/* Estilos de la sección Hobbies */
.hobbies {
    margin-bottom: 40px;
}

.hobbies-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
}

.hobby {
    text-align: center;
}

.hobby img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

.hobby p {
    margin-top: 10px;
}

/* Estilos del pie de página */
footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: #fff;
}

footer a {
    color: #ff0;
    text-decoration: none;
}
