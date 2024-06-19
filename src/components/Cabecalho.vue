<script setup>
import { useRouter } from 'vue-router';
defineProps({
    titulo: {
        type: String,
        required: true
    },
    logo: {
        type: String,
        required: true
    },
})
</script>

<template>
    <nav>
        <div id="cab">
            <div id="div_logo">
                <span>
                    <img :src="logo" >
                </span>
            </div>
            <div id="login" @submit.prevent="goToPosts">
                <button id="b" class="btn btn-primary">Sair</button>
            </div>
            <div id="div_titulo">
                <span>{{ titulo }}</span>
            </div>
        </div>
    </nav>
</template>

<style scoped>
    nav {
        background-color: white;
        color: white;
        padding: 20px;
        right: 0px;
        width: 90%;
        position: absolute;
        top: 0px;
    }
    #cab{
        display: flex;
        justify-content: space-between;
    }
    #div_logo{
        display: flex;
        align-items: center;
        margin: auto;
    }
    #div_titulo{
        color:black;
    }
    #login{
        text-align: right;
        width: 100%;
    }
    #b{
        width: 75px
    }
</style>