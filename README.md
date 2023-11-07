git clone https://github.com/acho512garcia/acho512garcia.github.io.git
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Personal Website</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header>
        <h1>Your Name</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#gallery">Gallery</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>I am a Business Analytics major at UT Austin's McCombs School of Business. I work as a basketball official for the Texas High School Basketball Officials Association with the Austin Chapter. Additionally, I have been a Texas Realtor in the Central Texas area for 3 years now.</p>
    </section>

    <section id="experience">
        <h2>Experience</h2>
        <p>I have experience in various coding languages and software, including Python, SQL, pandas, Microsoft Excel, and R. I am also the founding father and president of the Alpha Sigma Phi Fraternity, Eta Eta chapter at UT Austin. In the summer of 2023, I coached a high school basketball team and interned with Texas Pro Academy as an assistant of player development for professional, overseas, college, and elite high school basketball players.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>SQL</li>
            <li>pandas</li>
            <li>Microsoft Excel</li>
            <li>R</li>
        </ul>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="image-gallery">
            <img src="image1.jpg" alt="Image 1">
            <img src="image2.jpg" alt="Image 2">
            <img src="image3.jpg" alt="Image 3">
            <img src="image4.jpg" alt="Image 4">
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Your Name. All rights reserved.</p>
    </footer>
</body>

</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

.image-gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.image-gallery img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    margin: 10px;
}

