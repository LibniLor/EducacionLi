# EducacionLi
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>EmprendeEdu - Plataforma Educativa</title>
</head>
<body>
    <header>
        <h1>EmprendeEdu</h1>
        <p>Tu camino hacia el conocimiento</p>
    </header>

    <nav>
        <ul>
            <li><a href="#cursos">Cursos</a></li>
            <li><a href="#recursos">Recursos</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <section id="cursos">
        <h2>Cursos Destacados</h2>
        <div class="curso">
            <img src="curso1.jpg" alt="Curso 1">
            <h3>Introducción a la Programación</h3>
            <p>Descubre el fascinante mundo de la programación desde cero.</p>
        </div>

        <div class="curso">
            <img src="curso2.jpg" alt="Curso 2">
            <h3>Diseño Web Moderno</h3>
            <p>Aprende a crear sitios web atractivos y responsivos.</p>
        </div>
    </section>

    <section id="recursos">
        <h2>Recursos Educativos</h2>
        <ul>
            <li><a href="#">Libros Recomendados</a></li>
            <li><a href="#">Herramientas Útiles</a></li>
            <li><a href="#">Conferencias Online</a></li>
        </ul>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>¿Tienes alguna pregunta o sugerencia? ¡Contáctanos!</p>
        <form action="contacto.php" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            <button type="submit">Enviar Mensaje</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 EmprendeEdu - Plataforma Educativa</p>
    </footer>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #3498db;
    color: white;
    text-align: center;
    padding: 20px;
}

nav {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 10px;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

section {
    padding: 40px;
}

#contacto form {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 20px;
}

footer {
    background-color: #34495e;
    color: white;
    text-align: center;
    padding: 10px;
    position: absolute;
    bottom: 0;
    width: 100%;
}
