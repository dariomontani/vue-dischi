<template>
  <header class="d-flex justify-content-between ps-3 pe-3">
    <div>
      <img
        src="../assets/img/spotify-logo.png"
        alt="Spotify"
      >
    </div>
    <div>
      <select class="form-select mt-3">
        <option value="">
          Seleziona un genere
        </option>
        <option value="Jazz">
            Jazz
        </option>
      </select>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style lang="scss">
header {
    height: 70px;
    background-color: #2e3a46;
    line-height: 70px;
    img {
        width: 50px;
    }
}
</style>