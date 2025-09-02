/* ======== Banner ======== */
#banner {
  height: 250px; /* Altura fixa para o banner */
  background-image: url("imagens/ceu_restaurante.png"); /* Imagem de topo */
  background-position: center 25%; /* Centraliza verticalmente com leve deslocamento */
  background-size: cover; /* Preenche sem distorcer */
  background-repeat: no-repeat; /* Evita repetição */
}

/* ======== Seção Sobre ======== */
#sobre {
  max-width: 900px; /* Limita largura para melhor leitura */
  margin: 20px auto; /* Centraliza com espaçamento vertical */
  text-align: center; /* Centraliza texto */
  background: #fff; /* Fundo branco */
  padding: 20px; /* Espaço interno */
  border-radius: 8px; /* Bordas suaves */
  box-shadow: 0 4px 8px rgba(0,0,0,0.08); /* Sombra leve */
}

/* ======== Layout Flex Principal ======== */
.layout-flex {
  display: flex; /* Ativa flexbox */
  flex-wrap: wrap; /* Permite quebra de linha */
  gap: 20px; /* Espaço entre colunas */
  max-width: 1100px; /* Limita largura total */
  margin: 0 auto; /* Centraliza layout */
}

/* ======== Publicidades ======== */
#publicidade {
  flex: 1 1 300px; /* Flexível com base mínima de 300px */
}

.titulo-publicidade {
  text-align: center; /* Centraliza o texto horizontalmente */
  font-size: 1.3rem; /* Define o tamanho da fonte (1rem = tamanho base do documento) */
  color: #ff9800; /* Cor laranja vibrante para destaque */
  margin-bottom: 14px; /* Espaço abaixo do título para separar do conteúdo seguinte */
}

.container-publicidade {
  display: flex; /* Ativa o layout flexível para organizar os elementos lado a lado */
  flex-direction: row; /* Organiza os itens em linha (horizontalmente) */
  gap: 30px; /* Espaço entre cada item dentro do container */
}

.publicidade {
  background: #fff; /* Fundo branco para destacar o conteúdo */
  border-radius: 8px; /* Bordas arredondadas para um visual mais suave */
  overflow: hidden; /* Garante que conteúdo/imagens não ultrapassem as bordas arredondadas */
  box-shadow: 0 4px 10px rgba(0,0,0,0.08); /* Sombra leve para dar profundidade */
  transition: transform 0.2s ease, box-shadow 0.2s ease; /* Anima suavemente transformações e sombra */
}

.publicidade:hover {
  transform: translateY(-3px); /* Move o card levemente para cima ao passar o mouse */
  box-shadow: 0 6px 14px rgba(0,0,0,0.12); /* Intensifica a sombra no hover para efeito de destaque */
}

.publicidade img {
  width: 100%; /* Faz a imagem ocupar toda a largura do card */
  aspect-ratio: 16 / 13; /* Mantém proporção fixa da imagem */
  object-fit: cover; /* Corta a imagem para preencher o espaço sem distorcer */
  object-position: top center; /* Mantém o foco no topo central da imagem */
}

.mensagem {
  padding: 12px; /* Espaçamento interno para o texto não encostar nas bordas */
  font-size: 0.95rem; /* Tamanho de fonte levemente menor que o padrão */
  color: #333; /* Cor de texto cinza escuro para boa leitura */
}

.mensagem h3 {
  margin-top: 8px; /* Espaço acima do subtítulo */
  font-size: 1rem; /* Tamanho de fonte padrão para subtítulo */
}

.destaque {
  background-color: #ff9800; /* Fundo laranja para chamar atenção */
  color: #fff; /* Texto branco para contraste */
  padding: 2px 6px; /* Espaçamento interno pequeno para manter compacto */
  border-radius: 4px; /* Bordas levemente arredondadas */
}
@media (max-width: 768px) {
  .container-publicidade {
    flex-direction: column; /* Empilha os cards verticalmente no celular */
    gap: 20px; /* Reduz o espaço entre eles */
  }
}


/* ======== Botões de Ação ======== */
.botao-whatsapp,
.botao-instagram {
  display: inline-block; /* Faz o botão se comportar como elemento inline, mas permitindo definir largura/altura */
  margin-top: 6px; /* Espaço acima do botão para separá-lo de outros elementos */
  padding: 6px 10px; /* Espaçamento interno: 6px em cima/baixo e 10px nas laterais */
  font-size: 0.85rem; /* Tamanho da fonte levemente menor que o padrão */
  color: #fff; /* Texto branco para contraste com o fundo colorido */
  text-decoration: none; /* Remove o sublinhado padrão dos links */
  font-weight: bold; /* Deixa o texto em negrito para dar mais destaque */
  border-radius: 4px; /* Bordas levemente arredondadas para um visual mais amigável */
  transition: background-color 0.3s ease; /* Suaviza a mudança de cor no hover */
}

