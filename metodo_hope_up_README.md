Prova Teórica – Tópico 3 (Hope Up 7)

A seguir, 30 perguntas misturando múltipla escolha, verdadeiro/falso, dissertativas e interpretação de código sobre o HTML e CSS do site Tempero da Sol.

(Múltipla Escolha) Qual a função da tag <meta name="viewport" content="width=device-width, initial-scale=1.0">? 
a) Definir a codificação de caracteres 
b) Forçar carregamento de CSS externo 
►c) Ajustar escala e largura em dispositivos móveis 
d) Inserir descrição para SEO

(Verdadeiro/Falso) A declaração <!DOCTYPE html> é opcional em HTML5.
►F

(Dissertativa) Explique o conceito de semântica em HTML e cite três tags semânticas empregadas no projeto Tempero da Sol.
►o conceito de semântica se dá por ordem em hierarquia.
  ∟<head><body><main>

(Interpretação de Código) Dado o trecho abaixo, descreva o efeito de display: flex; flex-wrap: wrap; nos elementos filhos de .layout-flex.

css
.layout-flex {
  display: flex;
  flex-wrap: wrap;
}
►eles herdarão flexbox com quebra de linha.

(Múltipla Escolha) Qual propriedade CSS define proporção fixa para uma imagem dentro de um card? 
a) object-fit: contain; 
b) aspect-ratio: 16 / 13; 
c) background-size: cover; 
d) flex: 1 1 300px;
►esta eu não sei.

(Verdadeiro/Falso) O atributo alt de <img> é dispensável para SEO e acessibilidade.
►V

(Dissertativa) Compare o uso de <section> e <div> em termos de significado semântico e propósito.
►<section>
   ∟ usado para agrupamento tematica do conteudo principal("sobre nós""Serviços""contatos")

►<div>
   ∟ usado para agrupamento generico onde pode ser relacionado ao conteudo ou não.

(Interpretação de Código) Explique o que faz este seletor e como afeta a usabilidade:

css
.publicidade:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 14px rgba(0,0,0,0.12);
}
►estas propriedades css fazem com que a classe referenciada via classe recebe uma sombra(hover), transform: translateY(-3px); eu não sei o que faz; box-shadow: 0 6px 14px rgba(0,0,0,0.12); cria-se uma caixa sombreada

(Múltipla Escolha) Qual tag descreve conteúdo independente que pode ser redistribuído ou reutilizado (ex: um card de prato)? 
a) <section> 
►b) <article> 
c) <aside> 
d) <div>

(Verdadeiro/Falso) O Flexbox é mais indicado para layouts bidimensionais (linhas e colunas simultâneas).
►F

(Dissertativa) Descreva como aplicar uma media query para telas até 600px e por que isso é fundamental em uma abordagem mobile-first.
►aplico uma media query assim:
<strong>vou tentar<strong>:

.tela {
    display: flex;
}
@media {
    .tela{
        display: 600px;
    }
}


(Interpretação de Código) Qual o propósito de background-position: center 25%; em #banner?
►em #banner este: background-position: center 25%; faz com que do centro p o alto seja elevado 25% p cima.

(Múltipla Escolha) Para que serve object-fit: cover; em imagens de publicidade? 
►a) Ajusta a imagem ao container, mantendo proporção e cortando as bordas 
b) Faz a imagem ocupar toda a largura sem preservar proporção 
c) Posiciona a imagem no topo esquerdo 
d) Reduz o tamanho do arquivo da imagem

(Verdadeiro/Falso) O atributo aria-label substitui qualquer texto visível e remove a necessidade de legenda.
►F

(Dissertativa) Justifique a escolha de IDs como #sobre e classes como .layout-flex para aplicar CSS de forma clara e escalável.
►em #IDs layput-flex aplicarão propriedades especificas neste id, em .classes layout-fles aplicará para multiplas classes pre-determinadas por mim.

(Interpretação de Código) Por que o link para WhatsApp usa https://wa.me/55… em vez de https://api.whatsapp.com/send?phone=55…?
►se não me engano: .../wa.me/... é a url do whtsapp.

