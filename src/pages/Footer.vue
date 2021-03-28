<template>
    <div class="main fit row no-wrap justify-start items-start content-start">
        <div class="one  self-start q-ma-lg">
            <img src="../assets/logo.svg" alt="">
        </div>
        <div class="two  self-start q-ma-lg">
            <h6>Product</h6>
<br>
            <p>Overview</p>
            <p>Pricing</p>
            <p>Marketplace</p>
            <p>Features</p>
            <p>Integrations</p>
        </div>
        <div class="three  self-start q-ma-lg">
            <h6>Company</h6>
            <br>
            <p>About</p>
            <p>Team</p>
            <p>Blog</p>
            <p>Careers</p>
        </div>

        <div class="four  self-start q-ma-lg">
            <h6>Connect</h6>
            <br>
            <p>Contact</p>
            <p>Newsletter</p>
            <p>LinkedIn</p>
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
            line-height: 0.9;
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