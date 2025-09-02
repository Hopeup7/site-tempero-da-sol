<!DOCTYPE html> <!-- Declara o tipo de documento, informando ao navegador que é HTML5 -->
<html lang="pt-BR"> <!-- Início do documento HTML, definindo o idioma principal como português do Brasil -->
<head> <!-- Cabeçalho do documento (metadados e configurações gerais) -->
    <meta charset="UTF-8"> <!-- Define a codificação de caracteres para UTF-8 (suporta acentos e caracteres especiais) -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Configura a responsividade para dispositivos móveis -->
    <meta name="description" content="Projeto Tempero da Sol - Sistema de reservas e cálculo de comida por peso com propaganda"> <!-- Descrição para SEO -->
    <title>Tempero da Sol</title> <!-- Título da página que aparece na aba do navegador -->
    <link rel="stylesheet" href="temp_front/temp.styles.css"> <!-- Importa o arquivo CSS para estilização -->
</head>
<body> <!-- Início do corpo da página (conteúdo visível) -->

    <!-- Banner -->
    <header id="banner"> <!-- Cabeçalho visual, normalmente usado para logo ou imagem de destaque -->
    </header>

    <!-- Seção Sobre -->
    <section id="sobre"> <!-- Seção apresentando informações sobre o site ou negócio -->
        <h1>Tempero da Sol</h1> <!-- Título principal -->
        <p><strong>O sabor de gerações que você merece!!!</strong></p> <!-- Texto destacado em negrito -->
    </section>

    <!-- Conteúdo Principal com layout flex -->
    <main class="layout-flex"> <!-- Conteúdo principal da página, com classe para layout em flexbox -->
        
        <!-- Coluna de Publicidade -->
        <aside id="publicidade" aria-label="Seção de anúncios publicitários"> <!-- Conteúdo secundário, ideal para anúncios, com acessibilidade -->
            <section class="secao-publicidade"> <!-- Agrupa toda a área de publicidades -->
                <h2 class="titulo-publicidade">📢 Publicidades</h2> <!-- Título da seção de anúncios -->

                <div class="container-publicidade"> <!-- Container flexível para agrupar os anúncios -->
                    
                    <!-- ANÚNCIO 1 -->
                    <div class="publicidade corte"> <!-- Bloco de anúncio com classe extra para estilo específico -->
                        <img src="temp_front/imagens/public_cortes.jpg" alt="Corte de cabelo Santana"> <!-- Imagem do anúncio com texto alternativo -->
                        <div class="mensagem"> <!-- Conteúdo textual do anúncio -->
                            <p><strong>Julio - O Natural dos Cortes de Cabelo</strong> 💥</p> <!-- Nome do anunciante -->
                            <h3><span class="destaque">Localização e Contato</span></h3> <!-- Subtítulo -->
                            <p>
                                Rua Alfredo Pujol, em frente ao Colégio Barão Homem de Mello<br> <!-- Endereço com quebra de linha -->
                                Santana, São Paulo – SP<br>
                                <strong>Instagram:</strong>  
                                <a href="https://www.instagram.com/hopeup47/" target="_blank" class="botao-instagram">📷 Siga-nos</a><br> <!-- Link para Instagram -->
                                <strong>WhatsApp:</strong> 
                                <a href="https://wa.me/5511953339198" target="_blank" class="botao-whatsapp">📲 Fale conosco</a> <!-- Link para WhatsApp -->
                            </p>
                        </div>
                    </div>

                    <!-- ANÚNCIO 2 -->
                    <div class="publicidade funilaria"> <!-- Segundo anúncio, com classe específica -->
                        <img src="temp_front/imagens/public_fun_dan.jpg" alt="Serviço de funilaria"> <!-- Imagem do anúncio -->
                        <div class="mensagem"> <!-- Texto do anúncio -->
                            <p><strong>Excelência em reparos automotivos na Zona Norte de SP</strong> 💥</p> <!-- Título -->
                            <h3><span class="destaque">Localização e Contato</span></h3>
                            <p>
                                Rua Padre João Gualberto, 440A – Imirim, São Paulo – SP<br>
                                <strong>Instagram:</strong>  
                                <a href="https://instagram.com/_OFICINA3D" target="_blank" class="botao-instagram">📷 Siga-nos</a><br>
                                <strong>WhatsApp:</strong> 
                                <a href="https://wa.me/5511974026145" target="_blank" class="botao-whatsapp">📲 Fale conosco</a>
                            </p>
                        </div>
                    </div>

                </div> <!-- Fim do container-publicidade -->
            </section>
        </aside>

        <!-- Coluna de Conteúdo -->
        <section id="conteudo"> <!-- Área principal de textos informativos -->
            <h2>Tempero da Sol</h2> <!-- Subtítulo -->
            <p>
                Há mais de 30 anos, o <strong>Tempero da Sol</strong> leva à mesa o sabor que nasceu no coração de Minas Gerais. 
                <strong>Solange</strong>, dona e cozinheira, aprendeu com sua mãe a arte da comida caseira, feita com carinho e atenção em cada detalhe. 
                Ao seu lado, sua filha — braço direito na cozinha — traz vasta experiência e dedicação, garantindo que cada prato seja um abraço em forma de sabor.
            </p>
            <p>
                No comando da churrasqueira, <strong>Vandro</strong> atua há mais de 10 anos como churrasqueiro, com um controle impecável sobre o preparo e a estocagem das carnes, seguindo as melhores práticas de higiene. 
                Seu profissionalismo é o reflexo de um gaúcho apaixonado pela arte do churrasco.
            </p>
            <p>
                A família se completa com o marido de Solange, que cuida da gestão com zelo e atenção, além de apoiar a esposa em todas as tarefas, inclusive na lavagem e organização dos produtos. 
                E também com <strong>Alex</strong>, que se doa 100% em todas as situações, trazendo maestria na confecção de gelatinas que encantam os clientes — clientes que são, sem dúvida, nota 10.
            </p>
            <p>
                No self-service, a churrascaria oferece cortes selecionados como alcatra, picanha, pernil, fraldinha, picanha ao alho, coraçãozinho, linguiça, medalhão de frango, coxa e sobrecoxa, e cupim. 
                Cada carne é temperada com cuidado especial, realçando o sabor e garantindo maciez. 
                <br>O carro-chefe é a marmita generosa de aproximadamente <strong>1,2 kg</strong>, perfeita para quem quer levar para casa o sabor irresistível do <strong>Tempero da Sol</strong>.
            </p>
        </section>

    </main> <!-- Fim do conteúdo principal -->

    <!-- Rodapé -->
    <footer> <!-- Rodapé da página -->
        <p>&copy; 2025 Tempero da Sol - Todos os direitos reservados</p>
        <p>&copy; Equipe Powered By HopeUp 7.DEV</p>
    </footer>

