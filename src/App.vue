<template lang="pt-br">
  <div class="page">
    <navbar></navbar>
    <MyBody></MyBody>
  </div>
</template>
<script>
import navbar from '@/components/navbar.vue'
import MyBody from '@/components/MyBody.vue'
export default {
  components: { navbar , MyBody }
}
</script>
<style scoped>

  .page{
    background: #E1E1DD;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0px;
    gap: 0px;
  }
  
</style>