(Múltipla Escolha) Qual elemento HTML é apropriado para agrupar a navegação ou widgets laterais? 
a) <header> 
b) <main> 
►c) <aside> 
d) <footer>

(Verdadeiro/Falso) É recomendável envolver todo o conteúdo HTML apenas em <div> para facilitar o CSS.
►F

(Dissertativa) Explique o papel da tag <main> e como ela contribui para a acessibilidade.
► <main> é a tag responsavel por todo o conteudo essencial e central do site.

(Interpretação de Código) O que acontece se remover max-width: 1100px; da regra .layout-flex?
►eu perco o limite de segurança de largura que é até 1100px;

(Múltipla Escolha) Qual propriedade CSS controla o espaçamento interno de um elemento? 
a) margin 
►b) padding 
c) gap 
d) border-radius

(Verdadeiro/Falso) O seletor footer { background: #333; } aplica estilo a qualquer elemento <footer> presente na página.
►V

(Dissertativa) Descreva como o atributo lang="pt-BR" no elemento <html> impacta mecanismos de busca e tecnologias assistivas.
►o atributo lang="pt-BR" no elemento <html> é determinate para navegadores dizendo explicitamente que este documento esta redigido sobre as normas do português do Brasil.

(Interpretação de Código) Identifique o objetivo desta media query e exemplifique uma regra aplicada dentro dela:

css
@media (max-width: 768px) {
  .layout-flex { flex-direction: column; }
}
► a regra identificada foi o valor: column, que é recomendado e considerado uma boa pratica para mobile-first.

(Múltipla Escolha) Qual display cria um contêiner bidimensional de linhas e colunas? 
a) display: block; 
b) display: inline-block; 
c) display: flex; 
►d) display: grid;

***só até aqui por enquanto, depois do trampo, contiunuo.15:39-19/09/2025.

***continuação 10:09-20/09/2025 * Deus é Tudo.Me ajudde Deus neste questionário.

(Verdadeiro/Falso) <span> e <div> têm o mesmo comportamento semântico.
►F
 ∟ <span> elemento inline para estilização de blocos individuais.
 ∟ <div> agrupamento genérico de conteúdo, onde dependendo de onde a <div> estar o que lhe esta indentado é referente a ela e o mesmo vale para ela, e psso ter <div> com <span>, mas não o contrário.

(Dissertativa) Defina o propósito da tag <header> e como ela foi usada no site Tempero da Sol.
► <header>
    ∟aplica o foco n aimagem de topo de site podendo ser um icone, um aimagem ou um logotipo e recomendado que seja feito via ID pelo CSS.
    <head>
    ∟ Seu propósito é conter dados nos bastidores que são essenciais tais como viewport para mobile-firs, charset para codificação correta, titúlo do navegador que posso deixar a meu bel querer, referencia, ou melhor, o contexto e conceito de ponteiro para o CSS pode certamente ser aplicado ao que link rel... href faz

(Interpretação de Código) Explique o efeito visual de border-radius: 8px; em .publicidade.
►não sei, me explique por favor.

(Múltipla Escolha) O que faz object-position: top center; em uma imagem? 
►a) Posiciona a imagem no meio horizontal e topo vertical 
b) Faz a imagem aparecer em segundo plano 
c) Ajusta a escala da imagem 
d) Remove o padding da imagem

(Dissertativa) Avalie como a combinação de Flexbox, Grid e media queries garante a responsividade do site e proponha uma melhoria adicional.
►Agora qeu estou conhecendo CSS e por gostar de artes abstratas, sinto que vou me dar bem com sites totalmente hogeneos em flexbox com grid e focado em mobile-first, e também em telas dobraveis como aquele cel que dobram os tradicionais, e telas curvadas e telas de pc gamer...sinto que vou me dar bem com css, mas vou digeri-lo aos opucos saborendo, pois é bem rico em propriedades, valores, parametros e leva tempo, mas com base solida e criatividade dá para se criar ótimos projetos, que vou explorar, alias, copilot, o que da para se fazer aprincipio com html e css em todas as frentes possívis?

Como fui?
dados complexos em probabilidades sobre mim relacionado à:
 ∟compreensão
 ∟interpretação
 ∟acertos
 ∟erros
 ∟estatiticas
 ∟o que vc sugere aqui neste ultimo topico, copilot?

