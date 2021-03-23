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
            background-image:url(https://upload.wikimedia.org/wikipedia/commons/d/d9/Mercury_in_color_-_Prockter07-edit1.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: 85% 45%; 
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
            <a href="https://en.wikipedia.org/wiki/Venus" class="PlanetAfter" style="right:2%; top:14%">Venus</a>
        </div>
        <div>
            <h1 class="Planetname"><b>Mercury</b></h1>
        </div>
        <div>
            <p class="Planetinfo">
                The only planet in the solar system not to be surrounded by an atmosphere really. A reason for this is it has a small mass, hence weak gravity, which allows gases to escape its atmosphere to space. Mercury is also the closest planet to the sun in our solar system, it is small and circular, and the sun’s solar wind pushes any gases that attempt to form an atmosphere around Mercury away. <br> A fun fact about Mercury is that it can heat up to 800 degrees fahrenheit during the day, much hotter than the temperatures needed to cook you, and cool down to -300 degrees fahrenheit during the night, these extremes are due to having no atmosphere to trap gases and regulate the temperature and weather on the planet.
            </p>
        </div>
        <a href="https://wikipedia.org" class="BacktoHome" style="right:15%; bottom:7%">Back to Home</a>
        </div>
    </body>
</html>
