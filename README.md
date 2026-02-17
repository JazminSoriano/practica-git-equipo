<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard Escolar</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>

    <header>
        <h1 id="titulo-principal">Sistema de gestión escolar</h1>


        <form action="#" method="get">
            <label for="filtro-fecha">Fecha:</label>
            <input type="date" id="filtro-fecha" name="fecha">
            <input type="search" placeholder="Buscar" name="busqueda">
            <button type="submit">Enviar</button>
        </form>
    </header>

    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Reportes</a></li>
            <li><a href="#">Configuración</a></li>
            <li><a href="#">Salir</a></li>
        </ul>
    </nav>

    <main>
        
        <section class="tarjeta-info borde-verde">
            <h2>Alumnos inscritos</h2>
            <p>Total de alumnos activos: <strong>1,350</strong></p>
        </section>


        <section class="tarjeta-info borde-amarillo">
            <h2>Grupos activos</h2>
            <p>Grupos abiertos este semestre: <strong>35</strong></p>
        </section>


        <section class="tarjeta-info borde-verde">
            <h2>Docentes asignados</h2>
            <p>Profesores con carga horaria: <strong>65</strong></p>
        </section>
    </main>


    <footer>
        <p>&copy; 2026. Jazmin Alejandra Soriano Garcia. Grupo: 972</p>
    </footer>


</body>
</html>
