<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pricing Page</title>
    <link rel="icon" href="/images/icon.png">
    <style>
        body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #485893;
    color: white;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
}

nav a img {
    vertical-align: middle;
}

main {
    padding: 20px;
}

#main-content {
    text-align: center;
    border: 3px solid black;
    color: black;
    padding: 20px;
    background-color: #f0f0f0;
}

.plan {
    border: 8px solid white;
    height: 5.5cm;
    width: 5cm;
    margin: 20px;
    padding: 10px;
    background-color: #485893;
    color: white;
    display: inline-block;
}

.verify {
    width: 18px;
}

#currency-selector {
    display: grid;
    place-items: center;
    color: black;
    margin-top: 20px;
}

#footer {
    background-color: #485893;
    padding: 10px;
    text-align: center;
}

#footer-text {
    color: white;
}

    </style>
</head>

<body>
    <header>
        <nav>
            <a href="/index.html">Home</a>
        </nav>
    </header>

    <main>
        <section id="main-content">
            <h1 class="hp">PLANS AND PRICING</h1>
            <h2 class="hp">SELECT THE PLAN</h2>
            <p class="hp">Choose the currency and plan according to your convenience.</p>

            <div class="plan" id="basic-plan">
                <h2>Basic Plan</h2>
                <p>
                    10GB Disk space <br>
                    10GB Bandwidth <br>
                    10 Email accounts
                </p>
            </div>

            <div class="plan" id="pro-plan">
                <h2>Pro-Plan</h2>
                <p>
                    20GB Disk space <br>
                    20GB Bandwidth <br>
                    20 Email accounts
                </p>
            </div>

            <div class="plan" id="proplus-plan">
                <h2>Pro-Plus Plan</h2>
                <p>
                    50GB Disk space <br>
                    50GB Bandwidth <br>
                    50 Email accounts
                </p>
            </div>

            <div id="currency-selector">
                <h3>Select The Currency In Which you want to pay</h3>
                <select name="currency" id="currency">
                    <option value="null">Select currency</option>
                    <option value="INR">INR</option>
                    <option value="USD">USD</option>
                    <option value="EURO">EUR</option>
                    <option value="AUD">AUD</option>
                    <option value="CAD">CAD</option>
                    <option value="YEN">YEN</option>
                </select>
            </div>
        </section>
    </main>

    <footer id="footer">
        <p id="footer-text">Contact us at mail-: <b><i>rohanadhav78@gmail.com</i></b></p>
    </footer>
</body>

</html>