/* Botão do WhatsApp */
.botao-whatsapp { 
  background-color: #25d366; /* Verde oficial do WhatsApp */
}
.botao-whatsapp:hover { 
  background-color: #1ebe5d; /* Tom de verde mais escuro no hover para efeito visual */
}

/* Botão do Instagram */
.botao-instagram { 
  background-color: #e1306c; /* Rosa oficial do Instagram */
}
.botao-instagram:hover { 
  background-color: #c72c61; /* Tom de rosa mais escuro no hover para efeito visual */
}


/* ======== Estilo para Vídeos do Instagram ======== */
.buffet-section {
  display: flex; /* Organiza os elementos filhos (texto e vídeo) lado a lado em linha */
  flex-wrap: wrap; /* Permite que os elementos quebrem linha se o espaço horizontal for insuficiente */
  align-items: flex-start; /* Alinha os itens ao topo da seção, mantendo o texto e o vídeo nivelados */
  gap: 30px; /* Espaçamento entre os elementos filhos, tanto horizontal quanto vertical */
  margin-bottom: 40px; /* Espaço abaixo da seção para separar visualmente das próximas */
}

.buffet-text {
  flex: 1 1 60%; /* Define que o bloco de texto ocupa 60% da largura disponível, com flexibilidade para crescer ou encolher conforme necessário */
  min-width: 300px;
  margin-bottom: -10px; /* Ajuste fino para compensar espaçamento visual abaixo */
  
}

.buffet-img {
  flex: 1 1 40%; /* Ocupa 40% da largura disponível, complementando os 60% do texto ao lado */
  display: flex; /* Permite organizar os elementos internos (imagem + botão) em coluna */
  flex-direction: column; /* Empilha os elementos verticalmente: imagem em cima, botão embaixo */
  align-items: center; /* Centraliza horizontalmente os elementos dentro do contêiner */
  justify-content: flex-start; /* Alinha os elementos ao topo do contêiner */
  margin-top: -50px; /* Espaço acima da imagem para afastar do conteúdo anterior */
  margin-bottom: -10px; /* Ajuste fino para compensar espaçamento visual abaixo */
  min-width: 300px;
}


.buffet-img img {
  width: 100%; /* A imagem ocupa toda a largura do contêiner pai */
  height: auto; /* Altura fixa para manter consistência visual com os vídeos anteriores */
  object-fit: contain; /* A imagem preenche o espaço sem distorcer, cortando o excesso se necessário */
  object-position: center; /* Centraliza o foco da imagem dentro do espaço disponível */
  border-radius: 10px; /* Bordas arredondadas para um visual mais suave e moderno */
  box-shadow: 0 0 10px rgba(0,0,0,0.2); /* Sombra leve para destacar a imagem do fundo */
}
.botao-instagram {
  margin-top: 10px; /* Espaço acima do botão para separá-lo de outros elementos */
  padding: 10px 30px; /* Espaçamento interno: altura confortável e largura suficiente para manter o texto em uma linha */
  background-color: #E1306C; /* Cor oficial do Instagram para identidade visual */
  color: white; /* Texto branco para contraste com o fundo rosa */
  text-decoration: none; /* Remove o sublinhado padrão dos links */
  border-radius: 5px; /* Bordas arredondadas para um visual mais amigável */
  font-weight: bold; /* Texto em negrito para dar destaque */
  transition: background-color 0.3s ease; /* Suaviza a mudança de cor no hover */
  white-space: nowrap; /* Impede quebra de linha — mantém todo o texto em uma única linha */
  display: inline-block; /* Faz o botão respeitar o tamanho do conteúdo e permite aplicar padding */
}

.botao-instagram:hover {
  background-color: #C13584; /* Cor mais escura no hover para efeito visual */
}

/* ======== Faixa Divisória Tempero da Sol ======== */
.faixa-divisoria {
  width: 100%; /* Ocupa toda a largura disponível */
  min-height: 180px; /* Altura mínima para garantir presença visual */
  background-image: url("imagens/fundos_buffet_completo.JPG"); /* Imagem de fundo da faixa */
  background-size: cover; /* Faz a imagem cobrir toda a área, cortando se necessário */
  background-position: center; /* Centraliza a imagem no espaço */
  background-repeat: no-repeat; /* Evita repetição da imagem */
  margin: 40px 0; /* Espaço acima e abaixo da faixa */
  border-top: 4px solid #ffcc33; /* Linha superior dourada */
  border-bottom: 4px solid #ffcc33; /* Linha inferior dourada */
}

/* ======== Conteúdo Principal ======== */
#conteudo {
  flex: 2 1 600px; /* Flex-grow: 2 (cresce mais), flex-shrink: 1 (pode encolher), flex-basis: 600px (largura base) */
  background: #fff; /* Fundo branco para destacar o conteúdo */
  padding: 30px; /* Espaçamento interno para respiro do conteúdo */
  border-radius: 8px; /* Bordas arredondadas para suavizar o visual */
  box-shadow: 0 4px 8px rgba(0,0,0,0.08); /* Sombra leve para dar profundidade */
}

