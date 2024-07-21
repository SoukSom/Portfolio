<script setup>

</script>

<template>
  <div class="education-container h-full lg:h-screen p-10 flex items-center">
    <div class="w-full">
        <div class="w-full flex justify-center pt-10">
            <p class="text-warning font-bold pt-10 text-2xl lg:text-4xl">MY <span class="text-white">SKILL</span></p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10 mt-10 w-full">
            <div class="card-container card text-white w-ful border-1 shadow-xl">
                <div class="card-body">
                    <h2 class="card-title flex justify-center font-bold text-warning text-base lg:text-2xl">WEB DEVELOPMENT</h2>
                    <div class="flex justify-center py-5 md:py-10">
                        <div class="flex justify-center w-full">
                            <span class="iconify icon-size" data-icon="vscode-icons:file-type-html"></span>
                        </div>
                        <div class="flex justify-center w-full">
                            <span class="iconify icon-size" data-icon="vscode-icons:file-type-css"></span>
                        </div>
                        <div class="flex justify-center w-full">
                            <span class="iconify icon-size" data-icon="vscode-icons:file-type-js-official"></span>
                        </div>
                        <div class="flex justify-center w-full">
                            <span class="iconify icon-size" data-icon="vscode-icons:file-type-vue"></span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card-container card text-white w-full border-1 shadow-xl">
                <div class="card-body">
                    <h2 class="card-title flex justify-center font-bold text-warning text-base lg:text-2xl">UX/UI DESIGN</h2>
                    <div class="flex justify-center py-5 md:py-10">
                        <div class="flex justify-center w-full">
                            <span class="iconify icon-size" data-icon="logos:figma"></span>
                        </div>
                        <div class="flex justify-center w-full">
                            <span class="iconify icon-size" data-icon="devicon:canva"></span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card-container card text-white w-full border-1 shadow-xl">
                <div class="card-body">
                    <h2 class="card-title flex justify-center font-bold text-warning text-base lg:text-2xl">COMPUTER SKILL</h2>
                    <div class="flex justify-center py-5 md:py-10">
                        <div class="flex justify-center w-full">
                            <span class="iconify icon-size" data-icon="devicon:git"></span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<style scoped>
.education-container{
    background: #111827;
}

.card-container{
    background: #020617;
    border: 1px solid #ffa600;
    box-shadow: 0 0 10px #ffa600;
}

.icon-size{
    height: 64px;
    width: 64px;
}

@media (max-width: 639px) {
    .icon-size{
        height: 32px;
        width: 32px;
    }
}
</style>