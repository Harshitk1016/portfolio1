# portfolio1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harshit Kumar - Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <style>
        *{
            margin: 0;
            
            color: white;
        }
    body{
        background-color: rgb(0, 0, 33);
        color: white;
        font-family: 'poppins', sans-serif;
    }
    nav{
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 60px;
        background-color: rgb(5, 5, 62);
    }
    nav ul{
        display: flex;
        justify-content: center;
    }
    nav ul li{
        list-style: none;
        margin: 0 23px;
    }
    nav ul li a{
       text-decoration: none;
       color: white;
    }
    nav ul li a:hover{
      color: rgb(147, 111, 248);
      font-size: 1.04rem;
    }
    .left{
        font-size:  1.5rem;;
    }
    .firstsection{
        display: flex;
        justify-content: space-around ;
        margin: 130px;

    }
    .firstsection > div{
        width: 30%;

    }
    .leftsection{
    
       font-size: 2rem;
    }
    .rightsection img{
        width: 80%;
        
    }
    .purple{
        color: blueviolet;
    }
    #element{
        color: blueviolet;
    }
    .secondsection {
        font-size: 1.6rem;
        margin: 10%;
    }     
    .footer ul {
        display: flex;
        justify-content: center;
        margin: 80%;
    }    
    .secondsection h2 div{
        font-size: 3rem;
        margin: auto;
    }                                                
    .therdesection{
        font-size: 23px;
        margin: auto;
        
    }
    .secondsection h2{
        margin: auto;
    }
    </style>
</head>
<body>
    <head>
        <nav>
            <div class="left">Harshit KUMAR</div>
            <div class="right">
                <ul>
                     <li><a href="">HOME</li></a>
                    <li><a href="">ABOUT</li></a>
                    <li><a href="">EDUCATION</li></a>

                </ul>
            </div>
        </nav>
    </head>
    
    <main>
        <section class="firstsection">
            <div class="leftsection">
                Hi, My name is <span class="purple">Harshit Kumar</span> 
                <div>and I am a </div>
                <span id="element"></span>
            </div>
            <div class="rightsection">
<img src="bg.png.png" >
            </div>
        </section>
        <section class="secondsection">
            <h1>About me</h1>
            <div class="center">
                Harshit Kumar is a dedicated student at <span class="purple">GBPUAT Pantnagar University </span> , 
                where he is pursuing a degree in <span class="purple">Computer Engineering</span> .
                 Alongside his academic studies, Harshit is actively learning web development,
                  reflecting his keen interest in building and designing websites. 
                  In his free time, he enjoys playing online games, 
                  which not only provide a fun and engaging way to relax but also inspire his creativity and problem-solving skills. 

            </div>
<hr>
            <h2>skills</h2>
            <div class="center">
                C++/C
            </div>
            <hr>
            <h3>Intrests</h3>
            <div>
                <li>Gaming(online)</li>
                <li>web development</li>
            </div>
        </section>
    </main>
    <hr>
    <section class="therdesection">
            <ul>
            <li><a href="https://www.linkedin.com/in/harshit-kumar-5163b9291?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Linkedin</a></li>
            <li><a href="https://www.instagram.com/harshit.10.16?igsh=amhsanZrYjNzN25z">Instragram</a></li>
        </ul>
    </section>
   <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
          strings: ['Computer Engineering Student'],
          typeSpeed: 50,
        });
      </script>
</body>
</html>