#conteudo h2 {
  color: #b22222; /* Vermelho escuro para destaque do título */
  margin-top: 0; /* Remove espaço extra acima do título */
}


/* ======== Rodapé ======== */
/* ======== Rodapé ======== */
footer {
  text-align: center; /* Centraliza todo o conteúdo do rodapé horizontalmente */
  background: #333; /* Fundo cinza-escuro para contraste e destaque */
  color: #fff; /* Texto branco para boa legibilidade sobre o fundo escuro */
  padding: 15px 10px; /* Espaçamento interno: 15px em cima/baixo e 10px nas laterais */
  font-size: 0.85rem; /* Texto levemente menor que o padrão para um visual mais discreto */
  margin-top: 30px; /* Espaço acima do rodapé para separá-lo do conteúdo anterior */
}


/* ======== Responsividade ======== */
@media (max-width: 768px) { 
  /* Aplica as regras abaixo apenas quando a largura da tela for de 768px ou menor 
     (tablets na vertical e celulares grandes) */

  .layout-flex {
    flex-direction: column; /* Muda o layout flexível para coluna, empilhando os elementos verticalmente */
  }

  #publicidade, #conteudo {
    flex: 1 1 100%; /* Faz cada um ocupar 100% da largura disponível e permitir ajuste de tamanho */
  }

  .publicidade img {
    height: 160px; /* Reduz a altura das imagens de publicidade para caber melhor em telas menores */
  }

  .faixa-divisoria {
    min-height: 120px; /* Reduz a altura mínima da faixa para economizar espaço */
    margin: 30px 0; /* Ajusta o espaçamento acima e abaixo da faixa */
    border-width: 3px; /* Deixa as bordas superior e inferior um pouco mais finas */
  }
}


/* ======== Imagem da Seção Experiência ======== */
.imagem-experiencia {
  width: 100%;
  height: 300px;
  object-fit: cover;
  object-position: 45% 70%;
}

/* ======= Container principal da publicidade final ======== */
.container-publicidade-final {
  display: flex; /* Define layout flexível para alinhar elementos filhos */
  justify-content: center; /* Centraliza horizontalmente o conteúdo dentro do container */
  width: 100%; /* Ocupa toda a largura disponível */
  margin-top: 20px; /* Espaço acima do container */
} 

/* ======== Bloco que envolve a propaganda ======== */
#propaganda-final {
  width: 100%; /* Ocupa toda a largura possível */
  max-width: 1100px; /* Limita a largura máxima para não ficar muito esticado em telas grandes */
  background-color: #f2f2f2; /* Fundo cinza claro */
}

/* ======== Estilo da publicidade em destaque ======== */
.publicidade.destaque-final {
  background: #fff; /* Fundo branco para destacar o conteúdo */
  border-radius: 8px; /* Cantos arredondados */
  overflow: hidden; /* Esconde qualquer conteúdo que ultrapasse os limites do bloco */
  box-shadow: 0 4px 10px rgba(0,0,0,0.08); /* Sombra suave para dar profundidade */
  transition: transform 0.2s ease, box-shadow 0.2s ease; /* Animação suave ao passar o mouse */
}

/* ======== Efeito ao passar o mouse ======== */
.publicidade.destaque-final:hover {
  transform: translateY(-3px); /* Move levemente o bloco para cima */
  box-shadow: 0 6px 14px rgba(0,0,0,0.12); /* Sombra mais intensa para destacar o hover */
}

/* ======== Imagem dentro da publicidade ======== */
.publicidade.destaque-final img {
  width: 100%; /* Imagem ocupa toda a largura do bloco */
  height: 540px; /* Altura fixa para manter proporção visual */
  object-fit: contain; /* Mantém a proporção da imagem sem cortar */
  object-position: center; /* Centraliza a imagem dentro do espaço */
}

/* ======== Texto da mensagem da publicidade ======== */
.publicidade.destaque-final .mensagem {
  padding: 12px; /* Espaço interno ao redor do texto */
  font-size: 0.95rem; /* Tamanho de fonte levemente menor que o padrão */
  color: #333; /* Cor do texto em cinza escuro para boa leitura */
}

/* ======== Título dentro da mensagem ======== */
.publicidade.destaque-final .mensagem h3 {
  margin-top: 8px; /* Espaço acima do título */
  font-size: 1rem; /* Tamanho de fonte do título */
}

/* ======== Responsividade para telas até 768px ======== */
@media (max-width: 768px) {
  #propaganda-final {
    flex: 1 1 100%; /* Faz o bloco ocupar 100% da largura disponível no layout flex */
  }

  .publicidade.destaque-final img {
    height: 160px; /* Reduz altura da imagem para caber melhor em telas menores */
  }
}


