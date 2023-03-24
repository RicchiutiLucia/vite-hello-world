<script>
export default {
    data(){
        return {
            message: 'La mia prima app con Vite!'
        }
    }
}
</script>

<template>

    <div>
        <h1 class="title">
            {{ message }}
        </h1>
    </div>

</template>

<style scoped>
.title {
    color: blueviolet;
    border: 2px solid blue;
    padding: 30px;
}
</style>