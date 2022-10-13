<template>
    <div class="home">
        <div class="top-bar">
            <h1>Jornal Marcial</h1>
        </div>
        <div class="container">

           <h2>Aviso JM</h2>
           
           <span>
            Bom pessoal, me chamo Everton da Silva Cabral, fui um dos fundadores da página Bigodudo Sincero no Facebook, eu e mais duas pessoas realizamos a criação com o intuito de promover o mundo marcial e poder contribuir com os nossos pensamentos e ideias para esse universo, no meu ver o bigodudo foi um sucesso, mas devido a prioridades pessoais e o enorme tempo que o bigodudo sincero necessitava, o grupo foi se desfazendo ao ponto de não criarmos mais conteúdos, após esse período percebi que foi criado uma página chamada Bigodudo Sincero 2.0 no instagram, essa página foi criada por outras pessoas não autorizadas e desconhecidas, a princípio fiquei chateado, pois usaram da imagem do bigodudo sincero sem nossa autorização, tentei reativar a conta do bigodudo original para realizar um comunicado, mas devido ao tempo de não uso e alguns procedimentos exagerados de segurança, não conseguimos reativar a conta pois esquecemos a senha, o intuito do bigodudo sincero sempre foi criar um movimento e com essa filosofia resolvi deixar essa situação de lado, acredito que alguns já puderam identificar a diferença da essência desse novo bigodudo 2.0 para o bigodudo original, hoje decidi voltar a realizar análises, mas desta vez sem o anonimato, infelizmente não poderei usar aquele bom humor do bigodudo, pois infelizmente algumas pessoas não sabem interpretar e acabam se ofendendo, realizarei as análises de uma forma bem respeitosa e sucinta, passando apenas a minha opinião, caso vocês gostem continuarei realizando as análises, queria comunicar também que não sou formado em música, me considero muito limitado no assunto, mas isso não impede de me expressar. Obrigado!
           </span>
        
        </div>
        <hr>
        <div class="analise">

           
        
            <div class="video">
                <p id="titulo"> Análise da Banda Marcial Mardônio Coelho</p>
             <LazyYoutubeVideo src="https://www.youtube.com/embed/1On7Crew6nA" />
            </div>
             <div class="text">
                Entrada: Infelizmente a banda entrou em quadra sem fardamento, entendo que é algo que não depende da banda, mas sim dos recursos disponibilizados para a escola, mas não posso deixar de comentar que a falta do fardamento faz muita diferença no impacto da banda como também no psicológico de quem assiste e julga.  A escolha da música de entrada não foi ruim, mas também não achei perfeita, porém foi muito bem executada com destaque para o naipe de tuba que executou e preencheu muito bem a música, a banda pode se atentar mais na sincronização de movimentos, o rapaz do trombone não acompanhou a velocidade do conjunto quando o mór deu o comando para ‘preparar pra tocar’, ajeitando isso, o garbo ficaria praticamente perfeito no momento inicial. Durante o deslocamento a percussão pesou um pouco a mão e em alguns momentos prejudicou a melodia da banda, a percussão deve controlar a intensidade na execução “tocar mais baixo”, durante a formação de palco alguns componentes apresentaram uma postura desuniforme com o conjunto e deselegante com o dorso muito curvado, a banda pode orientar os componentes a sempre esteram com o corpo firme e ereto. Percebo que na entrada, de um modo geral as primeiras vozes executam a música com maior intensidade que as segundas e terceiras vozes, com destaque para os segundos e terceiros trompetes que precisam executar a música na mesma intensidade que o primeiro trompete. 
                
             </div>
             <div class="text">
                Peça: Logo de início sinto a falta de intensidade dos tímpanos, a música pediu mais intensidade nos ataques iniciais dos tímpanos e o músico não respondeu, faltou segurança nas trompas e houve falha, a música também pedia mais intensidade para esse instrumento, também no início percebo que o trompete piccolo acentuou algumas notas no arpejo, acredito que essa execução deveria ser com uma intensidade contínua, o solista flugelhorn precisa se atentar a respiração para que o erro cometido no solo não se repita, caso o músico tenha alguma dificuldade com nervosismo, existe uma dica, quando estiver no ensaio ou estudando procure realizar algum exercício físico para acelerar os batimentos cardíacos, pode ser o ‘polichinelo’ antes de executar o trecho do solo, assim você ira conseguir trabalhar a sua respiração com o nível de estresse elevado parecido com o da apresentação, eu não concordo com a substituição dos souzafones pelo bombardão, acho que os souzafones ajudam na sonoridade da banda no tipo de ambiente barulhento que é a várzea, os euphoniums apresentaram bastante insegurança e desafinações em alguns momentos, parabéns para o naipe de trombone e tuba, os 2 trompetes e 3 trompetes precisam tocar com mais intensidade. Parabéns a banda, ótima apresentação!
             </div>
            <div class="text">
                fardamento - 0.7 |
                | percussão alta -0.2
                | garbo -0.5
                | desequilibrio entre as vozes -0.6 ------

                | timpanos no incio -0.1
                | trompas -1.0
                | piccolo -0.5
                | solo -0.2
                | euphoniums -0.5
                <br>
                De 100 Pontos a Banda fez 95.7 Pontos
            </div>

        </div>

        <div class="footer">
            <a href="https://www.instagram.com/?hl=pt-br" target="_blank"><img src="../../assets/insta.png" alt="Instagram" /></a> 
        </div>
    </div>
</template>


<script>

import LazyYoutubeVideo from 'vue-lazy-youtube-video'
export default {
    name: 'YourAwesomeComponent',
  components: {
    LazyYoutubeVideo,
  },
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Nanum+Myeongjo&display=swap');
@import url('https://fonts.googleapis.com/css2?family=EB+Garamond&display=swap');
@import 'vue-lazy-youtube-video/dist/style.css';
.home{
        background-color: black;
        height: auto;
    }
    .top-bar{
        display: flex;
        justify-content: center;
        background-color: 		#1C1C1C;
        color: 	#00FFFF;
        padding: 10px;
        height: 50px;
        align-items: center;
        font-weight: 400;
        font-family: 'Nanum Myeongjo', serif;
    }
    .container{
        color:			#808080;
        padding: 10px;
        font-family: 'EB Garamond', serif;
        font-size: 21px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        margin-bottom: 10px;
        text-align: center;
    }
    .footer{
        background-color: #1C1C1C;
        height: 150px;
        display: flex;
        align-items: center;
        justify-content: center;

    }
    .video{
        padding: 5px;
        margin-top: 10px;
        
    }
    h2{
        color: white;
        
    }
 #titulo{
    color: white;
    display: flex;
    justify-content: center;
    font-family: 'EB Garamond', serif;
    font-size: 18px;
    margin-top: 10px;
    margin-bottom: 10px;
 }
  
 .text{
    color: 	#DCDCDC;
    font-family: 'EB Garamond', serif;
    font-size: 21px;
    padding: 15px;
    
 }
 .analise{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
 }
 @media screen and (min-width: 1000px) {
  .top-bar{
    height: 100px;
    font-size: 25px;
  }
  #titulo{
    font-size: 20px;
  }
  .video{
    width: 600px;
    margin-left: 10px;
  }
  .text{
    width: 750px;
  }
}
 
</style>