Preparado para o Tópico 3: aplicação prática em código. Em seguida, simularemos respostas e correções em tempo real!





****************************************************************************




***2º parte do questinário do html e css aplicado no site tempero da sol***

Prova Teórica – Tópico 3 (Hope Up 7)

A seguir, mais 30 perguntas envolvendo teoria, interpretação e aplicação prática em código sobre o HTML e CSS do site Tempero da Sol.

1)(Múltipla Escolha) Qual seletor em CSS aplica estilos somente ao elemento <footer> com classe .footer? 
►a) footer.footer { … } 
    ∟ mas gostaria de saber pk no elemento footer quando vou aplia estilos nele via css, o vocabulo footer vai sem nada e depois  a classe?
b) .footer footer { … } 
c) #footer .footer { … } 
d) footer #footer { … }

2)(Verdadeiro/Falso) O Flexbox sozinho pode posicionar itens em linhas e colunas simultaneamente sem Grid.
► F
  ∟ esta é a função de Grid, tópico qu estudaremos no próximo projeto: CSS Grid

3)(Dissertativa) Explique o propósito de usar gap em um container Flexbox e dê um exemplo prático com .layout-flex.
► o propósito de gap é considerado uma boa prática ao usar gap em vez de margin para espaçamento interno de elementos.

.classe_exemplo{
  display-flex: flex
}
.classe_exemplo{
  flex: gap; \*aqui eu reduzo o espaçamento interno dos elemntos*\
}

4)(Interpretação de Código) Dado:

css
.buffet-img img {
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
}

Descreva o efeito visual resultante.
► nesta classe buffet-img em img especificadamente vou aplicar bordas em 10px;(quanto seria isso? me fale so pixels) quebrando suas adjacências pontiagudas em as arredondando suavemente em 10px; e vou aplicar um aleve sombra de meio preta.

5)(Múltipla Escolha) Para criar um overlay escuro sobre o banner usando pseudo-elemento, qual regra adicionaria ao #banner? 

a) #banner::before {
   content:""; position:absolute; inset:0; background:rgba(0,0,0,0.5); 
   } 

b) #banner:after {
   filter:brightness(50%); 
   } 

c) #banner {
   opacity:0.5; 
   } 

d) #banner overlay {
   background:black; 
   }

   ► não vou meter o loko, esta eu não sei, mas quero saber.

6)(Verdadeiro/Falso) Variáveis CSS (custom properties) podem ser definidas em :root para uso global.
►CSS tem variáveis? 
  ∟ me fale mais sobre isso...

7)(Dissertativa) Descreva como usar clamp() para criar uma tipografia fluida no <h1> principal.
► o clamp() pelo pouco que vi esta relacionado com letras em seus diversos tipos para que dependendo da responsividade, se adapta a ela de forma suave e harmónica.

8)(Interpretação de Código) Qual o propósito de

css
transition: transform 0.2s ease, box-shadow 0.2s ease;
em .publicidade?

► sei que haverá deslocamento suave em segundos feitos através do transition, mas o que é esse 'ease'?


9)(Múltipla Escolha) Qual propriedade controla a ordem dos itens Flex sem alterar a marcação HTML? 
a) z-index 
b) order 
►c) flex-basis 
  ∟flex-basis mantém padronização.
d) justify-content

10)(Verdadeiro/Falso) O atributo loading="lazy" em <img> melhora performance ao carregar imagens fora da tela.
► V
  ∟e é considerado uma boa prática, pois espera o navegador carregar a página, para então carregar a imagem de forma preguiçosa...suavinho...

11)(Dissertativa) Explique como aria-label e role="navigation" juntos aprimoram acessibilidade de menus.
► Sei que aria-label melhora usabilidade, mas gostaria de saber como? e acredito que a classe role="navigation" em combinação com aria label faz com que determ,inado bloco que possivelmente conmtenha um menu ou item parecido, tenha um scroll própio.

12)(Interpretação de Código) Analise:

html
<a href="#" role="button" class="botao-whatsapp">📲 WhatsApp</a>
Por que role="button" pode ser útil?

►não sei, mas vamos usar no próximo projeto. mas já me adiante do que este novo elemento html faz....

