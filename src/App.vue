<script setup>
import { RouterLink, RouterView } from "vue-router";
import Navbar from './components/nav.vue'
import Home from './components/home.vue'
import Doyouknow from './components/doyouknow.vue'
import Lesgo from "./components/lesgo.vue";
import Footer from "./components/footer.vue";

</script>

<template>
    <div class="bg-gradient-to-r from-[#F8EFFE] to-[#E9F6F5]">
        <Navbar/>
        <Home/>
        
    </div>
    <Doyouknow/>
    <Lesgo/>
    <Footer/>
    

<RouterView />
</template>

