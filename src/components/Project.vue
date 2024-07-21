<script setup>

</script>

<template>
    <div class="project-container flex flex-col items-center justify-center p-10 h-full lg:h-screen">
        <div class="title">
            <p class="text-2xl lg:text-4xl font-bold text-white">PRO<span class="text-warning">JECT</span></p>
        </div>
        <div class="flex flex-col justify-center items-center">
            <p class="content-text text-white text-2xl lg:text-6xl font-bold">COMMING SOON . . .</p>
            <p class="text-white font-medium mt-7">or follow my <a href="https://github.com/SoukSom" target="_blank" class="text-warning">GitHup</a></p>
        </div>
    </div>
</template>

<style scoped>
.project-container{
    background: #020617;
}

.content-text{
    text-shadow: 0 0 100px #ffa600;
}

.title{
    margin-bottom: 50px;
}

@media (min-width: 640px) {
    .title{
        margin-bottom: 100px;
    }
}
</style>