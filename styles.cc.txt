/* Estilos Generales */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
}

/* Encabezado */
header {
    background: linear-gradient(to right, #ff4500, #ff6347);
    color: white;
    text-align: center;
    padding: 30px;
}

/* Navegación */
nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    background: #222;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 15px;
    display: block;
}

nav ul li a:hover {
    background: #ff4500;
}

/* Secciones */
section {
    padding: 40px;
    max-width: 800px;
    margin: auto;
}

h2 {
    color: #ff4500;
}

/* Animes */
.anime {
    background: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    text-align: center;
    margin-bottom: 20px;
}

.anime img {
    width: 100%;
    border-radius: 10px;
}

/* Pie de Página */
footer {
    text-align: center;
    background: #222;
    color: white;
    padding: 20px;
    margin-top: 20px;
}
