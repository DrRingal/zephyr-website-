<!DOCTYPE html>
<html>
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
    background-image:url(https://upload.wikimedia.org/wikipedia/commons/c/c7/Saturn_during_Equinox.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: 75% 45%; 
    background-size:auto 90vh;
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
            <a href="https://en.wikipedia.org/wiki/Jupiter" class="PlanetBefore" style="left:2%; top:14%">Jupiter</a>
            <a href="https://en.wikipedia.org/wiki/Uranus" class="PlanetAfter" style="right:2%; top:14%">Uranus</a>
        </div>
        <div>
            <h1 class="Planetname"><b>Saturn</b></h1>
        </div>
        <div>
            <p class="Planetinfo">
                6th Planet from the sun. This planet also has fast wind speeds like Jupiter, although the ones in Saturn’s atmosphere can reach speeds of up to 1800 km/h. There are certain “spots” on Saturn like those on Jupiter, but they are much smaller and there are much less of them as compared to Jupiter, an example of one such storm would be the “Dragon Storm” that was captured in 2004 by the Cassini Spacecraft. The North pole shows a regular hexagonal structure, and this storm observed was believed to have been going on deeper in the atmosphere of the planet, as it was observed on and off for months. <br>Fun Fact, Saturn has many moons, and Titan has a weather cycle like earth, but with methane instead of water, and much colder temperatures.
            </p>
        </div>
        <a href="https://wikipedia.org" class="BacktoHome" style="right:15%; bottom:7%">Back to Home</a>
        </div>
    </body>
</html>
