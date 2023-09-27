<script setup>
import {ref} from 'vue';
const header= ref('Mi Carrito de Compras')
</script>

<template>
  <h1> <i class="material-icons shopping-cart-icon">local_mall </i>{{header}}</h1>

</template>

<style scoped>
.shopping-cart-icon{
font-size: 10rem;
}
</style>
