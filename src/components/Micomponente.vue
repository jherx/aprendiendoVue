<template>
    <div>
        <h1>Mi primer componente</h1>
        <h2>{{sub}}</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam voluptatem commodi quasi, impedit dicta similique eius officiis ab quia quos esse maiores quas eveniet voluptates, fugit sequi facilis tempore! Impedit.</p>
        <form action="">
            <input type="color" name="coloreate" id="colors">
        </form>
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