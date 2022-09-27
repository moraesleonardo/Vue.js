<template>
<div id="align">
    <div>
        <b-jumbotron id="back" header="Aluno Leonardo Moraes" lead="Assessment de Frameworks Front-end e conexão com Back-end">
        </b-jumbotron>
    </div>     
</div>
</template>

<script>
import ToastMixin from "@/mixins/toastMixin.js";

export default {
name: "Home",
}
</script>

<style>
#back{
    background-color: #gray;
    }
#align{
    height: calc(40vh - 36px);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: botton;
    text-align: center;
}
</style>