13)(Múltipla Escolha) Para centralizar horizontal e verticalmente um item Flex, usa-se: 
►a) align-items: center; justify-content: center; 
    ∟ estamos nos refereindo a itens, não textos, então align-items: center; centraliza e justify-content: center; foca no centro.
b) text-align: center; vertical-align: middle;
c) margin: auto; 
d) display: grid; place-items: center;

14)(Verdadeiro/Falso) object-fit: contain; sempre preenche completamente tanto largura quanto altura do contêiner.
► F
  ∟ object-fit: contain; faz com que de forma suave seja recortada as bordas.
  ∟ object-fit: fill; é 'faz sempre preenche completamente tanto largura quanto altura do contêiner.'

15)(Dissertativa) Como você implementaria um grid de 3 colunas para as seções de publicidade em telas grandes?
► Grid usaremos no próximo projeto(e será um blog de um advogado e dará para usarmos CSS Grid?)

16)(Interpretação de Código) O que faz esta media query?

css
@media (prefers-reduced-motion: reduce) {
  * { transition: none !important; animation: none !important; }
}
► Sei somente que há uma regra absoluta proveniente de '!important' e que será aplicada em algum dispositivo específico.

17)(Múltipla Escolha) Qual unidade relative ao font-size do elemento atual? a) rem 
   ∟ esta é a propriedade par controle de altura de fonte. mas as demais seriam para?
b) em 
c) vh 
d) px

18)(Verdadeiro/Falso) Um <div> com display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); cria colunas flexíveis.
► cria? não sei... me fale mais sobre isso.

19)(Dissertativa) Descreva como usar um SVG inline para criar um ícone de localização ao lado de “Rua Alfredo Pujol” no rodapé.
►interessante, vamos aplicar no proximo projeto, e quando aprenderei e me dedicarei a entender e solidificar este conhecimento que esta já pré-estabelecido se Deus permitir.

20)(Interpretação de Código) Qual resultado de:

css
.titulo-principal h1 { 
  text-shadow: 2px 2px 4px rgba(0,0,0,0.3); 
  }

  ► o texto contido no <h1> principal e único por página, o que é recomendado super boa prática, receberá uma sombra, que visualmente vou colocar no proximo projeto.

21)(Múltipla Escolha) Para forçar que um link abra em nova aba sem causar vulnerabilidade, qual atributo adicional usar? 
a) rel="noopener noreferrer" 
b) target="_self" 
   ∟ este foi um 'chute irresistível'...-Papai do Céu me ensine...
c) download 
d) hrefLang

22)(Verdadeiro/Falso) box-sizing: border-box; faz com que padding e border sejam incluídos na largura total do elemento.
► V
  ∟ mas por quê?(e este por quê com acnto em fim de frase está correto, não é?)

23)(Dissertativa) Explique a diferença entre padding e margin e cite um uso para cada no Tempero da Sol.
► padding espaçamento externo dentro de um container flex, e margin espaçamento interno e não sei mais... 

24)(Interpretação de Código) No CSS:

css
.buffet-section { flex-direction: column; }
Em qual situação isso deve entrar?
►my brother, copilot, em '@mediaqueries'.

25)(Múltipla Escolha) Qual propriedade ajusta a cor de fundo de todo o <body>? 
a) body bg-color 
b) body { background-color: … }
   ∟está é a prppriedade correta que aplica cor da todo o fundo do <body>
c) :root { bg: … } 
d) * { background: … }

26)(Verdadeiro/Falso) O seletor .container-publicidade > .publicidade seleciona todos os descendentes de qualquer nível.
► então os parênteses angulares usados como símbolos matemáticos em CSS podem especificar filhos que podem herdar?

27)(Dissertativa) Como você documentaria o propósito de cada classe em um arquivo CSS para facilitar manutenção?
► cada classe em um arquivo css é útil para customização de múltiplos elemntos simultaneamente.

28(Interpretação de Código) Para criar um layout de 2 colunas que vire 1 coluna abaixo de 500px, escreva a media query correta.
►Vamos estudas display: grid; no próximo projeto.

