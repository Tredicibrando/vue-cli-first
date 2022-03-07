<template>
  <div id="app">
    <MyTitle />
    <MyJumbo />
  </div>
</template>

<script>
import MyTitle from '@/components/MyTitle'
import MyJumbo from '@/components/MyJumbo'


export default {
  name: 'App',
  components: {
    MyTitle,
    MyJumbo,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app{
  text-align: center;
  padding: 10px 0;
}
</style>
