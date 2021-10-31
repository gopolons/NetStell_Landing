<template>
    <div class="container-fluid">
        <nav class="row center">
            <div class="row">
                <b-navbar toggleable="xl" type="light">
                    <b-navbar-brand to="#">
                        <img :src="require(`@/assets/logo.png`)" alt="logo" height="75" class="d-inline-block align-top">
                    </b-navbar-brand>
                <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
                    <b-collapse id="nav-collapse" is-nav>
                        <b-navbar-nav>
                            <b-nav-item class="pl-3 pr-3 but-font" to="#">О НАС</b-nav-item>
                            <b-nav-item class="pl-3 pr-3 but-font" to="#">НАПРАВЛЕНИЯ</b-nav-item>
                            <b-nav-item class="pl-3 pr-3 but-font" to="#">ЭКСПЕРТИЗА</b-nav-item>
                            <b-nav-item class="pl-3 pr-3 but-font" to="#">ПРОЕКТЫ</b-nav-item>
                            <b-nav-item class="pl-3 pr-3 but-font" to="#">ПАРТНЕРЫ</b-nav-item>
                            <b-nav-item class="pl-5 pr-5 but-font" to="#" link-classes="btn btn-primary text-white">+7 (900) 000 00 00</b-nav-item>
                        </b-navbar-nav>
                    </b-collapse>
                </b-navbar>
            </div>
        
        </nav>
    </div>

</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
.width-100 {
    z-index: 0;
    width: 100%;
}
.center {
    display: flex;
    justify-content: center;
}
.but-font {
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
}

</style>