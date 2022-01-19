<template>
  <div class="card p-3 text-center border-0">
    <div class="p-3">
      <img
        class="img-fluid mb-3"
        src="https://www.onstageweb.com/wp-content/uploads/2018/09/bon-jovi-new-jersey.jpg"
        alt=""
      >
      <p class="title text-uppercase fw-bold">
        NEW JERSEY
      </p>
      <p class="subtitle lead mb-0">
        Bon Jovi
      </p>
      <p class="small">
        1988
      </p>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Card',
    data(){
        return
    }
}
</script>

<style lang='scss'>
.card {
  background-color: transparent !important;
  div {
    background-color: #2e3a46;
    height: 100%;
  }
  .subtitle,
  .small {
    color: #7d7977;
  }
}
</style>