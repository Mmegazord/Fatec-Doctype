<template>
<div>
  <body>

    <!--Some of this HTML is directly from Pavilion.  You can change it to whatever you want if you want to mimic this design.-->
    <footer class="flex-rw">
<!--   
        <ul class="footer-list-top">
            <li>
                <h4 class="footer-list-header">About Pavilion</h4>
            </li>
            <li><a href='/shop/about-mission' class="generic-anchor footer-list-anchor" itemprop="significantLink">GET
                    TO KNOW US</a></li>
            <li><a href='/promos.html' class="generic-anchor footer-list-anchor" itemprop="significantLink">PROMOS</a>
            </li>
            <li><a href='/retailers/new-retailers.html' class="generic-anchor footer-list-anchor"
                    itemprop="significantLink">BECOME A RETAILER</a></li>

            <li><a href='/job-openings.html' itemprop="significantLink" class="generic-anchor footer-list-anchor">JOB
                    OPENINGS</a></li>

            <li><a href='/shop/about-show-schedule' class="generic-anchor footer-list-anchor"
                    itemprop="significantLink">EVENTS</a></li>
        </ul>
        <ul class="footer-list-top">
            <li>
                <h4 class="footer-list-header">The Gift Selection</h4>
            </li>


            <li><a href='/Angels/cat/id/70' class="generic-anchor footer-list-anchor">ANGEL FIGURINES</a></li>
            <li><a href='/Home-Decor/cat/id/64' class="generic-anchor footer-list-anchor">HOME DECOR</a></li>
            <li><a href='/Mugs/cat/id/32' class="generic-anchor footer-list-anchor">MUGS</a></li>
            <li><a href='/Pet-Lover/cat/id/108' class="generic-anchor footer-list-anchor">PET LOVER</a></li>
            <li><a href='/Ladies-Accessories/cat/id/117' class="generic-anchor footer-list-anchor"
                    target="_blank">HANDBAGS & JEWELRY</a></li>
        </ul>
        <ul class="footer-list-top">
            <li id='help'>
                <h4 class="footer-list-header">Please Help Me</h4>
            </li>
            <li><a href='/shop/about-contact' class="generic-anchor footer-list-anchor"
                    itemprop="significantLink">CONTACT</a></li>
            <li><a href='/faq.html' class="generic-anchor footer-list-anchor" itemprop="significantLink">FAQ</a></li>
            <li id='find-a-store'><a href='/shop/store-locator' class="generic-anchor footer-list-anchor"
                    itemprop="significantLink">STORE LOCATOR</a></li>
            <li id='user-registration'><a href='/shop/user-registration?URL=' class="generic-anchor footer-list-anchor"
                    itemprop="significantLink">NEW USERS</a></li>
            <li id='order-tracking'><a href='/shop/order-status' itemprop="significantLink"
                    class="generic-anchor footer-list-anchor">ORDER STATUS</a></li>
        </ul> -->
        <!-- seção de icones -->
        <section class="footer-social-section flex-rw">
            <!-- texto -->
            <!-- <span class="footer-social-overlap footer-social-connect">
                SIGA A &lt;!DOCTYPE&gt;
            </span> -->
            <!-- final do texto -->
            <!-- icones -->
            <span class="footer-social-overlap footer-social-icons-wrapper">
                <!-- O atributo global  itemprop é usado para adicionar propriedades para um item.
                     Todo elemento HTML pode ter um atributo itemprop  especificado
                     e um itemprop consiste em um par de nome e valor. 
                     Cada par de nome e valor é chamado de propriedade, e um grupo de uma ou mais 
                     propriedades forma um item. Os valores das propriedades são ou um texto ou uma
                     URL e pode ser associada a uma grande variedade de elementos  -->
               
                <a href="https://behance.com" class="generic-anchor behance" target="_blank" title="Behance"
                    itemprop="significantLink"><i class="fab fa-behance-square"></i></a>
                <a href="https://www.facebook.com" class="generic-anchor facebook" target="_blank"
                    title="Facebook" itemprop="significantLink"><i class="fab fa-facebook-square"></i></a>
                <a href="http://github.com" class="generic-anchor github" target="_blank" title="Github"
                    itemprop="significantLink"><i class="fab fa-github-square"></i></a>
                <a href="https://www.twitter.com" class="generic-anchor twitter" target="_blank" title="Twitter"
                    itemprop="significantLink"><i class="fab fa-twitter-square"></i></a>

            </span>
            <!-- final dos ícones -->
        </section>
        <!-- final da seção de icones -->

        <!-- últimas informações -->
        <section class="footer-bottom-section flex-rw">
            <div class="footer-bottom-wrapper">
                <i class="fa fa-copyright" role="copyright">

                </i> 2019 All Rights Reserved.
                <address class="footer-address" role="company address">&lt;!DOCTYPE&gt; Av. Antonio Neudenir Benagna Micali,107.Taquaritinga-SP
                    </address>
            </div>
           
        </section>
        <!-- final das últimas informações -->
    </footer>
    <!-- final do footer -->
</body>
</div>
</template>
<style  scoped>
html, body {
  height: 100%;
}

body {
  font-size: 14px;
  margin: auto;
  display: flex;
  flex-flow: column nowrap;
  font-family: "Space Mono", monospace;
  justify-content: space-between;
}


a {
  text-decoration: none;
}

.generic-anchor {
  color: white;
}
.facebook:hover{
color:#487eb0;
}
.twitter:hover{
  color: #22a6b3;
}
.github:hover{
  color:#6c5ce7;
}
.behance:hover{
  color:#0097e6;
}




.flex-rw {
  display: flex;
  flex-flow: row wrap;
}

footer {
  background: black;
  margin-top: auto;
  width: 100%;
}

.footer-social-section {
  width: 100%;
  align-items: center;
  justify-content: space-around;
  position: relative;
  margin-top: 5px;
}

.footer-social-overlap {
  position: relative;
  background-color: black;
}

.footer-social-connect {
  font: 3.5em;
  color: #fff;
}

.footer-social-overlap > a {
  font-size: 2em;
}

.footer-bottom-section {
  width: 100%;
  padding: 10px;
  border-top: 1px solid #ccc;
  margin-top: 10px;
}

.footer-bottom-wrapper {
  font-size: 1.5em;
  color: #fff;
  text-align: center;
}

.footer-social-overlap > a:not(:first-child) {
  margin-left: 10px;
}

.footer-address {
  display: inline;
  font-style: normal;
}

@media screen and (min-width: 568px) {
  .footer-list-anchor {
    font-size: 1.5em;
  }
  .footer-social-overlap > a {
    font-size: 3em;
  }
  .footer-social-section {
    justify-content: center;
  }
  .footer-bottom-section {
    margin-right: auto;
  }
  .footer-social-overlap {
    display: flex;
    justify-content: center;
  }
  .footer-social-icons-wrapper {
    width: 100%;
    padding: 0;
  }
  .footer-bottom-section {
    padding: 0 5px 10px 5px;
  }
  .footer-bottom-wrapper {
    text-align: center;
    width: 100%;
    margin-top: 10px;
  }
}

</style>