/* ======== Faixa Experiência Tempero ======== */
.experiencia-tempero1 {
  width: 100%; /* Ocupa toda a largura disponível */
  height: 380px; /* Altura fixa da faixa em telas grandes */
  object-fit: fill; /* Preenche todo o espaço, podendo distorcer a imagem */
  object-position: center; /* Centraliza o conteúdo da imagem dentro do espaço */
  margin: 40px 0; /* Espaço acima e abaixo da faixa */
  border-top: 4px solid #ffcc33; /* Borda superior amarela */
  border-bottom: 4px solid #ffcc33; /* Borda inferior amarela */
  box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* Sombra suave para dar profundidade */
  display: block; /* Garante que o elemento seja exibido como bloco */
}

/* ======== Responsividade para telas até 768px ======== */
@media (max-width: 768px) {
  .experiencia-tempero1 {
    height: 120px; /* Reduz altura para caber melhor em telas menores */
    margin: 30px 0; /* Reduz espaçamento vertical */
    border-width: 3px; /* Bordas mais finas */
  }
}

/* ======== Centralização e estilo do título H2 na seção Buffet ======== */
.centralização-de-h2-buffet h2 {
  font-family: 'Georgia', serif; /* Fonte serifada, elegante */
  font-size: 2.2em; /* Tamanho grande para destaque */
  color: #8B4513; /* Tom terroso, remete a comida caseira */
  margin-bottom: 20px; /* Espaço abaixo do título */
  text-align: center; /* Centraliza o texto */
}

/* ======== Centralização e estilo do título H2 na seção Linha Divisória ======== */
.centralizacao-h2-linha-divisoria h2 {
  font-family: 'Georgia', serif; /* Fonte serifada, elegante e clássica */
  font-size: 2.2em; /* Tamanho grande para destaque visual */
  color: #8B4513; /* Tom terroso, remete a comida caseira e aconchego */
  margin-bottom: 20px; /* Espaço abaixo do título para separar do conteúdo seguinte */
  text-align: center; /* Centraliza o texto horizontalmente */
}

/* ======== Centralização e estilo do subtítulo H3 na seção Buffet ======== */
.centralizacao-h3-buffet h3 {
  font-family: 'Georgia', serif; /* Mantém a mesma tipografia para consistência visual */
  font-size: 1.5em; /* Menor que o H2, mas ainda com destaque */
  margin-bottom: 20px; /* Espaço abaixo do subtítulo */
  text-align: center; /* Centraliza o texto */
}

/* ======== Centralização e estilo do título H2 na seção Marmitinha ======== */
.centralizacao_marmitinha h2 {
  font-family: 'Georgia', serif; /* Fonte serifada para manter a identidade visual */
  font-size: 2.2em; /* Mesmo tamanho do H2 da linha divisória para uniformidade */
  color: #8B4513; /* Mesmo tom terroso para coerência de paleta */
  margin-bottom: 20px; /* Espaço abaixo do título */
  text-align: center; /* Centraliza o texto */
}

/* ======== Centralização e estilo do título H2 na seção Marmitinha 2 ======== */
.centralizacao_marmitinha2 h2 {
  font-family: 'Georgia', serif; /* Fonte serifada */
  font-size: 2.2em; /* Tamanho grande */
  color: #8B4513; /* Tom terroso */
  margin-bottom: 20px; /* Espaço inferior */
  text-align: center; /* Centralização horizontal */
}


/* ======== Título principal ======== */
.titulo-principal h1 {
  font-family: 'Georgia', serif; /* Fonte serifada, elegante e clássica */
  font-size: 2.5em; /* Tamanho grande para destaque */
  color: #8B4513; /* Tom terroso, remete a comida caseira */
  margin-bottom: 20px; /* Espaço abaixo do título */
  text-align: center; /* Centraliza o texto */
}

/* ======== Container dos botões de contato ======== */
.botoes-contato {
  display: flex; /* Usa layout flexível */
  flex-direction: column; /* Organiza os botões em coluna (um abaixo do outro) */
  align-items: center; /* Centraliza horizontalmente os botões */
  gap: 15px; /* Espaço entre os botões */
  margin-top: 20px; /* Espaço acima do bloco de botões */
}

/* ======== Estilo dos links/botões ======== */
.botoes-contato a {
  display: inline-block; /* Permite definir largura e altura, mas ainda se comporta como texto */
  background-color: #d35400; /* Cor quente que remete à comida */
  color: white; /* Texto branco para contraste */
  text-decoration: none; /* Remove sublinhado padrão */
  font-weight: bold; /* Texto em negrito */
  padding: 15px 30px; /* Espaçamento interno (vertical e horizontal) */
  border-radius: 8px; /* Cantos arredondados */
  width: 400%; /* Muito maior que o normal — pode ser proposital para ocupar mais espaço */
  max-width: 600px; /* Limita a largura máxima */
  text-align: center; /* Centraliza o texto dentro do botão */
  transition: background-color 0.3s ease; /* Animação suave na mudança de cor */
}

