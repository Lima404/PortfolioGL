<template lang="pt-br">
    <section class="title-container">
        <div class="container title">
            <header>
                <h1><strong>P</strong>ORTFÓLIO</h1>
            </header>
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>

    .title-container{
        background: #E1E1DD;
        display: flex;
        flex-direction: row;
    }

    .title{
        max-width: 1086px;
    }


    header{
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 0px 180px 20px;
        gap: 10px;
        border-bottom: 2px solid #000000;
        box-sizing: border-box;
    }

    h1{
        font-family: 'Old English Text MT';
        font-style: normal;
        font-weight: 400;
        font-size: 128px;
        line-height: 160px;
        color: #000000;
        text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    }

    strong{
        font-size: 160px;   
    }

    @media (max-width:960px) {
        h1{
            font-size: 100px;
        }
        strong{
            font-size: 116px;
        }
    }

    @media (max-width:745px) {
        h1{
            font-size: 80px;
        }
        strong{
            font-size: 100px;
        }
    }

    @media (max-width:610px) {
        h1{
            font-size: 60px;
        }
        strong{
            font-size: 80px;
        }
    }

    
</style>