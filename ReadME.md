#WebTech Projekt

<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>About Me Profile card || Learning Robo</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css" integrity="sha512-+4zCK9k+qNFUR5X+cKL9EIR+ZOhtIloNl9GIKS57V1MyNsYpYcUrUeQc9vNfzsWfV28IaLL3i96P9sdNyeRssA==" crossorigin="anonymous" />
  </head>
  <body>
    
    <div class = "about-wrapper">
      <div class = "about-left">
        <div class = "about-left-content">
          <div>
            <div class = "shadow">
              <div class = "about-img">
                <img src = "https://cdn.pixabay.com/photo/2018/11/13/21/43/instagram-3814049__340.png" alt = "about image">
              </div>
            </div>

            <h2>Learning Robo</h2>
            <h3>Web developer</h3>
          </div>

          <ul class = "icons">
            <li><i class = "fab fa-facebook-f"></i></li>
            <li><i class = "fab fa-twitter"></i></li>
            <li><i class = "fab fa-linkedin"></i></li>
            <li><i class = "fab fa-instagram"></i></li>
          </ul>
        </div>
        
      </div>

      <div class = "about-right">
        <h1>Hello<span>!</span></h1>
        <h2>Here's who I am & what I do</h2>
        <div class = "about-btns">
          <button type = "button" class = "btn btn-pink">resume / CV</button>
          <button type = "button" class = "btn btn-white">Git hub</button>
        </div>

        <div class = "about-para">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus, aspernatur possimus ullam quaerat, laboriosam ex voluptate aliquid laborum, obcaecati ratione accusamus! Ea nisi modi dolor nam numquam? Temporibus, molestias amet.</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Natus iure tempora alias laudantium sapiente impedit!</p>
        </div>
        <div class="credit">Made with <span style="color:tomato">❤</span> by <a href="https://www.learningrobo.com/">Learning Robo</a></div>
      </div>
    </div>
    
   <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800&display=swap');

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body{
    font-family: 'Poppins', sans-serif;
}
.about-wrapper{
    height: 100vh;
}
.about-left{
    background-color: #21D4FD;
    background-image: linear-gradient(19deg, #21D4FD 0%, #B721FF 100%);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
    color:#fff
}
.about-left-content > div{
    background: #12192c;
    padding: 4rem 4rem 2.5rem 5rem;
    text-align: center;
    
    border-radius: 12px 12px 0 0;
}
.about-left-content{
    box-shadow: 0px 0px 18px -1px rgba(0, 0, 0, 0.39);
    -webkit-box-shadow: 0px 0px 18px -1px rgba(0, 0, 0, 0.39);
    -moz-box-shadow: 0px 0px 18px -1px rgba(0, 0, 0, 0.39);
    border-radius: 12px;
    width:80%;
}
.about-img img{
    display: block;
    width: 200px;
}
.about-img{
    width: 200px;
    height: 200px;
    overflow: hidden;
    border-radius: 50%;
    transition: all 0.5s ease-in-out;
}
.shadow{
    margin-left: auto;
    margin-right: auto;
    border-radius: 50%;
    width: 200px;
    height: 200px;
}



.about-left-content h2{
    font-size: 2rem;
    margin: 2.2rem 0 0.6rem 0;
    line-height: 1.2;
    padding-bottom: 1rem;
    border-bottom: 2px solid #B721FF;
}
.about-left-content h3{
    text-transform: uppercase;
    font-weight: 300;
    letter-spacing: 5px;
    margin-top: 1.2rem;
}
.icons{
    background: #12192c;
    display: flex;
    justify-content: center;
    padding: 0.8rem 0;
    border-radius: 0 0 12px 12px;
}
.icons li{
    list-style-type: none;
    background: #B721FF;
    color: #fff;
    width: 40px;
    height: 40px;
    margin: 0 0.5rem;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    cursor: pointer;
    transition: all 0.5s ease-in-out;
}
.icons li:hover{
    background: #edffec;
    color: #000;
}
.about-right{
    background: #12192c;
    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 0 5rem;
    text-align: center;
    color:#fff
}
.about-right h1{
    font-size: 5rem;
    text-transform: uppercase;
}
.about-right h1 span{
    color: #B721FF;
}
.about-right h2{
    font-weight: 600;
}
.about-btns{
    display: flex;
    margin: 2rem 0;
}
.btn{
    border: none;
    font-size: 0.9rem;
    text-transform: uppercase;
    border: 2px solid #fff;
    border-radius: 20px;
    padding: 0.55rem 0;
    width: 130px;
    font-weight: 600;
    background: transparent;
    margin: 0 0.5rem;
    cursor: pointer;
    color:#fff
}
.btn.btn-pink{
    background: #B721FF;
    color: #fff;
    border-color: #B721FF;
    transition: all 0.5s ease-in-out;
}
.btn.btn-pink:hover{
    background: transparent;
    border-color: #fff;
    color: #fff;
}
.btn.btn-white{
    transition: all 0.5s ease-in-out;
}
.btn.btn-white:hover{
    background: #B721FF;
    border-color: #B721FF;
    color: #fff;
}
.about-para p{
    font-weight: 300;
    padding: 0.5rem;
    opacity: 0.8;
}

@media screen and (min-width: 992px){
    .about-wrapper{
        display: grid;
        grid-template-columns: repeat(2, 2fr);
    }

    .about-left{
        position: relative;
    }
    .about-left-content{
        position: absolute;
        width:80%
    
    }
}
.credit{
    text-align: center;
    color: #fff;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.credit a{
    text-decoration: none;
    color:#B721FF;
    font-weight: bold;
} 
</style>
  </body>
</html>
