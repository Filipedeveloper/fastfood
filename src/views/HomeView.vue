<template>
  <TheBanner/>
  <div class="main-container">
    <h1>Monte o seu banner </h1>
    <TheBurgerForm/>  
  </div>
  
</template>

<script>
import TheBanner from '@/components/TheBanner.vue';
import TheBurgerForm from '@/components/TheBurgerForm.vue';




export default {
  name: 'HomeView',
  components: {
    TheBanner,
    TheBurgerForm
    
  }
}
</script>
