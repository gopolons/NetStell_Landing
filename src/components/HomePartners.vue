<template>
    <div class="container-fluid">
        <div class="row pt-5">
            <div class="col-5"></div>
            <div class="col-7 pr-0 text-left">
                <h1 class="background-secondary pl-5 pt-2 pb-2 color-white">НАШИ ПАРТНЕРЫ</h1>
            </div>
        </div>
        <div class="row">
            <SwiperPartners/>
        </div>
    </div>
</template>

<script>
import SwiperPartners from './SwiperPartners.vue'

export default {
    components: { SwiperPartners },
    name: 'HomePartners' 
}
</script>

<style scoped>

.background-secondary {
    background-color: #18D1FF;
}

.color-white {
    color: white;
}

.square {
  height: 300px;
  width: 100%;
  background-color: #555;
}
</style>