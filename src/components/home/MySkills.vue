<template lang="pt-br">
    <section class="skills-container">
        <div class="container skills">
            <h2 id="titles">SKILLS</h2>
            <div class="box-skills">
                <div class="texts">
                    <div class="javascript">
                        <p class="topic">JAVASCRIPT</p>
                        <p><span>A</span>lgum tempo se passou e comecei a procurar algumas automações, já havia passado por disciplinas como algoritmos e lógica de programação e programação orientada a objetos isso me deu base para evoluir um pouco mais, então conheci o javascript que me ajudou muito a deixar meus projetos web mais completos.</p>
                    </div>
                    <div class="HTML">
                        <p class="topic">HTML & CSS</p>
                        <div class="desc">
                            <p><span>C</span>omecei a estudar html junto com css em 2019, nesse ano comecei a me interessar em aprender mais sobre desenvolvimento de tecnologia. Inicialmente fiz pesquisas, procurei vídeos no YouTube e cursos online, com o passar do tempo comecei a colocar em prática tudo o que estava aprendendo. Foi nessa época que começou a base para o meu crescimento como desenvolvedor.</p>
                        </div>
                        <div class="others">

                            <p><span>E</span>ssas são as principais linguagens, bibliotecas e frameworks do meu dia a dia, ainda estudo muito sobre elas para melorar meus projetos tanto pessoais como profissionais.</p>
                            <div class="topico">
                                <img src="../../assets/skills/topico1.svg" alt="topico1">
                                <img src="../../assets/skills/topico2.svg" alt="topico2">
                            </div>
                        </div>
                    </div>
                    <div class="vue">
                        <p class="topic">VUE.JS</p>
                        <p><span>A</span> linguagem vue.js surgiu na minha trajetória a partir dos meus primeiros projetos com a empresa byte seridó jr e recomendação de um amigo. Com o passar do tempo me identifiquei com o framework e assim, criando novos projetos, inclusive este, desde a componentização até a integração javascript e modelagem de propriedades entre componentes.</p>
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
        border-bottom: 1px solid #000000;
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
        padding: 0px 20px;
        gap: 210px;
    }

    .card2{
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        gap: 265px;
    }

    .topic{
        padding: 10px;
        border-radius: 20px;
        background: rgba(0, 0, 0, 0.13);
        box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
    }

    .texts{
        display: flex;
        flex-direction: row;
        justify-content: center;
        padding: 0px;
        gap: 27px;
    }

    .javascript{
        max-width: 250px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        padding: 0px;
        gap: 10px;
    }

    .HTML{
        max-width: 520px;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px;
    }

    .vue{
        max-width: 250px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 0px;
        gap: 10px;
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
    
    @media (max-width:1120px) {
        .texts{
            display: flex;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content: none;
            padding: none;
            gap: 27px;
        }
    }

    @media (max-width:1078px) {
        .vue{
            max-width: 74%;
        }
    }

    @media (max-width:800px) {
        .HTML{
            max-width: 74%;
            padding-bottom: 20px;
            border-bottom: 1px solid #000000;
        }
        .javascript{
            max-width: 74%;
            padding-bottom: 20px;
            border-bottom: 1px solid #000000;
        }
    }
</style>