<template lang="html">
    <div>
        <v-header></v-header>
        <Islider></Islider>
        <Welfare></Welfare>
        <Service></Service>
        <v-footer></v-footer>
        <Navbar></Navbar>
    </div>
</template>

<script>
    import vHeader from '../public/header.vue'
    import Islider from './islider.vue'
    import Welfare from './welfare.vue'
    import Service from './service.vue'
    import vFooter from '../public/footer.vue'
    import Navbar from '../public/navbar.vue'
    export default {
        components: {
            vHeader,
            Islider,
            Welfare,
            Service,
            vFooter,
            Navbar
        }
    }
</script>

<style lang="scss">

</style>