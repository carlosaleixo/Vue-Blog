<script setup>
import Corpo2 from './CorpoBlog2.vue'
import img2 from '../assets/post1.webp'
import img3 from '../assets/post2.webp'
import img4 from '../assets/post3.webp'
</script>

<template>
    <header>
        <Corpo2 :post="img2" 
            titulo="MySQL no Google Cloud SQL"
            txt="Este post é um é um guia passo a passo para você aprender a hospedar o seu banco de dados MySQL no Google Cloud SQL.
            Obviamente você precisa de uma conta no Google e um cartão de crédito para ativar o faturamento. Se for a primeira 
            vez o Google irá te dar $300 para experimentar qualquer serviço, assim você pode aprender, conhecer e até avaliar os preços cobrados.
            Todos os serviços que você configura no GCloud ficam agrupados por projetos, então a primeira coisa a se fazer é criar ou selecionar um projeto." 
        />
        <br>
        <span> _________________________________________________</span>
        <Corpo2 :post="img3" 
            titulo="Programação Funcional - Tudo o Que Você Precisa Saber! Artigo 1 de 10" 
            txt="Olá Pessoal nesta série vamos falar sobre um importante Paradigma de Programação, A Programação Funcional e como ela é 
            aplicada no JavaScript. Preparamos uma Série de 10 artigos para abordar com exemplos o que é a Programação Funcional, Esse 
            é o primeiro artigo. Quais são os conceitos que fazem parte desse Paradigma e como Programar em JavaScript utilizando a Programação 
            Funcional? Veja a resposta nesta série completa.
            Obs. ao Leitor: Por vezes caro leitor, você verá em nossos posts a sigla TL;DR quando ela estiver presente prepare-se, vêm texto longo por aí, 
            assim o resumo do post será colocado no Parágrafo TL;DR algo como Too Long Didn't Read ou Texto Longo, Não Li."
        />
        <br>
        <span> __________________________________________________</span>
        <Corpo2 :post="img4" 
            titulo="Instalando e Configurando o PHP 7 e o Apache no Windows com Xampp" 
            txt="PHP 7 é a linguagem por trás dos maiores sites do mundo, entre eles, Facebook, Google, Wikipedia e muitos outros *. Preparamos um vídeo que faz 
            parte do Curso Completo de PHP 7 da ETEC na Udemy para ensinar como instalar e configurar o PHP 7 e o Apache utilizando um facilitador para isso o XAMPP.
            Existe uma diferença entre Linguagem de Programação e Servidor Web, neste vídeo abordamos a diferença entre essas tecnologias e o que é um instalador como o XAMPP."
        />
    </header>
</template>

<style scoped>
span{
  color: red;
}
</style>