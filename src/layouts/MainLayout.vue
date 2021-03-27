<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container>

      <div class="fit column no-wrap justify-start items-center content-start">
        <div class="section-1">
          <Navbar class="navbar"/>
          <div class="sec-1">
            <h1>A modern publishing platform</h1>
            <p>Grow your audience and build your online brand</p>
            <div class="button-sec-1 fit row wrap justify-center items-start content-start">
            <div class="q-pr-md">
              <q-btn unelevated rounded size="13px" text-color="white" label="Login" />
            </div>
            <div class="q-pl-md">
              <q-btn unelevated rounded size="13px" color="white" text-color="primary" label="Sign Up" />
            </div>
          </div>
          </div>
            <div class="img"></div>
        </div>
        <div class="section-2">
          <SectionTwo/>
        </div>
        <div class="section-3">
          <div class="img"></div>
          <SectionThree/>
        </div>
        <div class="section-4">Section-4</div>
        <div class="section-5">Section-5</div>
        <div class="section-6">Section-6</div>
        <div class="section-7">Section-7</div>
      </div>

      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import SectionThree from 'src/pages/SectionThree.vue'
import Navbar from '../pages/Navbar'
import SectionTwo from '../pages/SectionTwo'
export default{
  name: 'MainLayout',

  components: {
    Navbar,
    SectionTwo,
    SectionThree
  },

  setup () {

    }
  }

</script>

<style lang="scss" scoped>
/* For positioning an image as a background of a certain portion of a webpage,
  that image should be wrapped by a relative positioned wrapper. Just as bellow:
*/
  .section-1{
    border-radius: 0px 0px 0px 50px;
    height: 400px;
    width:100%;
    position: relative;
    background: linear-gradient(90deg, rgba(255, 143, 112, 0.897) 0%, rgba(255, 61, 84, 0.801) 100%);
    margin-bottom: 100px;
  }
  .section-2{
        margin-bottom: 100px;
  }
    .section-3{
      display: flex;
      justify-content: center;
      align-items: center;
    border-radius: 0px 100px 0px 120px;
    height: 350px;
    width:100%;
    position: relative;
    z-index: -1;
    background: linear-gradient(90deg, rgba(44,45,63,1) 0%, rgba(63,65,100,1) 100%);
    margin-bottom: 100px;
    .img{
    background-image: url("../assets/bg-pattern-circles.svg");
    background-size: 850px 850px ;
    // background-size: cover ;
    background-repeat: no-repeat;
    background-position: bottom left;
    // background-position: center center;
    background-color: rgba(0, 0, 0, 0);
    inset: 0px;
    opacity: 1;
    position: absolute;
    width: 100%;
    height: 100%;
    // z-index: 0;
  }
  }

  .img{
    background-image: url("../assets/bg-pattern-intro.svg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    background-color: rgba(0, 0, 0, 0);
    inset: 0px;
    opacity: 1;
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: -1;
  }
  .sec-1{
    margin: 5px auto;
    text-align: center;
    color: white;
    h1{
      font-size: 40px;
    }
  }

</style>