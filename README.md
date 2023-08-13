# HernanRoss

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Institute HernanRoss</title>
    <link rel="stylesheet" href="style.css">
</head>
<body> 
<header class="header">
     <div class="menu container">
       <a href="#" class="logo">logo</a>
       <input type="checkbox" id="menu">
      <label for="menu">
        <img src="" class="menu-icono" alt="">
      </label>
      <nav class="navbar">
          <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Contacto</a></li>
                
            </ul>
        </nav>
    </div>
    <div class="header-content container">

        <div class="header-txt">
            <h1>Institute HernanRoss</h1>
        <p>
         Our intitution distinguishes itself by focusin 
         on the personalization of education, adapting curricula 
         to the individual needs of each student. In addition, 
         we are enriched by a diverse and collaborative community 
         that provides the opportunity to interact with people
         from different backgrounds and perspectives, preparing 
         them for the globalized world in which we live.
         By choosing our institute, you are opting for an education that 
         goes beyon the calssrom, cultivating social, emotional and 
         intelectual skills that are essential for success in the 21st 
         century. We are committed to your growth and development, and 
         look forward to being your partners on the path to a promising 
         future full of possibilities.
     </p>

        </div>

        
     </div>
</header>

     <section class="general container">
        <h2>Our information</h2>
            <div class="general-content">  
            <div class="general-1 txt">
                <h3>Mission</h3>
                    <p>
                        The mission of our English language institution is to provide our  
                        students with the tools and language skills necessary to communicate 
                        effectively in a globalized and multicultural environment. 
                    </p>
            
                </div>
            <div class="general-2 txt">
            <h3>Vision</h3>
            <p>
                The vision of our English language institution is to become a 
                world leader in English language teaching, recognized for its academic 
                excellence, innovative approach and unwavering commitment to 
                the success and growth of its students.

            </p>
            
        </div>
        <div class="general-3 txt">
            <h3>Values</h3>
            <p>
                Academic excellence, commitment to learning, respect for students, 
                cultural diversity, and focus on personal development.
            </p>
            
        </div>

     </div>


     </section>

     <footer class="footer container">
        <h2>Contacto</h2>

        <form>
            <input class="campo" type="text" placeholder="Name">
            <input class="campo" type="text" placeholder="Email">
            <input type="submit" class="btn-2" value="Sent">
            
        </form>


    
        <div class="footer-txt2">
            <p>¡Thank you for contacting us!</p>
            </div>
            

        <div class="footer-txt">
            <p>CEO: ANDYS HERNANDEZ</p>
            
        </div>

     </footer>


</body>
</html>


@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap');


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    list-style: none;
}

body {
    font-family: 'Poppins', sans-serif;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
}

.header {
    background-image: url(imagenes/fedf5e8bac1f58519dfb0463a8bd2bff.jpg);
    background-position: center bottom;
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 110vh;
    display: flex;
    position: flex;
    align-items: center;

}

.menu {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
    z-index: 1000;
}

.logo {

    color: blue;
    font-size: 25px;
    font-weight: 800;
}

.menu .navbar ul li {
    position: relative;
    float: left;
}

.menu .navbar ul li a {
    font-size: 18px;
    padding: 20px;
    color: blue;
    display: block;
    font-weight: 600;
}

#menu {
    display: none;
}

.menu-icono {
    width: 25px;
}

.menu label {
    cursor: pointer;
    display: none;
}

.header-txt {
    text-align: center;
}

.header-txt h1 {
    font-size: 85px;
    color: blue;
    text-transform: uppercase;
}

.header-txt p {
    color: black;
    font-size: 16px;
    padding: 0 250px;
    margin-bottom: 45px;
}


.btn-1 {
    display: inline-block;
    padding: 12px 45px;
    border: 1px solid white;
    color: white;
    font-size: 16px;
    text-transform: uppercase;
    font-weight: 600;
}

.btn-1:hover {
    color: #1b293a;
    background-color: #FFFDFC;
}

.general {
    padding: 50px 0;
    text-align: center;
}

.general-content {
    display: flex;
    justify-content: space-between;
    margin-top: 55px;
}

.general-1 {
    background-image: url(imagenes/color-1.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 450px;
    width: 600px;
    padding: 50px 55px;
}

.general-2 {
    background-image: url(imagenes/azul_mas_verde_color_jade_50387_6_600.png);
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 450px;
    width: 600px;
    padding: 60px 55px;
}

.general-3 {
    background-image: url(imagenes/color-3.jpg);
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 600px;
    height: 450px;
    padding: 60px 55px;
}

h2 {
    font-size: 40px;
    text-transform: uppercase;
    color: blue;
}

.txt h3 {
font-size: 30px;
color: #FFFDFC;
text-transform: uppercase;
margin-bottom: 10px;
}

.txt p {
    color: white;
    font-size: 20px;
}

.footer {
    padding: 100px 0 0 0;
    text-align: center;
}

.form {
    margin-top: 35px;
}

.campo {
    margin-right: 10px;
    padding: 17px 35px;
    border: 2px solid #b4b4b4;
    outline: none;
    color: #1b293a;
}

.campo::placeholder {
    color: #b4b4b4;
}

.btn-2 {
    padding: 17px 35px;
    border: 2px solid #1b293a;
    color: #FFFDFC;
    background-color: #1b293a;
}

.footer-txt {
    margin-top: 100px;
    border-top: 1px solid #b4b4b47e;
    padding: 20px 0;
}

.footer-txt p {
    color: #1b293a;
    font-size: 16px;
}

.footer-txt2 p {
    font-size: 20px;
    color: #1b293a;
}

@media (max-width:991px) {
    .menu {
        padding: 30px;
    }
    .menu label {
        display: initial;
    }
    
    .header {
    
        min-height: 0vh;
    }

    .header-content {
        padding: 100px 30px;
    }

    .header-txt h1 {
        font-size: 50px;
    }

    .header-txt p {
        padding: 0;
    }

    .general {
        padding: 30px 30px 0 30px;
    }

    .general-content {
        flex-direction: column;
        align-items: center;
        margin-top: 20px;
    }

    .general-1 {
        height: 350px;
        padding: 100px;
        margin-bottom: 10px;
    }
    
    .general-2 {
        height: 400px;
        padding: 100px;
        margin-bottom: 10px;
    }

    .general-3 {
        height: 350px;
        padding: 100px;
