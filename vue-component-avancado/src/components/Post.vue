<template>
    <div class="post">
        <div class="post-cabecalho">
            <slot name="cabecalho"></slot>
        </div>
        <div class="post-conteudo">
            <slot></slot>
        </div>
        <div class="post-rodape">
            <slot name="rodape"></slot>
            <a href="#" class="link">
                <slot name="botao">Ler mais...</slot>
            </a>
        </div>
    </div>
</template>

<script>
export default {};
</script>

<style scoped>
.post {
    margin: 15px auto;
}

.post-cabecalho {
    padding: 5px 12px;
    background-color: #eeeeee;
}

.post-conteudo {
    font-size: 16px;
}

.post-rodape {
    font-style: italic;
}

.link{
    float: right;
}
</style>