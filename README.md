# pokemoncoding.html
<!DOCTYPE html>
<html>

<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pixelify+Sans:wght@400;600&display=swap" rel="stylesheet">



    <meta charset="UTF-8">
    <meta http-equiv="X-UA-compatible" content="IE=edge">
    <meta name="viewport" content="wide=device-width,initial-scale=1.0">
    <link rel="stylesheet" href="style/style.css">
    </link>
    <title>Pokedex</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Pixelify+Sans:wght@400;500;600&family=Roboto:ital,wght@1,300&display=swap"
        rel="stylesheet">
    <style>
        body {
            font-family: 'Pixelify Sans', sans-serif;

        }

        ul {
            list-style-type: none;
            display: flex;

        }


        li {
            list-style-type: none;
        }

        #Pokedex {
            width: 22rem;
            height: 35rem;
            background-color: white;
            border-radius: 8px;
            border: 10px solid white;

            background-size: 460px;
        }

        .name {
            display: flex;
            margin: auto;
            color: black;
            font-family: 'Pixelify Sans', sans-serif;
            text-align: center;
            font-size: 30px;
            text-transform: uppercase;
            border: 10px solid black;
            scale: 120px;
            




        }

        .image {

            display: flex;
            margin: auto;




            height: 130px;
            scale: 90%;
        }

        .Type1 {
            justify-content: center;
            display: flex;
            text-align: center;
            margin: auto;
            
            margin-right: 70px;
            
            font-size: 25px;
            border: 5px solid black;
         
 


        }
        .Type2 {
            justify-content: center;
            display: flex;
            text-align: center;
            margin-left: 80px;
            font-size: 25px;
            margin-top: -40px;
            border: 5px solid black;
        
      
        }
      


        h1 {
            padding-inline-start: 0;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    grid-gap: 20px;
    

            font-family: 'Pixelify Sans', sans-serif;
            font-size: 60px;
            text-align: center;
            background-color: white;
            border: 20px solid rgb(240, 93, 93);
            background-color: red;
            border-radius: 100px;
       

        }

        p {
            
            padding: 3%;
        }

        .l1 {
            background-color: #f5f5f5;
            box-shadow: #ff535088 5px 5px 15px;
            height: 6cm;
            width: 30%;
            margin-right: 1%;
            margin-left: 1%;
            scale: 90%;
            background-image: url(https://js-pokedex-virid.vercel.app/src/pokeball-icon.png);
            background-position: -49px;
            background-repeat: no-repeat;
            background-attachment: fixed;
        
            



        }
        .image:hover,.l1:hover {
            transform: scale(80%); 
            font-size: 3;
            scale: 120%;
            z-index: 2;
        }
        .Type3 {
            display: flex;
            text-align: center;
            margin: auto;
            justify-content: center;
            font-size: 25px;
            border: 5px solid black;
        }
       .bar {
        display: grid;
            text-align: center;
            margin: auto;
            box-shadow: rgba(0, 0, 0, 0.17) 0px -23px 25px 0px inset, rgba(0, 0, 0, 0.15) 0px -36px 30px 0px inset, rgba(0, 0, 0, 0.1) 0px -79px 40px 0px inset, rgba(0, 0, 0, 0.06) 0px 2px 1px, rgba(0, 0, 0, 0.09) 0px 4px 2px, rgba(0, 0, 0, 0.09) 0px 8px 4px, rgba(0, 0, 0, 0.09) 0px 16px 8px, rgba(0, 0, 0, 0.09) 0px 32px 16px;
            scale: 100%;
            font-size: 56;
            font-weight: 400;
            padding: 100;
            

            
            
       }
       .generation {
        font-size: 30px;
        display: cont;
        font-weight: bolder;
        margin-top: -2ch;
        border: 10px solid black;
        transform: uppercase;
        border-radius: 20px;
       }

 
        


   

        


        

       
    </style>
</head>

<body>
    <h1> Pokedex  </h1>
    
<ul>
    <div class="bar"> 
        <p class="generation"> GEN 1</p>
    <ul>
       
        <li class="l1">
            <p class="name"> bulbasaur </p>
           
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/bulbasaur.gif"
                alt="bulbasaurimg">
            <div class="Type1" style="background: #AB549A;"> Poison
            </div>
            <div class="Type2" style="background: #78CD54"> Grass </div>
            
        </li> 
        <li class="l1">
            <p class="name"> ivysaur</p>
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/ivysaur.gif"
                alt="ivysaur">
                <div class="Type1" style="background: #AB549A;"> Poison
                </div>
                <div class="Type2" style="background: #78CD54"> Grass </div>
            
        </li>
        <li class="l1">
            <p class="name"> Venusaur </p>
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/venusaur.gif">
            <div class="Type1" style="background: #AB549A;"> Poison</div>
            <div class="Type2" style="background: #78CD54;"> Grass</div>
        </li>
        
    </ul>
    <ul> 
        <li class="l1">
            <p class="name"> Charmander </p>
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/charmander.gif">
            <div class="Type3" style="background: #FF5350;"> Fire </div>
        <li class="l1">
            <p class="name"> Charmeleon </p>
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/charmeleon.gif">
            <div class="Type3" style="background: #FF5350;"> Fire </div>
        </li>
        <li class="l1">
            <p class="name"> Charizard </p>
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/charizard.gif">
            <div class="Type3" style="background: #FF5350;"> Fire </div>
        </li>
    </ul>
    <ul>
        <li class="l1">
            <p class="name"> Squirtle </p>
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/squirtle.gif">
            <div class="Type3" style="background: rgba(0, 0, 255, 0.975);"> Water </div>
        </li>
        <li class="l1">
            <p class="name"> Wartortle</p>
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/wartortle.gif">
            <div class="Type3" style="background: blue"> Water</div>
        </li>
        <li class="l1">
            <p class="name"> Blastoise</p>
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/blastoise.gif">
            <div class="Type3" style="background: blue;" style="position: relative;"> Water</div>
        </li>
        </ul>
        <ul>
        <li class="l1">
            <p class="name"> Caterpie</p>
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/caterpie.gif">
            <div class="Type3" style="background: greenyellow;">Bug</div>

        </li>
        <li class="l1">
            <p class="name"> Metapod</p>
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/metapod.gif">
            <div class="Type3" style="background: greenyellow;">Bug</div>

        </li>
        <li class="l1">
            <p class="name"> butterfree </p>
           
            <img class="image" src="https://projectpokemon.org/images/normal-sprite/butterfree.gif"
                alt="butterfree">
            <div class="Type1" style="background: #AB549A;"> Poison
            </div>
            <div class="Type2" style="background: greenyellow"> Grass </div>
            
        </li> 

        </ul>
        </div>






</body>

</html>
