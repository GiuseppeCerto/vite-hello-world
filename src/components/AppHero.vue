<script>
export default{
    data() {
        return {
            subTitle: 'Hello World!'

        }
    }
}
</script>

<template>
    <div>
        <h3>
            {{ subTitle }}
        </h3>
    </div>
</template>

<style>
    .main_title{
        position: absolute;
        top: 30%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
</style>