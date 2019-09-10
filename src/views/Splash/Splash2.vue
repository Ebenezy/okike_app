<template>
    <div class="okike-splash2">
        <div class="okike-splash2-inner">
            <div class="container okike-splash2-inner2">
                <div></div>
                <div>
                    <router-link to="Splash3"><img src="../../assets/images/okike-logo-white.svg"></router-link>
                </div>
                <div class="explore-txt">
                    <h3>Explore your <br><b>African Taste</b>, <br>From the tips of <br>your <b>fingers</b></h3>
                </div>
                <div class="foot-note-2">
                    <p><router-link to="Splash2"><font-awesome-icon icon="circle" class="fontawesom"/></router-link>
                        <router-link to="Splash3"><font-awesome-icon icon="circle" class="fontawesom1"/></router-link>
                    </p>
                </div>
            </div>
        </div>
    </div>
    <!--<vueper-slides autoplay>-->
        <!--<v-icon slot="pausedIcon" large color="white">pause_circle_outline</v-icon>-->
        <!--<vueper-slide v-for="(slide, i) in slides"-->
                      <!--:key="slide.id"-->
                      <!--:title="slide.title"-->
                      <!--:content="slide.content"-->
                      <!--:style="'background-color: ' + colors[i % 4]"></vueper-slide>-->
    <!--</vueper-slides>-->
</template>

<script>
    // import { VueperSlides, VueperSlide } from 'vueperslides'
    import 'vueperslides/dist/vueperslides.css'

    export default {
        name: "Splash2.vue",
        // components: { VueperSlides, VueperSlide },
        created(){
            setTimeout( () => this.$router.push({ path: '/Splash3'}), 3000);

        }

    }
</script>

<style scoped>

</style>