<!-- <template>
  <v-card>
    <v-toolbar

      class="!h-16 !bg-[#7cea72] !border-none sticky"
    >
    <button class="text-3xl font-bold hover:scale-105 ml-2 ">Noka Coffee </button>


       <v-spacer></v-spacer>
        <v-tabs
        center-active="true"
          v-model="currentItem"
          fixed-tabs
          slider-color="Black"
        >
          <v-tab

            v-for="item in items"
            :key="item"

          >
            {{ item }}
          </v-tab>

        </v-tabs>

    </v-toolbar>

    <v-tabs-items v-model="currentItem">
      <v-tab-item
        v-for="item in items.concat(more)"
        :key="item"

      >

      </v-tab-item>
    </v-tabs-items>

  <v-parallax
    src="https://th.bing.com/th/id/R.c125b21f444fdb5c57fa6d0024ecccae?rik=YiMEODDZAYMInA&pid=ImgRaw&r=0"
    height="700"
  >
    <div class="d-flex flex-column fill-height justify-center align-center text-white">
      <h1 class="text-7xl font-weight-thin mb-4 border-[1px] shadow-lg border-transparent">
        <span class="font-extrabold text-[#53e945]"  > Nokka</span> <span> Coffee</span>
      </h1>
      <h4 class="subheading text-[#2ec76b] text-3xl">
        Coffee Harvesting And Exporting
      </h4>
      <h5 class="w-[500px] text-2xl flex">
        Nokka Coffee is Located In west Guji Zone Engaged in cofffe harvesting and Producing
        for last 10 years and Exporting Coffee to International Maeket
      </h5>
      <div class="flex gap-10 m-5">
        <v-btn size="x-large">Contact Us</v-btn>
        <v-btn size="x-large">About  Us</v-btn>
      </div>


    </div>
  </v-parallax>
</v-card>
</template>
<script>
  export default {
    data: () => ({
      currentItem: 'tab-Web',
      items: [
        'Home', 'Gallery ', 'About Us', 'Contact Us', 'Servies',
      ],


    }),

    methods: {
      addItem (item) {
        const removed = this.items.splice(0, 1)
        this.items.push(
          ...this.more.splice(this.more.indexOf(item), 1),
        )
        this.more.push(...removed)
        this.$nextTick(() => { this.currentItem = 'tab-' + item })
      },
    },
  }
</script>

<style>

</style> --><template>
  <v-card>
    <v-toolbar
      
      class="!h-16 !bg-[#7cea72] !border-none sticky"
    >
    <button class="text-3xl font-bold hover:scale-105 ml-2 ">Nokka Coffee </button>

      
       <v-spacer></v-spacer>
       <v-tabs v-model="currentItem" fixed-tabs>
          <v-tab :key="'tab-home'" :value="'tab-home'">
            <router-link to="/">Home</router-link>
          </v-tab>
          <v-tab :key="'tab-shopping'" :value="'tab-shopping'">
            <router-link to="/shopping">Shopping</router-link>
          </v-tab>
          <v-tab :key="'tab-videos'" :value="'tab-videos'">
            <router-link to="/avout">Videos</router-link>
          </v-tab>
          <v-tab :key="'tab-images'" :value="'tab-images'">
            <router-link to="/images">Images</router-link>
          </v-tab>
        </v-tabs>
     
    </v-toolbar>

  
    <router-view></router-view>
</v-card>
</template>
<script>
 export default {
  data: () => ({
    currentItem: 'tab-home'
  })
};
</script>

<style>

</style>