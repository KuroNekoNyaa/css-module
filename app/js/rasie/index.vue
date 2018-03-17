<template lang="html">
    <div>
        <v-header></v-header>
        <Slider></Slider>
        <Daily></Daily>
        <In></In>
        <More></More>
        <v-footer cname="mfooter"></v-footer>
        <Navbar></Navbar>
    </div>
</template>

<script>
    import vHeader from '../public/header.vue'
    import Slider from './rslider.vue'
    import Daily from './daily.vue'
    import In from './in.vue'
    import More from './more.vue'
    import vFooter from '../public/footer.vue'
    import Navbar from '../public/navbar.vue'
    export default {
        components: {
            vHeader,
            Slider,
            Daily,
            In,
            More,
            vFooter,
            Navbar
        }
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