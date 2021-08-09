# challenge1andela
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0"><!-- displays site properly based on user's device -->
    <link rel="icon" type="images/png" sizes="32*32" href="./images/favicon-32x32.png"/>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Big+Shoulders+Display:wght@700&family=Lexend+Deca&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">
    <title>HEX HAT</title>
</head>
<body>
    <div class="container">
    <div class="card bright-orange" >  
         <img src="/challenge/images/icon-sedans.svg" alt="">
        <h3>sedans</h3> 
       <p>choose a sedan for ist affordability and excellent fuel economy. Ideal for cruising in the city
     or on your next road trip.
       </p> <button class="btn">LEARN MORE</button>
       
       <div class="card dark-cyan">
        <img src="/challenge/images/icon-suvs.svg" alt=""> 
         <h3>suvs</h3>
     <p>   take an SUV for its spacious interior,power,and
          versatility. Perfect for your next family vacation
           and off-road adventures.</p> <button class="btn">LEARN MORE</button>
     
     <div class="card very-dark-cyan">
    <img src="/challenge/images/icon-luxury.svg" alt="">  
            <h3>luxury</h3> 
           <p> Cruise in the best car brands without the bloated prices.
               enjoy the enhanced comfort of a luxury rentaland arrive  in style.
           </p>
            <button class="btn">LEARN MORE</button>
          
    </div> 
</body>

<div class="attribution">
    challenge by <a href="https:frontendmentor.io?
    ref=challenge" target="_blank">frontendmentor</a>
    coded by <a href="#">kabengera</a>. 
    here</a>.
</div>


</html>
        
:root {
   
--Bright-orange: hsl(31, 77%, 52%) ;
--Dark-cyan: hsl(184, 100%, 22%) ;
--Very-dark-cyan: hsl(179, 100%, 13%) ; 

}





* {
  margin: 0 ;
  padding: 0 ;
  box-sizing: border-box ;
}
body,
button {
  font-family: "lexend deca", sans-serif;
}
h3 {
  font-family: "big shoulder display", sans-serif;
  text-transform: uppercase;
  font-size: 30px;
}

p  {
    Font size: 15px;
    line-height: 1.6;
}
.btn {
    background-color: #fff;
    border: 2px solid #fff;
    border-radius: 30px;
    padding: 10px 20px;
    cursor: pointer;
    transition: all 0.4 ease-in-out ;
}

.bright-orange {
    background-color: var(--Bright-orange) ;
    color: #fff
    border-radius: 10px 10px 0 0 ;
}
.bright-orange .btn {
    color: var(--Bright-orange);

}
.dark-cyan {
    background-color: var(--Dark-cyan);
    color: #fff;

}
.dark-cyan .btn {
    color: var(--Dark-cyan);
}
.very-dark-cyan {
    background-color: var(--very-dark-cyan) ;
    color: #fff;
    border - radius:0 0 10px 10px ;
}
.very-dark-cyan .btn {
    color: var(--Very-dark-cyan);
}
.btn:hover {
    background-color: transparent;
    color: #fff;
}

.container {
    padding: 20px ;
}
.card {
    padding: 30px ;

}
.card img {
    margin-bottom:25px;
}
.card h3 {
    margin-bottom:20px;
}

}
.attribution {
  font-size: 10px;
  text-align: center;
}
.attribution a {
  color: hsl(228, 45%, 44%);
}
@media (min-width: 992px) {
    .container {
        display: flex ;
        align-items: center ;
        justify-content: center ;
       min-height: 100vh ; 
       max-width: 900px ;
       margin: auto ;
    }
    .bright-orange {
        border-radius: 10px 0 0 10px;
    }
    .dark-cyan {
        border-radius: 0 10px 10px 0;
    }
.card p {
    margin-bottom: 50px;

}

@media (min-width:1280px) {

    .container {
        max-width: 1100px;
    }
}        
        
        
        
        
        
        
        
        
        
        
        
        
        
