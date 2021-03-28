<template>
  <div class="main">
      <div class="left">
          <div>
          <h1>Free, open, simple</h1>
          <p>Blogr is a free and open source application backed by a large community of helpful developers. It supports
  features such as code syntax highlighting, RSS feeds, social media integration, third-party commenting tools,
  and works seamlessly with Google Analytics. The architecture is clean and is relatively easy to learn.</p>
          </div>
          <div>
          <h1>Powerful tooling</h1>
          <p>Batteries included. We built a simple and straightforward CLI tool that makes customization and deployment a breeze, but
  capable of producing even the most complicated sites.</p>
          </div>
      </div>
      <div class="right">
          <img src="../assets/illustration-laptop-desktop.svg" alt="">
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    h1{
        text-align: center;
        font-size: 25px;
        font-weight: 500;
        color:  hsl(237, 17%, 21%);
    }
    .main{
        display: flex;
        flex-direction: row-reverse;
        justify-content: space-around;
        align-items: center;
        padding: 20px;
         h1{
        font-size: 25px;
        font-weight: 500;
        text-align: unset;
    }
    p{
        color:hsl(237, 23%, 32%);
    }
    }
    img{
        max-width: 700px;
    }
    .left{
        max-width: 450px;
        margin-right: 50px;

    }

    @media (max-width: 1024px){
        .left{
        max-width: 400px;
        margin-right: 40px;
    }
        img{
        max-width: 500px;
    }
    }
</style>