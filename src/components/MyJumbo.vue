<template>
  <div class="jumbo">
    <h2>Dopo mille mila tentativi i nostri eroi sono riusciti</h2>
  </div>
</template>

<script>
export default {
  name: 'MyJumbo',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

  .jumbo{
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url(https://picsum.photos/800/350);
    background-size: cover;
    height: 350px;
    background-repeat: no-repeat;
    background-position: center;
  }

  .jumbo h2{
    font-size: 34px;
    color: white;

  }


</style>
