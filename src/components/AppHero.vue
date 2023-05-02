<script>
    import AppTitle from "./AppTitle.vue"
    export default{
        name: "AppHero",
        components: {
        AppTitle
        },
        data(){
            return{

            }
        },
        methods: {
            
        },
    }
    
</script>

<template>
    <div class="jumbotron jumbotron-fluid">
        <div class="container">
            <AppTitle/>
            <p class="lead">This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
        </div>
    </div>
</template>

<style scoped>

div {
    color: #B6E1F2;
}


</style>