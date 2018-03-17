<template lang="html">
    <div>
        <v-header></v-header>
        <h-slider></h-slider>
        <Novice></Novice>
        <Borrow></Borrow>
        <Money></Money>
        <Product></Product>
        <Life></Life>
        <v-footer></v-footer>
        <Navbar></Navbar>
    </div>
</template>

<script>
    import vHeader from '../public/header.vue'
    import hSlider from './hslider.vue'
    import Novice from './novice.vue'
    import Borrow from './borrow.vue'
    import Money from './money.vue'
    import Product from './product.vue'
    import Life from './life.vue'
    import vFooter from '../public/footer.vue'
    import Navbar from '../public/navbar.vue'
export default {
    components:{
        vHeader,
        hSlider,
        Novice,
        Borrow,
        Money,
        Product,
        Life,
        vFooter,
        Navbar
    }
}
</script>

<style lang="scss" module>
  @import '../../css/reset.scss';

</style>
