<template>
<div>
  <q-layout>
   
    <q-header>
      Sistema de contas a pagar
    </q-header>

    <q-footer>

      Deus amou o mundo de tal maneira que deu o seu filho unigênito para que todo aquele que nele crê não pereça mas tenha a vida eterna.

    </q-footer>

   
      <q-page-container id="menu">
        
      </q-page-container>

      <q-page-container id="corpo">
    
        <router-view />

      </q-page-container>    
   


  </q-layout>
  </div>
</template>
<script>
import { defineComponent, ref } from 'vue'

export default defineComponent({
  name: 'MainLayout',

  components: {
    
  },

  setup () {   
    return {
      
    }
  }
})
</script>
<style scoped>
  .q-layout{
    background-color: rgb(165, 157, 146);
  }

.q-header,.q-footer{
  font-size: 25px;
  text-align: center;
}

#menu{
  border: 1px solid;
  width: 20%;
  height: 100%;
  float: left;
  position: absolute;


}

#corpo{
  float: right;
  position: relative;
  width: 75%;
}





</style>
