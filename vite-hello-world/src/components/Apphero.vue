<template>
     <div class="jumbotron">
        <p>{{ hero }}</p>
    </div>
</template>

<script>
    export default {
        name: 'Apphero',
        data() {
            return{
                hero: 'Benvenuti nella mia app creata con Vite.'
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>