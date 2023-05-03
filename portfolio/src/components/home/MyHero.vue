<template lang="pt-br">
    <section class="hero-container">
        <div class="container hero">
                <div class="answer">
                    <h2><span>W</span>HO I'M?</h2>
                    <div class="text">
                        <P><strong>M</strong>y name is Gabriel, I'm 23 years old and I live in RN. The last 2 years were a turning point in my future, it was at that moment that I started to be curious about programming, and thus, I started my studies in web development.</P>
                        <P>Currently, I am an academic in information systems at UFRN and a front-end programmer / UI/UX designer, I still intend to become full-stack, in order to be a reference in web development. Added to that, today I am a programmer and marketing director for the company Júnior byte seridó, and in addition to that, I also get involved in some projects as a freelancer.</P>
                        <P>I have some principles as pillars in my life, I keep my values ​​well defined and thus, I understand that trust, loyalty, respect, responsibility and commitment are the basis of anything to build in life.</P>
                        <P>Finally, I feel ready and happy to live each stage of life in the necessary way, thus learning from all stages and evolving as a person and professional.</P>
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
        padding: 10px;
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



    
</style>