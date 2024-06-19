<script setup>
defineProps({
  titulo: {
    type: String,
    required: true
  },
  txt: {
    type: String,
    required: true
  },
  post: {
        type: String,
        required: true
    }
})
</script>

<template>
    <div class="largura">
        <div class="cab">
            <div class="div_logo">
                <span>
                    <img :src="post">
                </span>
            </div>
            <div id="div_titulo">
                <span>{{ titulo }}</span>
            </div>
            <div id="div_txt">
                <span>{{ txt }}</span>
            </div>
        </div>
    </div>
</template>

<style scoped>
#div_titulo{
    color: red;
    font-family: 'Times New Roman';
}
#div_txt{
    font-family: 'Arial';
}
.cab{
    text-align: justify;
}
.largura{
    max-width: 90%;
    align-items: center;
    margin: auto;
}
.div_logo{
    max-width: 90%;
}
</style>