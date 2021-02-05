<template>
    <div id="app">
        <h1>Vue JS</h1>
        <Post titulo="olaaaa">
            <template v-slot:cabecalho>
                <h2>Titulo</h2>
            </template>
            <template v-slot>
                <p>Conteudo</p>
            </template>
            <template v-slot:rodape>
                <small>Rodape</small>
            </template>
            <template v-slot:botao>
              Detalhes
            </template>
        </Post>

        <Post titulo="olaaaa">
            <template v-slot:cabecalho>
                <h2>Titulo</h2>
            </template>
            <template v-slot>
                <p>Conteudo</p>
            </template>
            <template v-slot:rodape>
                <small>Rodape</small>
            </template>
        </Post>

        <Post titulo="olaaaa">
            <template v-slot:cabecalho>
                <h2>Titulo</h2>
            </template>
            <template v-slot>
                <p>Conteudo</p>
            </template>
            <template v-slot:rodape>
                <small>Rodape</small>
            </template>
        </Post>
       
    </div>
</template>

<script>
import Post from "./components/Post.vue";
export default {
    components: {
        Post,
    },
};
</script>

<style>
</style>