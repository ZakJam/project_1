## style css

  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style>

## html

  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">Zakaria Jamali</a>.
  </div>


  <img src="/src/assets/images/illustration-article.svg" alt="image" class="image">

    <button>Learning</button>
    <p>Published 21 Dec 2023</p>
    <h1>HTML & CSS foundations</h1>
    <p>These languages are the backbone of every website, defining structure, content, and presentation.</p>

  <img src="/src/assets/images/image-avatar.webp" alt="image_of_Greg">
    <p>Greg Hooper</p>




## Just structure html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no"> 
  <link rel="icon" type="image/png" sizes="32x32" href="./assets/images/favicon-32x32.png">
  <title>Frontend Mentor | Blog preview card</title>
  <link rel="stylesheet" href="/src/css/style.css">
  <link rel="icon" type="image/png" href="/src/assets/images/favicon-32x32.png">


</head>
<body>


<div class="container column">


  <div class="first_ctr">



  </div>


  <div class="second_ctr">

  
  </div>


  <div class="third_ctr row" >

  

  </div>
  


</div>




  
  

</body>
</html>




## just structure css

.column {
    display: flex;
    flex-direction: column;
}

.row{
    display: flex;
    flex-direction: row;
}

html,body{
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100%;
}

body{
    border: 1px blue solid;
    box-sizing: border-box; /* key */
    display:flex;
    justify-content: center;
    align-items: center;
    background-color: #F4D04E;

}

.container{
    border: 1px black solid;
    width: 75.2%;
    border-radius: 15px;
    padding: 25px;
    background-color: white;
    height: 52%;
    box-shadow: 10px 10px;
    min-width: 200px;
    max-width: 328px;
}



.first_ctr , 
.second_ctr, 
.third_ctr {
    border: 1px red solid;
}

.first_ctr{
    width: 100%;
    height: 50%;
}

.second_ctr{
    height: 35%;
}

.third_ctr{
    height: 15%;
}


@media screen and (min-width: 1440px ) {


.container {
    width: 22.7%;
    padding: 30px;
    height: 45%;
    max-width: 400px ;
}


}








