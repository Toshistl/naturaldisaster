<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Natural Disasters</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="hero">
        <div class="overlay">
            <h1>Natural Disasters</h1>
            <p>Natural disasters cause significant harm to human life, property, and the environment.</p>
            <a href="#about" class="btn">Learn More</a>
        </div>
    </header>
    <nav class="navbar">
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#history">History</a></li>
            <li><a href="#quotes">Quotes</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="about" class="section">
            <h2>What are Natural Disasters?</h2>
            <p> <strong>Natural disasters</strong> refer to catastrophic events caused by natural forces such as earthquakes, tsunamis, hurricanes, wildfires, and floods. These events result in significant damage to human life, property, and the environment.</p>
            <ul>
                <li><strong>Earthquakes:</strong> Powerful earthquakes can cause massive destruction to buildings and loss of life.</li>
                <li><strong>Tsunamis:</strong> Large waves caused by underwater earthquakes can devastate coastal communities.</li>
                <li><strong>Hurricanes:</strong> Severe storms with strong winds and heavy rain that cause widespread damage.</li>
                <li><strong>Wildfires:</strong> Fires in forests or dry areas that can rapidly spread, destroying land and property.</li>
                <li><strong>Floods:</strong> Overflowing of water bodies due to heavy rainfall or snowmelt, causing widespread destruction.</li>
            </ul>
        </section>
        <section id="history" class="section bg-light">
            <h2>History of Natural Disasters</h2>
            <p>Natural disasters have occurred throughout history, causing significant devastation. Some notable events include:</p>
            <ul>
                <li><strong>2011:</strong> The earthquake and tsunami in Japan caused massive destruction, including the meltdown of the Fukushima nuclear power plant.</li>
                <li><strong>2004:</strong> The Indian Ocean tsunami claimed over 230,000 lives across multiple countries.</li>
                <li><strong>2005:</strong> Hurricane Katrina in the United States resulted in widespread flooding and the displacement of millions of people.</li>
                <li><strong>2017:</strong> The earthquake in Mexico caused substantial damage, including the collapse of buildings and loss of life.</li>
                <li><strong>2019:</strong> The Australian wildfires destroyed vast areas of land and endangered wildlife.</li>
            </ul>
        </section>
        <section id="quotes" class="section">
            <h2>Quotes</h2>
            <blockquote>"The best way to predict the future is to prepare for it." – Abraham Lincoln</blockquote>
            <blockquote>"In the face of disaster, humanity must come together and rebuild." – Unknown</blockquote>
            <blockquote>"Natural disasters are a reminder of our vulnerability and the importance of resilience." – Unknown</blockquote>
            <blockquote>"The effects of a natural disaster last long after the disaster itself is over." – Unknown</blockquote>
            <blockquote>"Preparedness is the key to surviving a natural disaster." – Unknown</blockquote>
        </section>
    </main>
    <footer id="contact" class="footer">
        <p>Contact: <a href="mailto:drkness925@gmail.com">drkness925@gmail.com</a></p>
        <p>© 2024 Natural Disasters. All rights reserved.</p>
    </footer>
</body>
</html>
<script> 
window.onscroll = function () {
    const navbar = document.querySelector('.navbar');
    if (window.scrollY > 50) {
        navbar.style.position = 'fixed';
        navbar.style.top = '0';
        navbar.style.width = '100%';
    } else {
        navbar.style.position = 'relative';
    }
};
</script>

