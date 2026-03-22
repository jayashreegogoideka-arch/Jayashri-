
<!DOCTYPE html>
<html>
<head>
    <title>APC Restaurant</title>

    <style>
        body {
            margin: 0;
            font-family: Arial;
            background: linear-gradient(to right, #fff5f5, #ffe6e6);
        }

        header {
            background: #b30000;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            background: white;
            margin: 15px;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
        }

        img {
            border-radius: 10px;
            margin: 5px;
        }

        footer {
            background: #b30000;
            color: white;
            text-align: center;
            padding: 10px;
        }

        button {
            padding: 8px;
            margin: 3px;
            background: #b30000;
            color: white;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>

<body>

<!-- LANGUAGE BUTTONS -->
<div style="text-align:center; margin:10px;">
    <button onclick="setLang('en')">English</button>
    <button onclick="setLang('as')">অসমীয়া</button>
    <button onclick="setLang('bn')">বাংলা</button>
    <button onclick="setLang('hi')">हिंदी</button>
</div>

<!-- HEADER -->
<header>
    <img src="logo.png" width="200">
    <h1 id="title">APC Restaurant</h1>
    <p id="tagline">Authentic Assamese Taste</p>
    <p id="owner"><strong>Owner: MADHAB DEKA</strong></p>
</header>

<!-- MENU -->
<section>
    <h2 id="menu">Menu</h2>

    <img src="fish.jpg" width="200"><br>
    <p id="fish">Fish Fry - ₹200</p>

    <img src="mutton.jpg" width="200"><br>
    <p id="mutton">Mutton with Rice - ₹250</p>

    <img src="chai.jpg" width="200"><br>
    <p id="chai">Special Chai - ₹10-20</p>

    <p id="curry">Mutton Curry - ₹200</p>
</section>

<!-- ACHAR -->
<section>
    <h2 id="achar">Pickles</h2>
    <p id="acharText">Homemade Pickles Available - ₹50</p>
</section>

<!-- ADDRESS -->
<section>
    <h2 id="address">Address</h2>
    <p id="addr">Assam, Bishwanath, Borgaon</p>

    <a href="https://www.google.com/maps/search/?api=1&query=Assam+Bishwanath+Borgaon" target="_blank">
        <button id="dir">Get Directions</button>
    </a>
</section>

<!-- CONTACT -->
<section>
    <h2 id="contact">Contact</h2>
    <p>📞 9678058369</p>
</section>

<footer>
    <p>© 2025 APC Restaurant</p>
</footer>

<!-- LANGUAGE SCRIPT -->
<script>
function setLang(lang) {

    if(lang === 'en') {
        title.innerText = "APC Restaurant";
        tagline.innerText = "Authentic Assamese Taste";
        menu.innerText = "Menu";
        fish.innerText = "Fish Fry - ₹200";
        mutton.innerText = "Mutton with Rice - ₹250";
        chai.innerText = "Special Chai - ₹10-20";
        curry.innerText = "Mutton Curry - ₹200";
        achar.innerText = "Pickles";
        acharText.innerText = "Homemade Pickles Available - ₹50";
        address.innerText = "Address";
        addr.innerText = "Assam, Bishwanath, Borgaon";
        dir.innerText = "Get Directions";
        contact.innerText = "Contact";
    }

    if(lang === 'as') {
        title.innerText = "APC ৰেষ্টুৰেণ্ট";
        tagline.innerText = "আসল অসমীয়া সোৱাদ";
        menu.innerText = "মেনু";
        fish.innerText = "মাছ ফ্ৰাই - ₹200";
        mutton.innerText = "মাটন ভাত - ₹250";
        chai.innerText = "চাহ - ₹10-20";
        curry.innerText = "মাটন কাৰি - ₹200";
        achar.innerText = "আচাৰ";
        acharText.innerText = "ঘৰুৱা আচাৰ উপলব্ধ - ₹50";
        address.innerText = "ঠিকনা";
        addr.innerText = "অসম, বিশ্বনাথ, বৰগাঁও";
        dir.innerText = "দিশ চাওক";
        contact.innerText = "যোগাযোগ";
    }

    if(lang === 'bn') {
        title.innerText = "APC রেস্টুরেন্ট";
        tagline.innerText = "আসল অসমীয়া স্বাদ";
        menu.innerText = "মেনু";
        fish.innerText = "মাছ ফ্রাই - ₹200";
        mutton.innerText = "মাটন ভাত - ₹250";
        chai.innerText = "চা - ₹10-20";
        curry.innerText = "মাটন কারি - ₹200";
        achar.innerText = "আচার";
        acharText.innerText = "ঘরের আচার পাওয়া যায় - ₹50";
        address.innerText = "ঠিকানা";
        addr.innerText = "অসম, বিশ্বনাথ, বরগাঁও";
        dir.innerText = "দিকনির্দেশ";
        contact.innerText = "যোগাযোগ";
    }

    if(lang === 'hi') {
        title.innerText = "APC रेस्टोरेंट";
        tagline.innerText = "असली असमिया स्वाद";
        menu.innerText = "मेनू";
        fish.innerText = "फिश फ्राई - ₹200";
        mutton.innerText = "मटन चावल - ₹250";
        chai.innerText = "चाय - ₹10-20";
        curry.innerText = "मटन करी - ₹200";
        achar.innerText = "अचार";
        acharText.innerText = "घर का अचार उपलब्ध - ₹50";
        address.innerText = "पता";
        addr.innerText = "असम, बिश्वनाथ, बोरगांव";
        dir.innerText = "रास्ता देखें";
        contact.innerText = "संपर्क";
    }
}
</script>

</body>
</html>
