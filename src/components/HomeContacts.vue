<template>
    <div class="container-fluid">
        <div class="row pt-5">
            <div class="col-12">
                <h1 class="text-center">КОНТАКТЫ</h1>

            </div>
        </div>
        <div class="row pl-5 pr-5 pt-5">
            <div class="col-5 text-left">
                <h3>Адрес:</h3>
                <p>РФ, 123022, Москва, ул. 1905 года, 10А, стр. 1Ст. м. Улица 1905 года</p>
                <h3>Телефон:</h3>
                <p>+7 (499) 347-30-48</p>
                <h3>E-mail:</h3>
                <p>info@netstell.ru</p>
            </div>
            <div class="col-7">
                <div class="square"></div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomeContacts'
}
</script>

<style scoped>
.square {
  height: 400px;
  width: 100%;
  background-color: #555;
}
</style>