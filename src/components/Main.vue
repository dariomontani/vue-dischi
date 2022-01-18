<template>
  <div class="container">
      <Card />
  </div>
</template>

<script>
import Card from './Card.vue'

export default {
    name: "Main",

    components:{
        Card,
    },

    data(){
        return{
        }
    },

    methods: {
        getCards () {
            axios.get('https://flynn.boolean.careers/exercises/api/array/music')
            .then()
            .catch()
        }
    }
}
</script>

<style lang="scss">
    @import "~bootstrap/scss/bootstrap";
</style>