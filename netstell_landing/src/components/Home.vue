<template>
    <div class="home container-fluid">
        <div class="row position-relative align-items-center">
            <img class="width-100" :src="require(`@/assets/homescreenbanner.jpg`)" alt="home screen banner">
            <div class="position-absolute col-12">
                <h2 class="color-white">Создаем цифровое пространство для вашего бизнеса</h2>
                <h1 class="color-white">NetStell - системный интегратор</h1>
            </div>
        </div>
    </div>

</template>

<script>
export default {
  name: 'Home'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.width-100 {
    z-index: 0;
    width: 100%;
}
.color-white {
    color: white;
}
.color-primary {
    color: #142B51;
}
.background-primary {
    background-color: #001E54;
}
.image-row {
    right: 10%;
    top: 19%; 
}



</style>

