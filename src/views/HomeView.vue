<template>
  <BannerBurger/>
  <div class="main-container">
    <h1>Monte Seu Burger</h1>
    <BurgerForm/>
  </div>
</template>

<script>
  import BannerBurger from '../components/Banner.vue';
  import BurgerForm from '@/components/BurgerForm.vue';

  export default{
    name:"HomerView",
    components:{
    BannerBurger,
    BurgerForm
}
  }
</script>
