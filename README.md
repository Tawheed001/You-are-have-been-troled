<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>You are have been Troled🤣</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
    <style>
        body {
            background: linear-gradient(45deg, #ff0000, #00ff00, #0000ff);
            animation: bgAnimation 5s infinite alternate;
        }
        @keyframes bgAnimation {
            0% { filter: hue-rotate(0deg); }
            100% { filter: hue-rotate(360deg); }
        }
        .fake-button {
            background: red;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <nav class="container-fluid">
        <ul>
            <li><strong>You are have been Troled🤣</strong></li>
        </ul>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Confusion</a></li>
            <li><a href="#" role="button">Click Me (Fake)</a></li>
        </ul>
    </nav>
    <main class="container">
        <div class="grid">
            <section>
                <hgroup>
                    <h2>Welcome to Your Ultimate Confusion</h2>
                    <h3>Prepare to be bamboozled!</h3>
                </hgroup>
                <p>Did you really think this was a real website? Haha, gotcha!</p>
                <figure>
                    <img src="" alt="Trolling Image" />
                    <figcaption><a href="#" target="_blank">Click Here for Nothing</a></figcaption>
                </figure>
                <h3>Fun Facts:</h3>
                <p>- You just wasted precious seconds of your life.</p>
                <p>- This button below does absolutely NOTHING!</p>
                <button class="fake-button" onclick="alert('Just kidding, this does nothing!')">Click Me</button>
            </section>
        </div>
    </main>
    <section aria-label="Subscribe example">
        <div class="container">
            <article>
                <hgroup>
                    <h2>Subscribe to Nowhere</h2>
                    <h3>Get updates on nothing important!</h3>
                </hgroup>
                <form class="grid">
                    <input type="text" id="firstname" name="firstname" placeholder="First Name" aria-label="First Name" required />
                    <input type="email" id="email" name="email" placeholder="Email" aria-label="Email" required />
                    <button type="submit" onclick="event.preventDefault()">Submit (But Nothing Happens)</button>
                </form>
            </article>
        </div>
    </section>
    <footer class="container">
        <small><a href="#">Privacy Policy</a> • <a href="#">Terms of Confusion</a></small>
    </footer>
</body>
</html>
