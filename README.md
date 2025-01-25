# css
web105 2024
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 1rem;
}

.nav-bar {
    display: flex;
    justify-content: center;
    list-style: none;
    background-color: #333;
    margin: 0;
    padding: 0;
}

.nav-bar li {
    margin: 0 1rem;
}

.nav-bar a {
    color: white;
    text-decoration: none;
    padding: 0.5rem 1rem;
    display: block;
}

.nav-bar a:hover {
    background-color: #575757;
    border-radius: 5px;
}

.book-collection {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1rem;
    padding: 2rem;
}

.book-card {
    background-color: #f9f9f9;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    padding: 1rem;
    text-align: center;
}

.book-card img {
    max-width: 100%;
    border-radius: 10px;
}

button.add-to-cart {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s;
}

button.add-to-cart:hover {
    background-color: #45a049;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
}

footer .social-links {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

footer .social-links li {
    margin: 0 1rem;
}

footer .social-links a {
    color: white;
    text-decoration: none;
}

