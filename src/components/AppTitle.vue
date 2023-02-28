<script>
export default{
    data() {
        return {
            mainTitle: "La mia prima app con Vite!"

        }
    }
}
</script>

<template>
    <div>
        <h1  class="main_title">
            {{ mainTitle }}
        </h1>
    </div>
</template>

<style>
    .main_title{
        position: absolute;
        top: 70%;
        left: 50%;
        transform: translate(-50%, -50%);
        color: darkviolet;
    }
</style>