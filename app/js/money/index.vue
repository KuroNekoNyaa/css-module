<template lang="html">
    <div>
        <heador></heador>
        <slider></slider>
        <Ada></Ada>
        <Money></Money>
        <Adb></Adb>
        <Finance></Finance>
        <Adc></Adc>
        <v-footer cname="mfooter"></v-footer>
        <Navbar></Navbar>
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Slider from './mSlider.vue'
import Ada from './ada.vue'
import Money from './money.vue'
import Adb from './adb.vue'
import Finance from './finance.vue'
import Adc from './adc.vue'
import vFooter from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
export default {
    components: {
        Heador,
        Slider,
        Ada,
        Money,
        Adb,
        Finance,
        Adc,
        vFooter,
        Navbar
    },
}
</script>

<style lang="scss">
.mfooter{
    margin-top: 0!important;
    ul{

        li:first-child{
            display: none;
        }
    }
}
</style>
