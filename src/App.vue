<template>
  <HeaderView />
  <router-view/>
</template>

<script>
import HeaderView from "./layout/HeaderView.vue"
export default {
    components: {
      HeaderView 
    },
}
</script>
