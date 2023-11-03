<template lang="pt-br">
    <div class="body">
        <MyTitle></MyTitle>
        <MyHero></MyHero>
        <MyProjects></MyProjects>
        <MySkills></MySkills>
        <MyContact></MyContact>
    </div>
</template>
<script>
import MyTitle from '@/components/home/MyTitle.vue'
import MyHero from '@/components/home/MyHero.vue'
import MyProjects from '@/components/home/MyProjects.vue'
import MySkills from '@/components/home/MySkills.vue'
import MyContact from '@/components/home/MyContact.vue'
export default {

    components: { MyTitle , MyHero , MyProjects , MySkills, MyContact }
    
}
</script>
<style scoped>


    .body{
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px;
        gap: 30px;
    }
    
    
</style>