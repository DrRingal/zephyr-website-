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
    background-image:url(https://media.wired.com/photos/5d04045bde1abfe4e801d054/2:1/w_2343,h_1171,c_limit/Science-Neptune-FA-PIA01492_orig.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: 80% 45%; 
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
    border:1px solid rgb(0 0 0);
    border-radius:6px;
    color:black;
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
    opacity:0.5;
}
    .PlanetAfter:hover{
        background-color:white;
        color:black;
        border-radius:6px;
    }
    </style>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
        <script>
            $(document).ready(function() {
                $(".PlanetAfter").click(function() {
                    window.alert("Pluto isn't a planet, silly! Why else would you think we'd hide the button?");
                });
            });
        </script>
    </head>
    <body class="background">
        <div class="everything">
        <div class="header">
            <img src="https://i.imgur.com/M26SxH2.png" class="logo" style="top:1.5%;left:2.5%">
            <a href="https://en.wikipedia.org/wiki/Saturn" class="PlanetBefore" style="left:2%; top:14%">Uranus</a>
            <a class="PlanetAfter" style="right:2%; top:14%">Pluto</a>
        </div>
        <div>
            <h1 class="Planetname"><b>Neptune</b></h1>
        </div>
        <div>
            <p class="Planetinfo">
                Last Planet from the Sun, since 2006 when Pluto was classified as a dwarf planet. When Voyager 2 was on its mission and flew past Neptune, it saw a storm similar to the one on Jupiter, and we call it the “great dark spot” because it is an anticyclonic storm like the red one on Jupiter. Unlike Jupiter’s, however, the great dark spot was not there 5 years later when the Hubble Space Telescope looked at it again. Even though it is the furthest from the solar system and has hardly any solar energy, its winds are the fastest in the solar system and reach speeds of up to 2,200 km/h. Neptune has an interior heat source like the gas giants do, and it’s role in the weather planets is up to speculation as researchers try to figure out how the heat inside of these planets’ cores impacts their weather patterns. <br>A fun fact about Neptune is that it may look different each time a telescope looks at it because it's wind moves so fast around the planet.
            </p>
        </div>
        <a href="https://wikipedia.org" class="BacktoHome" style="right:15%; bottom:7%">Back to Home</a>
        </div>
    </body>
</html>
