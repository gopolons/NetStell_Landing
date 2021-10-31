<template>
    <div class="container-fluid">
        <div class="row pt-5">
            <div class="col-3">
                <h1 class="color-primary">О КОМПАНИИ</h1>
            </div>
        </div>

        <div class="pt-5">
            <div class="row position-relative">
                <div class="col-8 pt-5 pb-5 pr-5 pl-5 background-primary">
                    <div class="row">
                        <p class="col-8 text-left color-white">NetStell - команда, объединяющая профессиональные кадры с глубокой многолетней экспертизой в реализации проектов, связанных с созданием и развитием информационной платформы современного бизнеса различного масштаба и направленности. Основная деятельность компании включает разработку информационных систем и их отдельных сегментов, оптимизацию готовых решений в IT инфраструктуре за счет собственных программных доработок и аппаратной модернизации, проектирование и строительство телекоммуникационных сетей, центров обработки данных, диспетчерских и инженерных систем.</p>

                    </div>
                    <div class="row pl-3 pt-5">
                        <button type="button" class="col-4 btn btn-light">Подробнее</button>
                    </div>
                </div>
                <div class="row position-absolute image-row">
                    <img class="image" :src="require(`@/assets/homeimg1.jpeg`)" alt="office img">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
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
.width-100 {
    z-index: 0;
    width: 100%;
}
p {
    line-height: 38.5px;
}

.image {
    z-index: 1;
    height: 40vh;
    box-shadow: rgba(43, 43, 43, 0.4) 0px 0px 100px;
}
</style>

<script>
export default {
    name: 'HomeAbout'
}
</script>