<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ENEM 2025 - Guia de Estudos</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: linear-gradient(135deg, #2c3e50, #4a6491);
            color: white;
            padding: 20px 0;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 28px;
            font-weight: 700;
            display: flex;
            align-items: center;
        }
        
        .logo span {
            color: #ffd700;
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 25px;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: #ffd700;
        }
        
        .hero {
            background: linear-gradient(rgba(44, 62, 80, 0.8), rgba(44, 62, 80, 0.8)), url('https://images.unsplash.com/photo-1523240795612-9a054b0db644?auto=format&fit=crop&w=1920&h=600') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 80px 20px;
        }
        
        .hero h1 {
            font-size: 42px;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 20px;
            max-width: 700px;
            margin: 0 auto 30px;
        }
        
        .btn {
            display: inline-block;
            background-color: #ffd700;
            color: #2c3e50;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s;
        }
        
        .btn:hover {
            background-color: #fff;
            transform: translateY(-3px);
        }
        
        .subjects {
            padding: 80px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            color: #2c3e50;
            font-size: 36px;
            position: relative;
        }
        
        .section-title:after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background: #ffd700;
            margin: 15px auto;
        }
        
        .subjects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .subject-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .subject-card:hover {
            transform: translateY(-10px);
        }
        
        .subject-icon {
            background: #4a6491;
            color: white;
            font-size: 40px;
            padding: 30px;
            text-align: center;
        }
        
        .subject-content {
            padding: 25px;
        }
        
        .subject-content h3 {
            color: #2c3e50;
            margin-bottom: 15px;
        }
        
        .subject-content ul {
            list-style: none;
            margin-left: 10px;
        }
        
        .subject-content ul li {
            margin-bottom: 10px;
            position: relative;
            padding-left: 25px;
        }
        
        .subject-content ul li:before {
            content: '✓';
            color: #4a6491;
            position: absolute;
            left: 0;
            font-weight: bold;
        }
        
        .study-tips {
            background-color: #2c3e50;
            color: white;
            padding: 80px 0;
        }
        
        .tips-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }
        
        .tip-card {
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 10px;
            text-align: center;
            backdrop-filter: blur(5px);
        }
        
        .tip-card i {
            font-size: 40px;
            color: #ffd700;
            margin-bottom: 20px;
        }
        
        .author {
            padding: 80px 0;
            text-align: center;
        }
        
        .author-content {
            max-width: 700px;
            margin: 0 auto;
        }
        
        .social-links {
            margin-top: 20px;
        }
        
        .social-links a {
            display: inline-block;
            background: #4a6491;
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            line-height: 40px;
            margin: 0 10px;
            transition: all 0.3s;
        }
        
        .social-links a:hover {
            background: #2c3e50;
            transform: translateY(-5px);
        }
        
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 30px 0;
            font-size: 14px;
        }
        
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 20px;
                justify-content: center;
            }
            
            nav ul li {
                margin: 0 10px;
            }
            
            .hero h1 {
                font-size: 32px;
            }
            
            .hero p {
                font-size: 18px;
            }
        }
    </style>
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <div class="container header-content">
            <div class="logo">ENEM<span>2025</span></div>
            <nav>
                <ul>
                    <li><a href="#">Início</a></li>
                    <li><a href="#">Matérias</a></li>
                    <li><a href="#">Simulados</a></li>
                    <li><a href="#">Dicas</a></li>
                    <li><a href="#">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Banner Principal -->
    <section class="hero">
        <div class="container">
            <h1>Prepare-se para o ENEM 2025</h1>
            <p>O guia definitivo com tudo o que você precisa estudar para conquistar sua vaga na universidade</p>
            <a href="#materias" class="btn">Começar Agora</a>
        </div>
    </section>

    <!-- Matérias -->
    <section class="subjects" id="materias">
        <div class="container">
            <h2 class="section-title">Matérias para Estudar</h2>
            <div class="subjects-grid">
                <div class="subject-card">
                    <div class="subject-icon">
                        <i class="fas fa-language"></i>
                    </div>
                    <div class="subject-content">
                        <h3>Linguagens e Códigos</h3>
                        <ul>
                            <li>Língua Portuguesa</li>
                            <li>Gramática e Interpretação</li>
                            <li>Literatura Brasileira</li>
                            <li>Língua Estrangeira</li>
                            <li>Artes e Educação Física</li>
                        </ul>
                    </div>
                </div>

                <div class="subject-card">
                    <div class="subject-icon">
                        <i class="fas fa-calculator"></i>
                    </div>
                    <div class="subject-content">
                        <h3>Matemática</h3>
                        <ul>
                            <li>Álgebra e Funções</li>
                            <li>Geometria e Trigonometria</li>
                            <li>Matemática Financeira</li>
                            <li>Estatística e Probabilidade</li>
                            <li>Análise Combinatória</li>
                        </ul>
                    </div>
                </div>

                <div class="subject-card">
                    <div class="subject-icon">
                        <i class="fas fa-flask"></i>
                    </div>
                    <div class="subject-content">
                        <h3>Ciências da Natureza</h3>
                        <ul>
                            <li>Física (Mecânica, Óptica)</li>
                            <li>Química (Orgânica, Inorgânica)</li>
                            <li>Biologia (Genética, Ecologia)</li>
                            <li>Energia e Sustentabilidade</li>
                            <li>Saúde e Doenças</li>
                        </ul>
                    </div>
                </div>

                <div class="subject-card">
                    <div class="subject-icon">
                        <i class="fas fa-globe-americas"></i>
                    </div>
                    <div class="subject-content">
                        <h3>Ciências Humanas</h3>
                        <ul>
                            <li>História do Brasil</li>
                            <li>História Geral</li>
                            <li>Geografia Humana e Física</li>
                            <li>Filosofia e Sociologia</li>
                            <li>Atualidades e Geopolítica</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Dicas de Estudo -->
    <section class="study-tips">
        <div class="container">
            <h2 class="section-title" style="color: #fff;">Dicas de Estudo</h2>
            <div class="tips-grid">
                <div class="tip-card">
                    <i class="fas fa-calendar-alt"></i>
                    <h3>Planejamento</h3>
                    <p>Crie um cronograma de estudos equilibrado, distribuindo as matérias ao longo da semana.</p>
                </div>

                <div class="tip-card">
                    <i class="fas fa-book"></i>
                    <h3>Material de Qualidade</h3>
                    <p>Utilize livros, videoaulas e exercícios recomendados por especialistas em ENEM.</p>
                </div>

                <div class="tip-card">
                    <i class="fas fa-pen-fancy"></i>
                    <h3>Redação</h3>
                    <p>Pratique pelo menos uma redação por semana e peça para alguém avaliar.</p>
                </div>

                <div class="tip-card">
                    <i class="fas fa-brain"></i>
                    <h3>Revisões</h3>
                    <p>Faça revisões espaçadas do conteúdo para fixar melhor o aprendizado.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sobre a Autora -->
    <section class="author">
        <div class="container">
            <h2 class="section-title">Sobre a Autora</h2>
            <div class="author-content">
                <h3>Alissa Medeiros</h3>
                <p>Este site foi concebido e desenvolvido por Alissa Medeiros para auxiliar estudantes na preparação para o ENEM 2025. Com organização, material de qualidade e dedicação, você pode alcançar sua aprovação!</p>
                
                <div class="social-links">
                    <a href="https://instagram.com/alissa.medeiros" target="_blank">
                        <i class="fab fa-instagram"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Rodapé -->
    <footer>
        <div class="container">
            <p>Site concebido por ALISSA MEDEIROS - ENEM 2025</p>
            <p>© 2023 - Todos os direitos reservados</p>
        </div>
    </footer>
</body>
</html>
