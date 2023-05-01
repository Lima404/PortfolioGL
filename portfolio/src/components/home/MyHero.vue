<template lang="pt-br">
    <div class="hero-container">
        <div class="container hero">
            <div class="base">
                <article>
                    <h1>My Portfolio</h1>
                    <p>Hi, my name is <strong>Gabriel Lima</strong>, I'm a student of information systems in Federal University of Rio Grande do Norte, currently i'm focused on developing my skills in programming. Lately I'm focusing on front-end web development but I want to become a Full-Stack and mobile programmer.</p>
                </article>
                <img src="../../assets/hero/foto.svg" alt="">
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>

    .hero-container{
        background: linear-gradient(to right, #054572, #13dace) ;
        display: flex;
    }

    .hero{
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .base{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 100px 0px; 
        gap: 100px;
    }

    h1{
        font-family: 'Roboto Mono', monospace;
        font-weight: 400;
        font-size: 2rem;
        padding-bottom: 30px;
        color: #13dace;
    }

    p{
        font-family: 'Roboto Mono', monospace;
        font-weight: 400;
        font-size: 1.5rem;
    }

    img{
        border-radius: 20px;
    }

    strong{
        color: #13dace;
        font-weight: 600;
        font-size: 1.9rem;
    }

    
</style>