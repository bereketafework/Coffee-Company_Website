<template>
  <v-card>
    <v-toolbar
      
      class="!h-16 !bg-[#7cea72] !border-none sticky"
    >
    <button class="text-3xl font-bold hover:scale-105 ml-2 " router:to="/Home.vue" >Nokka Coffee </button>

      
       <v-spacer></v-spacer>
       <v-tabs v-model="currentItem" @change="currentItem" >
          <v-tab :key="'tab-home'" :value="'tab-home'">
            <router-link to="/">Home</router-link>
          </v-tab>
          <v-tab :key="'tab-shopping'" :value="'tab-shopping'">
            <router-link to="/about">About Us</router-link>
          </v-tab>
          <v-tab :key="'tab-videos'" :value="'tab-videos'">
            <router-link to="/gallery">Gallery</router-link>
          </v-tab>
          <v-tab :key="'tab-images'" :value="'tab-images'">
            <router-link to="/contact ">Contact Us</router-link>
          </v-tab>
        </v-tabs>

     
    </v-toolbar>

  
    <router-view></router-view>
</v-card>
</template>
<script>
import Navbar from './components/Navbar.vue';

 export default {
  components: { Navbar },
  data: () => ({
    currentItem: ''
  })
  
};
</script>

