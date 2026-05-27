# projeto-APRENDER-MAIS-2-VERS-O   HTML
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">


    <title> 🎓 Aprender+</title>

    <!-- CSS -->
    <link rel="stylesheet" href="style.css">

    <!-- Font Awesome -->

    <style>
        .header nav a {
            margin: 0 10px;
            color: white;
            text-decoration: none;
        }

        .logo {
            color: white;
            font-weight: bold;
        }

        .login {
            background: transparent;
            border: 1px solid rgb(178, 54, 122);
            padding: 8px 15px;
            color: white;
            border-radius: 10px;
        }

        /* HERO */
        .hero {
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 200px;
        }

        .hero img {
            width: 300px;
        }

        /* mudar a cor do card*/
        .cards {
            display: flex;
            justify-content: center;
            gap: 10px;
            padding: 30px;
        }

        .card {
            background: #0f172a;
            padding: 20px;
            border-radius: 10px;
        }
    </style>
</head>

<body>
    <!-- TOPO -->

    <header class="header">

        <div class="logo">
            <img src="ChatGPT Image 13 de mai. de 2026, 15_36_55.png" alt="logo Aprender+">
            <span>APRENDER+</span>
        </div>

        <nav class="navbar"> 
            <a href="#"> INICIO</a> 
            <a href="#"> CURSOS</a>

            <a href="#"> ÁREA DO ESTUDANTE</a> 

            <a href="#"> CONTATOS</a>
            </nav> 

            <button class="login">FAZER LOGIN 
                
            </button>

                
    </header>



    <section class="hero">

        <div class="hero-text">

            <h1> Sua jornada de aprendizado<br>começa aqui!</h1>

            <p>
                 Aprender+ oferece cursos e recursos para te ajudar 
                 a alcançar seus 
                 objetios educacionais
                 no estado de São paulo.
            </p>
                
        
            <button class="primary-btn">     
                    Explorar cursos
                </button>   
     </div> 


         <div class="hero-image">

        <img src="ChatGPT Image 25 de mai. de 2026, 16_53_51.png" 
        alt="Imagem de estudos">

        </div>

    </section>

    <!-- CARDS -->

    <section class="cards">

        <div class="card">
    
            <div class="icon-box">
                <i class="fa-solid fa-book-open"></i>
            </div>
    
            <h3>ENSINO FUNDAMENTAL</h3>
    
            <p>
                Conteúdos completos para fortalecer sua base escolar.
            </p>
    
            <button>Saber Mais</button>
    
        </div>
    
    
        <div class="card">
    
            <div class="icon-box">
                <i class="fa-solid fa-graduation-cap"></i>
            </div>
    
            <h3>ENSINO MÉDIO</h3>
    
            <p>
                Prepare-se para vestibulares e desafios acadêmicos.
            </p>
    
            <button>Saber Mais</button>
    
        </div>
    
    
        <div class="card">
    
            <div class="icon-box">
                <i class="fa-solid fa-laptop-code"></i>
            </div>
    
            <h3>CURSOS TÉCNICOS</h3>
    
            <p>
                Aprenda tecnologia, programação e cursos profissionais.
            </p>
    
            <button>Saber Mais</button>

    
        </div>


        <div class="card">
    
            <div class="icon-box">
                <i class="fas fa-microchip"></i>
            </div>
    
            <h3>IA</h3>
    
            <p>
                Aprenda mais e avançe nos estudos com a IA.
            </p>
    
            <button>Saber Mais</button>

    
        </div>
    
    </section>
   
     <script src=" script.js"></script>

</body>

</html>
