<template>
<div class="q-pa-lg fit row wrap justify-between items-start content-start">
    <q-bar class="qbar " >
        <div>
            <img class="q-pr-lg" src="../assets/logo.svg" alt="logo">
        </div>
      <div class="cursor-pointer non-selectable q-pr-lg" style="color: white;">
        Product
        <q-menu >
          <q-list dense style="min-width: 100px" >
            <q-item clickable v-close-popup>
              <q-item-section>Overview</q-item-section>
            </q-item>
            <q-item clickable v-close-popup>
              <q-item-section>Pricing</q-item-section>

            </q-item>
            <q-item clickable v-close-popup>

              <q-item-section>Marketplace</q-item-section>

            </q-item>
            <q-item clickable v-close-popup>

              <q-item-section>Features</q-item-section>
            </q-item>
            <q-item clickable v-close-popup>
              <q-item-section>Integrations</q-item-section>
            </q-item>

          </q-list>
        </q-menu>
      </div>

      <div class="q-ml-md cursor-pointer non-selectable q-pr-lg" style="color: white;">
        Company
        <q-menu auto-close>
          <q-list dense style="min-width: 100px">
            <q-item clickable>
              <q-item-section>About</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>Blog</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>Careers</q-item-section>
            </q-item>
          </q-list>
        </q-menu>
      </div>

      <div class="q-ml-md cursor-pointer non-selectable " style="color: white;">
        Connect
        <q-menu auto-close>
          <q-list dense style="min-width: 100px">
            <q-item clickable>
              <q-item-section>Contact</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>Newsletter</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section>LinkedIn</q-item-section>
            </q-item>
            <q-separator />
          </q-list>
        </q-menu>
      </div>
    </q-bar>
    <q-bar class="q-pa-md" style="background-color: rgba(0,0,0,0);">
        <div class="q-pr-md">
            <q-btn class="login-btn" unelevated rounded size="13px" text-color="white" label="Login" />
        </div>
        <div class="q-pl-md">
            <q-btn class="signup-btn" unelevated rounded size="13px" color="white" text-color="primary" label="Sign Up" />
        </div>
    </q-bar>

  </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
h1{
    font-size: 16px;
}
.q-pa-lg{
    margin: 50px auto;
    max-width: 1000px;
    background-color: rgba(54, 14, 14, 0);
    max-height: 100px;
    .qbar{
        background-color: rgba(54, 14, 14, 0);
    }
}

.q-btn{
&:hover{
  &.signup-btn{
    background-color: rgba(255, 255, 255, 0.212) !important;
    color: white !important;
  }
}
}
</style>