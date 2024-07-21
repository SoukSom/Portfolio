<script setup>

</script>

<template>
<div class="about-container h-full lg:h-screen flex items-center py-10">
    <div class="grid grid-cols-1 lg:grid-cols-2 w-full">
        <div class="flex justify-center">
            <div class="image-container hidden lg:flex w-1/4 lg:w-1/2">
                <img src="../assets/image/My_profile2.jpg" class="rounded-xl w-full h-full z-10">
                <div class="border-position border border-warning rounded-xl w-full h-full"></div>
            </div>
        </div>
        <div class="flex flex-col justify-center items-start">
            <div>
                <div class="flex justify-center">
                    <p class="text-white font-bold mb-10 px-10 text-2xl sm:text-4xl">ABOUT <span class="text-warning">ME</span></p>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-1 w-full">
                    <div class="flex justify-center w-full">
                        <div class="about-image-container flex justify-center w-6/12 sm:w-8/12 lg:hidden mb-10 sm:mb-0">
                            <img src="../assets/image/My_profile.jpg" class="profile-image z-10 rounded-ss-3xl rounded-ee-3xl   w-full">
                            <div class="border-image flex  h-full w-full rounded-ss-3xl rounded-ee-3xl"></div>
                        </div>
                    </div>
                    <div class="md:flex flex-col justify-center lg:block">
                        <p class="text-white leading-relaxed tracking-wide px-10 mb-2 sm:mb-5">Hello, my name is Souksomvang Xengnengxai, you can call me Souk. I'm a student at National University of Laos, Faculty of Engineering, Department of Computer Engineering and Information Technology.</p>
                        <p class="text-white leading-relaxed tracking-wide px-10">My MBTI type is INFP. I'm a quiet person and am trying to develop my communication skills. My goal is to become a fullstack developer.</p>
                    </div>
                </div>
            </div>
        </div>    
    </div>
</div>
</template>

<style scoped>
.about-container{
    background: #020617;
}

.image-container{
    position: relative;
}

.image-container img{
    position: relative;
    box-shadow: 0 0 3px #ffa600;
}

.profile-image{
    box-shadow: 0 0 10px #6c6c6a;
}

.border-position{
    border: 15px solid #ffa600;
    box-shadow: 0 0 5px #ffa600;
    position: absolute;
    left: -30px;
    bottom: -30px;
}

.about-image-container{
    position: relative;
}

.border-image{
    position: absolute;
    border: 10px solid #ffa600;
    box-shadow: 0 0 5px #ffa600;
    position: absolute;
    right: -20px;
    top: -20px;
}
</style>