</body> <!-- Fim do corpo -->
</html> <!-- Fim do documento HTML -->

***

css

/* ======== Banner ======== */
#banner {
  height: 250px;
  background-image: url("imagens/ceu_restaurante.png"); /* Ajuste o caminho se necessário */
  background-position: center 25%;
  background-size: cover;
  background-repeat: no-repeat;
}

/* ======== Seção Sobre ======== */
#sobre {
  max-width: 900px;
  margin: 20px auto;
  text-align: center;
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.08);
}

/* ======== Layout Flex Principal ======== */
.layout-flex {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  max-width: 1100px;
  margin: 0 auto;
}

/* ======== Publicidades ======== */
#publicidade {
  flex: 1 1 300px;
}

.titulo-publicidade {
  text-align: center;
  font-size: 1.3rem;
  color: #ff9800;
  margin-bottom: 14px;
}

.container-publicidade {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.publicidade {
  background: #fff;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0,0,0,0.08);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.publicidade:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 14px rgba(0,0,0,0.12);
}

/* 🔹 Imagem menor, “digna” de publicidade */
.publicidade img {
  width: 100%;
  height: 140px;           /* Altura menor */
  object-fit: cover;
}

/* Mensagem */
.mensagem {
  padding: 12px;
  font-size: 0.95rem;
  color: #333;
}

.mensagem h3 {
  margin-top: 8px;
  font-size: 1rem;
}

.destaque {
  background-color: #ff9800;
  color: #fff;
  padding: 2px 6px;
  border-radius: 4px;
}

/* Botões */
.botao-whatsapp,
.botao-instagram {
  display: inline-block;
  margin-top: 6px;
  padding: 6px 10px;
  font-size: 0.85rem;
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  border-radius: 4px;
  transition: background-color 0.3s ease;
}

.botao-whatsapp { background-color: #25d366; }
.botao-whatsapp:hover { background-color: #1ebe5d; }

.botao-instagram { background-color: #e1306c; }
.botao-instagram:hover { background-color: #c72c61; }

/* ======== Conteúdo Principal ======== */
#conteudo {
  flex: 2 1 600px;
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.08);
}

#conteudo h2 {
  color: #b22222;
  margin-top: 0;
}

/* ======== Rodapé ======== */
footer {
  text-align: center;
  background: #333;
  color: #fff;
  padding: 15px 10px;
  font-size: 0.85rem;
  margin-top: 30px;
}

/* ======== Responsividade ======== */
@media (max-width: 768px) {
  .layout-flex {
    flex-direction: column;
  }
  #publicidade, #conteudo {
    flex: 1 1 100%;
  }
  .publicidade img {
    height: 160px; /* um pouco maior no mobile pra compensar largura */
  }
}
