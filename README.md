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
    background-image:url(https://www.esa.int/var/esa/storage/images/esa_multimedia/images/2020/09/hubble_captures_crisp_new_image_of_jupiter_and_europa/22212206-1-eng-GB/Hubble_Captures_Crisp_New_Image_of_Jupiter_and_Europa_pillars.jpg);
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
            <a href="https://en.wikipedia.org/wiki/Mars" class="PlanetBefore" style="left:2%; top:14%">Mars</a>
            <a href="https://en.wikipedia.org/wiki/Saturn" class="PlanetAfter" style="right:2%; top:14%">Saturn</a>
        </div>
        <div>
            <h1 class="Planetname"><b>Jupiter</b></h1>
        </div>
        <div>
            <p class="Planetinfo">
                5th planet from the sun, despite its great size, it spins very fast, and its days are less than 10 hours long. It has a very volatile atmosphere and weather system, and actually if made completely of gas, meaning it is not solid and there is no surface to stand on. Wind speeds on the planet can reach 600 km/h. It’s storms are famous and are/have been observed by astronomers for many years. One of these famous storms is the “great red spot”, which has been observed since supposedly the 17th century, and is called the “endless storm” by the astronomers of that time. <br>A fun fact about Jupiter is that it’s red spot is larger than Earth.
            </p>
        </div>
        <a href="https://wikipedia.org" class="BacktoHome" style="right:15%; bottom:7%">Back to Home</a>
        </div>
    </body>
</html>
