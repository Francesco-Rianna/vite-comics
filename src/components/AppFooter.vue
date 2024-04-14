<script>
    export default {
        name: 'AppFooter'
    }
</script>

<template>

  <div class="bg-foot">
    <div class="ms-container">
        <div class="d-flex gap-4 py-5 ">
            <div>
                <h5>DC COMICS</h5>
                <nav>
                    <ul class= 'list-unstyled'>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                     </ul>
                </nav>
                <h5>SHOP</h5>
            </div>

            <div>
                <h5>DC</h5>
                <nav>
                    <ul class= 'list-unstyled'>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                     </ul>
                </nav>
            </div>
    
           <div>
             <h5>SITES</h5>
             <nav>
                    <ul class= 'list-unstyled'>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                     </ul>
                </nav>

            </div>
        </div>
    </div>
  </div>

</template>

<style scoped lang="scss">
 @use '../style/partials/variables' as *;

   

    .bg-foot{
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        min-height: 500px;
        margin-top: 0; 

        h5{
            color: $color-white;
        }
        li{
            color: $color-white;
        }

        

    
    }

</style>