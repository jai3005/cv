**<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Jai-Your Average Guy</title>
    <link rel="icon" href="images/favicon.ico">
    <link rel="stylesheet" href="css/site.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300&family=Montserrat:wght@200&family=Sacramento&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500&family=Roboto&display=swap" rel="stylesheet">  
</head>
<body>
    <div class="top-conatiner">
        <img class="top-img" src="images/cloud.png" alt="cloud-img">
        <h1>I'm Jai</h1>
        <p><h2 class="sub">A Learning Web Developer</h2></p>
        <img class="bottom-img" src="images/cloud.png" alt="cloud-img">
        <img src="images/mountain.png" alt="mountain-img">
    </div>


    <div class="middle-container">
        <div class="profile">
          <img src="images/jai1.png" alt="Jai profile picture">
          <h2>Hello.</h2>
          <p class="intro">I'm a hardwoking and responsible guy who is willing to accept new challenges and learn new things at all point of time</p>
        </div>
        <hr>
        <div class="skills">
          <h2>My Hobbies.</h2>
          <div class="skill-row">
            <img class="skill-img" src="https://media.giphy.com/media/L8K62iTDkzGX6/giphy.gif" alt="web Development">
            <h3>Web Development</h3>
            <p>This is the first site I'm working on and I truly hope that this works out fine.FINGERS CROSSED🤞🤞</p>
          </div>
          <div class="skill-row">
            <img class="skill-imggg" src="https://media.giphy.com/media/YKSxfddY4MkCKKQPmh/giphy.gif" alt="orator">
            <h3>A Good Orator</h3>
            <p>One thing I feel im pretty good is speaking as thats the only thing i have been doing for the last 18 years,so if you want to know how to jst get up and debate about any topic CONTACT ME ASAP!! </p>
            </div>
          <div class="skill-row">
            <img class="skill-imgg" src="https://image.flaticon.com/icons/png/512/606/606668.png" alt="Football">
            <h3>Football</h3>
            <p>AND Most of all I crave FOOTBALL more than anything.Its the source of my happiness.Should I leave engineering to be a follow my happiness xd??</p>
            </div>

            <div class="skill-row">
             <img class="skill-imgggg" src="https://image.flaticon.com/icons/png/512/2490/2490421.png" alt="know">
             <h3>I Know Everything</h3>
             <p>Jst one more thing i know answer to all your questions.You Don't believe me type anything in th box and see for yourself</p>
             <form action="https://www.google.com/search">
               <input type="text" name="q">
               <button>Search</button>
             </form>

            </div>
            
        </div>
        <hr>
        <div class="contact-me">
          <h2>Get In Touch</h2>
          <h3>If You Have Scrolled Till Here </h3>
          <p class="end">Then dont be shy now! Let's meet and talk more! We can even go watch a football match after we code hehe!!</p>
          <a class="BUTTON_IBY" href="mailto:jai41518@gmail.com">CONTACT ME</a>
        </div>
      </div>
      
      
      <div class="bottom-container">
        <a class="linkedin-link" href="https://www.linkedin.com/in/jaivardhan-singh-811138142/2"><strong>LinkedIn  </strong></a>
        <a class="instagram-link" href="https://www.instagram.com/jaivardhan._singh._/"> <strong>Instagram</strong></a>
        <p class="copyright">© 2021 Jaivardhan Singh.</p>
      </div>
      

    </div>
    
    
</body>
</html>

**
.top-conatiner{
    background-color: #EAF6F6;
    position: relative;
    padding-top: 100px;
}
.profile{
    margin: 0;
    padding: 50px;
}

h1{
    margin: 50px auto 0 auto;
    font-family: 'Sacramento', cursive;
    font-size: 5.26rem;
    color: #66BFBF;
}

h2{
    
    font-family: 'Montserrat', sans-serif;
    font-size: 2.5rem;
    color: #21adad;
}

h3{
    font-family: 'Montserrat', sans-serif;
    color: #177579;
}

a{
    color: #032e30;
    margin: 10px 20px;
    text-decoration: none;
}
a:hover{
    color: #EAF6F6;
}

body{
    color: black;
    margin:0; /*This commands sets all the margins to 0 and it as we dont specify unit so it will judge accordingly*/
    text-align: center;
    font-family: 'Merriweather', serif;

}
.intro{
     width: 40%;
     margin: auto;
}

.middle-container{
    background-color: #B5EAEA;
}
    

.bottom-container{
    background-color: #66BFBF;
    padding: 25px;
}

p{
    line-height: 2;
}



.skills{
    margin-bottom: 100px;
}


.skill-row{
    width: 50%;
    margin: 50px auto 50px auto;
    text-align: left;
    line-height: 2;
}


.skill-img{
    width: 22%;
    float: left;
    padding: 30px;
}
.skill-imgg{
    width: 20%;
    float: left;
    margin-left: 10px;
}
.skill-imggg{
    width: 35%;
    float: right;
    padding: 30px;
}
.skill-imgggg{
    width: 20%;
    float: right;
}

input{
    background-color:#66BFBF;
}

button{
    background-color: #B5EAEA;
}
button:hover
{
    background-color:#daebee;
}
span{
    text-decoration: underline;
}

.bottom-img{
    position: absolute;
    bottom: 300px;
    left: 250px;
}

.top-img{
    position: absolute;
    right: 300px;
    top: 50px;
}

.sub{
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5rem;
    color: #66BFBF;
    font-weight:bold;
}
.end{
 width: 40%;
 margin: auto   ;   
}

.copyright{
    color:#EAF6F6;
    font-size: 0.75rem;
    padding: 15px;
}
hr{
    border: dotted grey 6px;
    border-bottom: none;
    width: 4%;
    margin: 80px auto;
}

.BUTTON_IBY {
    background: #66BFBF;
    background-image: -webkit-linear-gradient(top, #66BFBF, #66BFBF);
    background-image: -moz-linear-gradient(top, #66BFBF, #66BFBF);
    background-image: -ms-linear-gradient(top, #66BFBF, #66BFBF);
    background-image: -o-linear-gradient(top, #66BFBF, #66BFBF);
    background-image: -webkit-gradient(to bottom, #66BFBF, #66BFBF);
    -webkit-border-radius: 27px;
    -moz-border-radius: 27px;
    border-radius: 27px;
    color: #FFFFFF;
    font-family: Verdana;
    font-size: 15px;
    padding: 10px;
    -webkit-box-shadow: 1px 1px 8px 0 #2571EB;
    -moz-box-shadow: 1px 1px 8px 0 #2571EB;
    box-shadow: 1px 1px 8px 0 #2571EB;
    text-shadow: 1px 1px 20px #000000;
    border: solid #337FED 0;
    text-decoration: none;
    display: inline-block;
    cursor: pointer;
    text-align: center;
    margin: 50px auto;
 }
 
 .BUTTON_IBY:hover {
    border: solid #337FED 0;
    background: #177579;
    background-image: -webkit-linear-gradient(top, #177579, #177579);
    background-image: -moz-linear-gradient(top, #177579, #177579);
    background-image: -ms-linear-gradient(top, #177579, #177579);
    background-image: -o-linear-gradient(top, #177579, #177579);
    background-image: -webkit-gradient(to bottom, #177579, #177579);
    -webkit-border-radius: 0;
    -moz-border-radius: 0;
    border-radius: 0;
    text-decoration: none;
 }
