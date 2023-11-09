!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shayaan - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(0, 0, 33);
            color: white;
            font-family: sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(18, 18, 62);
            ;
        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            font-size: 1.01rem;
            color: rgb(170, 107, 228);
        }

        main hr {
            border: 0;
            background: #9c9c9c;
            height: 1px;
            margin: 60px 84px;
        }

        .left {
            font-size: 1.5rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            margin: 120px 0;
            align-items: center;

        }

        .firstSection>div {
            width: 30%;
        }

        .leftsection {
            margin: 70px 0;
            font-size: 3rem;
        }

        .rightSection img {
            width: 80%;

        }

        .purple {
            color: blueviolet;
        }

        .text-gray {
            color: gray;
        }

        #element {
            color: rgb(170, 107, 228);
        }

        .secondSection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }


        .secondSection h1 {
            font-size: 2rem;
        }

        .secondSection .box {
            background: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondSection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 100px;
        }

        .image-top {
            width: 23px;
            position: relative;
            top: -32px;
            left: -9px;
        }

        .vertical-title {
            position: relative;
            top: 75px;
            width: 150px    ;
        }

        .vertical-desc {}
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Shayaan's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section class="firstSection">
            <div class="leftsection">
                Hi, My name is <span class="purple">Shayaan</span>
                <div>and I am a passionate</div>

                <span id="element"></span>
            </div>
            <div class="rightSection">
                <img src="https://www.pngitem.com/pimgs/m/112-1127587_software-hire-developers-hd-png-download.png"
                    alt="">
            </div>
        </section>
        <hr>
        <section class="secondSection">
            <span class="text-gray">What I have done so far</span>
            <h1>Work Experience</h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="https://cdn-icons-png.flaticon.com/512/5072/5072860.png" alt="">
                    <div class="vertical-title">
                        HTML Developer
                    </div>
                    <div class="vertical-desc">
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Velit iusto in facere quaerat quis.
                        Nesciunt quo quae doloribus corporis sit repellendus quisquam id.
                    </div>
                </div>
                <div class="vertical">
                    Node.js Developer
                </div>
                <div class="vertical"></div>
                <div class="vertical"></div>
            </div>
        </section>

    </main>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'Graphics Designer', 'Web Designer', 'Video Editor'],
            typeSpeed: 50,
        });
    </script>

</body>

</html>
