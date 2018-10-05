<template>
 <div>
 <top></top>
 <product></product>
 </div>
</template>
<script>
import Top from './components/Top.vue'
import Product from './components/Product.vue'
export default {
  components: {
    'top': Top,
    'product': Product
  }
}
</script>
