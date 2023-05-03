<template lang="pt-br">
    <section class="porject-container">
        <div class="container project">
            <h2 class="title">PROJECTS</h2>
            <div class="box">
                <div class="card1">
                    <div class="desc">
                        <h3 class="title-card1"><strong>P</strong>ROJECT JR.</h3>
                        <div class="txt">
                            <p class="lib"><span>T</span>his project was my first contact with the job market, together with a team, I developed this website project for another jr company. In addition, I developed a lot as a professional, I learned to work better in a team, to study programming, to develop leadership, proactivity and agile methodologies. Finally, this was the project responsible for starting my professional life as a frod-end programmer and interface designer.</p>
                            <a href="https://github.com/byte-serido/projectJR-Consultoria-web">
                                <p class="show">SHOW MORE ></p>
                            </a>
                        </div>
                    </div>
                    <img src="../../assets/project/projectjr.svg" alt="project jr.">
                </div>
                <div class="card2">
                    <img src="../../assets/project/global.svg" alt="global pen">
                    <div class="desc">
                        <h3 class="title-card2"><strong>G</strong>LOBAL PEN.</h3>
                        <div class="txt">
                            <p class="lib"><span>T</span>he web-global project was the first freelance project I did for the company as a programmer, in this I tested my skills as a programmer and as a UI/UX designer. So, I carried out all the construction of the project myself, from the creation of the screen, as well as the implementation in code, the languages I used were: HTML, CSS and javascript with vue.js framework. Finally, the completion of the project was excellent, I was recognized for the effort and work I put into this project.</p>
                            <a href="https://github.com/Lima404/Web-Global">
                                <p class="show">SHOW MORE ></p>
                            </a>
                        </div>
                    </div>
                </div>
                <div class="card3">
                    <div class="desc">
                        <h3 class="title-card1"><strong>T</strong>EST BYTE LANDING PAGE</h3>
                        <div class="txt">
                            <p class="lib"><span>T</span>his was a project I did for the selection of the company byte seridó jr., here I put into practice web development concepts in HTML and CSS that I was studying and improving to develop a landing page with some differentials, the star of the project were some buttons with 3D animation, at the time I was very excited with the result, today I see that it was something simple.</p>
                            <a href="https://github.com/Lima404/byte-curriculo">
                                <p class="show">SHOW MORE ></p>
                            </a>
                        </div>
                    </div>
                    <img src="../../assets/project/landing.svg" alt="landig page">
                </div>
                <div class="card4">
                    <img src="../../assets/project/sigbike.svg" alt="sig-bike">
                    <div class="desc">
                        <h3 class="title-card2"><strong>S</strong>IG-BIKE</h3>
                        <div class="txt">
                            <p class="lib"><span>T</span>he sig-bike project was a programming study project written in C language, here the objective was to make a crud that manages a bicycle and electric skate rental shop.</p>
                            <a href="https://github.com/Lima404/SIG-BIKE">
                                <p class="show">SHOW MORE ></p>
                            </a>
                        </div>
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

    .project{
        max-width: 1085px;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px 3px 60px;
        gap: 100px;
        border-bottom: 2px solid #000000;
    }

    .title{
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        gap: 10px;
    }

    .box{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0px 29px;
        gap: 5px;
    }

    .title-card1{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 700;
        font-size: 40px;
        line-height: 46px;


        color: #000000;
    }

    .title-card2{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 700;
        font-size: 40px;
        line-height: 46px;
        text-align: right;

        color: #000000;
    }

    .show{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 400;
        font-size: 12px;
        line-height: 14px;
        text-align: right;
        transition: 1s;

        color: #000000;
    }

    .desc{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 0px;
        gap: 30px;
    }

    .card1{
        display: flex;
        flex-direction: row;
        justify-content: flex-end;
        align-items: flex-start;
        padding-bottom: 20px;
        border-bottom: 1px solid #000000;
        gap: 60px;
    }

    .card2{
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        padding-bottom: 20px;
        border-bottom: 1px solid #000000;
        gap: 60px;
    }

    .card3{
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        padding-bottom: 20px;
        border-bottom: 1px solid #000000;
        gap: 60px;
    }

    .card4{
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        gap: 60px;
    }

    .lib{
        margin-bottom: 30px;
        font-weight: 500;
    }

    h2{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 700;
        font-size: 32px;
        line-height: 37px;
        color: #000000;
    }

    p{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 25px;
        text-align: justify;

        color: #000000;
    }

    span{
        font-size: 32px;
    }

    img{
        margin-top: 40px;
    }

    a{
        text-decoration: none;
    }

    .show:hover{
        font-size: 14px;
        text-decoration: underline;
    }


    
</style>