/* ======== Efeito hover nos botões ======== */
.botoes-contato a:hover {
  background-color: #e67e22; /* Tom mais claro no hover */
}

/* ======== Rodapé ======== */
.footer {
  text-align: center; /* Centraliza o conteúdo do rodapé */
  padding: 20px; /* Espaçamento interno */
  background-color: #3e3d3d; /* Fundo cinza escuro */
  font-size: 14px; /* Texto menor */
  color: #eceef3; /* Texto em tom claro para contraste */
}

/* ======== Container "Powered by" ======== */
.powered-by {
  display: flex; /* Layout flexível */
  align-items: center; /* Alinha verticalmente ao centro */
  justify-content: center; /* Centraliza horizontalmente */
  gap: 10px; /* Espaço entre os elementos */
  margin-top: 10px; /* Espaço acima do bloco */
}

/* ======== Logo suave ======== */
.logo-suave {
  height: 24px; /* Altura fixa do logo */
  opacity: 0.6; /* Deixa o logo mais suave/menos chamativo */
  transition: opacity 0.3s ease; /* Transição suave ao mudar opacidade */
}

/* ======== Efeito hover no logo ======== */
.logo-suave:hover {
  opacity: 1; /* Destaca o logo ao passar o mouse */
}

/* ======== Imagem da publicidade com corte ======== */
.publicidade.corte img {
  width: 100%; /* Ocupa toda a largura disponível do container */
  max-width: 800px; /* Limita a largura máxima para não ficar exagerada em telas grandes */
  border-radius: 10px; /* Cantos arredondados */
  box-shadow: 0 0 10px rgba(0,0,0,0.2); /* Sombra suave ao redor da imagem */
  aspect-ratio: 16 / 25; /* Mantém proporção vertical mais alongada */
  object-fit: cover; /* Preenche o espaço cortando partes da imagem se necessário */
  object-position: top center; /* Foca no topo da imagem, centralizando horizontalmente */
}

/* ======== Responsividade até 768px ======== */
@media (max-width: 768px) {
  .publicidade {
    flex-direction: column-reverse; /* Inverte a ordem dos elementos dentro do container flex */
  }
}

/* ======== Responsividade até 1024px ======== */
@media (max-width: 1024px) {
  .layout-flex {
    flex-direction: column; /* Empilha os elementos verticalmente */
    padding: 0 20px; /* Adiciona espaçamento lateral */
  }

  .buffet-section {
    flex-direction: column; /* Empilha texto e imagem */
    gap: 20px; /* Espaço entre os elementos */
  }

  .buffet-text, .buffet-img {
    width: 100%; /* Ocupa toda a largura disponível */
    min-width: unset; /* Remove largura mínima definida anteriormente */
  }

  .publicidade img,
  .publicidade.destaque-final img {
    height: auto; /* Ajusta altura automaticamente para manter proporção */
    aspect-ratio: 16 / 9; /* Proporção mais horizontal para telas médias */
  }
}

/* ======== Responsividade até 600px (imagens) ======== */
@media (max-width: 600px) {
  .publicidade img,
  .publicidade.destaque-final img,
  .buffet-img img {
    aspect-ratio: auto; /* Remove proporção fixa */
    height: auto; /* Ajusta altura automaticamente */
    max-width: 100%; /* Garante que não ultrapasse a largura do container */
  }
}

/* ======== Responsividade até 600px (botões) ======== */
@media (max-width: 600px) {
  .botao-instagram,
  .botao-whatsapp,
  .botoes-contato a {
    padding: 12px 20px; /* Reduz espaçamento interno */
    font-size: 0.9rem; /* Fonte menor */
    width: 100%; /* Ocupa toda a largura disponível */
    max-width: 300px; /* Limita largura máxima */
  }

  .botoes-contato {
    gap: 10px; /* Espaço menor entre os botões */
  }
}

/* ======== Responsividade até 768px (faixas e banners) ======== */
@media (max-width: 768px) {
  .faixa-divisoria,
  .experiencia-tempero1 {
    height: 120px; /* Reduz altura */
    margin: 20px 0; /* Espaço vertical menor */
    border-width: 2px; /* Bordas mais finas */
  }
}

/* ======== Responsividade até 600px (títulos) ======== */
@media (max-width: 600px) {
  .titulo-principal h1,
  .centralizacao_marmitinha h2,
  .centralizacao-h2-linha-divisoria h2 {
    font-size: 1.8em; /* Reduz tamanho dos títulos principais */
  }

  .centralizacao-h3-buffet h3 {
    font-size: 1.2em; /* Reduz tamanho dos subtítulos */
  }
}

***
html:
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Projeto Tempero da Sol - Sistema de reservas e cálculo de comida por peso com propaganda">
    <title>Tempero da Sol</title>
    <link rel="stylesheet" href="temp_front/temp.styles.css">
