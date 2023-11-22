<template lang="pt-br">
    <section class="contact-container">
        <div class="container contact">
            <h2 id="titlec">CONTACT</h2>
            <div class="work">
                <p><strong>V</strong>ocê precisa de um programador?</p>
                <a href="mailto:gabriel.lima2307@uol.com.br">
                    <h3>VAMOS TRABALHAR JUNTOS ></h3>
                </a>
            </div>
            <div class="links">
                <a href="https://www.instagram.com/lima_g99/">
                    <img src="../../assets/links/instagram.svg" alt="instagram">
                </a>
                <a href="https://github.com/Lima404">
                    <img src="../../assets/links/github.svg" alt="github">
                </a>
                <a href="wa.me/5584996021457">
                    <img src="../../assets/links/wpp.svg" alt="wpp">
                </a>
                <a href="https://www.linkedin.com/in/gabriel-lima-2839b0195/">
                    <img src="../../assets/links/linkesdin.svg" alt="linkedin">
                </a>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>

    .contact{
        width: 1090px;
        display: flex;
        padding-bottom: 0px;
        flex-direction: column;
        align-items: center;
        padding: 5px;
        gap: 40px;
    }

    h2{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 700;
        font-size: 32px;
        line-height: 37px;
        color: #000000;
    }

    .work{
        display: flex;
        padding-bottom: 0px;
        flex-direction: column;
        align-items: center;
        gap: 20px;

        border-bottom: 1px solid #000;
    }

    P{
        color: #000;
        font-family: Times New Roman;
        font-size: 28px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
    }

    strong{
        font-size: 36px;
    }

    h3{
        color: #000;
        font-family: Times New Roman;
        font-size: 64px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        text-decoration-line: underline;
        transition: 1s;
    }

    h3:hover{
        font-size: 70px;
        text-decoration: underline;
    }

    .links{
        display: flex;
        padding: 10px;
        align-items: flex-start;
        gap: 30px;
    }

    @media (max-width:890px){

        h3{
            font-size: 40px;
        }

        h3:hover{
            font-size: 50px;
        }
        
    }
</style>