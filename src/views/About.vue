<template>
  <div>
   <body>
       <app-header/>
    <section class="sobre-section">
        <div class="interior-width">
            <h2 class="section-titulo">{Sobre nós}</h2>
            <hr class="border">
            <div class="sobre-section-linha">
                <div class="sobre-section-coluna">
                    <div class="sobre">
                        <p>É importante lembrar de onde viemos para saber aonde queremos chegar. Antes de nos unirmos
                            para formar uma das maiores empresas de desenvolvimento na área da tecnologia, tivemos uma
                            história cheia de desafios e de conquistas, as quais nos trouxeram até aqui. Conheça os
                            marcos mais importantes da nossa história!
                        </p>
                       
                    </div>

                </div>

                <div class="sobre-section-coluna">

                    <div class="video">
                        <div class="embed">
                                <iframe src="https://www.youtube.com/embed/MeWET6I-Jd4"></iframe>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>
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