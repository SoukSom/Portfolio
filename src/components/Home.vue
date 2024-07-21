<script setup>

</script>

<template>
    <div class="home-section h-96 lg:h-screen flex items-center px-10">
        <div class="grid grid-cols-1 lg:grid-cols-2 w-full">
            <div class="flex flex-col justify-center items-center">
                <div>
                    <p class="text-warning font-bold">Hello, Welcome</p>
                    <p class="text-white font-bold my-5 text-2xl sm:text-4xl" style="text-shadow: 0 0 5px #808080;">I'm Souksomvang Xengnengxai</p>
                    <p class="text-warning font-bold">Junior Developer</p>
                    <button class="contact-btn mt-5"><a href="#contact">Contact me</a></button>
                </div>
            </div>    
            <div class="hidden lg:flex justify-center">
                <div class="image-container w-1/2">
                    <img src="../assets/image/My_profile.jpg" class="rounded-xl w-full h-full z-10">
                    <div class="border-position border border-warning rounded-xl w-full h-full"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.home-section{
    background: #111827;
}

.contact-btn{
    padding: 10px;
    border: 2px solid #ffa600;
    border-radius: 5px;
    font-weight: bold;
    color: white;
}

.contact-btn:hover{
    box-shadow: 0 0 10px #ffa600;
}

.image-container{
    position: relative;
}

.image-container img{
    position: relative;
    box-shadow: 0 0 3px #ffa600;
}

.border-position{
    border: 15px solid #ffa600;
    box-shadow: 0 0 5px #ffa600;
    position: absolute;
    right: -30px;
    bottom: -30px;
}
</style>