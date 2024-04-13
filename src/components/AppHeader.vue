<script>
export default {
    name : 'AppHeader'
}
</script>

<template>
    <div class="ms-container d-flex align-items-center justify-content-between p-3">
        <img src="../assets/img/dc-logo.png" alt="logo">
        <nav>
            <ul class="d-flex gap-2 list-unstyled">
                <li>Characters</li>
                <li class="ms-hover">Comics</li>
                <li>Movies</li>
                <li>Tv</li>
                 <li>Games</li>
                <li>Collectibles</li>
                <li>Videos</li>
                <li>Fans</li>
                <li>News</li>
                <li>Shop</li>
            </ul>
        </nav>

    </div>
</template>

<style scoped lang="scss">
   .ms-container{
      img {
        width: 70px;
      }

      li {
        font-size: 20px;
      }

      li:hover{
           color:lightblue
      }
}
</style>