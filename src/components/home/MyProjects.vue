<template lang="pt-br">
    <section class="porject-container">
        <div class="container project">
            <h2 class="titlep">PROJECTS</h2>
            <CardProject />
        </div>
    </section>
</template>
<script>
import CardProject from '../ups/CardProject.vue';
export default {
    components: { CardProject }
}
</script>
<style scoped>

    .project{
        max-width: 1074px;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px 3px 60px;
        gap: 50px;
        border-bottom: 2px solid #000000;
    }

    .title-card1{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 700;
        font-size: 40px;
        line-height: 46px;


        color: #000000;
    }

    h2{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 700;
        font-size: 32px;
        line-height: 37px;
        color: #000000;
    }

    
</style>