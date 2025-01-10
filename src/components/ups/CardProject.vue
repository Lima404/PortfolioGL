<template lang="pt-br">
    <section class="porject-container">
        <div class="container project">
            <div class="box">
                <div class="card" v-for="project in projects" :key="project">
                    <div class="desc">
                        <h3 class="title-card1">{{ project.nome }}</h3>
                        <div class="txt">
                            <p class="lib"><span>{{project.FirstLetter}}</span>{{project.txt}}</p>
                            <a :href="project.Link1" target="blank">
                                <img src="/icons/Vector.svg" alt="">
                            </a>
                            <a :href="project.Link2" target="blank">
                                <img src="/icons/internet.svg" alt="">
                            </a>                            
                        </div>
                    </div>
                    <img :src="project.img" :alt="project.alt">
                </div>
                
            </div>
        </div>
    </section>
</template>
<script>
export default {
    data() {
        return{

                    
            projects: [

                {
                    nome: "Project Jr.",
                    FirstLetter: "E",
                    txt: "sse projeto foi meu primeiro contato com o mercado de trabalho, junto com uma equipe desenvolvi esse projeto de site para outra empresa jr. Além disso, me desenvolvi muito como profissional, aprendi a trabalhar melhor em equipe, a estudar programação, a desenvolver liderança, proatividade e metodologias ágeis. Por fim, este foi o projeto responsável por iniciar minha vida profissional como programador frod-end e designer de interfaces.study programming, to develop leadership, proactivity and agile methodologies. Finally, this was the project responsible for starting my professional life as a frod-end programmer and interface designer.",
                    Link1: "https://github.com/Lima404/Web-Global",
                    Link2: "https://project-jr.vercel.app",
                    img: "/project/projectjr.svg",
                    alt: "project jr.",
                },

                {
                    nome: "Global Pen",
                    FirstLetter: "O",
                    txt: " projeto web-global foi o primeiro projeto freelance que fiz para a empresa como programador, neste testei minhas habilidades como programador e como UI/UX designer. Então, eu mesmo realizei toda a construção do projeto, desde a criação da tela, bem como a implementação em código, as linguagens que utilizei foram: HTML, CSS e javascript com framework vue.js. Por fim, a conclusão do projeto foi excelente, fui reconhecido pelo esforço e trabalho que coloquei neste projeto.",
                    Link1: "https://github.com/Lima404/Web-Global",
                    Link2: "https://globalpen.netlify.app",
                    img: "/project/global.svg",
                    alt: "global pen"
                },

                {
                    nome: "Projeto Avicultura",
                    FirstLetter: "P",
                    txt: "rojeto avicultura foi um projeto que fiz como Diretor de Marketing pela Byte Seridó jr em parceiria com a empresa de desenvolvimento de sistema Viggo para a avicultura zangarelhas no municipio de acari RN, nesse projeto coordenei uma equipe a desenvolver as telas front-end web e mobile com UX/UI design, foi um projeto cheio de desafios, aqui aprendi a coordenar equipe, treinar pessoas, ensinar metodologias ágeis, atender o cliente, criar ideias, e pensar fora da caixa, foi a experiencia mais enriquecedora que tive durante meu tempo na EJ.",
                    Link1: "https://www.figma.com/design/tq7zYkAXH2AeVDFLTVlGpC/Avicultura----Byte-%2B-Viggo?node-id=302-36&t=z3gozc873XrRi2LQ-1",
                    Link2: "https://www.figma.com/design/tq7zYkAXH2AeVDFLTVlGpC/Avicultura----Byte-%2B-Viggo?node-id=302-36&t=z3gozc873XrRi2LQ-1",
                    img: "/project/avicultura.svg",
                    alt: "avicultura"
                },

                {
                    nome: "SigStorage",
                    FirstLetter: "O",
                    txt: " SigStorage foi um projeto que fiz para a disciplina de engenharia de softwere da faculdade, nele eu trabalhei como desenvolvedor front-end e Designer UX, foi um projeto que me dediquei bastante aos estudos de UX para criar uma plataforma com uma exceletne experiência de usuário, focada em um design minimalista e um dashboard de vendas.",
                    Link1: "https://github.com/Lima404/SigStorage_front",
                    Link2: "https://www.figma.com/proto/0R93mKRWYoRlrEmat2ZdK5/Projeto-Engenharia-de-softwere-2?node-id=76-2&p=f&t=CT3tMZjGrgBAfmR1-1&scaling=min-zoom&content-scaling=fixed&page-id=7%3A52&starting-point-node-id=76%3A2",
                    img: "/project/sigstorage.svg",
                    alt: ""
                },

                {
                    nome: "WhaleTale",
                    FirstLetter: "O",
                    txt: " projeto WhaleTale foi um freelance que fiz para uma startup de gamificação com nft, nela prestei serviços como UX e desenvolvi algumas interfaces para sua aplicação, Meu contrato com ela foi curto, pois pediram poucas e telas e muitos assets para compor artisticamente o projeto, foi um desafio para mim já que o estilo do projeto que eles me pediram é bem diferente do que estou acostumado a fazer, porém foi uma experiência enriquecedora onde descobri o quão adaptavél eu sou para desenvolver projetos fora da minha zona de conforto.",
                    Link1: "https://www.figma.com/design/gisAV6WPXSkgmiECfCxpUW/Projeto-WhaleTale?node-id=21-270&t=JpCMmFCwZxqd0Omp-1",
                    Link2: "https://www.figma.com/proto/gisAV6WPXSkgmiECfCxpUW/Projeto-WhaleTale?node-id=77-40&p=f&t=JpCMmFCwZxqd0Omp-0&scaling=min-zoom&content-scaling=fixed&page-id=52%3A2",
                    img: "/project/whaletale.svg",
                    alt: "whaletale"
                },

                {
                    nome: "AloMid",
                    FirstLetter: "A",
                    txt: " alomid é uma agencia de logistas de todas as empresas localizadas no shopping midway em natal, nela fiz uma parceiria com a byte seridó jr. para atuar na parte de arquitetura do sistema e modelagem de dados e gestão de projetos, além de tambem treinar uma equipe própria do midway como designer UX para utilizarem a ferramenta Figma, como material inicial, desenvolvi a landing page em grupo ensinando a eles todos os conceitos de componentização, prototipação, e vetorização que eles precisavam para criar os restantes das telas",
                    Link1: "https://www.figma.com/design/W7534IcHgLOjp6ye6JMVvC/Alomid---Apresenta%C3%A7%C3%A3o-(Copy)?node-id=2002-11&t=JpCMmFCwZxqd0Omp-1",
                    Link2: "https://www.figma.com/design/W7534IcHgLOjp6ye6JMVvC/Alomid---Apresenta%C3%A7%C3%A3o-(Copy)?node-id=2002-11&t=JpCMmFCwZxqd0Omp-1",
                    img: "/project/alomid.svg",
                    alt: "alomid"
                },

                {
                    nome: "PráticaSST",
                    FirstLetter: "O",
                    txt: " projeto PráticaSST foi um freelancer que consegui junto com colegas da faculdade, nós desenvolvemos um sistema de gestão de clientes de distribuição de documentos referentes a saúde e segurança do trabalho, foi o primeiro grande projeto que desenvolvemos sozinho, na qual aprendemos bastante sobre modelagem de banco de dados, interfaces do sistema, e expériencia de usuário, nesse projeto atuei como um pouco de tudo, Back-end, Front-end, Designer UX, Gestor de Projetos, QA, foi um projeto bem desafiador, já que a maior parte deles tivemos que estudar bastante e se virar sozinhos sem orientação, no fim conseguimos entregar o sistema 100% funcional, e me orgulho bastante de o ter finalizado!",
                    Link1: "https://github.com/Lima404/sst-practice-front-end",
                    Link2: "https://sst-practice-front-end.vercel.app",
                    img: "/project/praticasst.svg",
                    alt: "praticasst"
                },

            ],
            computed: {
                hasLink2() {
                return this.projects.some(project => project.Link2);
            }
            }
        }
    }
}
</script>
<style scoped>

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
        text-align: left;

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

    .show:hover{
        font-size: 14px;
        text-decoration: underline;
    }

    .desc{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 0px;
        gap: 30px;
    }

    .card{
        margin-top: 20px;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        padding-bottom: 20px;
        border-bottom: 1px solid #000000;
        gap: 60px;
    }

    .card1{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        padding-bottom: 20px;
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
        margin-left: 15px;
    }

   

    @media (max-width:860px){

        .card{
            max-width: 50%;
            flex-wrap: wrap;
        }

        .card1{
            max-width: 50%;
            flex-wrap: wrap;
        }
    }

    @media (max-width:650px){

        .card{
            max-width: 50%;
            flex-wrap: wrap;
        }

        .card1{
            max-width: 50%;
            flex-wrap: wrap;
        }
}

    @media(max-width:610px){
        img{
            display: none;
        }
    }


</style>