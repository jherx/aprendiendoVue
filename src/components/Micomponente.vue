<template>
    <div>
        <h1>Mi primer componente</h1>
        <h2>{{sub}}</h2>
    </div>
</template>
<script>
export default {
    name:"Micomponente",
    data() {
        return{
            sub: "El primer subtitulo de un componente"
            }
    },
}
</script>