29)(Múltipla Escolha) Qual atributo HTML marca o idioma principal do documento? 
a) <html lang="en"> 
b) <meta charset="UTF-8"> 
c) <head lang="pt"> 
d) <body lang="pt-BR">
     ∟ esat é o atributo, tag html que define explicitamente o idioma deste arquivo html. 

30)(Dissertativa) Proponha uma abordagem de teste unitário ou de integração para validar se o grid de pratos no buffet rende 100% de cobertura de largura sem quebrar itens.
► Vamos estudas display: grid; no próximo projeto, onde te pergunto: Daria aplicarmos css grid em blog?
  ∟ ou ainda mais especificamente, qual o conceito de blog e posso criá-lo a principio somente com html e css?

Bora colocar as mãos no código assim que chegar no seu ritmo! 🚀💻




****************************************************************************



***3º parte do questinário do html e css aplicado no site tempero da sol***

***🧪 Prova Teórica – Tópico 3 (Tempero da Sol)

Múltipla Escolha

1)Qual elemento semântico foi usado para representar o banner principal do site? 
a) <main>
    ∟ Todo o conteúdo principal do site.

b) <section>
    ∟Recomendado para agrupamento temático intrinsecamente ligado ao conteudo principal do site

►c) <header> 
     ∟o elemento, tag <header>, é responsável para colocar o banner principal do site.

d) <div>
    ∟ recomendado para agrupamento generico, podendo ser utilizado vinculado ao tema central ou independente.

2)O que faz a propriedade object-fit: cover; aplicada às imagens de publicidade? 
a) Estica a imagem para caber no espaço 
►b) Corta a imagem para preencher sem distorcer 
    ∟object-fit: cover;

c) Centraliza a imagem verticalmente 
d) Aplica sombra à imagem

3)Qual seletor CSS define espaçamento entre elementos em um layout flexível? 
a) margin 
b) padding 
►c) gap
    ∟recomendado para espaçamento entre elementos em um layoout flexível e considerado uma boa prática usá-lo em vez de margin que é imprevisível.

d) border-spacing

4)Qual tag representa conteúdo independente e reutilizável, como os cards de publicidade? 
a) <section> 
b) <article> 
c) <aside>
   ∟ a tag <aside> é de conteúdo independente e pode ser reutilizável(mas reutilizável como?)
d) <div>

5)Qual propriedade foi usada para suavizar a transição de sombra e movimento nos cards? 
a) animation 
b) transition 
c) transform 
►d) opacity
    ∟ este  foi um chute.

6)Qual atributo ARIA foi usado para melhorar a acessibilidade da seção de anúncios? 
a) aria-hidden 
►b) aria-label
    ∟ foi este e pk este e não os demais que estão nas opções desta pergunta?
c) aria-role 
d) aria-expanded

7)Qual unidade de medida foi usada para limitar a largura da seção “Sobre”? a) vh 
b) em 
c) px 
d) rem
► não sei, e gostaria de saber mais sobre isso.

8)Qual propriedade CSS foi usada para centralizar o conteúdo horizontalmente no rodapé? 
a) justify-content: center 
b) text-align: center 
►c) align-items: center 
    ∟ foi a propriedade css: align-items: center; que alinha os itens e recebe como valor o lainhar no centro.

d) margin: auto

9)O que faz flex: 1 1 300px aplicado em #publicidade? 
a) Define altura mínima 
►b) Define largura base e flexibilidade 
    ∟ flex: 1 1 300px; faz com que encolha, cresça e não ultrapasse 300px.

c) Aplica espaçamento interno 
d) Remove bordas

10)Qual tag foi usada para agrupar os botões de contato no final da página? a) <nav> 
b) <aside> 
c) <div>
    ∟ a tag <div> que é para situações como estas: agrupamneto de conteúdo genérico.
d) <footer>


Verdadeiro ou Falso

11)O seletor .layout-flex usa flex-wrap: wrap para permitir quebra de linha. 
► V
  ∟ a propriedade wrap é sinomimo de quebra de linha, e quandoda-mo-lo como valor ao flex-wrap: wrap; é pk vamos permitir quebra de linha no elemento .layout-flex(que aqui seria um elemento pai ou filho?) 

