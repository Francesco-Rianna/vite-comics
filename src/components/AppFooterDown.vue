<script>
export default {
    name: 'AppFooterDown'
}
</script>

<template>
    <div class="bg-foot-down">
        <div class="ms-container">
            <div class="d-flex justify-content-between py-4 align-items-center ">
                <button class="bg-transparent p-2">
                    SIGN-UP-NOW!
                </button>
                <div class="d-flex align-items-center">
                    <span class="mx-4">Follow Us</span>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
      
    
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;

    .bg-foot-down {
        background-color:#303030;
    } span{
        color: $color-white
    } button  {
        color: $color-white
    }
    

</style>