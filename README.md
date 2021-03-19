<!DOCTYPE html>
<html">
    <head>
        <!--The "background" class will be dependent on the background image chosen.-->
    	<meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1">
    <style>
        .everything{
    height:90vh;
    overflow:auto;
}
.header{
    size:absolute;
    height:13vh;
    width:100%;
    border-bottom:3px solid rgb(0 0 128);
    position:fixed;
    top:0%;
    left:0%;
    background-color:rgb(122 122 122);
    z-index: 1;
}
.background{
    background-image:url(https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/Uranus2.jpg/1200px-Uranus2.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: 80% 45%; 
    background-size:auto 100vh;
    background-color:black;
}
.logo{
    size: absolute;
    height:100%;
    position:absolute;
}
.Planetname{
    font-family:'Trebuchet MS', sans-serif;
    font-size:25pt;
    color:white;
    position:absolute;
    top:25%;
    left:7%;
}
.Planetinfo{
    font-family:'Nunito';
    font-size:14pt;
    color:white;
    position:absolute;
    top:40%;
    left:7%;
    size:absolute;
    width:40%;
}
.BacktoHome {
        background-color: black;
        border: 1px solid white;
        border-radius:6px;
        color: white;
        padding: 10px 16px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        position:fixed;
        transition-duration: 0.5s;
        cursor:pointer;
    }
    .BacktoHome:hover{
        background-color:white;
        color:black;
        border:1px solid white;
        border-radius:6px;
    }
.PlanetBefore{
    background-color:black;
    border:1px solid rgb(55 0 0);
    border-radius:6px;
    color:white;
    width:90px;
    padding-top:6px;
    padding-bottom:6px;
    margin:3px;
    text-align:center;
    text-decoration:none;
    display:inline-block;
    font-size:16px;
    position:fixed;
    transition-duration:.5s;
    cursor:pointer;
}
    .PlanetBefore:hover{
        background-color:white;
        color:black;
        border-radius:6px;
    }
.PlanetAfter{
    background-color:black;
    border:1px solid rgb(55 0 0);
    border-radius:6px;
    color:white;
    width:90px;
    padding-top:6px;
    padding-bottom:6px;
    margin:3px;
    text-align:center;
    text-decoration:none;
    display:inline-block;
    font-size:16px;
    position:fixed;
    transition-duration:.5s;
    cursor:pointer;
}
    .PlanetAfter:hover{
        background-color:white;
        color:black;
        border-radius:6px;
    }
    </style>
    </head>
    <body class="background">
        <div class="everything">
        <div class="header">
            <img src="https://i.imgur.com/M26SxH2.png" class="logo" style="top:1.5%;left:2.5%">
            <a href="https://en.wikipedia.org/wiki/Saturn" class="PlanetBefore" style="left:2%; top:14%">Saturn</a>
            <a href="https://en.wikipedia.org/wiki/Neptune" class="PlanetAfter" style="right:2%; top:14%">Neptune</a>
        </div>
        <div>
            <h1 class="Planetname"><b>Uranus</b></h1>
        </div>
        <div>
            <p class="Planetinfo">
                7th Planet from the solar system. Uranus has clouds of Methane Ice rather than clouds of ammonia like Jupiter and Saturn. It has an unremarkable atmosphere, having little features, and it lies on it’s side rotating rather than at a normal angle. This results in the poles getting more sun than the equator, and an extended period of darkness on one pole at certain times of a Uranian year. Humans have only had a single mission fly past Uranus, Voyager 2, and it may be a very long time until another mission is sent out as the planets need to align as they did in the 70s for that to happen again. <br> A fun fact about Uranus is that 84 years on Earth is equivalent to one Uranian year.
            </p>
        </div>
        <a href="https://wikipedia.org" class="BacktoHome" style="right:15%; bottom:7%">Back to Home</a>
        </div>
    </body>
</html>
