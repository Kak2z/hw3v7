<template>
  <div>
    <Navbar />
    <div class="flex main-container">
      <Sidebar />
      <div class="container">
          <nuxt />
      </div>
    </div>
  </div>
</template>

<script>


import { Component, Vue } from 'nuxt-property-decorator';
import Navbar from '@/components/navbar'
import Sidebar from '@/components/sidebar'

export default @Component({
  name: 'Default',
  components: { Navbar, Sidebar }
})

class Default extends Vue {
  
}
</script>

<style>
.main-container {
  min-height: 100vh;
}
.flex {
  display: flex;
} 
</style>
