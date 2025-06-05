<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="HandheldFriendly" content="true">
    <meta name="MobileOptimized" content="width">
    <meta name="theme-color" content="#ff66b2">
    <meta name="format-detection" content="telephone=no">
    <title>Festa da Katharyna - Bar Pub Night Girl</title>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Dancing+Script:wght@700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            -webkit-tap-highlight-color: transparent;
            -webkit-text-size-adjust: none;
            text-size-adjust: none;
        }

        html {
            width: 100%;
            overflow-x: hidden;
        }

        body {
            font-family: 'Roboto', sans-serif;
            color: white;
            background: url('kathybebendo.jpeg') no-repeat center center fixed;
            background-size: cover;
            position: relative;
            min-height: 100vh;
            width: 100%;
            overflow-x: hidden;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
            line-height: 1.4;
        }

        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.6);
            z-index: -1;
        }

        .container {
            max-width: 100%;
            width: 100%;
            margin: 0 auto;
            padding: 10px;
            position: relative;
            z-index: 1;
        }

        header {
            text-align: center;
            padding: 15px 5px;
            border-bottom: 2px solid #ff66b2;
            margin-bottom: 15px;
            width: 100%;
        }

        h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 2rem;
            color: #ff66b2;
            text-shadow: 2px 2px 4px #000;
            margin-bottom: 5px;
            word-break: break-word;
            line-height: 1.2;
        }

        h2 {
            font-family: 'Bebas Neue', cursive;
            font-size: 1.5rem;
            color: white;
            text-shadow: 2px 2px 4px #000;
            margin-bottom: 5px;
            line-height: 1.2;
        }

        h3 {
            font-family: 'Bebas Neue', cursive;
            font-size: 1.3rem;
            color: #ff66b2;
            margin: 12px 0 5px;
            text-shadow: 1px 1px 2px #000;
            line-height: 1.2;
        }

        .section {
            background-color: rgba(0, 0, 0, 0.7);
            border: 1px solid #333;
            border-radius: 5px;
            padding: 12px;
            margin-bottom: 15px;
            width: 100%;
        }

        ul {
            list-style-type: none;
            padding-left: 15px;
        }

        li {
            margin-bottom: 8px;
            position: relative;
            padding-left: 20px;
            font-size: 0.95rem;
        }

        li:before {
            content: '🍹';
            position: absolute;
            left: 0;
            font-size: 0.8em;
        }

        .beer-info {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 12px 0;
            background-color: rgba(255, 255, 255, 0.1);
            padding: 10px;
            border-radius: 5px;
            gap: 10px;
            width: 100%;
        }

        .beer-info img {
            width: 100%;
            max-width: 120px;
            border-radius: 4px;
        }

        .beer-info div {
            width: 100%;
        }

        .whatsapp-btn {
            display: block;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            border-radius: 25px;
            font-weight: bold;
            margin: 10px auto;
            transition: all 0.3s;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            width: 100%;
            max-width: 280px;
            text-align: center;
        }

        .map-container {
            margin-top: 15px;
            height: 50vh;
            min-height: 200px;
            max-height: 300px;
            border-radius: 5px;
            overflow: hidden;
            box-shadow: 0 0 10px rgba(255, 102, 178, 0.5);
            width: 100%;
        }

        .map-container iframe {
            width: 100%;
            height: 100%;
            border: none;
        }

        .playlist {
            columns: 1;
            column-gap: 15px;
            font-size: 0.9rem;
        }

        .churrasco-img {
            width: 100%;
            max-height: 200px;
            object-fit: cover;
            border-radius: 5px;
            margin: 10px 0;
            box-shadow: 0 0 6px rgba(255, 102, 178, 0.5);
        }

        .balaosupresa-img {
            width: 100%;
            max-height: 200px;
            object-fit: cover;
            border-radius: 5px;
            margin: 10px 0;
            box-shadow: 0 0 6px rgba(255, 102, 178, 0.5);
        }

        footer {
            text-align: center;
            padding: 12px 5px;
            margin-top: 20px;
            border-top: 1px solid #ff66b2;
            font-size: 0.95rem;
            width: 100%;
        }

        .rsvp-form {
            margin-top: 12px;
            background: rgba(0, 0, 0, 0.6);
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #333;
            width: 100%;
        }

        .form-group {
            margin-bottom: 8px;
            width: 100%;
        }

        .form-group label {
            display: block;
            margin-bottom: 3px;
            font-weight: bold;
            font-size: 0.9rem;
        }

        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 8px;
            border-radius: 3px;
            border: none;
            background: rgba(255, 255, 255, 0.9);
            font-size: 0.9rem;
        }

        .form-group textarea {
            min-height: 60px;
            resize: vertical;
        }

        .submit-btn {
            background: #ff66b2;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 3px;
            font-weight: bold;
            width: 100%;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 1rem;
            margin-top: 5px;
        }

        .flashing {
            animation: flash 2s infinite;
            font-size: 0.9rem;
        }

        @keyframes flash {
            0% { opacity: 1; }
            50% { opacity: 0.5; }
            100% { opacity: 1; }
        }

        .emoji {
            font-size: 1rem;
            vertical-align: middle;
        }

        @media only screen and (max-width: 320px) {
            h1 {
                font-size: 1.5rem;
            }
            h2 {
                font-size: 1.3rem;
            }
            .container {
                padding: 8px;
            }
            .section {
                padding: 10px;
            }
        }

        @media only screen and (min-width: 600px) {
            .container {
                max-width: 600px;
                padding: 15px;
            }
            .playlist {
                columns: 2;
            }
            .beer-info {
                flex-direction: row;
            }
        }

        @supports (-webkit-touch-callout: none) {
            body {
                height: -webkit-fill-available;
            }
            .container {
                min-height: -webkit-fill-available;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>✨ Venha para a minha festa! ✨</h1>
            <h2>no Playground!</h2>
            <p class="flashing">Vai ser épico, só alegria e drinks!</p>
        </header>

        <div class="section">
            <h3>🍖 O QUE ROLA:</h3>
            <ul>
                <li><strong>CHURRASCO COMPARTILHADO</strong> - Tragam 500g de carne ou qualquer coisa de churrasco</li>
                <img src="churrasco.jpg" alt="Churrasco" class="churrasco-img"><br>                
                <li><strong>PETISCOS</strong> - Vai ter umas gostosuras pra acompanhar</li>
                <li><strong>PLAYLIST ANIMADA</strong> - Só sucessos pra agitar! Sugestões de música? Pode ser Pop, Rock, nacionais ou internacionais, ou o que desejar! Mande mensagem</li>
            </ul>
           
        </div>


 <div class="section">
            <h3>🍺 CHOPEIRA GRÁTIS!</h3>
            <div class="beer-info">
                <img src="Chopeira.png" alt="Bebidas">
                <div>
                    <p><strong>Vai ter Chopeira 0800! Então não precisa levar bebida, a não ser que você beba outra coisa!</strong></p> <p>Só tragam 500g de carne ou qualquer coisa de churrasco, que iremos colocar uma carninha.</p> <p><strong>Vai ter BEER PONG! - Preparem-se para a competição!</strong></p>
                </div>
            </div>
            <p><center>Se estiver apertado, não deixa de vir! O importante é a presença! <span class="emoji">😘</span></center></p>
        </div>


        

    

        <div class="section">
            <h3>Você pensou que ia faltar, né?</h3>
            <ul>
                <li><strong>BALÃO SUPRESA!</strong> - lembra aqueles de festa? Vai ter que estourar! 🥳 kkkkk</li>
                <img src="balaosurpresa4.png" alt="balaosurpresa" class="balaosupresa-img"><br>
                
                <div class="playlist">
                    <p><center>Venha curtir, sorrir!</center></p>
                </div>
            </ul>
        </div>


        <div class="section">
            <h3>👗 DRESS CODE:</h3>
            <ul>
                <li><strong>Seja você mesmo!</strong> Venha confortável e no seu estilo</li>
                <li><strong>Opcional:</strong> Se quiser arrasar, vai de look noturno!</li>
            </ul>
        </div>



 <div class="section">
            <h3>📅 QUANDO:</h3>
            <p><span class="emoji">🗓️</span> <strong>Sábado, 26 de julho</strong></p>
            <p><span class="emoji">⏰</span> <strong>A partir das 13h, rolando até às 21 horas </strong></p>
        </div>

        <div class="section">
            <h3>📍 ONDE VAI SER? EM COPACABANA!</h3>
            <p>Rua Santa Clara 431 - Copacabana, Rio de Janeiro</p>
            
            <div class="map-container">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3673.254216178014!2d-43.18668892432058!3d-22.97055504024793!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9bd544d245819d%3A0x5c35a3f5a5f6b5a4!2sRua%20Santa%20Clara%2C%20431%20-%20Copacabana%2C%20Rio%20de%20Janeiro%20-%20RJ!5e0!3m2!1spt-BR!2sbr!4v1620000000000!5m2!1spt-BR!2sbr" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
        
        

        <div class="section">
            <h3>📞 CONFIRMAÇÃO:</h3>
            <p>Vai ter que rolar confirmação, hein! Me avisa até 25 de julho!</p>
            <a href="https://wa.me/5521988457601?text=Eu%20vou%20na%20sua%20festa,%20Katharyna!" class="whatsapp-btn" target="_blank">
                <i class="fab fa-whatsapp"></i> Confirmar Presença
            </a>
            
            <div class="rsvp-form">
                <form id="confirmacaoForm">
                    <div class="form-group">
                        <label for="nome">Seu Nome:</label>
                        <input type="text" id="nome" name="nome" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="telefone">Telefone:</label>
                        <input type="tel" id="telefone" name="telefone" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="mensagem">Mensagem (opcional):</label>
                        <textarea id="mensagem" name="mensagem" placeholder="Ex: Vou levar carne, frango, linguiça! Vegano! Coloca a minha música! Posso levar amigo(a)? Ou: Não posso faltar!"></textarea>
                    </div>
                    
                    <button type="submit" class="submit-btn">ENVIAR CONFIRMAÇÃO</button>
                </form>
            </div>
        </div>






       

        <footer>
            <p class="flashing">💃 ÚLTIMA CHAMADA: Vamos pular!</p>
            <br>
            <br>
            <br>
            <br>
            <p class="text-center">Developed by <a href="https://www.instagram.com/andherssonkaethanno/" target="_blank">Andy</a></p>
        </footer>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const titles = document.querySelectorAll('h1, h2, h3');
            
            titles.forEach(title => {
                const text = title.textContent;
                title.textContent = '';
                
                let i = 0;
                const typingEffect = setInterval(() => {
                    if (i < text.length) {
                        title.textContent += text.charAt(i);
                        i++;
                    } else {
                        clearInterval(typingEffect);
                    }
                }, 100);
            });
            
            // Máscara para telefone
            const phoneInput = document.getElementById('telefone');
            phoneInput.addEventListener('input', function(e) {
                let numbers = this.value.replace(/\D/g, '');
                if (numbers.length > 11) numbers = numbers.substring(0, 11);
                
                let formatted = '';
                if (numbers.length > 0) {
                    formatted = '(' + numbers.substring(0, 2);
                }
                if (numbers.length > 2) {
                    formatted += ') ' + numbers.substring(2, 7);
                }
                if (numbers.length > 7) {
                    formatted += '-' + numbers.substring(7, 11);
                }
                
                this.value = formatted;
            });

            // Formulário de confirmação
            document.getElementById('confirmacaoForm').addEventListener('submit', function(e) {
                e.preventDefault();
                
                const nome = document.getElementById('nome').value.trim();
                const telefone = document.getElementById('telefone').value.trim();
                const mensagem = document.getElementById('mensagem').value.trim();
                
                // Validação básica
                if (!nome || !telefone) {
                    alert('Por favor, preencha seu nome e telefone!');
                    return;
                }
                
                // Número formatado corretamente (sem caracteres especiais)
                const numeroWhatsApp = '5521988457601';
                
                // Construção da mensagem
                let textoWhatsApp = `*Confirmação para a festa da Katharyna!*%0A%0A`;
                textoWhatsApp += `*Nome:* ${encodeURIComponent(nome)}%0A`;
                textoWhatsApp += `*Telefone:* ${encodeURIComponent(telefone)}%0A`;
                
                if (mensagem) {
                    textoWhatsApp += `*Mensagem:* ${encodeURIComponent(mensagem)}%0A`;
                }
                
                // Abrir WhatsApp
                window.open(`https://wa.me/${numeroWhatsApp}?text=${textoWhatsApp}`, '_blank');
                
                // Limpar formulário
                this.reset();
            });
        });
    </script>
</body>
</html>
