<template>
 <b-jumbotron  text-variant="white" border-variant="dark">
  <template slot="header">
    Bootstrap Vue
  </template>
  <template slot="lead">
    This is a simple hero unit, a simple jumbotron-style component for
    calling extra attention to featured content or information.
  </template>
  <hr class="my-4">
  <p>
    It uses utility classes for typography and spacing to space content out within the larger container.
  </p>
</b-jumbotron>

</template>

<script>

import bJumbotron from 'bootstrap-vue/es/components/jumbotron/jumbotron'

export default {
  name: 'Top',
  components: {
    'b-jumbotron': bJumbotron
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.jumbotron{
    background-color: #ff6f4e ;
}

</style>
