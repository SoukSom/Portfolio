<script setup>

</script>

<template>
    <div class="contact-container h-full flex flex-col items-center justify-center p-10">
        <div class="mb-10">
            <p class="text-2xl lg:text-4xl text-white font-bold">CONTACT <span class="text-warning">ME</span></p>
        </div>
        <div class="sm:mt-10 mx-10 px-10 w-full flex flex-col justify-center items-center sm:flex-row sm:justify-between">
            <div class="mb-10 sm:md-0 sm:ms-10 sm:ps-10">
                <p class="text-white mb-5 font-bold text-xl text-center">Contact:</p>
                <div>
                    <div class="text-warning font-medium flex items-center"><span class="iconify" data-icon="bx:bxs-phone-call" style="color: #ffa600"></span> <span class="text-white font-normal ms-2">+856 2058 5891 13</span></div>
                </div>
                <div>
                    <div class="text-warning font-medium flex items-center"><span class="iconify" data-icon="ic:sharp-email" style="color: #ffa600"></span> <span class="text-white font-normal ms-2">souksomvank@gmail.com</span></div>
                </div>
            </div>
            <div class="sm:me-10 sm:pe-10 flex flex-col items-center">
                <p class="text-xl mb-5 font-bold text-white w-full text-center">Socail Media:</p>
                <div class="grid grid-cols-3">
                    <a href="https://www.facebook.com/souksomvang.cheng.3" target="_blank" class="socail-icon mx-5">
                        <span class="iconify" data-icon="ant-design:facebook-filled" style="color: white"></span>
                    </a>
                    <a href="https://www.instagram.com/xux_knos/" target="_blank" class="socail-icon mx-5">
                        <span class="iconify" data-icon="akar-icons:instagram-fill" style="color: white"></span>
                    </a> 
                    <a href="https://github.com/SoukSom" target="_blank" class="socail-icon mx-5">
                        <span class="iconify" data-icon="akar-icons:github-fill" style="color: white"></span>
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.contact-container{
    background: #111827;
}

.socail-icon{
    font-size: 32px;
}
</style>