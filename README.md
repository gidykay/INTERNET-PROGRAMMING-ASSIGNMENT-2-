//html code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OnePlus 12</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="specs.html">Specifications</a></li>
                <li><a href="pricing.html">Pricing</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="buynow.html">Buy Now</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h1>Introducing the OnePlus 12</h1>
        <p>The ultimate smartphone experience.</p>
        <a href="buynow.html">Buy Now</a>
    </section>

    <footer>
        <p>&copy; 2024 OnePlus 12</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OnePlus 12 - Specifications</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="specs.html">Specifications</a></li>
                <li><a href="pricing.html">Pricing</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="buynow.html">Buy Now</a></li>
            </ul>
        </nav>
    </header>

    <section id="specs">
        <h2>Specifications</h2>
        <ul>
            <li>6.8-inch AMOLED display</li>
            <li>Quad-camera setup</li>
            <li>5G connectivity</li>
            <li>5000mAh battery</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 OnePlus 12</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OnePlus 12 - Pricing</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="specs.html">Specifications</a></li>
                <li><a href="pricing.html">Pricing</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="buynow.html">Buy Now</a></li>
            </ul>
        </nav>
    </header>

    <section id="pricing">
        <h2>Pricing</h2>
        <table>
            <tr>
                <th>Model</th>
                <th>Price</th>
            </tr>
            <tr>
                <td>OnePlus 12 Standard</td>
                <td>$799</td>
            </tr>
            <tr>
                <td>OnePlus 12 Pro</td>
                <td>$999</td>
            </tr>
            <tr>
                <td>OnePlus 12 Ultimate</td>
                <td>$1199</td>
            </tr>
        </table>
    </section>

    <footer>
        <p>&copy; 2024 OnePlus 12</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OnePlus 12 - Contact</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="specs.html">Specifications</a></li>
                <li><a href="pricing.html">Pricing</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="buynow.html">Buy Now</a></li>
            </ul>
        </nav>
    </header>

    <section id="contact">
        <h2>Contact</h2>
        <p>For inquiries, please contact us at info@oneplus12.com</p>
    </section>

    <footer>
        <p>&copy; 2024 OnePlus 12</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OnePlus 12 - Buy Now</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="specs.html">Specifications</a></li>
                <li><a href="pricing.html">Pricing</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="buynow.html">Buy Now</a></li>
            </ul>
        </nav>
    </header>

    <section id="buynow">
        <h2>Buy Now</h2>
        <p>Click the button below to purchase the OnePlus 12.</p>
        <button id="buyButton">Buy Now</button>
    </section>

    <footer>
        <p>&copy; 2024 OnePlus 12</p>
    </footer>

    <script>
        document.getElementById('buyButton').addEventListener('click', function() {
            alert('You clicked the Buy Now button!');
        });
    </script>
</body>
</html>


//css code

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

section {
    padding: 50px;
}

#hero {
    background-color: #f2f2f2;
}

#hero h1 {
    font-size: 36px;
    color: #333;
}

#hero a {
    background-color: #007bff;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
}

#hero a:hover {
    background-color: #0056b3;
}

#features ul {
    list-style-type: square;
}

#pricing table {
    width: 100%;
    border-collapse: collapse;
}

#pricing th, #pricing td {
    border: 1px solid #333;
    padding: 10px;
    text-align: left;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}


//java code

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

section {
    padding: 50px;
}

#hero {
    background-color: #f2f2f2;
}

#hero h1 {
    font-size: 36px;
    color: #333;
}

#hero a {
    background-color: #007bff;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
}

#hero a:hover {
    background-color: #0056b3;
}

#features ul {
    list-style-type: square;
}

#pricing table {
    width: 100%;
    border-collapse: collapse;
}

#pricing th, #pricing td {
    border: 1px solid #333;
    padding: 10px;
    text-align: left;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
