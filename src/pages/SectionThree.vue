<template>
    <div class="main">
        <img src="../assets/illustration-phones.svg" alt="">
        <div class="right">
            <h1>State of the Art Infrastructure</h1>
            <p>With reliability and speed in mind, worldwide data centers provide the backbone for ultra-fast connectivity.
  This ensures your site will load instantly, no matter where your readers are, keeping your site competitive.</p>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .main{
        display: flex;
        color: white;
        justify-content: space-evenly;
        align-items: center;
        width: 100%;
        h1{
            font-size: 30px;
            font-weight: 500;
        }
        p{
            white-space: pre-wrap;
        }
        .right{
            max-width: 500px;
        }
    }
        @media (max-width: 1024px){
        .right{
        max-width: 400px;
        margin-right: 40px;
    }
        img{
        max-width: 500px;
    }
    }
</style>