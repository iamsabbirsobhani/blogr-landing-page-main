<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container>

      <div class="fit column no-wrap justify-start items-center content-start">
        <div class="section-1">
          <Navbar/>
          <!-- <div class="sec-1"> -->
            <div class="img"></div>
          <!-- </div> -->
        </div>
        <div class="section-2"></div>
        <div class="section-3"></div>
        <div class="section-4">Hi</div>
        <div class="section-5">Hi</div>
        <div class="section-6">Hi</div>
        <div class="section-7">Hi</div>
      </div>

      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import Navbar from '../pages/Navbar'
export default{
  name: 'MainLayout',

  components: {
    Navbar
  },

  setup () {

    return {
      }
    }
  }

</script>

<style scoped>
  .section-1{
    /* border:  5px solid black; */
    border-radius: 0px 0px 0px 50px;
    height: 300px;
    width:100%;
    position: relative;
    background: linear-gradient(90deg, rgba(255, 143, 112, 0.897) 0%, rgba(255, 61, 84, 0.801) 100%);
  }
  /* .sec-1{
    position: relative;
    height: 100%;
  } */
  .img{
    background-image: url("../assets/bg-pattern-intro.svg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    background-color: rgba(0, 0, 0, 0);
    inset: 0px;
    opacity: 1;
    position: absolute;
    width: 1200px;
    height: 100%;
    z-index: 1;
  }
</style>