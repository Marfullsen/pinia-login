<template>
  <Layout>
    <div style="margin: 1rem 0;">
      <PiniaLogo />
    </div>
    <CartForm></CartForm>
  </Layout>
</template>

<script lang="ts">
import Layout from './layouts/default.vue'
import PiniaLogo from './components/PiniaLogo.vue'

import { defineComponent, ref } from 'vue'
import CartForm from './components/CartForm.vue'

export default defineComponent({
  components: { Layout, PiniaLogo, CartForm }
})
</script>

<style scoped>  
img {
  width: 200px;
}
</style>
