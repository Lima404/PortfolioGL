<template lang="pt-br">
    <section class="hero-container">
        <div class="container hero">
                <div class="answer">
                    <h2><span>Q</span>UEM SOU EU!</h2>
                    <div class="text">
                        <P><strong>M</strong>eu nome é Gabriel, tenho 23 anos e moro no RN. Os últimos 2 anos foram uma virada no meu futuro, foi nesse momento que comecei a ter curiosidade por programação, e assim, iniciei meus estudos em desenvolvimento como programador full-stack.</P>
                        <P>Atualmente sou acadêmico em sistemas de informação pela UFRN e programador full-stack, UI/UX designer e pretendo também me especializar em análise de sistemas com Power-BI, e sonho um dia me tornar referência nesses serviços. Somado a isso, Sobre minhas experiências de mercado, fui durante dois anos programador e diretor de marketing da empresa Júnior byte seridó, e além disso, e também participei do desenvolvimento de alguns projetos como freelancer.</P>
                        <P>Tenho alguns princípios como pilares na minha vida, mantenho meus valores bem definidos e assim, entendo que confiança, lealdade, respeito, responsabilidade e comprometimento são a base de tudo que se constrói na vida.</P>
                        <P>Por fim, sinto-me pronto e feliz para viver cada etapa da vida da forma mais necessária e otimista, aprendendo assim em todas as fazes e desejo continuar evoluindo como pessoa e como profissional.</P>
                    </div>
                </div>
            <img src="../../assets/hero/EU.svg" alt="">
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>

    .hero{
        max-width: 1074px;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: flex-start;
        padding: 0px 33.5px 35px;
        gap: 60px;
        border-bottom: 2px solid #000000;
    }

    .answer{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 0px;
        gap: 20px;
    }

    .text{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        margin: 10px;
        gap: 10px;
    }

    h2{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 700;
        font-size: 48px;
        line-height: 69px;
        color: #000000;
    }

    span{
        font-size: 60px;
    }

    p{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 23px;
        text-align: justify;
        color: #000000; 
    }

    strong{
        font-size: 36px;
    }

    @media (max-width: 1065px) {
        .hero{
            flex-wrap: wrap;
        }

        .answer{
            max-width: 80%;
            align-items: center;
        }

        p{
            font-size: 24px;
        }
    }

    @media (max-width: 850px) {

        .answer{
            align-items: center;
        }

        p{
            width: 60%;
            font-size: 24px;
        }

        .text{
            align-items: center;
        }
    }

    
</style>