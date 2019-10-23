<template>
  <div>
  <body>
    <app-header/>
     <v-parallax
         dark
        src="../assets/planetas-hackathon.jpg" alt="imagem contendo ilustração de planetas e estrelas"
        >
     
      <h1 class=" text-center titulo-parallax">#HACKATHON &lt;!DOCTYPE&gt;</h1>
      <h3 class="text-center sub-parallax ">Um evento de outro mundo!</h3>
        
  
     
     <div class="text-center">
          <v-btn class="ma-5" outlined color="white" href="/paginas/hackathon">saiba mais</v-btn>
      </div>
        </v-parallax>
    <section class="servicos-section" title="Seção O que fazemos">
      <div class="inner-width">
        <h2 class="section-titulo">{O que fazemos}</h2>
        <p class="texto">
          Tudo feito com muito <strike>café</strike> amor e profissionalismo</p>
        <hr class="border"/>
        <div class="container">

          <div class="box">
            <div class="icon">
              <i class="fas fa-mobile-alt" alt="Criação de aplicativos" ></i>
            </div>
            <h3 class="servico-titulo">Apps</h3>
            <p class="servico-desc">
              Desenvolvemos de aplicativos e jogos para celulares dos sistemas Androind, iOS e Windows Phone.
            </p>
          </div>

          <div class="box">
            <div class="icon">
              <i class="fas fa-users" alt="Serviços de Acessibilidade" ></i>
            </div>
            <h3 class="servico-titulo">Acessibilidade</h3>
            <p class="servico-desc">
              Nós da  &lt;!DOCTYPE&gt; garantimos que nossos serviços proporcionem a inclusão de pessoas com ou sem deficiência.  
            </p>
          </div>

          <div class="box">
            <div class="icon">
              <i class="fas fa-brain" alt ="Desenvolvimento de tecnolgias com inteligência artificial"></i>
            </div>
            <h3 class="servico-titulo">Inteligência artificial</h3>
            <p class="servico-desc">
              Criamos aplicações que aprendem a base de dados para lidarem com grande volume de informações seja por texto, voz ou fotos.
            </p>
          </div>

          <div class="box">
            <div class="icon">
              <i class="fas fa-file-alt" alt="Serviços de otimização de sites (SEO)" ></i>
            </div>
            <h3 class="servico-titulo">Otimização de sites (SEO)</h3>
            <p class="servico-desc">
              Utilizamos do conjunto de técnicas SEO para deixar a pesquisa pelo seu site na primeira página em qualquer mecanismo de busca.
            </p>
          </div>
          <div class="box">
            <div class="icon">
              <i class="fas fa-code" alt="Criação de Sites" ></i>
            </div>
            <h3 class="servico-titulo">Sites</h3>
            <p class="servico-desc">
              Oferecemos os melhores serviços de criação e manutenção de sites responsivos (HTML e CSS) + um painel de controle (VueCli).
            </p>
          </div> 
          
          <div class="box">
            <div class="icon">
              <i class="fas fa-pen-fancy" alt="Serviços de Webdesign" ></i>
            </div>
            <h3 class="servico-titulo">Webdesign</h3>
            <p class="servico-desc">
              Aplicamos fundamentos de Design para a criação de layouts para sites. Utilizando conhecimentos como Tipografia, Teoria das cores, Diagramação, Gestalt, entre outros.
            </p>
            </div>
            
        </div>
        </div>
    </section>
     
       <v-parallax
         dark
        src="../assets/planetas-hackathon.jpg" alt="imagem contendo ilustração de planetas e estrelas"
       >
   
     <section class="projetos-destaques" title="Seção de Projetos">
        <h2 class="section-titulo">{Projetos}</h2>
        <!-- <div class="container">
          <div class="box">
            <div class="icon">
            <i class="fas fa-meteor" alt="projetos" ></i>
            </div>
        
            </div>
        </div> -->
        <p class="texto">
        Nossos projetos estão no Behance, venha conhecer!
        </p>
        <hr class="border"/>
        <div class="text-center">
      <v-btn class="ma-5 text-center" outlined color="white" href="https://www.behance.net/gallery/76255517/The-New-Design-Frontier" target="blank" >PORTFÓLIO</v-btn>
        </div>
         
    </section>
         </v-parallax>  
     
       
  
  </body>
 <app-footer/>
  </div>
</template>
<script>
 import AppHeader from '../components/AppHeader'
  import AppFooter from '../components/AppFooter'
export default {
  components:{
    AppFooter,AppHeader,
  }
}
</script>