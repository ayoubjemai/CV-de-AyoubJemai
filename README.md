# CV-de-AyoubJemai
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link rel="stylesheet" href="style.css">
    <title>Ayoub Jemai </title>  
</head>
<body>

    <header>
        <h2>My CV</h2>
        <a href="#" CLASS3LOGO3></a></a>
        <nav class="navigation">
            

        </nav>

    </header>



    <section class="main">
        <div>
            <h2>Hello I'm Ayoub Jemai<br><span>a student at alternance taki academy</span></h2>
            <p>My purpose of my demanding is my love of the technologie <br> exactly the computer computer science 
                <br>besides i want to have my experinece before even my graduation
                <br>also change the style of the education that takiacedemie offert <br> to us and focus on practice more than theoretical 
                <br>I hope you  accept me for this programme and thank you for this</p>
            <a href="#project"class="main-btn"></a>
            <br>
            <div class="social-icons">
                <a href="https://www.facebook.com/ayoub.jemai.1865"><i class="fa-brands fa-facebook"></i></a>
                <a href="https://www.instagram.com/ayoub.jemai.1865/"><i class="fa-brands fa-instagram"></i></a>
                <a href="https://twitter.com/jemaiayoub4"><i class="fa-brands fa-twitter"></i></a>
            </br>

            </div>
        </div>

    </section>

    <section class="cards" id="Adresse">
        <div class="content">
            <div class="card">
                <div class="icon">
                    <i class="fa-solid fa-map-location"></i>
                </div>
                <div class="info">
                    <h3>Gafsa mataloui 2134<br>34°18'47.8"N 8°23'04.1"E</br></h3>
                </div>
            </div>
            <div class="card">
                <div class="icon">
                    <i class="fa-solid fa-phone"></i>
                </div>
                <div class="info">
                    <h3>+21629093470</h3>
                </div>
                
            </div>
            <div class="card">
                <div class="icon">
                    <i class="fa-solid fa-envelope"></i>
                </div>
                <div class="info">
                    <h3>ayoubjemai@99gmail.com</h3>
                </div>
                
            </div>



        
        </div>
    </section>

    
</body>
</html>




@import url('https://fonts.googleapis.com/css2?family=Poppins:ital@1&display=swap');

*{
    ont-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

header {
    background-color: 	 #000000;
    color: aliceblue;
    width: 100%;
    position: fixed;
    z-index: 999;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 200px;
}

.header {
    background-color: red;
}

.logo{
    text-decoration: none;
    color: rgb(255, 0, 0);
    text-transform: uppercase;
    font-weight: 700;
    font-size: 1.8em;
}

.navigation a{
    color:  rgb(255, 0, 0);
    text-decoration: none;
    font-size: 1.1em;
    font-weight: 500;
    padding-left: 30px;
}
.navigation a:hover{
    color:  rgb(255, 255, 255);
    text-decoration: none;
    font-size: 1.1em;
    font-weight: 500;
    padding-left: 30px;
}
section{
    padding: 100px 200px;

}
.main{
    width: 100%;
    min-height: 100vh;
    display: flex;
    align-items: center;
    background: url(images/ayoub.jpg) no-repeat;
    background-size: 30em;
    background-position: 1000px 150px;
    background-color: #ADD8E6;
}

.main  h2 {
    color: rgb(3, 3, 3);
    font-size: 2em;
    font-weight: 500;
    font-style: italic;
}

.main h2 span{
    display: inline-block;
    margin-top: 10px;
    color: crimson;
    font-size: 50px;
    font-weight: 600;
    font-style: oblique;
}
.main p {
    display: flex;
    font-size: medium;
    color: black;
    font-weight: 500;
    display: flex;
    font-size: 1.8em ;
    font-style: italic;
    padding: 1em ;
}

.social-icons a{
    color: aliceblue;
    font-size: 2em;
    padding-right: 30px;

}

.title{
    display: flex;
    justify-content: center;
    color: aquamarine;
    font-size: 2.2em;
    font-weight: 800;
    margin-bottom: 30px;
    padding: 50px 800px 20px 50px;
}

.content{
    display: flex;
    justify-content: center;
    flex-direction: row;
    flex-wrap: wrap;
}

.card{
    background-color: aquamarine;
    width: 21.25em;
    box-shadow: 0 5px 25px rgba(1, 1, 1, 50%);
    border-radius: 5px;
    padding: 25px;
    margin: 15px;
    transition: 0.7s ease;
     
}
.card:hover{
    transform: scale(1.1);
}
.icon{
    font-size: 3em;
    text-align: center;

}

@media (max-width:1023px){
    header{
        padding: 8px 20px;
        font-size: smaller;
    }
    .navigationa{
        padding-left: 10px;

    }
    .title{
        font-size: 1.8em;
    }
    section{
        padding: 80px 20px;

    }
    .main-content h3{
        font: size 1.4em;em;

    }
    .content{
        flex-direction: column;
        align-items: centre;
    }
}
