<template lang="pt-br">
    <section class="navbar-container">
        <div class="container navbar">
            <div class="box">
                <div class="links">
                    <a href="#" class="menu-buttom">HOME</a>
                    <a href="#" class="menu-buttom">WHO I'M</a>
                    <a href="#" class="menu-buttom">PROJECTS</a>
                    <a href="#" class="menu-buttom">SKILLS</a>
                    <a href="#" class="menu-buttom">HOOBYS</a>
                    <a href="#" class="menu-buttom">CONTACT</a>
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
    
    .navbar-container{
        background: #E1E1DD;
        display: flex;
        flex-direction: row;
    }

    .navbar{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        padding: 10px 145px;
        gap: 40px;  
    }

    .box{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        padding: 20px 150px;
        gap: 40px;
        box-sizing: border-box;
        border-width: 3px 0px 1px 0px;
        border-style: solid;
        border-color: #000000;
    }

    .links{
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        padding: 0px;
        gap: 50px;
    }

    .menu-buttom{
        font-family: 'Times New Roman';
        font-style: normal;
        font-weight: 400;
        font-size: 24px;
        line-height: 28px;
        color: #000000;
        text-decoration: none;
        transition: 0.5s;
    }

    .menu-buttom:hover{
        font-size: 26px;
        font-weight: 600;
    }



</style>