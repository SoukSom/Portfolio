<script setup>
import { ref } from 'vue'
import Home from "./components/Home.vue";
import About from "./components/About.vue";
import Skill from "./components/Skill.vue";
import Project from "./components/Project.vue"
import Contact from "./components/Contact.vue"

const showScrollToTop = ref(false);

const onScroll = () => {
  showScrollToTop.value = window.scrollY > 200
}

const scrollToTop = () => {
  window.scrollTo({
    top: 0,
    behavior: 'smooth',
  });
};

window.addEventListener('scroll', onScroll);
</script>

<template>
  <div>
    <div class="navbar px-3 sticky top-0 z-40">
      <div class="hidden sm:flex">
        <a href="#home" class="banner text-xl text-white font-bold">About<span class="text-warning">Me.</span></a>
      </div>
      <div class="w-full">
        <ul class="flex justify-center px-1 w-full sm:justify-end">
          <li class="nav-link px-3 text-xs sm:text-sm"><a href="#home">Home</a></li>
          <li class="nav-link px-3 text-xs sm:text-sm"><a href="#about">About</a></li>
          <li class="nav-link px-3 text-xs sm:text-sm"><a href="#skill">Skill</a></li>
          <li class="nav-link px-3 text-xs sm:text-sm"><a href="#project">Project</a></li>
          <li class="nav-link px-3 text-xs sm:text-sm"><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
    <Home id="home"></Home>
    <About id="about"></About>
    <Skill id="skill"></Skill>
    <Project id="project"></Project>
    <Contact id="contact"></Contact>
    <button 
        v-if="showScrollToTop"
        @click="scrollToTop"
        class="scroll-to-top-button btn btn-warning"
    >
      <span class="iconify" data-icon="ep:caret-top" style="color: white;"></span>
    </button>
  </div>
</template>

<style scoped>
.navbar{
  background: #020617;
  color: #ffff;
}
  
.banner{
  cursor: pointer;
}

.banner:hover{
  text-shadow: 5px 0 10px #ffff ;
}

.nav-link{
  cursor: pointer;
}

.nav-link:hover{
  text-shadow: 0 0 10px  #ffff;
  color: #FFA500;
}

.nav-link:focus, .nav-link:active{
  color: #FFA500;
}

.scroll-to-top-button {
  position: fixed;
  bottom: 50px;
  right: 20px;
  width: 50px;
  height: 50px;
}
</style>
