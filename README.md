<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pokemon Legends Arceus </title>
    <link rel="stylesheet" href="PokemonQuizzie.css">
</head>
<body>
    <div id="Pokémon">
       <p>Welcome to world of Pokémon!<br> Well quiz about it anyway.
        We made a Pokémon quiz about one of the greatest games as of late.<br>
        How much do you know about...Pokémon Legends Arceus? <br><br> 
        Let's put your knowloge to the test and see if you have what it takes to be a Pokémon Master! <br><br>
        Gotta get em all right to see if your knowlege can be the very best like no one's  ever was.<br>
        Ready? Then lets begin!</p>
    </div>
    <div id="Pquiz">
        <h1>Pokémon Legends Arceus </h1>
        <hr>
        <p class="italic"> Tip: Hints can be found anywhere.</p>
        <p>Q1. Who was the developer who made Legends Arceus?</p>
        <input type="radio" name="question1" id="correct1"> Game Freak
        <input type="radio" name="question1"> Nintendo Entertainment planning and Development
        <input type="radio" name="question1"> Mob Games 
        <input type="radio" name="question1"> Arc System Works<br>

        <p>Q2. In which region does this game take place?</p>
        <input type="radio" name="question2"> Ancient Kalos
        <input type="radio" name="question2"> Ancient Paldea
        <input type="radio" name="question2" id="correct2"> Ancient Sinnoh
        <input type="radio" name="question2"> Ancient Galar<br>

        <p>Q3. Who are the starters you cn pick from?</p>
        <input type="radio" name="question3"> Chimchar/Snivy/Popplio 
        <input type="radio" name="question3" id="correct3"> Rowlet/Oshawott/Cyndaquil
        <input type="radio" name="question3"> Fennekin/Mudkip/Treecko
        <input type="radio" name="question3"> Tepig/Piplup/Chespin<br>

        <p>Q4. In what year did the game come out?</p>
        <input type="radio" name="question4"> 2019
        <input type="radio" name="question4"> 2017
        <input type="radio" name="question4" id="correct4">2022
        <input type="radio" name="question4"> 2014<br>

        <p>Q5. Which two clans are at odds with each other?</p>
        <input type="radio" name="question5"> Luster & Radiant Clans
        <input type="radio" name="question5"> Adamant & Oracle Clans
        <input type="radio" name="question5" id="correct5"> Diamond & Pearl Clans
        <input type="radio" name="question5"> Adaman & Irida Clans <br>

        <p>Q6. What do people in Hisui call Arceus?</p>
        <input type="radio" name="question6"> Allmighty Hoenn
        <input type="radio" name="question6"> Allmighty Alola
        <input type="radio" name="question6" id="correct6"> Allmighty Sinnoh
        <input type="radio" name="question6"> Allmighty Deer<br>

        <p>Q7. Who is the first ride Pokémon you get?</p>
        <input type="radio" name="question7"> Ursaluna 
        <input type="radio" name="question7"> Braviary
        <input type="radio" name="question7"> Basculegion
        <input type="radio" name="question7" id="correct7" > Wyrdeer<br>

        <p>Q8. Who is the first Noble Pokémon you face? </p>
        <input type="radio" name="question8"> Lady Liligant
        <input type="radio" name="question8"> Lord Arcanine
        <input type="radio" name="question8"> Lord Avalugg
        <input type="radio" name="question8" id="correct8"> Lord Kleavor<br>

        <p>Q9. When you defeat/befriend the Noble Pokémon wht do you get?</p>
        <input type="radio" name="question9" id="correct9"> Plate  
        <input type="radio" name="question9"> Nothing
        <input type="radio" name="question9"> Sachet
        <input type="radio" name="question9"> Potion<br>

        <p>Q10. In the end someone is always evil. Who betrayed you in the end?</p>
        <input type="radio" name="question10" id="correct10"> Volo
        <input type="radio" name="question10"> Commander Kamado
        <input type="radio" name="question10"> Ingo 
        <input type="radio" name="question10"> Cyllene <br>
        <hr>
        <input type="submit" name="submit" value="Answers" onclick="javascript:result()">

        <script type="text/javascript">
          function result() {
            var score = 0;
            if (document.getElementById('correct1').checked) {
              score++;
            }
            if (document.getElementById('correct2').checked) {
              score++;
            }
            if (document.getElementById('correct3').checked) {
              score++;
            }
            if (document.getElementById('correct4').checked) {
              score++;
            }
            if (document.getElementById('correct5').checked) {
              score++;
            }
            if (document.getElementById('correct6').checked) {
              score++;
            }
            if (document.getElementById('correct7').checked) {
              score++;
            }
            if (document.getElementById('correct8').checked) {
              score++;
            }
            if (document.getElementById('correct9').checked) {
              score++;
            }
            if (document.getElementById('correct10').checked) {
              score++;
            }


            alert("Your score is:" + score);
          }
          window.onscroll = function () {
            myFunction()
          };
        </script>
        
    <style> #Pquiz{
    background-color: mediumaquamarine;
    width: fit-content;
    height: auto;
    float: left;
    padding: 20px;
  }
  </style> 
</body>
</html>
