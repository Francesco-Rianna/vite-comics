<script>
export default {
    props :[
        'image',
        'title'
    ]
}
</script>
<template>
    <div class="ms-card ">
        <img :src="image" alt="comic-img">
        <h5> {{ title }}</h5>
        
    </div>

</template>
<style scoped lang="scss">
@use '../style/partials/variables' as *;

.ms-card {
    width: calc(100% / 6);
} img {
   width : 150px ; 
   height: 150px;
   object-fit: cover;
   object-position: top;
} h5 {
    color : $color-white ; 
    font-size: 15px;
    margin-top: 10px;
    
}
</style>