<template>
  <q-layout>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
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
</style>
