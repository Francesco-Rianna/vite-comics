<script>
export default {
    name : 'AppMain'
}
</script>

<template>
    <div class="bg-main">
        <div class="ms-container p-3">
            <h2>--------> Contents go here <------</h2>
        </div>
    </div>
    <div class="bg-main-2">
        <div class="ms-container">
            <nav>
                <ul class="d-flex list-unstyled gap-2 px-4 py-4 justify-content-between fs-4">
                    <li class="d-flex align-items-center">
                      <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                      <h5 class="ms-2">DIGITAL COMICS</h5>
                    </li>
                    <li class="d-flex align-items-center">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                      <h5 class="ms-2">DC MERCHANDISE</h5>
                    </li>
                    <li class="d-flex align-items-center">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                      <h5 class="ms-2">SUBSCRIPTION</h5>
                    </li>
                    <li class="d-flex align-items-center">
                        <img class="logo-locator" src="../assets/img/buy-comics-shop-locator.png" alt="">
                      <h5 class="ms-2">COMIC SHOP LOCATOR</h5>
                    </li>
                    <li class="d-flex align-items-center">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                      <h5 class="ms-2">DC POWER VISA</h5>
                    </li>
                </ul>
            </nav>
        </div>
    </div>
    

</template>

<style scoped lang="scss">
 @use '../style/partials/variables' as *;
   .bg-main{
     background-color: black;
     
     h2 {
        color : $color-white;
     }
      
   }

   .bg-main-2 {
    background-color: #0282f9; 
    height: 100px;
     ul {
        color : $color-white
     } img {
        width :40px;
     }
   }
</style>