12)O atributo alt nas imagens é ignorado em termos de acessibilidade. 
► F
  ∟ O atributo alt é considerado um aboa prática e fortemente recomendado para acessibilidade como texto alternativo.

13)O CSS define box-shadow nos cards de publicidade para dar profundidade visual. 
► V
  ∟ o CSS define o box-shadow para que ao se aplicar sombra, criamos perpsctiva de otica visual e numa imagem em 1D(tela) podemos ver em 3D(box-shadow)

14)O seletor @media (max-width: 768px) ajusta o layout para telas pequenas. ► V
  ∟ embora não saiba precisamente sua sintaxe, posso afirmar que quando colocamos entre parênteses o @media (max-width: 768px) dizemos que o que será aplicado pelas propriedades css em dispositivos de até 768px(equivale atablets?) serão especias para o este layout especifíco.

15)O elemento <aside> foi usado incorretamente para conteúdo principal. 
► F
  ∟ ele nem foi usado para conteúdo principal, ele é recomendado para contexto isolado, como publicidades, anuncios, e afins.

16)O seletor .publicidade:hover aplica transform: translateY(-3px) para mover o card para baixo. 
► V
  ∟ isto está correto, pois o transform: translateY(-3px); gera deslocamento de card.

17)O seletor .buffet-section usa display: grid para organizar os elementos. ► F
  ∟ usamos o display: flex, pois precisávamos de layout flexível e unidimensional, ou seja em linhas.

18)O botão do WhatsApp usa a cor oficial da marca como fundo. 
►V 

19)O seletor .botao-instagram:hover muda a cor do botão para um tom mais escuro. 
► V
  ∟ .botao-instagram:hover esta referencia em css faz com que apliquemos cor numa cor ja existente que aparece somente quano movemos ou clicamos num determinado elemento.

20)A imagem do banner usa background-position: center 25% para alinhar o foco no centro. 
► V
  ∟ background-position: center 25%; pega o centro d aimagem, foca em 25% mais acima para destaque da mesma.


Dissertativas

21)Explique como o layout flexível foi usado para organizar o conteúdo principal do site.
► usamos um layout-flexível, flexbox, pois visamos um site em dimensão unidimensional, ou sej ame linhas corridas em elementos aplicados o flexbox.

22)Justifique o uso de border-radius nos cards de publicidade e seu impacto visual.
► border-radius nos cards faz com que suas extremidades que se encontram fiquem mais suave conforme o valor a ela plaicado no css em px.

23)Descreva como a responsividade foi aplicada nas seções de buffet e marmitas.
► a responsividade foi aplicada a ficarem em forma de column, pois a responsividade me permite tratar este detalhe importante.

24)Avalie o uso de object-position: top center nas imagens e como isso afeta o foco visual.
► o uso de object-position: top center; nas imagens fazem com que o navegador foque em centralizar a imagem levando em conta o topo da imagem.

25)Explique como o CSS foi estruturado para destacar os títulos principais com tipografia e cor.
► o css foi estrtuturado para destacar os titulos em classes.

26)Analise o papel do rodapé no projeto e como ele reforça a identidade da marca HopeUp 7.DEV.
► o footer foi um dos locais que mais me conquistou no html, pois bem feito, e no meu caso, aplicando o metodo de estudo hope up em cada projeto, demosntra que o o que está no footer referente a marca HopeUp 7.DEV é seriedade e compromisso.

27)Descreva como o botão “📲 Pedir pelo WhatsApp” foi estilizado para chamar atenção e facilitar o contato.
► o botão “📲 Pedir pelo WhatsApp” foi estilizado via <span> que é um elemento, tag html para elementos inline cujo estilização são bem faceis se no <span> estiverem, pois o botão é um elemento inline, um elemnto num linha, e <span> trata isso.

28)Justifique a escolha de max-width em seções como #sobre e #propaganda-final.
► max-width impõe limite de largura que pode ser alcançada numa imagem, texto, bloco, video, para que respeite o limite estabelecido em max-width.

30)Explique como o HTML e CSS foram organizados para permitir impressão limpa e visualmente agradável.
► modularidade.

31)Proponha uma melhoria no layout da seção de marmitas para torná-la mais interativa e acessível. ***