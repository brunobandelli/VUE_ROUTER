<template>
    <div>
        <h4>Rota Pai</h4>
        <input type="text" name="email" id="email" placeholder="E-mail"><br>
        <input type="text" name="nome" id="nome" placeholder="Nome"><br>
        <button>Teste!</button>
        <h4>{{parametroDaRota}}</h4>
        <router-view/>

    </div>
</template>

<script>
export default {
    created(){
        // console.log("Bruno Bandelli")
        // console.log(this.$route.params.dado)
        // this.parametroDaRota = this.$route.params.dado
    },
    data(){
        return {
            parametroDaRota: "Nada"
        }
    }
}
</script>

