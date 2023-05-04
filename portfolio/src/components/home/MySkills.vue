<template lang="pt-br">
    <section class="skills-container">
        <div class="container skills">
            <h2 class="title">SKILLS</h2>
            <div class="box-skills">
                <div class="cards">

                </div>
                <div class="texts">
                    <div class="javascript">
                        <p><span>S</span>ome time passed and I started looking for some automations, I had already gone through disciplines such as algorithms and programming logic and that gave me the basis to evolve a little more, then I met javascript that helped me to make my projects more complete web.</p>
                    </div>
                    <div class="HTML">
                        <div class="desc">
                            <p><span>I</span> started studying html along with css in 2019, that year I started to be interested in learning more about technology development. Initially, I carried out research, looked for videos on YouTube and online courses, over time, I started to put into practice everything I was learning. It was at that time that the foundation for my growth as a developer began.</p>
                        </div>
                        <div class="others">
                            <p><span>T</span>hese are the main languages ​​of my day to day, but I still study other programming languages ​​that I intend to implement in my personal and professional projects. here's a list of what I occasionally program:</p>
                            <div class="topico">
                                <img src="../../assets/skills/topico1.svg" alt="topico1">
                                <img src="../../assets/skills/topico2.svg" alt="topico2">
                            </div>
                        </div>
                    </div>
                    <div class="vue">
                        <p><span>T</span>he vue.js language emerged in my trajectory from my first projects with the company byte seridó jr and a friend's recommendation. Over time, I identified myself with the framework and thus, creating new projects, including this one, from componentization to javascript integration and modeling of properties between components.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>

    .skills{
        max-width: 1074px;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px 0px 60px;
        gap: 40px;
    }

    .box-skills{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px;
        gap: 20px;
    }

    .cards{
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        gap: 20px;
    }

    .texts{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: flex-start;
        padding: 0px;
        gap: 27px;
    }

    .javascript{
        max-width: 250px;
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        gap: 10px;
    }

    .HTML{
        max-width: 520px;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 0px;
    }

    .desc{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 0px 0px 10px;
        gap: 10px;
        border-bottom: 1px solid #000000;
    }

    .others{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px;
        gap: 10px;
    }

    .topico{
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        gap: 20px;
    }

    .vue{
        max-width: 250px;
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        gap: 10px;
    }

    p{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 400;
        font-size: 24px;
        line-height: 41px;
        text-align: justify;
        color: #000000;
    }

    span{
        font-size: 36px;
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