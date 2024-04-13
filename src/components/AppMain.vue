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
                <ul class="d-flex list-unstyled gap-2 px-5 py-5 justify-content-between fs-4">
                    <li>Ciao</li>
                    <li>Ciao</li>
                    <li>Ciao</li>
                    <li>Ciao</li>
                    <li>Ciao</li>
                    <li>Ciao</li>

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
    background-color: blue; 
     ul {
        color : $color-white
     }
   }
</style>