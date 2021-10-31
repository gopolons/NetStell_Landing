<template>
    <div class="container-fluid ">
        <div class="row pt-5">
            <div class="col-10 pl-0 text-right">
                <h1 class="background-secondary pr-5 pt-2 pb-2 color-white">НАШИ ПРОЕКТЫ</h1>
            </div>

        </div>
        <div class="row">
            <SwiperProjects />
        </div>
    </div>
</template>

<script>
import SwiperProjects from './SwiperProjects.vue'
export default {
    components: { SwiperProjects },
    name: 'HomeProjects'
}
</script>

<style scoped>
.background-secondary {
    background-color: #18D1FF;
}

.color-white {
    color: white;
}
</style>