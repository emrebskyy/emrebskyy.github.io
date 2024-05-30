# emrebskyy.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sahibinden.com Klonu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Sahibinden.com Klonu</h1>
            <nav>
                <ul>
                    <li><a href="#">Ana Sayfa</a></li>
                    <li><a href="#">Satılık</a></li>
                    <li><a href="#">Kiralık</a></li>
                    <li><a href="#">Hakkımızda</a></li>
                    <li><a href="#">İletişim</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main>
        <section class="search">
            <div class="container">
                <h2>Aradığınızı Bulun</h2>
                <form>
                    <input type="text" placeholder="Ne aramıştınız?">
                    <button type="submit">Ara</button>
                </form>
            </div>
        </section>
    </main>
    <footer>
        <div class="container">
            <p>&copy; 2024 Sahibinden.com Klonu</p>
        </div>
    </footer>
</body>
</html>

/* Reset CSS */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Genel Stil */
body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header Stili */
header {
    background-color: #333;
    padding: 10px 0;
}

header h1 {
    font-size: 1.5rem;
    color: #fff;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Ana İçerik (Main) Stili */
main {
    padding: 20px 0;
}

.search {
    background-color: #fff;
    border-bottom: 1px solid #ddd;
    padding: 20px 0;
}

.search h2 {
    font-size: 1.2rem;
    margin-bottom: 10px;
}

input[type="text"] {
    width: 70%;
    padding: 10px;
    font-size: 1rem;
}

button {
    padding: 10px 20px;
    font-size: 1rem;
    background-color: #007bff;
    color: white;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

/* Footer Stili */
footer {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

