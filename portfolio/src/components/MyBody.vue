<template lang="pt-br">
    <div class="body">
        <MyTitle></MyTitle>
        <MyHero></MyHero>
        <MyProjects></MyProjects>
    </div>
</template>
<script>
import MyTitle from '@/components/home/MyTitle.vue'
import MyHero from '@/components/home/MyHero.vue'
import MyProjects from '@/components/home/MyProjects.vue'
export default {

    components: { MyTitle , MyHero , MyProjects }
    
}
</script>
<style scoped>


    .body{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px;
        gap: 30px;
    }
    
    
</style>