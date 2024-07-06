# Parallax-website-HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parallax Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <section class="parallax" id="section1">
        <div class="content">
            <h1>Welcome to the Parallax Website</h1>
            <p>Scroll down to see the effect</p>
        </div>
    </section>

    <section class="content-section">
        <h2>Content Section 1</h2>
        <p>This is a normal content section.</p>
    </section>

    <section class="parallax" id="section2">
        <div class="content">
            <h2>Parallax Section 2</h2>
        </div>
    </section>

    <section class="content-section">
        <h2>Content Section 2</h2>
        <p>This is another normal content section.</p>
    </section>

    <section class="parallax" id="section3">
        <div class="content">
            <h2>Parallax Section 3</h2>
        </div>
    </section>

    <section class="content-section">
        <h2>Content Section 3</h2>
        <p>More content here.</p>
    </section>

</body>
</html>
body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    font-family: Arial, sans-serif;
}

.parallax {
    height: 100vh;
    background-attachment: fixed;
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    text-align: center;
}

#section1 {
    background-image: url('https://via.placeholder.com/1920x1080');
}

#section2 {
    background-image: url('https://via.placeholder.com/1920x1080');
}

#section3 {
    background-image: url('https://via.placeholder.com/1920x1080');
}

.content-section {
    padding: 50px;
    background: #f4f4f4;
    text-align: center;
}

.content {
    background: rgba(0, 0, 0, 0.5);
    padding: 20px;
}
