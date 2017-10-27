<template>
  <h1>{{msg}}</h1>
</template>

<script>
export default {
  name: 'index',
  data() {
    return {
      msg: 'Index',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../global/functions.scss";

h1 {
  // color: white;
}
</style>
