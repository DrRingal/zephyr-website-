<!DOCTYPE html>
<html>
    <head>
        <!--The "background" class will be dependent on the background image chosen.-->
    <style>
        .header{
    size:absolute;
    height:13%;
    width:100%;
    position:absolute;
    top:0%;
    left:0%;
    background-color:rgb(122 122 122);
}
.background{
    background-image:url(data:image/jpeg;base64,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);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: 30% 45%; 
    background-size:auto 100vh;
    background-color:black;
}
.logo{
    size: absolute;
    height:100%;
    position:absolute;
    top:1.5%;
    left:2.5%;
}
.Planetname{
    font-family:'Trebuchet MS', sans-serif;
    font-size:25pt;
    color:white;
    position:fixed;
    top:25%;
    left:7%;
}
.Planetinfo{
    font-family:'Nunito';
    font-size:14pt;
    color:white;
    position:fixed;
    top:40%;
    left:7%;
    size:absolute;
    width:40%;
    overflow:auto;
}
.button {
        background-color: black;
        border: 1px solid white;
        border-radius:6px;
        color: white;
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        position:absolute;
        transition-duration: 0.5s;
        cursor:pointer;
    }
    .button:hover{
        background-color:white;
        color:black;
        border:1px solid white;
        border-radius:6px;
    }
    </style>
        <meta name="viewport" content="width=device-width,initial-scale=1">
        <link href="Zephyr Info Page Stylesheet.css" rel="stylesheet">
    </head>
    <body class="background">
        <div class="header">
            <img src="https://i.imgur.com/M26SxH2.png" class="logo">
        </div>
        <div>
            <h1 class="Planetname"><b>Uranus</b></h1>
        </div>
        <div class="Planetinfo">
            <p>
                7th Planet from the solar system. Uranus has clouds of Methane Ice rather than clouds of ammonia like Jupiter and Saturn. It has an unremarkable atmosphere, having little features, and it lies on it’s side rotating rather than at a normal angle. This results in the poles getting more sun than the equator, and an extended period of darkness on one pole at certain times of a Uranian year. Humans have only had a single mission fly past Uranus, Voyager 2, and it may be a very long time until another mission is sent out as the planets need to align as they did in the 70s for that to happen again. <br> A fun fact about Uranus is that 84 years on Earth is equivalent to one Uranian year.
            </p>
        </div>
        <a href="https://wikipedia.org" class="button" style="right:15%; bottom:7%">Back to Home</a>
    </body>
</html>
