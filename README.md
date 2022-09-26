# only-html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>test</title>
<style>
    body {
  background-color: #19944c;
  margin: 0 15%;
  font-family: sans-serif;
  }
    h1 {
  text-align: center;
  font-family: serif;
  font-weight: normal;
  text-transform: uppercase;
  border-bottom: 1px solid #57b1dc;
  margin-top: 30px;
}
    </style>
<style>

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}
</style>
</head>
<body>
    <main>
        <section>
          <img src="https://i.pinimg.com/564x/ae/c8/5c/aec85c58a40bdcd28a4ea0ae66df25a7.jpg"width="100" height="100">
           <h1 style="background-color:rgb(30, 255, 98);">Beautiful placies to visit in Vilnius</h1>
        </section>
        <section>
           <h2>1. Užupis</h2>
             <img src="https://www.govilnius.lt/images/5e20106736de745e237b428e?w=750&h=500" alt="Užupio Respublika"width="500" height="379">
           <h2>2. Gedimino pilis</h2>
             <img src="https://upload.wikimedia.org/wikipedia/commons/9/9d/Gedimino_pilis_by_Augustas_Didzgalvis.jpg" alt="Gedimino pilis from up high"width="500" height="379">
           <h2>3. Balsio regykla</h2>
             <img src="https://s1.15min.lt/images/photos/2022/01/18/original/takas-aplink-vilniu-zalieji-ezerai-61e7082cbf07f.jpg" alt="Beautiful view of Balsys"width="500" height="379">
           <a target="_blank" href="https://i.pinimg.com/564x/ae/80/20/ae8020e4ff3fc5337e0151ef4023c0b2.jpg"> <!-- cia pridet foto--><img src=""></a>
            <p style="color:rgb(9, 3, 3);">Click here to view more <a target="_blank" href="https://freecatphotoapp.com"><button class="button"><span>photos</span></button></a>.</p>
        </section>
        <section>
            <h1>
               <p>Look at this <a target="_blank" href="https://thirdeyetraveller.com/wp-content/uploads/THREECROSSHILL-11-of-23-689x459.jpg">view
               </a></p>
            </h1>
        </section>
        <section>
            <!--Prideti kazka-->
            <!-- pataisyti logo-->
            <p>© 2022</p>
        </section>
    </main>
</body>
</html>



