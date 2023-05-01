<template lang="pt-br">
    <div class="navbar-container">
        <div class="container navbar">
            <div class="card">
                <a class="menu-buttom">Home</a>
                <a class="menu-buttom">Projects</a>
                <a class="menu-buttom">Dashboard</a>
                <a class="menu-buttom">Contact</a>
                <a class="menu-buttom">Mensage</a>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    
    .card{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        gap: 30px;
        position: absolute;
        left: 26%;
        top: 600px;
    }

    .menu-buttom{
        color: black;
        display: flex;
        align-items: center;
        justify-content: center;
        font-family: 'Roboto Mono';
        border: 1px solid white;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        border-radius: 20px;
        width: 150px;
        height: 150px;
        cursor: pointer;
        padding: 10px 20px;
        transition: 0.5s ease-in-out;
    }

    .menu-buttom:hover{
        width: 200px;
        height: 200px;
        background-color: rgba(255, 255, 255, 0.301);
        font-size: 2rem;
        opacity: 1px;
    }

</style>