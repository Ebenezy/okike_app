<template>
    <!--<vueper-slides>-->
        <!--<vueper-slide v-for="(slide, i) in slides" :key="i" :title="slide.title" :content="slide.content">-->
    <div class="okike-splash3">
        <div class="okike-splash3-inner">
            <div class="container okike-splash3-inner2">
                <div></div>
                <div class="cash-icons">
                    <img src="../../assets/images/cash-icons.svg">
                </div>
                <div class="explore-txt">
                    <h3>Place <b>Order</b> <br><b>Receive</b> Order<br>Enjoy <b>Meal</b><br>Share <b>Experience</b></h3>
                </div>
                <div class="foot-note2">
                    <div class="typer-txt">
                        <vue-typer
                                :text='["#AbachaInLagos","#BoliInLagos","#PalmWineInLagos"]'
                                :repeat='Infinity'
                                :shuffle='false'
                                initial-action='typing'
                                :pre-type-delay='70'
                                :type-delay='70'
                                :pre-erase-delay='2000'
                                :erase-delay='250'
                                erase-style=''
                                :erase-on-complete='false'
                                caret-animation='blink'
                        ></vue-typer>
                        <!--<vue-typed-js :strings="['#AbachaInLagos', '#BoliInLagos', '#PalmWineInLagos']" :loop="true" >-->
                            <!--<h4 class="typing"></h4>-->
                        <!--</vue-typed-js>-->

                    </div>
                    <div ><router-link to="Login"><img src="../../assets/images/next-btn.svg" class="bounce-1"></router-link></div>
                </div>
            </div>
        </div>
    </div>
        <!--</vueper-slide>-->
    <!--</vueper-slides>-->
</template>

<script>
    // import { VueperSlides, VueperSlide } from 'vueperslides'
    export default {
        name: "Splash3.vue",
        // components: { VueperSlides, VueperSlide },
        data: () => ({
            slides: [
                {
                    title: 'Slide #1',
                    content: 'Slide content.'
                },

            ]
        })
    }
</script>

<style scoped>

</style>