<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curso para Mulheres Empoderadas e Desejadas | Transforme sua Vida</title>
    <style>
        :root {
            --primary: #e83e8c;
            --secondary: #6f42c1;
            --dark: #343a40;
            --light: #f8f9fa;
            --success: #28a745;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            color: var(--dark);
            line-height: 1.6;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header */
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        
        .logo {
            font-size: 2rem;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1491438590914-bc09fcaaf77a?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 0;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 1.5rem;
            margin-bottom: 30px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .cta-button {
            display: inline-block;
            background: var(--primary);
            color: white;
            padding: 15px 40px;
            font-size: 1.2rem;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }
        
        .cta-button:hover {
            background: var(--secondary);
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0,0,0,0.3);
        }
        
        /* Problem Section */
        .problem {
            padding: 80px 0;
            background-color: var(--light);
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            font-size: 2.5rem;
            color: var(--dark);
        }
        
        .problem-content {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
        }
        
        .problem-text {
            flex: 1;
            min-width: 300px;
            padding: 20px;
        }
        
        .problem-image {
            flex: 1;
            min-width: 300px;
            padding: 20px;
        }
        
        .problem-image img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        /* Solution Section */
        .solution {
            padding: 80px 0;
        }
        
        .benefits {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin-top: 50px;
        }
        
        .benefit {
            flex: 0 0 30%;
            min-width: 250px;
            text-align: center;
            margin-bottom: 30px;
            padding: 20px;
        }
        
        .benefit-icon {
            font-size: 3rem;
            color: var(--primary);
            margin-bottom: 20px;
        }
        
        /* Course Details */
        .course-details {
            padding: 80px 0;
            background-color: var(--light);
        }
        
        .modules {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .module {
            background: white;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        .module-title {
            font-size: 1.3rem;
            color: var(--primary);
            margin-bottom: 10px;
        }
        
        /* Testimonials */
        .testimonials {
            padding: 80px 0;
        }
        
        .testimonial-cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        
        .testimonial {
            flex: 0 0 30%;
            min-width: 250px;
            background: white;
            border-radius: 10px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            position: relative;
        }
        
        .testimonial:before {
            content: """;
            font-size: 5rem;
            color: var(--primary);
            opacity: 0.2;
            position: absolute;
            top: -10px;
            left: 10px;
        }
        
        .testimonial-text {
            font-style: italic;
            margin-bottom: 20px;
        }
        
        .testimonial-author {
            font-weight: bold;
            color: var(--primary);
        }
        
        /* Pricing */
        .pricing {
            padding: 80px 0;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            text-align: center;
        }
        
        .pricing-card {
            background: white;
            color: var(--dark);
            border-radius: 10px;
            padding: 40px;
            max-width: 500px;
            margin: 0 auto;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        
        .price {
            font-size: 3rem;
            font-weight: bold;
            color: var(--primary);
            margin: 20px 0;
        }
        
        .original-price {
            text-decoration: line-through;
            color: #999;
            font-size: 1.5rem;
        }
        
        .bonus {
            background: var(--success);
            color: white;
            padding: 10px;
            border-radius: 5px;
            margin: 20px 0;
        }
        
        .guarantee {
            margin: 20px 0;
            font-style: italic;
        }
        
        /* FAQ */
        .faq {
            padding: 80px 0;
            background-color: var(--light);
        }
        
        .faq-item {
            margin-bottom: 20px;
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        
        .faq-question {
            font-weight: bold;
            margin-bottom: 10px;
            font-size: 1.1rem;
        }
        
        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 40px 0;
            text-align: center;
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1.2rem;
            }
            
            .benefit, .testimonial {
                flex: 0 0 100%;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="logo">Mulheres Empoderadas</div>
            <div class="tagline">Descubra o poder que há em você</div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Curso para Mulheres Empoderadas e Desejadas</h1>
            <p>Descubra os segredos para se tornar uma mulher confiante, realizada e irresistível em todas as áreas da sua vida</p>
            <a href="#pricing" class="cta-button">QUERO ME INSCREVER AGORA</a>
        </div>
    </section>

    <!-- Problem Section -->
    <section class="problem">
        <div class="container">
            <h2 class="section-title">Você se identifica com alguma dessas situações?</h2>
            <div class="problem-content">
                <div class="problem-text">
                    <ul>
                        <li>Se sente insegura em relacionamentos?</li>
                        <li>Tem dificuldade para se impor no trabalho ou na vida pessoal?</li>
                        <li>Sente que não está vivendo todo o seu potencial?</li>
                        <li>Deseja ser mais desejada e admirada?</li>
                        <li>Quer conquistar mais autoconfiança e autoestima?</li>
                        <li>Anseia por um relacionamento mais equilibrado e satisfatório?</li>
                    </ul>
                    <p>Se você respondeu "sim" para alguma dessas perguntas, saiba que não está sozinha. Milhares de mulheres enfrentam os mesmos desafios.</p>
                </div>
                <div class="problem-image">
                    <img src="https://images.unsplash.com/photo-1487412947147-5cebf100ffc2?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Mulher refletindo">
                </div>
            </div>
        </div>
    </section>

    <!-- Solution Section -->
    <section class="solution">
        <div class="container">
            <h2 class="section-title">A solução que você procurava</h2>
            <p style="text-align: center; max-width: 800px; margin: 0 auto 50px;">O curso "Mulheres Empoderadas e Desejadas" foi desenvolvido especialmente para ajudar mulheres como você a transformarem suas vidas, conquistando autoconfiança, poder pessoal e relacionamentos mais satisfatórios.</p>
            
            <div class="benefits">
                <div class="benefit">
                    <div class="benefit-icon">💪</div>
                    <h3>Autoconfiança</h3>
                    <p>Desenvolva uma autoestima inabalável e confiança para enfrentar qualquer desafio.</p>
                </div>
                <div class="benefit">
                    <div class="benefit-icon">❤️</div>
                    <h3>Relacionamentos</h3>
                    <p>Aprenda a construir relacionamentos saudáveis baseados no respeito mútuo.</p>
                </div>
                <div class="benefit">
                    <div class="benefit-icon">🌟</div>
                    <h3>Realização Pessoal</h3>
                    <p>Descubra seu propósito e viva uma vida com mais significado e felicidade.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Course Details -->
    <section class="course-details">
        <div class="container">
            <h2 class="section-title">O que você vai aprender no curso</h2>
            <div class="modules">
                <div class="module">
                    <h3 class="module-title">Módulo 1: Autoconhecimento e Autoestima</h3>
                    <p>Descubra quem você realmente é, seus valores, forças e talentos. Aprenda técnicas para desenvolver uma autoestima sólida.</p>
                </div>
                <div class="module">
                    <h3 class="module-title">Módulo 2: Comunicação Assertiva</h3>
                    <p>Aprenda a se comunicar com clareza, confiança e elegância, expressando suas necessidades sem agressividade ou passividade.</p>
                </div>
                <div class="module">
                    <h3 class="module-title">Módulo 3: Inteligência Emocional</h3>
                    <p>Domine suas emoções e desenvolva resiliência para lidar com os desafios da vida de forma equilibrada.</p>
                </div>
                <div class="module">
                    <h3 class="module-title">Módulo 4: Feminilidade e Sedução</h3>
                    <p>Redescubra sua feminilidade e aprenda a usar sua energia feminina para se tornar mais atraente e desejada.</p>
                </div>
                <div class="module">
                    <h3 class="module-title">Módulo 5: Relacionamentos Saudáveis</h3>
                    <p>Aprenda a construir relacionamentos baseados no respeito, admiração e cumplicidade.</p>
                </div>
                <div class="module">
                    <h3 class="module-title">Módulo 6: Realização Profissional</h3>
                    <p>Descubra como alinhar sua carreira com seus valores e propósito de vida.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="testimonials">
        <div class="container">
            <h2 class="section-title">O que nossas alunas dizem</h2>
            <div class="testimonial-cards">
                <div class="testimonial">
                    <div class="testimonial-text">
                        "Este curso mudou minha vida completamente. Eu era uma pessoa insegura e hoje me sinto capaz de conquistar qualquer coisa que desejar."
                    </div>
                    <div class="testimonial-author">- Mariana, 32 anos</div>
                </div>
                <div class="testimonial">
                    <div class="testimonial-text">
                        "Finalmente entendi o que significa ser uma mulher empoderada. Meu relacionamento melhorou 100% e minha autoestima está nas alturas!"
                    </div>
                    <div class="testimonial-author">- Carla, 28 anos</div>
                </div>
                <div class="testimonial">
                    <div class="testimonial-text">
                        "As técnicas de comunicação que aprendi no curso me ajudaram não só na vida pessoal, mas também a conseguir uma promoção no trabalho."
                    </div>
                    <div class="testimonial-author">- Juliana, 35 anos</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing -->
    <section class="pricing" id="pricing">
        <div class="container">
            <h2 class="section-title" style="color: white;">Invista no seu desenvolvimento</h2>
            <div class="pricing-card">
                <h3>Curso Completo</h3>
                <p>6 módulos transformadores + bônus exclusivos</p>
                <div class="price">R$ 497</div>
                <div class="original-price">de R$ 997</div>
                <div class="bonus">MATRICULE-SE HOJE E GANHE 2 BÔNUS EXCLUSIVOS</div>
                <ul style="text-align: left; margin: 20px 0;">
                    <li>Acesso vitalício a todas as aulas</li>
                    <li>Material complementar em PDF</li>
                    <li>Grupo exclusivo no WhatsApp</li>
                    <li>4 sessões de mentoria em grupo</li>
                    <li>Certificado de conclusão</li>
                </ul>
                <div class="guarantee">✅ Garantia de 7 dias: Se não ficar satisfeita, devolvemos 100% do seu investimento</div>
                <a href="#" class="cta-button">QUERO ME INSCREVER AGORA</a>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="faq">
        <div class="container">
            <h2 class="section-title">Perguntas Frequentes</h2>
            <div class="faq-item">
                <div class="faq-question">Por quanto tempo terei acesso ao curso?</div>
                <div class="faq-answer">O acesso é vitalício! Você poderá assistir às aulas quantas vezes quiser, quando e onde quiser.</div>
            </div>
            <div class="faq-item">
                <div class="faq-question">Como funciona a garantia?</div>
                <div class="faq-answer">Se em até 7 dias você achar que o curso não é para você, basta nos enviar um e-mail que devolveremos 100% do valor pago, sem burocracia.</div>
            </div>
            <div class="faq-item">
                <div class="faq-question">Quanto tempo leva para ver resultados?</div>
                <div class="faq-answer">Os resultados variam de pessoa para pessoa, mas a maioria de nossas alunas relata mudanças significativas já nas primeiras semanas.</div>
            </div>
            <div class="faq-item">
                <div class="faq-question">Preciso ter algum conhecimento prévio?</div>
                <div class="faq-answer">Não! O curso foi desenvolvido para mulheres de todos os níveis de conhecimento e experiência.</div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>Curso para Mulheres Empoderadas e Desejadas</p>
            <p>CNPJ: 12.345.678/0001-99</p>
            <p>Email: contato@mulheresempoderadas.com.br</p>
            <p>© 2023 Todos os direitos reservados</p>
        </div>
    </footer>
</body>
</html># DinheiroIA
