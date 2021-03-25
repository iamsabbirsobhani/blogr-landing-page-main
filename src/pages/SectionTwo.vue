<template>
  <h1>Designed for the future</h1>
  <div class="main">
      <div class="left">
          <div>
          <h1> Introducing an extensible editor</h1>
          <p>  Blogr features an exceedingly intuitive interface which lets you focus on one thing: creating content.
  The editor supports management of multiple blogs and allows easy manipulation of embeds such as images,
  videos, and Markdown. Extensibility with plugins and themes provide easy ways to add functionality or
  change the looks of a blog.</p>
          </div>
          <div>
          <h1>  Robust content management</h1>
          <p>  Flexible content management enables users to easily move through posts. Increase the usability of your blog
  by adding customized categories, sections, format, or flow. With this functionality, you’re in full control.</p>
          </div>
      </div>
      <div class="right">
          <img src="../assets/illustration-editor-desktop.svg" alt="">
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