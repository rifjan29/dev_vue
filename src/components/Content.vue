<template>
    <div class="content-wrapper">
        <h1>Fine Best Logo</h1>
        <div class="content-img">
            <img src="../assets/instagram-icon.png" alt="" class="logo-img">    
        </div>
        <div class="content-img">
            <img src="../assets/Facebook-icon.png" alt="" class="logo-img">    
        </div>
        <div class="content-img">
            <img src="../assets/youtube-icon.png" alt="" class="logo-img">    
        </div>
         <div class="content-img">
            <img src="../assets/logo.png" alt="" class="logo-img">    
        </div>
  
    </div>    
</template>

<script>
export default {
    name: 'Content'
    
}
</script>

<style scoped>
    .content-wrapper{
        width: 70%;
        overflow: hidden;
        margin: 50px auto;
        background:grey;
    }
    .content-img{
        width: 150px;
        height: 150px;
        float: left;
        margin-right: 20px;
        margin-left: 20px;
    }
    .content-img .logo-img{
        width: 150px;
        height: 150px;
    }
</style>>
