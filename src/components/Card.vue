<template>
  <div class="col-5">
      <img :src="image" alt="">

  </div>
</template>

<script>
export default {
    name: "Card",
    props: [
        "image",
    ],
    data(){
        return{

        }
    }
}
</script>

<style lang="scss">
    div{
        border: 1px solid black;
    }
</style>