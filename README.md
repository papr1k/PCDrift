<!DOCTYPE html>
<html lang="lv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Datoru Veikals</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0e78be;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            background-color: #333;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        nav ul li {
            float: left;
        }
        nav ul li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav ul li a:hover {
            background-color: #111;
        }
        .container {
            padding: 20px;
        }
        .product {
            border: 1px solid #ddd;
            margin: 10px;
            padding: 10px;
            border-radius: 5px;
            display: inline-block;
            width: 30%;
            box-sizing: border-box;
        }
        .product img {
            width: 60%;
            height: auto;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 60%;
        }
    </style>
</head>
<body>
    <header>
        <h1>PCDrift Veikals</h1>
        <p>Labākie datori par izdevīgām cenām</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Sākums</a></li>
            <li><a href="#products">Produkti</a></li>
            <li><a href="#about">Par Mums</a></li>
            <li><a href="#contact">Kontakti</a></li>
        </ul>
    </nav>

    <div class="container">
        <section id="home">
            <h2>Sākums</h2>
            <p>Laipni lūdzam mūsu datoru veikalā! Zemāk jūs redzat 3 piedāvājumus ar dažādām cenām,</p>
                 <p>svarīgi zināt ka tie ir tikai paraugi kurus tāpat var pasūtīt,</p>
                 <p>bet ir arī opcija sarumāt personalizētu datoru, pēc jūsu vajadzībām un maksā tas tikpat cik piedāvājumi zemāk.</p>
        </section>

        <section id="products">
            <h2>Jau gatavi varianti</h2>
            <div class="product">
                <img src="![DATORS](https://github.com/user-attachments/assets/0bcb52a0-ac43-466b-81cc-c58ca5101485)" alt="Mājas dators">
                <h3>Mājas</h3>
                <p>Šāds dators noderēs mācībām, darbam un būs spējīgs palaist dauz spēles, bet zemā kvalitātē.</p>
                <p><strong>Cena ap: 400€</strong></p>
            </div>
            <div class="product">
                <img src="![DATORS]![DARORS2](https://github.com/user-attachments/assets/e6d64e60-d6b8-46b0-8213-523bf289b8de)" alt="Spēļu dators">
                <h3>Spēļu</h3>
                <p>Šis dators noderēs vienkāršai lietošanai, kā pamācīties, paskatīties filmas,  paspēlēt labā kvalitātē.</p>
                <p><strong>Cena ap: 900€</strong></p>
            </div>
            <div class="product">
                <img src="![DATORS3](https://github.com/user-attachments/assets/9138ac07-a3a0-43ba-be10-ceb8c9437f6d)" alt="Vip">  
                <h3>Vip</h3>
                <p>Šis dators noderēs gandrīz visām spēlēm labākejā kvalitātē un darbam kas prasa jaudīgu datoru.</p>
                <p><strong>Cena ap: 1400€</strong></p>
            </div>
        </section>

        <section id="about">
            <h2>Par Mums</h2>
            <p>Mēs esam maza komanda no pāris cilvēkiem, kura vēlas dot Latvijaj,</p>
                <p> jaudīgus, kvalitatīvus datorus par zemām cenām.</p>
        </section>

        <section id="contact">
            <h2>Kontakti:</h2>
            <p>Jautājumu gadījumā lūdzu sazinieties ar mums:</p>
            <p>Telefons: +371 22090771</p>
            <p>E-pasts: info@datoruveikals.lv</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 PCDrift Veikals. Visas tiesības aizsargātas.</p>
    </footer>
</body>
</html>
