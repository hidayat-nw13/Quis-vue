<template>
    <div>
        <div class="bg-light p-3">
            <div class="ml-5 my-5">
                <h4>Complete your Room</h4>
                <h4>With what we Designed</h4>
            </div>
            <div class="d-flex justify-content-around">
                <cardCmpVue joko="cangkir mauttie" wi="89.300.000" dodo="chair-2"></cardCmpVue>
                <cardCmpVue joko="Syail Amenno" wi="89.000.000" dodo="chair-1"></cardCmpVue>
                <cardCmpVue joko="Samman kakka" wi="14.500.000" dodo="chair-3"></cardCmpVue>
                <cardCmpVue joko="Lino Lino" wi="22.000.000" dodo="chair-4"></cardCmpVue>
            </div>
        </div>
    </div>
</template>
  
<script>
import cardCmpVue from './cardCmp.vue';

export default {
    name: "sliderCmp",
    components: { cardCmpVue }
}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
  