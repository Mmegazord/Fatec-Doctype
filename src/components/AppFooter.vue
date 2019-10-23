<template>
  <v-card height="150"
  class="black">
 
  
    <v-footer
      absolute
      class="font-weight-regular white--text black"
    >
      <v-col
        class="text-center"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>&lt;!Doctype&gt;</strong>
      
      </v-col>
      <v-col
      class="text-center"
        cols="12"
      >
      <i class="fab fa-behance-square" href="https://www.behance.net/gallery/76255517/The-New-Design-Frontier" target="blank"></i>
       <i class="fab fa-facebook-square" href="https://www.facebook.com" target="blank" ></i>
        <i class="fab fa-github-square" href="https://github.com" target="blank"></i>
         <i class="fab fa-twitter-square" href="https://www.twitter.com" target="blank"></i> 
      </v-col>
    </v-footer>
  </v-card>
</template>
<style  scoped>
i{
  color:white;
  margin:10px;
  font-size: 33px;
}
</style>