</head>
<body>
    
    <div id="container-site"> <!-- Início do container-site -->
        <!-- Banner -->
        <header id="banner"></header>

        <main class="layout-flex">

            <!-- 1. SOBRE NÓS -->
            <section id="sobre">
                <div class="titulo-principal">
                    <h1>Tempero da Sol</h1>
                </div>

                <p><strong>O sabor de gerações que você merece!!!</strong></p>
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

            <!-- 2. PUBLICIDADES -->
            <div class="publicidade-container">
            <aside id="publicidade" aria-label="Seção de anúncios publicitários">
                <section class="secao-publicidade">
                    <h2 class="titulo-publicidade">📢 Publicidades</h2>
                    <div class="container-publicidade">
                        <!-- ANÚNCIO 1 -->
                        <div class="publicidade corte">
                            <img src="temp_front/imagens/corte_public.webp" alt="Corte de cabelo Santana">
                            <div class="mensagem">
                                <p><strong>Junior - O Natural dos Cortes de Cabelo</strong> 💥</p>
                                <h3><span class="destaque">Localização e Contato</span></h3>
                                <p>
                                    Rua Alfredo Pujol, em frente ao Colégio Barão Homem de Mello<br>
                                    Santana, São Paulo – SP<br>
                                    <strong>Instagram:</strong>  
                                    <a href="https://www.instagram.com/hopeup47/" target="_blank" class="botao-instagram">📷 Siga-nos</a><br>
                                    <strong>WhatsApp:</strong> 
                                    <a href="https://wa.me/5511953339198" target="_blank" class="botao-whatsapp">📲 Fale conosco</a>
                                </p>
                            </div>
                        </div>

                        <!-- ANÚNCIO 2 -->
                        <div class="publicidade funilaria">
                            <img src="temp_front/imagens/public_fun_dan.jpg" alt="Serviço de funilaria">
                            <div class="mensagem">
                                <p><strong>Excelência em reparos automotivos na Zona Norte de SP</strong> 💥</p>
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
                    </div>
                </section>
            </aside>
        </div>

            

    <!-- 3. LINHA DIVISÓRIA -->       
            <section id="experiencia-tempero">
                <div class="centralizacao-h2-linha-divisoria">
                    <h2>Sabores que contam histórias</h2>
                </div>
                
                <img class="imagem-experiencia" src="temp_front/imagens/div_buffet.JPG" alt="Serviço de Buffet Completo">
                

                

            <!-- 4. EXPERIÊNCIA TEMPERO -->
            <div class="linha-divisoria">
                <h2>Uma Experiência Que Vai Muito Além do Sabor</h2>
            </div>

                <article class="prato-quente">
                    <h3>Arroz à Grega & Feijão da Roça</h3>
                    <p>
                        No coração da cozinha, <strong>Solange</strong> transforma ingredientes simples em 
                        memórias inesquecíveis. O <em>arroz à grega</em>, soltinho e carregado de aromas, 
                        encontra o <em>feijão da roça</em>, encorpado e temperado com aquele toque mineiro 
                        que só quem nasceu no interior conhece. É comida de verdade, feita no fogo da dedicação 
                        e servida com o amor de quem cozinha para a família.
                    </p>
                </article>

                <article class="saladas">
                    <h3>Saladas Frescas & Criativas</h3>
                    <p>
                        Preparadas pela filha de Solange, cada salada é uma obra de arte da natureza: 
                        folhas crocantes, legumes coloridos e combinações que equilibram sabor e nutrição. 
                        Tudo lavado e higienizado com rigor, cortado na hora e temperado para realçar o frescor. 
                        Resultado? Saladas saudáveis, maravilhosas e suculentas, que alimentam o corpo e encantam o olhar.
                    </p>
                </article>

                <article class="churrasqueira">
                    <h3>Picanha no Ponto Perfeito</h3>
                    <p>
                        Na churrasqueira, <strong>Vandro</strong> exibe sua maestria com a <em>picanha</em>: 
                        dourada por fora, suculenta por dentro e servida no espeto profissional que desperta o apetite. 
                        Mais que sabor, a picanha traz benefícios como proteína de alta qualidade e minerais essenciais — 
                        e aqui, cada corte é manuseado com higiene impecável, do preparo ao prato. 
                        Uma experiência que eleva o churrasco à categoria de arte.
                    </p>
                </article>
            </section>
             <div class="container-publicidade-final">
            <aside id="propaganda-final" aria-label="Última propaganda">
            <section class="publicidade destaque-final">
                <img src="temp_front\imagens\temp_anuncie_aqui.PNG" alt="Anuncie Aqui">
                <div class="mensagem">
                <p><strong>Venha anunciar com a gente e coloque seu negócio em destaque.</strong> 💥</p>
                <h3><span class="destaque">Promoções Especiais</span></h3>
                <p>
                    Anunciamos com a atenção que seu negócio merece!<br>
                    <strong>Instagram:</strong>  
                    <a href="https://www.instagram.com/hopeup47/" target="_blank" class="botao-instagram">📷 Siga-nos</a><br>
                    <strong>WhatsApp:</strong> 
                    <a href="https://wa.me/5511953339198" target="_blank" class="botao-whatsapp">📲 Fale conosco</a>
                </p>
                </div>
            </section>
            </aside>
        </div>
        
        <section id="buffet-completo">
        
        
        <div class="centralização-de-h2-buffet">
        <h2><strong>Aqui no Tempero da Sol...</strong>
        </div>
        <div class="centralizacao-h3-buffet">
            <h3>...você Encontra em Nosso Delicioso Buffet...</h3>
        </div>
        
        <!-- Lista de Saladas -->
        <div class="buffet-flex">
        <section class="buffet-section">
            <div class="buffet-text">
            
            <h3>...🥗 Deliciosas e Nutritivas Saladas Comumente Servidas...</h3>
            
            <ul>
            <li>Alface Americana, Crespa e Roxa</li>
            <li>Rúcula e Agrião</li>
            <li>Tomate Comum e Cereja</li>
            <li>Cenoura Ralada</li>
            <li>Beterraba Crua e Cozida</li>
            <li>Repolho Branco e Roxo</li>
            <li>Milho Verde</li>
            <li>Ervilha</li>
            <li>Palmito</li>
            <li>Grão-de-bico</li>
            <li>Ovos de Codorna</li>
            <li>Maionese de Legumes</li>
            <li>Salpicão</li>
            <li>Molhos variados (rosé, iogurte, limão, mostarda e mel)</li>
            <li><strong>...haverá opções específicas para cada dia da semana...</strong></li>
            </ul>
            <h4>Saladas que são nutritivas e muito gostosaaas...Vem!!!...Vem!!!</h4>
            <h4>Vem nos visitar no Instagram!!!</h4>
            </div>
            <div class="buffet-img">
            <img src="temp_front\imagens\saladas_buffet.jpg" alt="Buffet de Saladas">
            <a href="https://www.instagram.com/temperodasol/" target="_blank" class="botao-instagram">                📷 Ver no Instagram
            </a>
            </div>

            </section>

        <!-- Seção 2: Pratos Quentes Comuns -->
            <section class="buffet-section">
            <div class="buffet-text">
            <h3>🍛... Em Nosso Buffet de Pratos Quentes há...</h3>
            
            <ul>
            <li>Arroz branco e à Grega, integral e Carreteiro</li>
            <li>Feijão carioca e preto</li>
            <li>Feijoada</li>
            <li>Farofa Caseira</li>
            <li>Macarrão ao alho e óleo</li>
            <li>Lasanha de Carne ou Frango ou ainda de Berinjela ou Abobrinha</li>
            <li>Purê de Batata</li>
            <li>Escondidinho de Carne Seca</li>
            <li>Legumes Refogados</li>
            <li>Frango com Quiabo</li>
            <li>Moqueca de Peixe</li>
            <li>Estrogonofe</li>
            <li>...e muito mais delícias...Vem!!!</li>
            <li><strong>...haverá opções específicas para cada dia da semana...</strong></li>
            </ul>
            <h4>hum...Este buffet é de dar água na boca...Vem!!!...Vem!!!</h4>
            <h4>Vem nos visitar no Instagram!!!</h4>
            </div>
            <div class="buffet-img">
            <img src="temp_front\imagens\buffet_p_quentes.jpg" alt="Buffet de Pratos Quentes">
            <a href="https://www.instagram.com/temperodasol/" target="_blank" class="botao-instagram">                📷 Ver no Instagram
            </a>
            </div>

            </section>


        <!-- Seção 3: Churrasco -->
            <section class="buffet-section">
            <div class="buffet-text">
            <h3>...🥩 Carnes Nobres e Paladares Únicos...</h3>
            
            <ul>
            <li>Picanha</li>
            <li>Alcatra</li>
            <li>Fraldinha</li>
            <li>Costela bovina</li>
            <li>Linguiça toscana e calabresa</li>
            <li>Coração de frango</li>
            <li>Medalhão de frango com bacon</li>
            <li>Coxa e sobrecoxa</li>
            <li>Carne de porco (pernil, costelinha)</li>
            <li>Peixe grelhado</li>
            <li>Espetinhos variados</li>
            <li><strong>...haverá opções específicas para cada dia da semana...</strong></li>
            </ul>
            <h4>Olha só que delícia...Vem!!!...Vem!!!</h4>
            <h4>Vem nos visitar no Instagram!!!</h4>
            </div>
            <div class="buffet-img">
            <img src="temp_front\imagens\img2_pic_buffet.webp" alt="Buffet de Saladas">
            <a href="https://www.instagram.com/temperodasol/" target="_blank" class="botao-instagram">                📷 Ver no Instagram
            </a>
        </div>

        </section>



            <!-- *** -->

        </div> <!-- Fim do buffet-flex -->

        <section>
        <div class="centralizacao_marmitinha">
            <h2>🔥 Do prato montado à marmita completa</h2>
        </div>
        <p>Seja no buffet com churrasco ou na marmita para viagem, o <strong>Tempero da Sol</strong> entrega sempre o mesmo compromisso: comida farta, sabor marcante e preço justo.</p>
        <p>Depois de se deliciar com nosso buffet por quilo ou aproveitar o self-service com churrasco, que tal levar um pouco desse sabor pra casa?</p>
        <p>Nossas marmitas são preparadas com os mesmos cortes nobres e acompanhamentos generosos — tudo com aquele tempero caseiro que conquista no primeiro garfo.</p>

        <div style="margin-top: 30px;">
        <section id="experiencia-tempero">
                <div class="centralizacao_marmitinha2">
                    <h2>👩‍🍳 Um recado da Sol pra você</h2>                    
                </div>
                <h3>Do prato montado à marmita completa</h3>
                <img class="experiencia-tempero1" src="temp_front/imagens/fundo_final.png" alt="Paisagem do Tempero da Sol">
        </section>
            
            <p><strong>Oi, sou a Sol — e é com muito carinho que preparo cada receita que sai da nossa cozinha. Aqui no Tempero da Sol, não tem segredo: é comida feita com alma, como se fosse pra minha própria família.</p>
            <p>Se você já passou por aqui e montou seu prato no buffet, sabe do que estou falando. E se ainda não experimentou nossas marmitas, deixa eu te contar: elas são pensadas pra matar a fome de verdade, sem miséria e com muito sabor.</p>
            <p>Não é só arroz e feijão — é aquele frango bem temperado, a linguiça crocante, a panceta que derrete na boca, e a picanha que faz qualquer dia parecer domingo. Tudo isso acompanhado de batata frita, farofa e macarrão, porque aqui a gente acredita que comida boa tem que ser completa.</p>
            <p>Então se hoje você não pode sentar na nossa mesa, leva um pedacinho dela com você. As marmitas estão sempre quentinhas, esperando por você com o mesmo cuidado que eu colocaria num prato pra minha família.</strong></p>
        </div>

        <section>
            <div class="centralizacao_marmitinha3">
                    <h2>🔥 Marmitas para Retirar</h2>
                </div>
            
            <p>Leve o sabor do Tempero da Sol para casa com nossas marmitas fartas e irresistíveis. Todas acompanham:</p>
            <ul>
            <li>Arroz</li>
            <li>Feijão</li>
            <li>Farofa</li>
            <li>Batata frita</li>
            <li>Macarrão</li>
            </ul>
            <p><strong>Peso mínimo garantido:</strong> 1,2 kg de refeição!</p>

            <h3>⭐🍖Opções e Preços:</h3>
            <ul>
            <li><strong>Marmita mista</strong> (picanha, alcatra, pernil, cupim, panceta, linguiça, frango): <span class="preco">R$ 30,00</span></li>
            <li><strong>Pernil acebolado:</strong> <span class="preco">R$ 20,00</span></li>
            <li><strong>Calabresa acebolada:</strong> <span class="preco">R$ 20,00</span></li>
            <li><strong>Frango e linguiça</strong> (2 frangos e 1 linguiça ou vice-versa): <span class="preco">R$ 20,00</span></li>
            <li><strong>Filé de frango</strong> (3 a 4 filés): <span class="preco">R$ 20,00</span></li>
            <li><strong>Frango à milanesa</strong> (3 a 4 filés): <span class="preco">R$ 20,00</span></li>
            </ul>

            <p><em>Preços sujeitos a alteração sem aviso prévio.</em></p>

            <section class="contato-tempero">
            <h2>❤️🍲 Peça com carinho, receba com sabor</h2>
            <p>
                <strong>Fale direto com a Sol pelo WhatsApp, escolha sua marmita de preferência, pague via Pix e retire no local.</strong>
                Simples, rápido e feito com afeto — como tudo que sai da nossa cozinha.
            </p>

            <div class="botoes-contato">
                <a href="https://wa.me/5511958040466" target="_blank" class="botao-whatsapp">
                📲 Pedir pelo WhatsApp
                </a>
                <a href="https://www.instagram.com/temperodasol/" target="_blank" class="botao-instagram">
                📷 Ver no Instagram
                </a>
            </div>
            </section>

            <p>Endereço: <strong>Rua Alfredo Pujol, 106 — Santana, Zona Norte de São Paulo</strong></p>
            <p>Telefone fixo: <strong>(11) 2367-8733</strong></p>
        </section>
        </section>
        
        </main>
       

    </div> <!-- Fim do container-site -->

    <!-- Rodapé -->
    <footer class="footer">
    <p>© 2025 Tempero da Sol - Todos os direitos reservados</p>
    <div class="powered-by">
        <img src="temp_front/imagens/icone_hopeup.png" alt="Logo HopeUp 7.DEV" class="logo-suave">
        <span>© Equipe Powered By HopeUp 7.DEV</span>
    </div>
    </footer>


</body>
</html>


